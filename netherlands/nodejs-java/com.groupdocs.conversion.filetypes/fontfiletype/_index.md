---
title: "FontFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert lettertype‑documenten."
type: docs
weight: 17
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Definieert lettertype‑documenten. Bevat de volgende typen: [Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Ttf), [Eot](../../com.groupdocs.conversion.filetypes/fontfiletype\#Eot), [Otf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Otf), [Cff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Cff), [Type1](../../com.groupdocs.conversion.filetypes/fontfiletype\#Type1), [Woff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff), [Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff2), Meer informatie over lettertype‑formaten [hier][].


[here]: https://wiki.fileformat.com/font
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontFileType()](#FontFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Ttf](#Ttf) | Een bestand met de extensie .ttf vertegenwoordigt lettertype‑bestanden die gebaseerd zijn op de TrueType‑specificaties van lettertype‑technologie. |
| [Eot](#Eot) | Een bestand met de extensie .eot is een OpenType‑lettertype dat in een document is ingebed. |
| [Otf](#Otf) | Een bestand met de extensie .otf verwijst naar het OpenType‑lettertype‑formaat. |
| [Cff](#Cff) | Een bestand met de extensie .cff is een Compact Font Format en staat ook bekend als een PostScript Type 1, of CIDFont. |
| [Type1](#Type1) | Type 1‑lettertypen zijn een verouderde Adobe‑technologie die veel werd gebruikt in desktop‑publissoftware en printers die PostScript konden gebruiken. |
| [Woff](#Woff) | Een bestand met de extensie .woff is een web‑lettertype‑bestand gebaseerd op het Web Open Font Format (WOFF). |
| [Woff2](#Woff2) | Een bestand met de extensie .woff is een web‑lettertype‑bestand gebaseerd op het Web Open Font Format (WOFF). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Serialisatieconstructor

### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Een bestand met de extensie .ttf vertegenwoordigt lettertype‑bestanden die gebaseerd zijn op de TrueType‑specificaties van lettertype‑technologie. Het werd oorspronkelijk ontworpen en uitgebracht door Apple Computer, Inc voor Mac OS en later overgenomen door Microsoft voor Windows OS. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/ttf/

### Eot {#Eot}
```
public static final FontFileType Eot
```


Een bestand met de extensie .eot is een OpenType‑lettertype dat in een document is ingebed. Deze worden voornamelijk gebruikt in web‑bestanden zoals een webpagina. Het werd gecreëerd door Microsoft en wordt ondersteund door Microsoft‑producten, inclusief PowerPoint‑presentaties met de extensie .pps. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/eot/

### Otf {#Otf}
```
public static final FontFileType Otf
```


Een bestand met de extensie .otf verwijst naar het OpenType‑lettertype‑formaat. Het OTF‑formaat is schaalbaarder en breidt de bestaande functies van TTF‑formaten uit voor digitale typografie. Ontwikkeld door Microsoft en Adobe, combineert OTF de kenmerken van PostScript‑ en TrueType‑lettertype‑formaten. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/otf/

### Cff {#Cff}
```
public static final FontFileType Cff
```


Een bestand met de extensie .cff is een Compact Font Format en staat ook bekend als een PostScript Type 1, of CIDFont. CFF fungeert als een container om meerdere lettertypen samen op te slaan in één eenheid, bekend als een FontSet. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/cff/

### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1‑lettertypen zijn een verouderde Adobe‑technologie die veel werd gebruikt in desktop‑publissoftware en printers die PostScript konden gebruiken. Hoewel Type 1‑lettertypen niet worden ondersteund op veel moderne platforms, webbrowsers en mobiele besturingssystemen, worden ze nog steeds ondersteund op sommige besturingssystemen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/type1/

### Woff {#Woff}
```
public static final FontFileType Woff
```


Een bestand met de extensie .woff is een web‑lettertype‑bestand gebaseerd op het Web Open Font Format (WOFF). Het heeft een formaat‑specifieke gecomprimeerde container gebaseerd op ofwel TrueType (.TTF) of OpenType (.OTT) lettertype‑typen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/woff/

### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Een bestand met de extensie .woff is een web‑lettertype‑bestand gebaseerd op het Web Open Font Format (WOFF). Het heeft een formaat‑specifieke gecomprimeerde container gebaseerd op ofwel TrueType (.TTF) of OpenType (.OTT) lettertype‑typen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/font/woff/

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
