---
title: "VideoFiltyp"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar videodokument Inkluderar följande typer        Läs mer om videoformat här."
type: docs
weight: 26
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Definierar videodokument Inkluderar följande typer: , , , , , , , Läs mer om videoformat [here][].


[here]: https://docs.fileformat.com/video/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VideoFileType()](#VideoFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Mp4](#Mp4) | MP4 (kort för MPEG‑4 Part 14) är ett filformat baserat på ISO/IEC 14496‑12:2004 som bygger på QuickTime File Format men formellt specificerar stöd för Initial Object Descriptors (IOD) och andra MPEG‑funktioner. |
| [Avi](#Avi) | AVI‑filformatet är ett Audio Video‑multimediakontainerfilformat som introducerades av Microsoft. |
| [Flv](#Flv) | FLV (Flash Video) är ett containerfilformat med .flv‑tillägget. |
| [Mkv](#Mkv) | MKV (Matroska Video) är en multimediakontainer liknande MOV‑ och AVI‑format men den stödjer mer än ett ljud‑ och undertextspår i samma fil. |
| [Mov](#Mov) | MOV‑ eller QuickTime‑filformatet är en multimediakontainer som utvecklats av Apple: innehåller ett eller flera spår, där varje spår håller en viss datatyp, t.ex. |
| [Webm](#Webm) | En fil med .webm‑tillägg är en videofil baserad på det öppna, royalty‑fria WebM‑filformatet. |
| [Wmv](#Wmv) | Windows Media Video är det komprimerade videoformat som utvecklats av Microsoft. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Serialiseringskonstruktor

### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (kort för MPEG‑4 Part 14) är ett filformat baserat på ISO/IEC 14496‑12:2004 som bygger på QuickTime File Format men formellt specificerar stöd för Initial Object Descriptors (IOD) och andra MPEG‑funktioner. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/mp4/

### Avi {#Avi}
```
public static final VideoFileType Avi
```


AVI‑filformatet är ett Audio Video‑multimediakontainerfilformat som introducerades av Microsoft. Det innehåller ljud‑ och videodata som skapats och komprimerats med flera codecs (kodare/avkodare) såsom XVid och DivX. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/avi/

### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) är ett containerfilformat med .flv‑tillägget. FLV används för att leverera ljud‑/videoinnehåll över internet med Adobe Flash Player eller Adobe Air. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/flv/

### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) är en multimediakontainer liknande MOV‑ och AVI‑format men den stödjer mer än ett ljud‑ och undertextspår i samma fil. En MKV‑fil är Matroska‑multimediakontainerformatet som används för video. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/mkv/

### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV- eller QuickTime-filformatet är en multimediabehållare som utvecklats av Apple: innehåller ett eller flera spår, där varje spår innehåller en viss typ av data, t.ex. video, ljud, text osv. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/mov/

### Webm {#Webm}
```
public static final VideoFileType Webm
```


En fil med .webm‑tillägg är en videofil baserad på det öppna, royaltyfria WebM‑filformatet. Den har designats för att dela video på webben och definierar filbehållarens struktur inklusive video‑ och ljudformat. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/webm//

### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video är det komprimerade videoformatet som utvecklats av Microsoft. Efter standardiseringen av Society of Motion Picture and Television Engineers (SMPTE) anses WMV nu vara ett öppet standardformat. Läs mer om detta filformat [here][].


[here]: https://docs.fileformat.com/video/wmv/

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
