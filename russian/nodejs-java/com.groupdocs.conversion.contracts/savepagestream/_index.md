---
title: "SavePageStream"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Описывает делегат для сохранения страницы преобразованного документа в поток."
type: docs
weight: 24
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/savepagestream/
---```
public interface SavePageStream
```

Describes delegate for saving converted document page into stream.
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | Saves converted document page into stream. |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


Saves converted document page into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Converted page number |

**Returns:**
java.io.OutputStream - Must return a stream where the converted document page will be saved
