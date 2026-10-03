---
title: "EBookFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert CAD‑documenten (Computer Aided Design) die worden gebruikt voor 3D‑grafische bestandsformaten en die 2D‑ of 3D‑ontwerpen kunnen bevatten."
type: docs
weight: 14
url: /nl/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Definieert CAD-documenten (Computer Aided Design) die worden gebruikt voor 3D-graphicsbestandsformaten en 2D- of 3D-ontwerpen kunnen bevatten.
Bevat de volgende typen:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Meer informatie over CAD‑formaten [hier](../https://wiki.fileformat.com/cad).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Epub](#Epub) | De EPUB‑extensie is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. |
|
|  | [Mobi](#Mobi) | Het MOBI‑bestandsformaat is een van de meest gebruikte e‑book bestandsformaten. |
|
|  | [Azw3](#Azw3) | AZW3, ook bekend als Kindle Format 8 (KF8), is de aangepaste versie van het AZW e‑book digitale bestandsformaat ontwikkeld voor Amazon Kindle‑apparaten. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Serialisatieconstructor


### Epub {#Epub}
```
public static final EBookFileType Epub
```


De EPUB‑extensie is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. Het formaat is inmiddels zo gangbaar geworden dat het wordt ondersteund door veel e‑readers en softwaretoepassingen. Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Het MOBI‑bestandsformaat is een van de meest gebruikte e‑book bestandsformaten. Het formaat is een verbetering ten opzichte van het oude OEB (Open Ebook Format)-formaat en werd gebruikt als propriëtair formaat voor de Mobipocket Reader. Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, ook bekend als Kindle Format 8 (KF8), is de aangepaste versie van het AZW e‑book digitale bestandsformaat ontwikkeld voor Amazon Kindle‑apparaten. Het formaat is een verbetering ten opzichte van oudere AZW‑bestanden en wordt alleen op Kindle Fire‑apparaten gebruikt met achterwaartse compatibiliteit voor het voorouderformaat, namelijk MOBI en AZW. Leer meer over dit bestandsformaat [hier](../https://docs.fileformat.com/ebook/azw3/).


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
