# HMPL

This is a **VS Code extension** that treats files with a custom file extension (e.g., `.hmpl`) as HTML. It applies HTML syntax highlighting, auto-closing tags, and other related features to these files.

## Features

- Supports any theme compatible with HTML files.
- Auto-closing and auto-pairing of HTML tags.
- Syntax highlighting for `.hmpl` files using standard HTML grammar.

## Getting Started

### Installation

1. Clone or download this repository to your local machine.
2. Open the project folder in Visual Studio Code.
3. Install dependencies (if any) by running:

   ```bash
   npm install
   ```

4. Package the extension by running:

   ```bash
   vsce package
   ```

5. Install the generated `.vsix` file in your VS Code:
   - Open the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
   - Click the menu icon (`...`) in the top-right corner and select **Install from VSIX...**.
   - Select the `.vsix` file you generated.

### Usage

1. Open any file with the `.hmpl` extension in VS Code.
2. The file will automatically be treated as an HTML file, with syntax highlighting and other features enabled.

## Development Guide

### Project Structure

Here is a quick overview of the files in this project:

- **`package.json`**: Metadata and configuration for your extension. Defines the custom file extension and maps it to HTML syntax.
- **`language-configuration.json`**: Configuration for brackets, comments, and auto-closing pairs.
- **`syntaxes/html.tmLanguage.json`**: Contains the grammar rules for HTML syntax highlighting.
- **`extension.js`**: The main script for the extension. Currently, it contains boilerplate code and can be extended for additional features.

### Running the Extension in Debug Mode

To test your extension in VS Code:

1. Open the extension project folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. Open a `.hmpl` file in the new window to see your extension in action.

### Packaging for Distribution

1. Ensure your `package.json` is properly configured (e.g., name, version, and publisher).
2. Run the following command to generate a `.vsix` file:

   ```bash
   vsce package
   ```

3. Publish your extension to the Visual Studio Code Marketplace:

   ```bash
   vsce publish
   ```

   > Note: You’ll need a publisher account and a Personal Access Token (PAT) to publish your extension.

---

This guide should help you understand how to use and develop the `HMPL`. Feel free to enhance it with additional features or customizations!
