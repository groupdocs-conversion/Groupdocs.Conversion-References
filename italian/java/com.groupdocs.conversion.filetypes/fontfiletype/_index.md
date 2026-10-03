---
title: "FontFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti Font."
type: docs
weight: 17
url: /it/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Definisce i documenti Font.
Include i seguenti tipi:
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
Scopri di più sui formati dei caratteri [qui](../https://wiki.fileformat.com/font).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Ttf](#Ttf) | Un file con estensione .ttf rappresenta file di carattere basati sulla tecnologia dei font secondo le specifiche TrueType. |
|
|  | [Eot](#Eot) | Un file con estensione .eot è un font OpenType incorporato in un documento. |
|
|  | [Otf](#Otf) | Un file con estensione .otf si riferisce al formato di font OpenType. |
|
|  | [Cff](#Cff) | Un file con estensione .cff è un Compact Font Format, noto anche come PostScript Type 1 o CIDFont. |
|
|  | [Type1](#Type1) | I font Type 1 sono una tecnologia Adobe obsoleta, ampiamente utilizzata nei software di desktop publishing e nelle stampanti che supportavano PostScript. |
|
|  | [Woff](#Woff) | Un file con estensione .woff è un font web basato sul Web Open Font Format (WOFF). |
|
|  | [Woff2](#Woff2) | Un file con estensione .woff è un font web basato sul Web Open Font Format (WOFF). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Costruttore di serializzazione


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Un file con estensione .ttf rappresenta file di carattere basati sulla tecnologia dei font secondo le specifiche TrueType. È stato inizialmente progettato e lanciato da Apple Computer, Inc per Mac OS ed è stato successivamente adottato da Microsoft per Windows OS. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


Un file con estensione .eot è un font OpenType incorporato in un documento. Questi sono principalmente usati nei file web, come le pagine web. È stato creato da Microsoft ed è supportato dai prodotti Microsoft, inclusi i file di presentazione PowerPoint .pps. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


Un file con estensione .otf si riferisce al formato di font OpenType. Il formato OTF è più scalabile ed estende le funzionalità esistenti dei formati TTF per la tipografia digitale. Sviluppato da Microsoft e Adobe, OTF combina le caratteristiche dei formati di font PostScript e TrueType. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


Un file con estensione .cff è un Compact Font Format, noto anche come PostScript Type 1 o CIDFont. CFF funge da contenitore per memorizzare più font insieme in un'unica unità chiamata FontSet. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


I font Type 1 sono una tecnologia Adobe obsoleta, ampiamente utilizzata nei software di desktop publishing e nelle stampanti che supportavano PostScript. Sebbene i font Type 1 non siano supportati in molte piattaforme moderne, nei browser web e nei sistemi operativi mobili, sono ancora supportati in alcuni sistemi operativi. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


Un file con estensione .woff è un font web basato sul Web Open Font Format (WOFF). Possiede un contenitore compresso specifico del formato basato su font TrueType (.TTF) o OpenType (.OTT). Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Un file con estensione .woff è un font web basato sul Web Open Font Format (WOFF). Possiede un contenitore compresso specifico del formato basato su font TrueType (.TTF) o OpenType (.OTT). Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/font/woff/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
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
