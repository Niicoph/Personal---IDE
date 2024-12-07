# Instructions

1. Install "Custom CSS and JS Loader" VS Code Extension.
2. Copy the contents of settings.json to your VS Code's settings.json
3. Add `vscode_custom_css.imports` array to your settings.json file:
```
"vscode_custom_css.imports": [
    // For Linux
    // "file:///Users/your-user-name/custom-vscode.css",
    // "file:///Users/your-user-name/custom-vscode-script.js"
],
```
4. Update ownership
```
sudo chown -R your-user-name /usr/share/code
```
5. Enable "Custom CSS and JS Loader" (using command palette).
