---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of opgemaakte tekst."
type: docs
weight: 28
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Definieert Word Processing‑bestanden die gebruikersinformatie bevatten in platte tekst of Rich Text‑formaat. Een platte‑tekst bestandsformaat bevat onopgemaakte tekst en er kunnen geen lettertype‑ of pagina‑instellingen enz. worden toegepast. Daarentegen staat een Rich Text‑bestandsformaat opmaakopties toe, zoals het instellen van lettertype‑type, stijlen (vet, cursief, onderstrepen, enz.), paginamarges, koppen, opsommingstekens en nummers, en verschillende andere opmaakfuncties. Bevat de volgende bestandstypen: [Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Doc), [Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docm), [Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docx), [Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dot), [Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotm), [Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotx), [Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Odt), [Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Ott), [Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Rtf), [Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Txt), [Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Md), Meer informatie over Word Processing‑formaten [hier][].


[here]: https://wiki.fileformat.com/word-processing
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingFileType()](#WordProcessingFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Doc](#Doc) | Bestanden met de .doc‑extensie vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat. |
| [Docm](#Docm) | DOCM‑bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. |
| [Docx](#Docx) | DOCX is een bekend formaat voor Microsoft Word‑documenten. |
| [Dot](#Dot) | Bestanden met de .DOT‑extensie zijn sjabloonbestanden die zijn gemaakt door Microsoft Word om vooraf opgemaakte instellingen te hebben voor het genereren van verdere DOC‑ of DOCX‑bestanden. |
| [Dotm](#Dotm) | Een bestand met de DOTM‑extensie vertegenwoordigt een sjabloonbestand dat is gemaakt met Microsoft Word 2007 of hoger. |
| [Dotx](#Dotx) | Bestanden met de DOTX‑extensie zijn sjabloonbestanden die zijn gemaakt door Microsoft Word om vooraf opgemaakte instellingen te hebben voor het genereren van verdere DOCX‑bestanden. |
| [Rtf](#Rtf) | Introductie en documentatie door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en grafische elementen te coderen voor gebruik binnen applicaties. |
| [Odt](#Odt) | ODT‑bestanden zijn een type documenten die zijn gemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument Tekstbestandsformaat. |
| [Ott](#Ott) | Bestanden met de OTT‑extensie vertegenwoordigen sjabloondocumenten die zijn gegenereerd door applicaties in overeenstemming met de OASIS OpenDocument‑standaard. |
| [Txt](#Txt) | Een bestand met de .TXT‑extensie vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. |
| [Md](#Md) | Tekstbestanden die zijn gemaakt met Markdown‑taaldialecten worden opgeslagen met de .MD‑ of .MARKDOWN‑bestandsextensie. |
| [Ml](#Ml) | Ml‑bestand |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Serialisatieconstructor

### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


Bestanden met de .doc‑extensie vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/doc

### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM‑bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/docm

### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX is een bekend formaat voor Microsoft Word‑documenten. Introductie vanaf 2007 met de release van Microsoft Office 2007, de structuur van dit nieuwe documentformaat werd gewijzigd van platte binaire naar een combinatie van XML‑ en binaire bestanden. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/docx

### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Bestanden met .DOT‑extensie zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOC‑ of DOCX‑bestanden. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/dot

### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Een bestand met DOTM‑extensie vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Bestanden met DOTX‑extensie zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOCX‑bestanden. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Introductie en documentatie door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en grafische elementen te coderen voor gebruik binnen applicaties. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT‑bestanden zijn een type documenten die zijn gemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument‑tekstbestandsformaat. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/odt

### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Bestanden met OTT‑extensie vertegenwoordigen sjabloondocumenten die door applicaties worden gegenereerd in overeenstemming met het OpenDocument‑standaardformaat van OASIS. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/ott

### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Een bestand met .TXT‑extensie vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final WordProcessingFileType Md
```


Tekstbestanden gemaakt met Markdown‑taaldialecten worden opgeslagen met de .MD‑ of .MARKDOWN‑bestandsextensie. MD‑bestanden worden opgeslagen in platte‑tekstformaat dat Markdown‑taal gebruikt, die ook inline‑tekensymbolen bevat, waarmee wordt bepaald hoe tekst kan worden opgemaakt, zoals inspringingen, tabelopmaak, lettertypen en koppen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/md

### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml‑bestand

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
