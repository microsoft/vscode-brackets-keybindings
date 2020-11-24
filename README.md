# Brackets Keymap for Visual Studio Code

This extension ports popular Brackets keyboard shortcuts to Visual Studio Code. After installing the extension and restarting VS Code your favorite keyboard shortcuts from Brackets are now available. 

## What keyboard shortcuts are included?

You can see all the keyboard shortcuts in the extension's contribution list. 

## Why don't all the keyboard shortcuts work?

VS Code does not implement all of the commands available in Brackets. If you would like to see a feature in VS Code that is in Brackets, please open an [issue on GitHub](https://github.com/Microsoft/vscode/issues/new). 

## How do I contribute a keyboard shortcut?

We may have missed a keyboard shortcut. If we did please help us out! It is very easy to make a PR. 

1. Head over to our [GitHub repository](https://github.com/Microsoft/vscode-brackets-keybindings).
2. Open [`package.json`](https://github.com/Microsoft/vscode-vs-keybindings/blob/master/package.json).
3. Add a [keybinding rule](https://code.visualstudio.com/api/references/contribution-points#contributes.keybindings) to [`contributes.keybindings`](https://github.com/Microsoft/vscode-brackets-keybindings/blob/master/package.json#L26).
4. Open a pull request.

You can read more about how to contribute keybindings in extensions in the [official documentation](https://code.visualstudio.com/api/references/contribution-points#contributes.keybindings). 