---
title: "VideoFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce documenti video. Include i seguenti tipi        Scopri di più sui formati video qui."
type: docs
weight: 26
url: /it/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Definisce documenti video. Include i seguenti tipi: , , , , , , , Scopri di più sui formati video [qui](../https://docs.fileformat.com/video/).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (abbreviazione di MPEG-4 Part 14) è un formato di file basato su ISO/IEC 14496-12:2004, derivato dal QuickTime File Format, ma specifica formalmente il supporto per gli Initial Object Descriptors (IOD) e altre funzionalità MPEG. |
|
|  | [Avi](#Avi) | Il formato di file AVI è un contenitore multimediale Audio Video introdotto da Microsoft. |
|
|  | [Flv](#Flv) | FLV (Flash Video) è un formato di file contenitore con estensione .flv. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) è un contenitore multimediale simile ai formati MOV e AVI, ma supporta più tracce audio e di sottotitoli nello stesso file. |
|
|  | [Mov](#Mov) | Il formato di file MOV o QuickTime è un contenitore multimediale sviluppato da Apple: contiene una o più tracce, ciascuna traccia contiene un tipo particolare di dati, ad esempio. |
|
|  | [Webm](#Webm) | Un file con estensione .webm è un file video basato sul formato di file WebM, aperto e privo di royalty. |
|
|  | [Wmv](#Wmv) | Windows Media Video è il formato video compresso sviluppato da Microsoft. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Costruttore di serializzazione


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (abbreviazione di MPEG-4 Part 14) è un formato di file basato su ISO/IEC 14496-12:2004, derivato dal QuickTime File Format, ma specifica formalmente il supporto per gli Initial Object Descriptors (IOD) e altre funzionalità MPEG. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


Il formato di file AVI è un contenitore multimediale Audio Video introdotto da Microsoft. Contiene i dati audio e video creati e compressi utilizzando diversi codec (Codificatori/Decodificatori) come XVid e DivX. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) è un formato di file container con estensione .flv. FLV è usato per fornire contenuti audio/video su Internet utilizzando Adobe Flash Player o Adobe Air. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) è un contenitore multimediale simile ai formati MOV e AVI ma supporta più di una traccia audio e sottotitoli nello stesso file. Un file MKV è il formato di contenitore multimediale Matroska usato per i video. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV o formato file QuickTime è un contenitore multimediale sviluppato da Apple: contiene una o più tracce, ciascuna traccia contiene un particolare tipo di dati, ad es. Video, Audio, testo, ecc. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


Un file con estensione .webm è un file video basato sul formato file aperto e royalty‑free WebM. È stato progettato per condividere video sul web e definisce la struttura del contenitore del file includendo formati video e audio. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video è il formato video compresso sviluppato da Microsoft. Dopo la standardizzazione da parte della Society of Motion Picture and Television Engineers (SMPTE), WMV è ora considerato un formato standard aperto. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/video/wmv/).


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
