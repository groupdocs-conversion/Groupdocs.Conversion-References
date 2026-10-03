---
title: "SaveDocumentStream"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Menjelaskan delegasi untuk menyimpan dokumen yang dikonversi ke aliran output."
type: docs
weight: 23
url: /id/java/com.groupdocs.conversion.contracts/savedocumentstream/
---```
public interface SaveDocumentStream
```

Describes delegate for saving converted document into output stream.

## Methods

| Method | Description |
| --- | --- |
| [get()](#get--) | Saves converted document into output stream.
 |
### get() {#get--}
```
public abstract OutputStream get()
```


Saves converted document into output stream.


**Returns:**
java.io.OutputStream - Must return an output stream where the converted document will be saved

