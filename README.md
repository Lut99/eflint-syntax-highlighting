# eFLINT Syntax Highlighting
Provides basic syntax highlighting for the eFLINT language (https://gitlab.com/eflint) for Visual Studio Code.


## Installation
To install the extension in your local setup, clone the repository first.

Then, install [`npm`](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) and:
```bash
npm install -g vsce
```

Then, CD into the repository root and run:
```bash
vsce package
```
to compile the package file.

Finally, you can install the extension by navigating to the Extensions tab, click the three-dot menu at the top of the middle panel and select "Install from VSIX...". Browse to the extension, and click: "Install". The extension should now be added to your Visual Studio Code setup.

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
