# Notepad++ Keymap for VS Code

<img src="https://github.com/Microsoft/vscode-notepadplusplus-keybindings/blob/master/icon.png?raw=true" alt="logo" width="150">


This extension ports popular Notepad++ keyboard shortcuts to Visual Studio Code. After installing the extension and restarting VS Code your favorite keyboard shortcuts from Notepad++ are now available.

## What keyboard shortcuts are included?

| Command | Key |
| :---------: | :---------: |
| editor.foldAll | alt+0 
| editor.foldLevel1 | alt+1 
| editor.foldLevel2 | alt+2 
| editor.foldLevel3 | alt+3 
| editor.foldLevel4 | alt+4 
| editor.foldLevel5 | alt+5 
| editor.foldLevel6 | alt+6 
| editor.foldLevel7 | alt+7 
| editor.foldLevel8 | alt+8 
| editor.unfoldAll | shift+alt+0 
| editor.action.jumpToBracket | ctrl+shift+a 
| editor.action.duplicateSelection | ctrl+d 
| editor.action.commentLine | ctrl+q 
| editor.action.blockComment | ctrl+shift+q 
| editor.action.moveLinesDownAction | ctrl+shift+down 
| editor.action.moveLinesUpAction | ctrl+shift+up 
| editor.action.deleteLines | ctrl+l 

## Recommended extensions.

### Bookmarks
Looking for Bookmarks via the F2 keys? Hi! Install the Bookmark extension and map the commands to F2 keys to get similar bookmarks functionality: https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks


## How do I contribute a keyboard shortcut?

We may have missed a keyboard shortcut. If we did please help us out! It is very easy to make a PR.

1. Open [`package.json`](https://github.com/Microsoft/vscode-notepadplusplus-keybindings/blob/master/package.json).
2. Add a JSON object to [`contributes.keybindings`](https://github.com/Microsoft/vscode-notepadplusplus-keybindings/blob/master/package.json#L16) as seen below.
3. Open a pull request.

```json
{
    "mac": "<keyboard shortcut for mac>",
    "linux": "<keyboard shortcut for linux>",
    "win": "<keyboard shortcut for windows>",
    "key": "<default keyboard shortcut>",
    "command": "<name of the command in VS Code>"
}
```

You can read more about how to contribute keybindings in extensions in the [official documentation](http://code.visualstudio.com/docs/extensionAPI/extension-points#_contributeskeybindings).

## Mapping between VS Code and Notepad++

See https://docs.google.com/spreadsheets/d/1CUV0ZZHcI8NM7a5YiPbsPrKQRR59MY5n24qRza6UvNs/edit?usp=sharing

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
