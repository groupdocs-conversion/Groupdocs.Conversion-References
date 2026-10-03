---
title: "PublisherFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti Publisher."
type: docs
weight: 24
url: /it/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Definisce i documenti Publisher.
Include i seguenti tipi:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Scopri di più sui formati di Font [qui](../https://wiki.fileformat.com/publisher).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Pub](#Pub) | Un file PUB è un formato di documento Microsoft Publisher. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Costruttore di serializzazione


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Un file PUB è un formato di documento Microsoft Publisher. Viene utilizzato per creare diversi tipi di documenti di layout di design come newsletter, volantini, brochure, cartoline, ecc. I file PUB possono contenere testo, immagini raster e vettoriali. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
