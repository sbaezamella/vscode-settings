# VS Code Settings

# Font

- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

# Extensions

See my full list of extensions [here](https://gist.github.com/sbaezamella/e3490c75a01fb2878f0d8a0c51b493c8).

## Themes/Color

- Current theme:

  - [Horizon](https://github.com/jolaleye/horizon-theme-vscode)

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
  - Matching parenthesis and curly brackets to with colors

## Workflow

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  - Automatically add HTML/XML close tag
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  - Automatically rename paired HTML/XML tag

## IntelliSense/AutoComplete

- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  - Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  - Autocompletes npm modules in import/require statements
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  - Autocompletes filenames

## Style/Formatting

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - Integrates ESLint JS
- [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  - Automatically format javascript, JSON, CSS, Sass, and HTML files.

## Useful/Extra

- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  - Display inline the size of the required/imported package
- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  - Collaborative editing, debugging, and more inside VS Code

# Settings

```json
{
  "bracket-pair-colorizer-2.colors": [
    "#5fb3b3",
    "#c5a5c5",
    "#5a9bcf",
    "#fac863"
  ],
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.fontFamily": "Anonymous Pro",
  "editor.fontLigatures": true,
  "editor.fontSize": 18,
  "editor.formatOnSave": true,
  "editor.minimap.enabled": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "explorer.openEditors.visible": 0,
  "emmet.includeLanguages": {
    "javascript": "html"
  },
  "prettier.singleQuote": true,
  "python.linting.enabled": false,
  "python.pythonPath": "/bin/python",
  "sync.autoUpload": false,
  "sync.autoDownload": false,
  "sync.gist": "1fe853ee6a30df81f6db1c4fdad33dbd",
  "terminal.integrated.fontFamily": "monospace",
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.shell.windows": "D:\\Cygwin64\\bin\\bash.exe",
  "terminal.integrated.shellArgs.windows": ["-lic", "cd $OLDPWD; exec zsh"],
  "workbench.iconTheme": "vscode-icons",
  "workbench.settings.useSplitJSON": true,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.colorTheme": "Horizon Italic"
}
```
