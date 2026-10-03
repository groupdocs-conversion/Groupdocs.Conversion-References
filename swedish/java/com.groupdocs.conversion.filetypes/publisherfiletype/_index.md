---
title: "PublisherFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar Publisher-dokument."
type: docs
weight: 24
url: /sv/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Definierar Publisher-dokument.
Inkluderar följande typer:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Läs mer om teckensnittformat [här](../https://wiki.fileformat.com/publisher).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Pub](#Pub) | En PUB‑fil är ett Microsoft Publisher-dokumentfilformat. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Serialiseringskonstruktor


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


En PUB‑fil är ett Microsoft Publisher-dokumentfilformat. Den används för att skapa flera typer av designlayoutdokument såsom nyhetsbrev, flyers, broschyrer, vykort osv. PUB‑filer kan innehålla text, raster- och vektorbilder. Läs mer om detta filformat [här](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


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
