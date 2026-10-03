---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of rich‑text‑formaat."
type: docs
weight: 28
url: /nl/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of rich text-indeling. Een platte-tekst bestandsindeling bevat onopgemaakte tekst en geen lettertype- of pagina-instellingen enz. kunnen worden toegepast. Daarentegen staat een rich text-indeling opmaakopties toe, zoals het instellen van lettertype, stijlen (vet, cursief, onderstrepen, enz.), paginamarges, koppen, opsommingstekens en nummers, en verschillende andere opmaakfuncties.
Bevat de volgende bestandstypen:
[Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Doc),
[Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docm),
[Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Docx),
[Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dot),
[Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotm),
[Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Dotx),
[Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Odt),
[Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Ott),
[Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Rtf),
[Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Txt),
[Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype#Md),
Lees meer over tekstverwerkingsformaten [hier](../https://wiki.fileformat.com/word-processing).


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Doc](#Doc) | Bestanden met de extensie .doc vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat. |
|
|  | [Docm](#Docm) | DOCM-bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. |
|
|  | [Docx](#Docx) | DOCX is een bekend formaat voor Microsoft Word-documenten. |
|
|  | [Dot](#Dot) | Bestanden met de extensie .DOT zijn sjabloonbestanden gemaakt door Microsoft Word met vooraf opgemaakte instellingen voor het genereren van verdere DOC- of DOCX-bestanden. |
|
|  | [Dotm](#Dotm) | Een bestand met de extensie DOTM vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger. |
|
|  | [Dotx](#Dotx) | Bestanden met de extensie DOTX zijn sjabloonbestanden gemaakt door Microsoft Word met vooraf opgemaakte instellingen voor het genereren van verdere DOCX-bestanden. |
|
|  | [Rtf](#Rtf) | Geïntroduceerd en gedocumenteerd door Microsoft, vertegenwoordigt Rich Text Format (RTF) een methode om opgemaakte tekst en afbeeldingen te coderen voor gebruik in toepassingen. |
|
|  | [Odt](#Odt) | ODT-bestanden zijn een type documenten die zijn gemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument Tekstbestandsformaat. |
|
|  | [Ott](#Ott) | Bestanden met de extensie OTT vertegenwoordigen sjabloondocumenten die door applicaties zijn gegenereerd in overeenstemming met de OASIS OpenDocument-standaardindeling. |
|
|  | [Txt](#Txt) | Een bestand met de extensie .TXT vertegenwoordigt een tekstdocument dat platte tekst in de vorm van regels bevat. |
|
|  | [Md](#Md) | Tekstbestanden gemaakt met Markdown-taaldialecten worden opgeslagen met de extensie .MD of .MARKDOWN. |
|
|  | [Ml](#Ml) | Ml-bestand |
|
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


Bestanden met de extensie .doc vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


DOCM-bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van platte binair naar een combinatie van XML- en binaire bestanden.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Bestanden met de extensie .DOT zijn sjabloonbestanden gemaakt door Microsoft Word met vooraf opgemaakte instellingen voor het genereren van verdere DOC- of DOCX-bestanden.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Een bestand met de extensie DOTM vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Bestanden met de extensie DOTX zijn sjabloonbestanden gemaakt door Microsoft Word met vooraf opgemaakte instellingen voor het genereren van verdere DOCX-bestanden.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Geïntroduceerd en gedocumenteerd door Microsoft, vertegenwoordigt Rich Text Format (RTF) een methode om opgemaakte tekst en afbeeldingen te coderen voor gebruik in toepassingen.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


ODT-bestanden zijn een type documenten die zijn gemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument Tekstbestandsformaat.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Bestanden met de extensie OTT vertegenwoordigen sjabloondocumenten die door applicaties zijn gegenereerd in overeenstemming met de OASIS OpenDocument-standaardindeling.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Een bestand met de extensie .TXT vertegenwoordigt een tekstdocument dat platte tekst in de vorm van regels bevat.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


Tekstbestanden gemaakt met Markdown‑taaldialecten worden opgeslagen met de bestandsextensie .MD of .MARKDOWN. MD‑bestanden worden opgeslagen in platte‑tekstformaat dat Markdown‑taal gebruikt, die ook inline‑tekens bevat, waarmee wordt gedefinieerd hoe een tekst kan worden opgemaakt, zoals inspringingen, tabelopmaak, lettertypen en koppen. Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml-bestand


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
