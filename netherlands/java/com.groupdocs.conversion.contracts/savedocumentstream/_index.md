---
title: "SaveDocumentStream"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Beschrijft een delegate voor het opslaan van het geconverteerde document in een output-stroom."
type: docs
weight: 23
url: /nl/java/com.groupdocs.conversion.contracts/savedocumentstream/
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

