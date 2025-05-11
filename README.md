# HMPL

<div><a href="https://hmpl-lang.dev/vs-code-extension.html">Website page</a></div><br/>

HMPL syntax support in the VS Code code editor.

```html
<div>
  <div>{{#request src="/api/getHTML"}} {{/request}}</div>
</div>
```

## Features

- **HTML Syntax Highlighting**: Automatically applies HTML grammar and syntax highlighting to `.hmpl` files.
- **Bracket Matching**: Support for auto-closing and matching of HTML-like tags.
- **Seamless Theme Integration**: Compatible with all VS Code themes that support HTML.
- **Custom File Icons**: `.hmpl` files are displayed with a unique icon in the VS Code file explorer for easy identification.

## Installation

1. Open the Extensions view in Visual Studio Code by pressing `Ctrl+Shift+X` or `Cmd+Shift+X` on macOS.
2. Search for "HMPL" and click **Install**.
3. Once installed, open any file with the `.hmpl` extension, and the syntax highlighting will be applied automatically.

## Usage

1. Create a new file with the `.hmpl` extension or open an existing one.
2. Start writing code as you would in an HTML file.
3. Enjoy enhanced syntax support and visual styling optimized for `.hmpl` files.

## Customization

If you want to adjust how `.hmpl` files behave in the editor, you can:

- Change the icon theme:
  - Go to **Settings → File Icon Theme** and choose **HMPL Icons**.
- Adjust language-specific settings:
  - Open the **Command Palette** (`Ctrl+Shift+P` or `Cmd+Shift+P`), search for "Preferences: Open Settings (JSON)", and add language-specific configurations for `hmpl`.

**Example**:

```json
"[hmpl]": {
  "editor.tabSize": 2,
  "editor.autoClosingBrackets": "always"
}
```

## Changelog

Check the [Changelog](CHANGELOG.md) file for a detailed list of updates and changes in future versions.

## Contributing

We have a [Contributing Guide](https://github.com/hmpl-language/hmpl/blob/main/CONTRIBUTING.md) that describes the main steps for contributing to the project.

Thank you to all the people who have already contributed to HMPL, or related projects!

## License

This extension is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
