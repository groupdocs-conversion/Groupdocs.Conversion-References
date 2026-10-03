---
title: "SaveDocumentStream"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Dönüştürülmüş belgeyi çıktı akışına kaydeden temsilciyi açıklar."
type: docs
weight: 23
url: /tr/java/com.groupdocs.conversion.contracts/savedocumentstream/
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

