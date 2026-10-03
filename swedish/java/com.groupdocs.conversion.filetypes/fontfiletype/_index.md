---
title: "FontFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar teckensnittsdokument."
type: docs
weight: 17
url: /sv/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Definierar teckensnittsdokument.
Inkluderar följande typer:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Läs mer om teckensnittformat [här](../https://wiki.fileformat.com/font).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Ttf](#Ttf) | En fil med .ttf‑tillägg representerar teckensnittsfiler baserade på TrueType‑specifikationernas teckensnittsteknologi. |
|
|  | [Eot](#Eot) | En fil med .eot‑tillägg är ett OpenType‑teckensnitt som är inbäddat i ett dokument. |
|
|  | [Otf](#Otf) | En fil med .otf‑tillägg avser OpenType‑teckensnittformat. |
|
|  | [Cff](#Cff) | En fil med .cff‑tillägg är ett Compact Font Format och är även känt som PostScript Type 1 eller CIDFont. |
|
|  | [Type1](#Type1) | Type 1‑teckensnitt är en föråldrad Adobe‑teknik som var allmänt använd i skrivbordsbaserad publiceringsprogramvara och skrivare som kunde använda PostScript. |
|
|  | [Woff](#Woff) | En fil med .woff‑tillägg är en webbteckensnittsfil baserad på Web Open Font Format (WOFF). |
|
|  | [Woff2](#Woff2) | En fil med .woff‑tillägg är en webbteckensnittsfil baserad på Web Open Font Format (WOFF). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Serialiseringskonstruktor


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


En fil med .ttf‑tillägg representerar teckensnittsfiler baserade på TrueType‑specifikationernas teckensnittsteknologi. Den designades och lanserades ursprungligen av Apple Computer, Inc för Mac OS och antogs senare av Microsoft för Windows OS. Läs mer om detta filformat [här](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


En fil med .eot‑tillägg är ett OpenType‑teckensnitt som är inbäddat i ett dokument. Dessa används främst i webbfilers som en webbsida. Den skapades av Microsoft och stöds av Microsoft‑produkter inklusive PowerPoint‑presentationer (.pps‑filer). Läs mer om detta filformat [här](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


En fil med .otf‑tillägg avser OpenType‑teckensnittformat. OTF‑teckensnittformatet är mer skalbart och utökar de befintliga funktionerna i TTF‑formaten för digital typografi. Utvecklat av Microsoft och Adobe kombinerar OTF funktionerna i PostScript‑ och TrueType‑teckensnittformat. Läs mer om detta filformat [här](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


En fil med .cff‑tillägg är ett Compact Font Format och är även känt som PostScript Type 1 eller CIDFont. CFF fungerar som en behållare för att lagra flera teckensnitt tillsammans i en enhet som kallas FontSet. Läs mer om detta filformat [här](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1‑teckensnitt är en föråldrad Adobe‑teknik som var allmänt använd i skrivbordsbaserad publiceringsprogramvara och skrivare som kunde använda PostScript. Även om Type 1‑teckensnitt inte stöds i många moderna plattformar, webbläsare och mobila operativsystem, stöds de fortfarande i vissa operativsystem. Läs mer om detta filformat [här](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


En fil med .woff‑tillägg är en webbteckensnittsfil baserad på Web Open Font Format (WOFF). Den har ett format‑specifikt komprimerat paket baserat på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnittstyper. Läs mer om detta filformat [här](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


En fil med .woff‑tillägg är en webbteckensnittsfil baserad på Web Open Font Format (WOFF). Den har ett format‑specifikt komprimerat paket baserat på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnittstyper. Läs mer om detta filformat [här](../https://docs.fileformat.com/font/woff/).


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
