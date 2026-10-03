---
title: "PageDescriptionLanguageFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti di descrizione della pagina."
type: docs
weight: 20
url: /it/java/com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PageDescriptionLanguageFileType extends FileType implements Serializable
```

Definisce i documenti di descrizione della pagina.
Include i seguenti tipi:
[Svg](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Svg),
[Eps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Eps),
[Cgm](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Cgm),
[Xps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Xps),
[Tex](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Tex),
[Ps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Ps),
[Pcl](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Pcl),
[Oxps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Oxps),

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PageDescriptionLanguageFileType()](#PageDescriptionLanguageFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Svg](#Svg) | Un file SVG è un file Scalar Vector Graphics che utilizza un formato di testo basato su XML per descrivere l'aspetto di un'immagine. |
|
|  | [Eps](#Eps) | I file con estensione EPS descrivono essenzialmente un programma in linguaggio Encapsulated PostScript che definisce l'aspetto di una singola pagina. |
|
|  | [Cgm](#Cgm) | Computer Graphics Metafile (CGM) è un formato metafile gratuito, indipendente dalla piattaforma, standard internazionale per l'archiviazione e lo scambio di grafica vettoriale (2D), grafica raster e testo. |
|
|  | [Xps](#Xps) | Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications creati da Microsoft. |
|
|  | [Tex](#Tex) | TeX è un linguaggio che comprende sia funzionalità di programmazione sia di markup, utilizzato per impaginare documenti. |
|
|  | [Ps](#Ps) | PostScript (PS) è un linguaggio di descrizione di pagina di uso generale impiegato nel settore della pubblicazione desktop ed elettronica. |
|
|  | [Pcl](#Pcl) | PCL sta per Printer Command Language, che è un linguaggio di descrizione di pagina introdotto da Hewlett Packard (HP). |
|
|  | [Oxps](#Oxps) | Il formato file OXPS è noto come Open XML Paper Specification. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PageDescriptionLanguageFileType() {#PageDescriptionLanguageFileType--}
```
public PageDescriptionLanguageFileType()
```


Costruttore di serializzazione


### Svg {#Svg}
```
public static final PageDescriptionLanguageFileType Svg
```


Un file SVG è un file Scalar Vector Graphics che utilizza un formato di testo basato su XML per descrivere l'aspetto di un'immagine. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/svg).


### Eps {#Eps}
```
public static final PageDescriptionLanguageFileType Eps
```


I file con estensione EPS descrivono essenzialmente un programma di linguaggio Encapsulated PostScript che ne definisce l'aspetto di una singola pagina. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/eps).


### Cgm {#Cgm}
```
public static final PageDescriptionLanguageFileType Cgm
```


Computer Graphics Metafile (CGM) è un formato metafile gratuito, indipendente dalla piattaforma, standard internazionale per l'archiviazione e lo scambio di grafica vettoriale (2D), grafica raster e testo. CGM utilizza un approccio orientato agli oggetti e molte funzioni per la produzione di immagini. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/cgm).


### Xps {#Xps}
```
public static final PageDescriptionLanguageFileType Xps
```


Un file XPS rappresenta file di layout di pagina basati sulle XML Paper Specifications create da Microsoft. Questo formato è stato sviluppato da Microsoft come sostituto del formato file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/xps).


### Tex {#Tex}
```
public static final PageDescriptionLanguageFileType Tex
```


TeX è un linguaggio che comprende sia funzionalità di programmazione sia di markup, utilizzato per impaginare documenti. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/tex).


### Ps {#Ps}
```
public static final PageDescriptionLanguageFileType Ps
```


PostScript (PS) è un linguaggio di descrizione di pagina di uso generale impiegato nel settore della pubblicazione desktop ed elettronica. L'obiettivo principale di PostScript (PS) è facilitare la progettazione grafica bidimensionale. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/ps).


### Pcl {#Pcl}
```
public static final PageDescriptionLanguageFileType Pcl
```


PCL sta per Printer Command Language, che è un linguaggio di descrizione di pagina introdotto da Hewlett Packard (HP). Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/page-description-language/pcl).


### Oxps {#Oxps}
```
public static final PageDescriptionLanguageFileType Oxps
```


Il formato file OXPS è noto come Open XML Paper Specification. È un linguaggio di descrizione di pagina e formato documento. Microsoft è lo sviluppatore di questo formato. Il formato file OXPS è molto simile a questi file PDF. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/page-description-language/oxps).


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
