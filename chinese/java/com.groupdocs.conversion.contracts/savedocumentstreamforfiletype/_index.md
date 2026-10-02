---
title: "SaveDocumentStreamForFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "描述用于将已转换文档保存到流的委托。"
type: docs
weight: 24
url: /zh/java/com.groupdocs.conversion.contracts/savedocumentstreamforfiletype/
---```
public interface SaveDocumentStreamForFileType
```

Describes delegate for saving converted document into stream.

## Methods

| Method | Description |
| --- | --- |
| [invoke(FileType fileType)](#invoke-com.groupdocs.conversion.filetypes.FileType-) | Saves converted document into stream.
 |
### invoke(FileType fileType) {#invoke-com.groupdocs.conversion.filetypes.FileType-}
```
public abstract OutputStream invoke(FileType fileType)
```


Saves converted document into stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Converted document type
 |

**Returns:**
java.io.OutputStream - Must return a stream where the converted document will be saved

