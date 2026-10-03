---
title: "PublisherFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Publisher-Dokumente."
type: docs
weight: 24
url: /de/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Definiert Publisher-Dokumente.
Enthält die folgenden Typen:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Weitere Informationen zu Schriftformaten finden Sie [hier](../https://wiki.fileformat.com/publisher).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Pub](#Pub) | Eine PUB‑Datei ist ein Microsoft Publisher‑Dokumentdateiformat. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Serialisierungskonstruktor


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Eine PUB‑Datei ist ein Microsoft Publisher‑Dokumentdateiformat. Sie wird verwendet, um verschiedene Arten von Layout‑Design‑Dokumenten wie Newsletter, Flyer, Broschüren, Postkarten usw. zu erstellen. PUB‑Dateien können Text, Raster‑ und Vektorbilder enthalten. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


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
