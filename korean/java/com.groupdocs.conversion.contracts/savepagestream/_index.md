---
title: "SavePageStream"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "변환된 문서 페이지를 스트림에 저장하는 대리자를 설명합니다."
type: docs
weight: 25
url: /ko/java/com.groupdocs.conversion.contracts/savepagestream/
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

