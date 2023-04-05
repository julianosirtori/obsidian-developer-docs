<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [obsidian](./obsidian.md) &gt; [MetadataCache](./obsidian.metadatacache.md) &gt; [fileToLinktext](./obsidian.metadatacache.filetolinktext.md)

## MetadataCache.fileToLinktext() method

Generates a linktext for a file.

If file name is unique, use the filename. If not unique, use full path.

**Signature:**

```typescript
fileToLinktext(file: TFile, sourcePath: string, omitMdExtension?: boolean): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  file | [TFile](./obsidian.tfile.md) |  |
|  sourcePath | string |  |
|  omitMdExtension | boolean | _(Optional)_ |

**Returns:**

string
