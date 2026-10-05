---
title: "PdfFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert Pdf-documenten."
type: docs
weight: 21
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Definieert Pdf‑documenten. Bevat de volgende bestandstypen: [Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype\#Pdf),
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfFileType()](#PdfFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Pdf](#Pdf) | Portable Document Format (PDF) is een type document dat in de jaren 1990 door Adobe is gemaakt. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Serialisatieconstructor

### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) is een type document dat in de jaren 1990 door Adobe is gemaakt. Het doel van dit bestandsformaat was het introduceren van een standaard voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/view/pdf

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
