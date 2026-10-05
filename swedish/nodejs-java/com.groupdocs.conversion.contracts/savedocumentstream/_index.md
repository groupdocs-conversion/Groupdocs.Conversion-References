---
title: "SaveDocumentStream"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Beskriver delegat för att spara konverterat dokument i en utdataström."
type: docs
weight: 22
url: /sv/nodejs-java/com.groupdocs.conversion.contracts/savedocumentstream/
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
