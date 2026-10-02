---
title: "IConversionByPageCompleted"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "معالجة إكمال صفحة التحويل"
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.fluent/iconversionbypagecompleted/
---```
public interface IConversionByPageCompleted
```

Handle conversion page completed

## Methods

| Method | Description |
| --- | --- |
| [onConversionCompleted(ConvertedPageStream convertedPageStream)](#onConversionCompleted-com.groupdocs.conversion.contracts.ConvertedPageStream-) | Receive converted page stream.
 |
### onConversionCompleted(ConvertedPageStream convertedPageStream) {#onConversionCompleted-com.groupdocs.conversion.contracts.ConvertedPageStream-}
```
public abstract IConversionConvertOrCompress onConversionCompleted(ConvertedPageStream convertedPageStream)
```


Receive converted page stream. Will be fired only if "Save(SaveDocumentStreamForFileType)" is set.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedPageStream | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | Converted page stream provider
 |

**Returns:**
[IConversionConvertOrCompress](../../com.groupdocs.conversion.fluent/iconversionconvertorcompress) - Interface to continue conversion building

