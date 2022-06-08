# @markmirror/commands

Keyboard shortcuts and commands for the MarkMirror editor.


## Usage

```js
import { MarkMirror } from "@markmirror/core"
import { buildMarkdownCommands } from "@markmirror/commands"

const editor = new MarkMirror({
  extensions: [ buildMarkdownCommands(true) ]
})
```
