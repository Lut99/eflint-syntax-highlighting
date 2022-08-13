# eFLINT Syntax Highlighting
Provides basic syntax highlighting for the eFLINT language (https://gitlab.com/eflint) for Visual Studio Code.


## Installation
To install the extension in your local setup, you can either download or compile the package VSIX file.

### Downloading
Go to the [releases page](https://github.com/Lut99/eflint-syntax-highlighting/releases) and download the .vsix file from the latest release.

### Compilation
To compile the VSIX file manually, clone [the repository](https://github.com/Lut99/eflint-syntax-highlighting) first.

Then, install [`npm`](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) and:
```bash
npm install -g vsce
```

CD into the repository root and compile the extension to a package VSIX file:
```bash
vsce package
```

Finally, you can install the extension by navigating to the Extensions tab in a Visual Studio Code window, click the three-dot menu at the top of the middle panel and select "Install from VSIX...". Browse to the extension, and click: "Install". The extension should now be added to your Visual Studio Code setup.

![Screenshot to install VSIX file](img/showcase_vsix.png)  
_Menu to install local .vsix file using the [Panda Syntax](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda) theme._


## Features
Adds basic syntax highlighting for most keywords, buildin functions and data types for eFLINT. For example:


![Example syntax hightlighting](img/example.png)  
_Example snippet of eFLINT using the [Panda Syntax](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda) theme._

More constructs or features may be added in the future. Ideally, a language server might even provide much more advanced syntax highlighting.


## Release Notes
A brief overview of each release is given here. For more details, check the `CHANGELOG.md` file.

### 1.0.0
Initial release of the extension.
