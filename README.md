# VS Code Settings

# Font

- [Source Code Pro](https://github.com/adobe-fonts/source-code-pro)

# Extensions

See my full list of extensions [here](https://gist.github.com/sbaezamella/e3490c75a01fb2878f0d8a0c51b493c8).

## Themes/Color

- Current theme:

  - [Cobalt Next](https://github.com/davidleininger/cobaltnext-vscode)

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
	"editor.fontFamily": "Source Code Pro",
	"editor.fontLigatures": true,
	"editor.fontSize": 16,
	"editor.formatOnSave": true,
	"editor.minimap.enabled": true,
	"editor.multiCursorModifier": "ctrlCmd",
	"editor.snippetSuggestions": "top",
	"editor.suggestSelection": "first",
	"editor.wordWrap": "on",
	"explorer.openEditors.visible": 9,
	"emmet.includeLanguages": {
		"javascript": "html"
	},
	"prettier.singleQuote": true,
	"prettier.useTabs": true,
	"python.languageServer": "Microsoft",
	"python.pythonPath": "/usr/bin/python",
	"sync.autoDownload": false,
	"sync.autoUpload": false,
	"sync.gist": "1fe853ee6a30df81f6db1c4fdad33dbd",
	"terminal.integrated.fontFamily": "MesloLGS NF",
	"terminal.integrated.fontSize": 14,
	"window.menuBarVisibility": "toggle",
	"workbench.colorTheme": "Cobalt Next",
	"workbench.editor.tabSizing": "shrink",
	"workbench.settings.useSplitJSON": true,
	"workbench.startupEditor": "newUntitledFile",
	"workbench.iconTheme": "material-icon-theme"
}
```
