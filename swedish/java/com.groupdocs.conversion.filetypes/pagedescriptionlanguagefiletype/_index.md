---
title: "PageDescriptionLanguageFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar sidbeskrivningsdokument."
type: docs
weight: 20
url: /sv/java/com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PageDescriptionLanguageFileType extends FileType implements Serializable
```

Definierar sidbeskrivningsdokument.
Inkluderar följande typer:
[Svg](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Svg),
[Eps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Eps),
[Cgm](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Cgm),
[Xps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Xps),
[Tex](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Tex),
[Ps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Ps),
[Pcl](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Pcl),
[Oxps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Oxps),

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PageDescriptionLanguageFileType()](#PageDescriptionLanguageFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Svg](#Svg) | En SVG‑fil är en Scalar Vector Graphics‑fil som använder ett XML‑baserat textformat för att beskriva utseendet på en bild. |
|
|  | [Eps](#Eps) | Filer med EPS‑tillägg beskriver i huvudsak ett Encapsulated PostScript‑språkprogram som beskriver utseendet på en enskild sida. |
|
|  | [Cgm](#Cgm) | Computer Graphics Metafile (CGM) är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. |
|
|  | [Xps](#Xps) | En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. |
|
|  | [Tex](#Tex) | TeX är ett språk som omfattar både programmering och markup‑funktioner, och används för att sätta dokument. |
|
|  | [Ps](#Ps) | PostScript (PS) är ett allmänt syftande sidbeskrivningsspråk som används inom skrivbords- och elektronisk publicering. |
|
|  | [Pcl](#Pcl) | PCL står för Printer Command Language, vilket är ett Page Description Language som introducerades av Hewlett Packard (HP). |
|
|  | [Oxps](#Oxps) | Filformatet OXPS är känt som Open XML Paper Specification. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PageDescriptionLanguageFileType() {#PageDescriptionLanguageFileType--}
```
public PageDescriptionLanguageFileType()
```


Serialiseringskonstruktor


### Svg {#Svg}
```
public static final PageDescriptionLanguageFileType Svg
```


En SVG‑fil är en Scalar Vector Graphics‑fil som använder ett XML‑baserat textformat för att beskriva utseendet på en bild. Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/svg).


### Eps {#Eps}
```
public static final PageDescriptionLanguageFileType Eps
```


Filer med EPS‑tillägg beskriver i huvudsak ett Encapsulated PostScript‑språkprogram som beskriver utseendet på en enskild sida. Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/eps).


### Cgm {#Cgm}
```
public static final PageDescriptionLanguageFileType Cgm
```


Computer Graphics Metafile (CGM) är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och många funktionsbestämmelser för bildproduktion. Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/cgm).


### Xps {#Xps}
```
public static final PageDescriptionLanguageFileType Xps
```


En XPS‑fil representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Detta format utvecklades av Microsoft som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument. Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/xps).


### Tex {#Tex}
```
public static final PageDescriptionLanguageFileType Tex
```


TeX är ett språk som omfattar både programmering och markup‑funktioner, och används för att sätta dokument. Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/tex).


### Ps {#Ps}
```
public static final PageDescriptionLanguageFileType Ps
```


PostScript (PS) är ett allmänt syfte sidbeskrivningsspråk som används inom skrivbords- och elektronisk publicering. Huvudfokus för PostScript (PS) är att underlätta tvådimensionell grafisk design. Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/ps).


### Pcl {#Pcl}
```
public static final PageDescriptionLanguageFileType Pcl
```


PCL står för Printer Command Language, vilket är ett sidbeskrivningsspråk introducerat av Hewlett Packard (HP). Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/pcl).


### Oxps {#Oxps}
```
public static final PageDescriptionLanguageFileType Oxps
```


Filformatet OXPS är känt som Open XML Paper Specification. Det är ett sidbeskrivningsspråk och dokumentformat. Microsoft är utvecklaren av detta format. OXPS‑filformatet är mycket likt PDF‑filer. Läs mer om detta filformat [här](../https://docs.fileformat.com/page-description-language/oxps).


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
