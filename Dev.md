
# TODO
* Copy with syntax highlighting

## Creating 
## Creating a publisher
Create a publisher here.
* [Them Projects Azure Dev Portal](https://dev.azure.com/ThemProjects)

Create an organization here.
* [Publisher management portal](https://marketplace.visualstudio.com/manage/publishers/jeffmathew)
  * If 500, try logging in an incognito window with ad blockers disabled.

See your orgs here too
* [Azure devops me](https://aex.dev.azure.com/me?mkt=en-US)

Always make a new command prompt when running vsce commands.


## Commands
```
vsce login jeffmathew
vsce publish 
```
That never works so instead do `vsce package` and upload in the web ui. Where it will also fail.

# Resources
[Publishing](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
[API Reference](https://code.visualstudio.com/api/references/vscode-api#commands.registerTextEditorCommand)


editor.action.clipboardCopyWithSyntaxHighlightingAction
https://github.com/microsoft/vscode/blob/ffe53e8d710a6fce5e2bdc67f25914aea3c40d42/src/vs/editor/contrib/clipboard/browser/clipboard.ts
https://github.com/microsoft/vscode/blob/94916c0127843357dd47548cf1229383ab943e75/src/vs/editor/common/viewModel/viewModelImpl.ts#L873