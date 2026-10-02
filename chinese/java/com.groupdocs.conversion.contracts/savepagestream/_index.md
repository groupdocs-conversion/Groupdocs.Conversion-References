---
title: "SavePageStream"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "描述用于将已转换文档页面保存到流的委托。"
type: docs
weight: 25
url: /zh/java/com.groupdocs.conversion.contracts/savepagestream/
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

