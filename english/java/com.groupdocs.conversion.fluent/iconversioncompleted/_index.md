---
title: IConversionCompleted
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Handle conversion completed
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.conversion.fluent/iconversioncompleted/
---```
public interface IConversionCompleted
```

Handle conversion completed
## Methods

| Method | Description |
| --- | --- |
| [onConversionCompleted(ConvertedDocumentStream convertedDocumentStream)](#onConversionCompleted-com.groupdocs.conversion.contracts.ConvertedDocumentStream-) | Receive converted document stream. |
### onConversionCompleted(ConvertedDocumentStream convertedDocumentStream) {#onConversionCompleted-com.groupdocs.conversion.contracts.ConvertedDocumentStream-}
```
public abstract IConversionConvertOrCompress onConversionCompleted(ConvertedDocumentStream convertedDocumentStream)
```


Receive converted document stream. Will be fired only if "Save(string)" or "Save(SaveDocumentStreamForFileType)" is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedDocumentStream | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | Converted document stream provider |

**Returns:**
[IConversionConvertOrCompress](../../com.groupdocs.conversion.fluent/iconversionconvertorcompress) - Interface to continue conversion building
