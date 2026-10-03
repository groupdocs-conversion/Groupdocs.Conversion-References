---
title: "WordProcessingFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i file di elaborazione testi che contengono informazioni dell'utente in testo semplice o in formato rich text."
type: docs
weight: 28
url: /it/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Definisce i file di elaborazione testi che contengono informazioni dell'utente in formato testo semplice o testo formattato. Un formato di file di testo semplice contiene testo non formattato e non è possibile applicare impostazioni di carattere o di pagina, ecc. Al contrario, un formato di file di testo formattato consente opzioni di formattazione come impostare il tipo di carattere, gli stili (grassetto, corsivo, sottolineato, ecc.), i margini della pagina, le intestazioni, i punti elenco e i numeri, e diverse altre funzionalità di formattazione.
Include i seguenti tipi di file:
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
Scopri di più sui formati di elaborazione testi [qui](../https://wiki.fileformat.com/word-processing).


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Doc](#Doc) | I file con estensione .doc rappresentano documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato binario. |
|
|  | [Docm](#Docm) | I file DOCM sono documenti generati da Microsoft Word 2007 o versioni successive con la capacità di eseguire macro. |
|
|  | [Docx](#Docx) | DOCX è un formato molto noto per i documenti Microsoft Word. |
|
|  | [Dot](#Dot) | I file con estensione .DOT sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. |
|
|  | [Dotm](#Dotm) | Un file con estensione DOTM rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. |
|
|  | [Dotx](#Dotx) | I file con estensione DOTX sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. |
|
|  | [Rtf](#Rtf) | Introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni. |
|
|  | [Odt](#Odt) | I file ODT sono un tipo di documento creato con applicazioni di elaborazione testi basate sul formato OpenDocument Text. |
|
|  | [Ott](#Ott) | I file con estensione OTT rappresentano documenti modello generati da applicazioni conformi al formato standard OpenDocument di OASIS. |
|
|  | [Txt](#Txt) | Un file con estensione .TXT rappresenta un documento di testo che contiene testo semplice sotto forma di righe. |
|
|  | [Md](#Md) | I file di testo creati con dialetti del linguaggio Markdown vengono salvati con estensione .MD o .MARKDOWN. |
|
|  | [Ml](#Ml) | File Ml |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Costruttore di serializzazione


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


I file con estensione .doc rappresentano documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato binario.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


I file DOCM sono documenti generati da Microsoft Word 2007 o versioni successive con la capacità di eseguire macro.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX è un formato molto noto per i documenti Microsoft Word. Introdotto dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da binario puro a una combinazione di file XML e binari.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


I file con estensione .DOT sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Un file con estensione DOTM rappresenta un file modello creato con Microsoft Word 2007 o versioni successive.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


I file con estensione DOTX sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


I file ODT sono un tipo di documento creato con applicazioni di elaborazione testi basate sul formato OpenDocument Text.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


I file con estensione OTT rappresentano documenti modello generati da applicazioni conformi al formato standard OpenDocument di OASIS.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Un file con estensione .TXT rappresenta un documento di testo che contiene testo semplice sotto forma di righe.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


I file di testo creati con i dialetti del linguaggio Markdown vengono salvati con l'estensione .MD o .MARKDOWN. I file MD sono salvati in formato testo semplice che utilizza il linguaggio Markdown, il quale include anche simboli di testo in linea, definendo come un testo può essere formattato, ad esempio rientri, formattazione di tabelle, caratteri e intestazioni. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


File Ml


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
```


Opzioni di conversione predefinite preparate per il tipo di file


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
