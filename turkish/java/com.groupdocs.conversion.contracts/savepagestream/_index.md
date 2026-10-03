---
title: "SavePageStream"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Dönüştürülmüş belge sayfasını akışa kaydeden temsilciyi açıklar."
type: docs
weight: 25
url: /tr/java/com.groupdocs.conversion.contracts/savepagestream/
---```
public interface SavePageStream
```

Describes delegate for saving converted document page into stream.

## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | Saves converted document page into stream.
 |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


Saves converted document page into stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Converted page number
 |

**Returns:**
java.io.OutputStream - Must return a stream where the converted document page will be saved

