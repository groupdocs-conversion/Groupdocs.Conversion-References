---
title: "EBookFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar CAD‑dokument (Computer Aided Design) som används för 3D‑grafikfilformat och kan innehålla 2D‑ eller 3D‑designer."
type: docs
weight: 14
url: /sv/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Definierar CAD-dokument (Computer Aided Design) som används för 3D-grafikfilformat och kan innehålla 2D- eller 3D-design.
Inkluderar följande typer:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Läs mer om CAD‑format [här](../https://wiki.fileformat.com/cad).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Epub](#Epub) | EPUB‑extension är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för utgivare och konsumenter. |
|
|  | [Mobi](#Mobi) | MOBI‑filformatet är ett av de mest använda e‑bokfilformaten. |
|
|  | [Azw3](#Azw3) | AZW3, även känt som Kindle Format 8 (KF8), är den modifierade versionen av AZW‑e‑bokfilformatet som utvecklats för Amazon Kindle‑enheter. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Serialiseringskonstruktor


### Epub {#Epub}
```
public static final EBookFileType Epub
```


EPUB‑extension är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för utgivare och konsumenter. Formatet har nu blivit så vanligt att det stöds av många e‑läsare och programvaror. Läs mer om detta filformat [här](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


MOBI‑filformatet är ett av de mest använda e‑bokfilformaten. Formatet är en förbättring av det gamla OEB (Open Ebook Format)-formatet och användes som proprietärt format för Mobipocket Reader. Läs mer om detta filformat [här](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, även känt som Kindle Format 8 (KF8), är den modifierade versionen av AZW‑e‑bokfilformatet som utvecklats för Amazon Kindle‑enheter. Formatet är en förbättring av äldre AZW‑filer och används endast på Kindle Fire‑enheter med bakåtkompatibilitet för det föregående filformatet, dvs. MOBI och AZW. Läs mer om detta filformat [här](../https://docs.fileformat.com/ebook/azw3/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
