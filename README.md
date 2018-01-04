# vscode-terraform-azure README

The VSCode Terraform Azure extension is designed to increase developer productivity building Terraform modules for Azure.  The extension provides, linting, terraform command support, resource graph visualization, testing and cloudshell integration inside of VSCode.

![overview](images/image1.png)

## Features

This extension supports the following features:

### Terraform-Azure: init

### Terraform-Azure: plan

### Terraform-Azure: apply

### Terraform-Azure: validate

### Terraform-Azure: refresh

### Terraform-Azure: destroy

### Terraform-Azure: visualize

### Terraform-Azure: execute test

### Terraform-Azure: push

This command will sync workspace files that meet filter `tf-azure.files` setting in your configuration to Azure - Cloudshell.

## Requirements

This extension requires [Docker](http://www.docker.io) if you are using the execute test feature and [GraphViz dot](http://www.graphviz.org) if you are using the visualize feature.

## Supported Environments

* [Microsoft Azure](https://azure.microsoft.com)
* [Azure Stack](https://azure.microsoft.com/en-us/overview/azure-stack/)
* [Microsoft Azure China](https://www.azure.cn/)
* [Microsoft Azure US Government](https://azure.microsoft.com/en-us/features/gov/)

## Extension Settings

* `tf-azure` - Parent for Terraform-Azure related extension settings
  * `tf-azure.terminal` - Specifies terminal used to run Terraform commands. Valid settings are `cloudshell` or `integrated`
  * `tf-azure.files` - Indicates the files that should be synchronized to Azure cloudshell using the glob pattern string, for example `**/*.{tf,txt}`

## Known Issues

Windows support for dot has some unhandled exception cases.  We are working to improve this area.

## Release Notes

### 1.0.0

Initial release of vscode-terraform-azure extension.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on OSX or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on OSX or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**