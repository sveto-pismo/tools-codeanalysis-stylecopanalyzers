<center style="padding: 2rem">
    <img src="assets/packageIcon.png" alt="SvetoPismo" width="128">
    <h1>SvetoPismo.Tools.CodeAnalysis.StyleCopAnalyzers</h1>
</center>

This NuGet package leverages the power of StyleCop Analyzers
to enforce code quality standards that are tailored to the organization's specific needs.
By default,
the package uses a set of analyzer rules that have been configured to align with the organization's coding practices,
ensuring that our code is always compliant and maintainable.

Key features:

- Utilize Roslyn .NET Analyzers for powerful and customizable code analysis
- Defaults suited to the organization's coding practices
- Ensures code compliance and maintainability

## Installation
To install this package, use the NuGet Package Manager Console:

```shell
PM> Install-Package SvetoPismo.Tools.CodeAnalysis.StyleCopAnalyzers
```
Or you can search for "SvetoPismo.Tools.CodeAnalysis.StyleCopAnalyzers"
in the NuGet Package Manager UI and install it from there.

## Usage
After installing the package, the MSBuild and .editorconfig properties will be set automatically.
- You can modify the MSBuild properties by updating the values in your .csproj or .vbproj file.
- You can modify the .editorconfig properties by creating .editorconfig file and overriding the default values.

## Configuration

To modify the severity level of a rule, you can add the following code to your .editorconfig file:

```editorconfig
# dotnet_diagnostic.<Rule>.severity = <Severity>
```

For example, to change the severity level of `SA9999` to "error", add the following line to your .editorconfig file:

```editorconfig
# dotnet_diagnostic.SA9999.severity = error
```


## Contributing
If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request.
Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

