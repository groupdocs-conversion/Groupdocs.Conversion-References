---
title: "FontFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar teckensnittsdokument."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Definierar teckensnitts-dokument. Inkluderar följande typer: [Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Ttf), [Eot](../../com.groupdocs.conversion.filetypes/fontfiletype\#Eot), [Otf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Otf), [Cff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Cff), [Type1](../../com.groupdocs.conversion.filetypes/fontfiletype\#Type1), [Woff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff), [Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff2), Läs mer om teckensnittformat [här][].


[here]: https://wiki.fileformat.com/font
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontFileType()](#FontFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Ttf](#Ttf) | En fil med .ttf‑ändelse representerar teckensnittsfiler baserade på TrueType‑specifikationstekniken. |
| [Eot](#Eot) | En fil med .eot‑ändelse är ett OpenType‑teckensnitt som är inbäddat i ett dokument. |
| [Otf](#Otf) | En fil med .otf‑ändelse avser OpenType‑teckensnittformat. |
| [Cff](#Cff) | En fil med .cff‑ändelse är ett Compact Font Format och är även känt som PostScript Type 1 eller CIDFont. |
| [Type1](#Type1) | Type 1‑teckensnitt är en föråldrad Adobe‑teknik som var allmänt använd i skrivbordsbaserad publiceringsprogramvara och skrivare som kunde använda PostScript. |
| [Woff](#Woff) | En fil med .woff‑filändelse är en webbfontfil baserad på Web Open Font Format (WOFF). |
| [Woff2](#Woff2) | En fil med .woff‑filändelse är en webbfontfil baserad på Web Open Font Format (WOFF). |
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


En fil med .ttf‑filändelse representerar teckensnittsfiler baserade på TrueType‑specifikationernas teckensnittsteknik. Den designades och lanserades ursprungligen av Apple Computer, Inc för Mac OS och antogs senare av Microsoft för Windows‑OS. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/ttf/

### Eot {#Eot}
```
public static final FontFileType Eot
```


En fil med .eot‑filändelse är ett OpenType‑teckensnitt som är inbäddat i ett dokument. Dessa används främst i webbfilar såsom en webbsida. Den skapades av Microsoft och stöds av Microsoft‑produkter inklusive PowerPoint‑presentationen .pps‑fil. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/eot/

### Otf {#Otf}
```
public static final FontFileType Otf
```


En fil med .otf‑filändelse avser OpenType‑teckensnittformat. OTF‑formatet är mer skalbart och utökar de befintliga funktionerna i TTF‑format för digital typografi. Utvecklat av Microsoft och Adobe kombinerar OTF funktionerna i PostScript‑ och TrueType‑teckensnittformat. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/otf/

### Cff {#Cff}
```
public static final FontFileType Cff
```


En fil med .cff‑filändelse är ett Compact Font Format och är även känt som PostScript Type 1 eller CIDFont. CFF fungerar som en behållare för att lagra flera teckensnitt tillsammans i en enhet som kallas FontSet. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/cff/

### Type1 {#Type1}
```
public static final FontFileType Type1
```


Type 1‑teckensnitt är en föråldrad Adobe‑teknik som användes i stor utsträckning i skrivbordsbaserad publiceringsprogramvara och skrivare som kunde använda PostScript. Även om Type 1‑teckensnitt inte stöds i många moderna plattformar, webbläsare och mobila operativsystem, så stöds de fortfarande i vissa operativsystem. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/type1/

### Woff {#Woff}
```
public static final FontFileType Woff
```


En fil med .woff‑filändelse är en webbfontfil baserad på Web Open Font Format (WOFF). Den har en format‑specifik komprimerad behållare baserad på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnittstyper. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/woff/

### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


En fil med .woff‑filändelse är en webbfontfil baserad på Web Open Font Format (WOFF). Den har en format‑specifik komprimerad behållare baserad på antingen TrueType (.TTF) eller OpenType (.OTT) teckensnittstyper. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/font/woff/

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
