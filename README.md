# VS Code Settings

This README describes my personal settings and configuration for Visual Studio Code editor.

## Font

- [Cascadia Code](https://github.com/microsoft/cascadia-code)

## Extensions

See my full list of extensions [here](https://gist.github.com/sbaezamella/e3490c75a01fb2878f0d8a0c51b493c8).

## Themes/Color

- Current theme:

  - [Cobalt Next](https://github.com/davidleininger/cobaltnext-vscode)

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
  - Matching parenthesis and curly brackets to with colors

## Workflow

### HTML

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  - Automatically rename paired HTML/XML tag
- [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

### Flutter

- [Awesome Flutter Snipets](https://marketplace.visualstudio.com/items?itemName=Nash.awesome-flutter-snippets)
- [BLoC](https://marketplace.visualstudio.com/items?itemName=FelixAngelov.bloc)
- [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)
- [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)
- [Pubspec Assist](https://marketplace.visualstudio.com/items?itemName=jeroen-meijer.pubspec-assist)

### Java

- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

### JavaScript

- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

### Python

- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- [Python](https://code.visualstudio.com/docs/editor/extension-marketplace)

## IntelliSense/AutoComplete

- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  - Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  - Autocompletes npm modules in import/require statements
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  - Autocompletes filenames
- [Tailwind Css IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

## Style/Formatting

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - Integrates ESLint JS
- [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  - Automatically format javascript, JSON, CSS, Sass, and HTML files.
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

## Useful/Extra

- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  - Display inline the size of the required/imported package
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)

## Settings

```json
{
    "bracket-pair-colorizer-2.colors": [
        "#5fb3b3",
        "#c5a5c5",
        "#5a9bcf",
        "#fac863"
    ],
    "color-highlight.markerType": "underline", // requires Color Highlight Extension
    "color-highlight.markRuler": false, // requires Color Highlight Extension
    "diffEditor.ignoreTrimWhitespace": false,
    "editor.colorDecorators": false, // using Color Hightlight instead
    "editor.fontFamily": "Cascadia Code, Operator Mono Medium, Source Code Pro",
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "editor.formatOnSave": true,
    "editor.letterSpacing": 0.5,
    "editor.lineHeight": 26,
    "editor.suggestSelection": "first",
    "editor.tabSize": 2,
    "editor.wordWrap": "on",
    "emmet.includeLanguages": {
        "javascript": "html"
    },
    "explorer.openEditors.visible": 9,
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "files.insertFinalNewline": true,
    "notebook.cellToolbarLocation": {
        "default": "right",
        "jupyter-notebook": "left"
    },
    "prettier.singleQuote": true,
    "prettier.useTabs": true,
    "python.showStartPage": false,
    "python.testing.pytestEnabled": true,
    "redhat.telemetry.enabled": false,
    "settingsSync.keybindingsPerPlatform": false,
    "sourcery.token": "user_lKBnF0g_PB262PCUBGioU37HbkyIPPJkGdW_BLQ7S_N9CRJtNT7OiurzShI",
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "terminal.integrated.fontSize": 14,
    "window.menuBarVisibility": "toggle",
    // "window.title": "(ツ)_/¯ ${dirty} ${activeEditorShort}",
    "window.title": "${dirty}${activeEditorShort} / ${rootName}",
    "workbench.colorTheme": "Cobalt Next",
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter-notebook"
    },
    "workbench.editor.tabSizing": "shrink",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.settings.useSplitJSON": true,
    "workbench.startupEditor": "newUntitledFile",
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.selectionHighlight": false,
        "editor.suggest.snippetsPreventQuickSuggestions": false,
        "editor.suggestSelection": "first",
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": false
    },
    "sqltools.useNodeRuntime": true,
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[python]": {
        "editor.tabSize": 4,
        "editor.defaultFormatter": "ms-python.python"
    },
    "latex-workshop.view.pdf.viewer": "tab",
    "eslint.format.enable": true,
    "[typescript]": {
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "sonarlint.rules": {
        "typescript:S1488": {
            "level": "off"
        }
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
}
```
