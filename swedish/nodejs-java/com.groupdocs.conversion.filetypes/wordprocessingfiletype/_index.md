---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar ordbehandlingsfiler som innehåller användarinformation i vanlig text eller rik textformat."
type: docs
weight: 28
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Definierar Word Processing‑filer som innehåller användarinformation i vanlig text eller Rich Text Format. Ett vanligt textfilformat innehåller oformaterad text och ingen teckensnitt‑ eller sidinställning etc. kan tillämpas. I kontrast tillåter ett Rich Text‑filformat formateringsalternativ såsom att ange teckensnittstyp, stilar (fet, kursiv, understruken osv.), sidmarginaler, rubriker, punktlistor och nummer, samt flera andra formateringsfunktioner. Inkluderar följande filtyper: [Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Doc), [Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docm), [Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docx), [Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dot), [Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotm), [Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotx), [Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Odt), [Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Ott), [Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Rtf), [Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Txt), [Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Md), Lär dig mer om Word Processing‑format [here][].


[here]: https://wiki.fileformat.com/word-processing
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingFileType()](#WordProcessingFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Doc](#Doc) | Filer med .doc‑ändelse representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. |
| [Docm](#Docm) | DOCM‑filer är dokument som skapats av Microsoft Word 2007 eller senare med möjlighet att köra makron. |
| [Docx](#Docx) | DOCX är ett välkänt format för Microsoft Word‑dokument. |
| [Dot](#Dot) | Filer med .DOT‑ändelse är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC‑ eller DOCX‑filer. |
| [Dotm](#Dotm) | En fil med DOTM‑ändelse representerar en mallfil skapad med Microsoft Word 2007 eller senare. |
| [Dotx](#Dotx) | Filer med DOTX‑ändelse är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX‑filer. |
| [Rtf](#Rtf) | Introducerat och dokumenterat av Microsoft, Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i applikationer. |
| [Odt](#Odt) | ODT‑filer är en typ av dokument som skapats med ordbehandlingsprogram baserade på OpenDocument Text File‑formatet. |
| [Ott](#Ott) | Filer med OTT‑ändelse representerar mall‑dokument som genererats av program i enlighet med OASIS' OpenDocument‑standardformat. |
| [Txt](#Txt) | En fil med .TXT‑ändelse representerar ett textdokument som innehåller vanlig text i form av rader. |
| [Md](#Md) | Textfiler skapade med Markdown‑språkdialekter sparas med filändelsen .MD eller .MARKDOWN. |
| [Ml](#Ml) | Ml‑fil |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Serialiseringskonstruktor

### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


Filer med .doc‑ändelse representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM-filer är Microsoft Word 2007 eller högre genererade dokument med möjlighet att köra makron. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/docm

### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX är ett välkänt format för Microsoft Word-dokument. Introducerat från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från ren binär till en kombination av XML- och binära filer. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/docx

### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Filer med .DOT‑tillägg är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC‑ eller DOCX‑filer. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/dot

### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


En fil med DOTM‑tillägg representerar en mallfil skapad med Microsoft Word 2007 eller senare. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Filer med DOTX‑tillägg är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX‑filer. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Introducerat och dokumenterat av Microsoft representerar Rich Text Format (RTF) en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT‑filer är en typ av dokument som skapats med ordbehandlingsprogram baserade på OpenDocument Text‑filformatet. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/odt

### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Filer med OTT‑tillägg representerar mall‑dokument som genererats av program i enlighet med OASIS OpenDocument‑standardformatet. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/ott

### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


En fil med .TXT‑tillägg representerar ett textdokument som innehåller vanlig text i form av rader. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final WordProcessingFileType Md
```


Textfiler skapade med Markdown‑språkdialekter sparas med filändelsen .MD eller .MARKDOWN. MD‑filer sparas i vanligt textformat som använder Markdown‑språket, vilket också inkluderar inline‑textsymboler som definierar hur text kan formateras, såsom indrag, tabellformatering, typsnitt och rubriker. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/word-processing/md

### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml‑fil

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
