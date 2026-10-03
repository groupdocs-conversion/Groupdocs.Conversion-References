---
title: "SaveDocumentStream"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Descrive il delegato per salvare il documento convertito in uno stream di output."
type: docs
weight: 23
url: /it/java/com.groupdocs.conversion.contracts/savedocumentstream/
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

