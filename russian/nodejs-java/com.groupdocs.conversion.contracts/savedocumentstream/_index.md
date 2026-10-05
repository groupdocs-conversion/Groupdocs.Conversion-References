---
title: "SaveDocumentStream"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Описывает делегат для сохранения преобразованного документа в выходной поток."
type: docs
weight: 22
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/savedocumentstream/
---```
public interface SaveDocumentStream
```

Describes delegate for saving converted document into output stream.
## Methods

| Method | Description |
| --- | --- |
| [get()](#get--) | Saves converted document into output stream. |
### get() {#get--}
```
public abstract OutputStream get()
```


Saves converted document into output stream.

**Returns:**
java.io.OutputStream - Must return an output stream where the converted document will be saved
