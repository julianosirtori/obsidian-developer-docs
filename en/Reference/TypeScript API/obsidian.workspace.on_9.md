<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [obsidian](./obsidian.md) &gt; [Workspace](./obsidian.workspace.md) &gt; [on](./obsidian.workspace.on_9.md)

## Workspace.on() method

Triggered when the user opens the context menu on a file.

**Signature:**

```typescript
on(name: 'file-menu', callback: (menu: Menu, file: TAbstractFile, source: string, leaf?: WorkspaceLeaf) => any, ctx?: any): EventRef;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  name | 'file-menu' |  |
|  callback | (menu: [Menu](./obsidian.menu.md)<!-- -->, file: [TAbstractFile](./obsidian.tabstractfile.md)<!-- -->, source: string, leaf?: [WorkspaceLeaf](./obsidian.workspaceleaf.md)<!-- -->) =&gt; any |  |
|  ctx | any | _(Optional)_ |

**Returns:**

[EventRef](./obsidian.eventref.md)
