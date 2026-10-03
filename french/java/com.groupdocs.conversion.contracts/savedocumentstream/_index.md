---
title: "SaveDocumentStream"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Décrit le délégué pour enregistrer le document converti dans le flux de sortie."
type: docs
weight: 23
url: /fr/java/com.groupdocs.conversion.contracts/savedocumentstream/
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

