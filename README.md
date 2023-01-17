# vscode-clip-them-lines

Copies the lines you've selected with the line number and additional document meta data. Like below:

```
Path: src/extension.ts
17:         const selection = sorted[j];
18: 
19:         for (let j = selection.start.line; j <= selection.end.line; ++j) {
20:           const line = textEditor.document.lineAt(j);
21:           lines.push(`${line.lineNumber + 1}: ${line.text}`);
22:         }
23: 
24:         if (j !== sorted.length - 1) {
25:           lines.push('...');
26:         }
```

## Features

* Copy text with line numbers.
* Works with multi-select.

## Release Notes

### 1.0.0

Initial release.