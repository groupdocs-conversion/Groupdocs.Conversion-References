---
title: "EBookFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert CAD‑Dokumente (Computer Aided Design), die für 3D‑Grafikdateiformate verwendet werden und 2D‑ oder 3D‑Entwürfe enthalten können."
type: docs
weight: 14
url: /de/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Definiert CAD-Dokumente (Computer Aided Design), die für 3D‑Grafikdateiformate verwendet werden und 2D‑ oder 3D‑Designs enthalten können.
Enthält die folgenden Typen:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Erfahren Sie mehr über CAD‑Formate [hier](../https://wiki.fileformat.com/cad).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Epub](#Epub) | Die EPUB-Erweiterung ist ein E‑Book-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Leser bereitstellt. |
|
|  | [Mobi](#Mobi) | Das MOBI-Dateiformat ist eines der am weitesten verbreiteten E‑Book-Dateiformate. |
|
|  | [Azw3](#Azw3) | AZW3, auch bekannt als Kindle Format 8 (KF8), ist die modifizierte Version des AZW‑E‑Book‑Digitaldateiformats, das für Amazon‑Kindle‑Geräte entwickelt wurde. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Serialisierungskonstruktor


### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB-Erweiterung ist ein E‑Book-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Verbraucher bereitstellt. Das Format ist inzwischen so verbreitet, dass es von vielen E‑Readern und Softwareanwendungen unterstützt wird. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Das MOBI-Dateiformat ist eines der am weitesten verbreiteten E‑Book-Dateiformate. Das Format ist eine Weiterentwicklung des alten OEB (Open Ebook Format)-Formats und wurde als proprietäres Format für den Mobipocket Reader verwendet. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, auch bekannt als Kindle Format 8 (KF8), ist die modifizierte Version des AZW‑E‑Book‑Digitaldateiformats, das für Amazon‑Kindle‑Geräte entwickelt wurde. Das Format ist eine Weiterentwicklung älterer AZW‑Dateien und wird nur auf Kindle‑Fire‑Geräten verwendet, wobei es abwärtskompatibel zum Vorgängerformat, d. h. MOBI und AZW, ist. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/ebook/azw3/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Standard‑Konvertierungsoptionen für den Dateityp vorbereitet


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
