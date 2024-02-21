---
title: IConversionByPageCompleted
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Handle conversion page completed
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.conversion.fluent/iconversionbypagecompleted/
---```
public interface IConversionByPageCompleted
```

Handle conversion page completed
## Methods

| Method | Description |
| --- | --- |
| [onConversionCompleted(ConvertedPageStream convertedPageStream)](#onConversionCompleted-com.groupdocs.conversion.contracts.ConvertedPageStream-) | Receive converted page stream. |
### onConversionCompleted(ConvertedPageStream convertedPageStream) {#onConversionCompleted-com.groupdocs.conversion.contracts.ConvertedPageStream-}
```
public abstract IConversionConvertOrCompress onConversionCompleted(ConvertedPageStream convertedPageStream)
```


Receive converted page stream. Will be fired only if "Save(SaveDocumentStreamForFileType)" is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedPageStream | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Converted page stream provider |

**Returns:**
[IConversionConvertOrCompress](../../com.groupdocs.conversion.fluent/iconversionconvertorcompress) - Interface to continue conversion building
