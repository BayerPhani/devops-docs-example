# DevOps Docs Example

Example on how to generate documentation and push it to [devops-docs](https://github.com/bayer-int/devops-docs).

In this case MkDocs with the MkDocs Material theme is used. Any other static website builder or raw files work as well.

## Steps

1. Create a repository based on this template (or copy contents to new repository).
2. (Optional) Adjust parameters for the `publish-docs` workflow ([full reference](https://docs.int.bayer.com/ref/))
    * `namespace`: add a custom path your documentation will be available on
    * `spa`: flag as Single Page Application
    * `auth`: protect your documentation with an Azure AD group
3. Write your documentation!

You can then access your documentation via `https://docs.int.bayer.com/-/$YOUR_REPOSITORY/` or `https://docs.int.bayer.com/$YOUR_NAMESPACE/`.

## Editing Documentation

You can edit your documentation locally, for which you will need to install the Python Poetry package manager. Another option is to make use of the preconfigured GitHub CodeSpaces environment as described below.

### GitHub CodeSpaces

1. Open this repository in a CodeSpace by going to `Code > CodeSpaces > New CodeSpace`
2. Wait for the CodeSpace to finish loading
3. Start MkDocs to serve locally with `Ctrl + Shift + B`, or

    ```bash
    poetry run mkdocs serve
    ```

    or launch Task via VS Code menu `Terminal > Run Task... > Launch MkDocs`

4. Open the page by clicking the link in the cmd, the popup (left right corner), or by going to the `Ports` tab.
5. Write your documentaton!

## Template Information

[devops-docs-example](https://github.com/bayer-int/devops-docs-example)
v1.3.2
