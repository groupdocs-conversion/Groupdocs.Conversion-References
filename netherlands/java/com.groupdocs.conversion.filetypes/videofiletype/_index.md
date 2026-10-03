---
title: "VideoFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert videodocumenten. Bevat de volgende typen        Lees meer over videoformaten hier."
type: docs
weight: 26
url: /nl/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Definieert videodocumenten. Bevat de volgende typen: , , , , , , , Lees meer over videoformaten [hier](../https://docs.fileformat.com/video/).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (kort voor MPEG-4 Part 14) is een bestandsformaat gebaseerd op ISO/IEC 14496-12:2004 dat is gebaseerd op QuickTime File Format, maar formeel ondersteuning specificeert voor Initial Object Descriptors (IOD) en andere MPEG‑functies. |
|
|  | [Avi](#Avi) | Het AVI‑bestandsformaat is een audio‑video multimedia‑containerbestandsformaat dat werd geïntroduceerd door Microsoft. |
|
|  | [Flv](#Flv) | FLV (Flash Video) is een containerbestandsformaat met de .flv-extensie. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) is een multimedia‑container vergelijkbaar met het MOV‑ en AVI‑formaat, maar ondersteunt meer dan één audio‑ en ondertitelingsspoor in hetzelfde bestand. |
|
|  | [Mov](#Mov) | MOV of QuickTime‑bestandsformaat is een multimedia‑container die is ontwikkeld door Apple: bevat één of meer sporen, elk spoor bevat een bepaald type gegevens, d.w.z. |
|
|  | [Webm](#Webm) | Een bestand met een .webm-extensie is een videobestand gebaseerd op het open, royalty‑vrije WebM‑bestandsformaat. |
|
|  | [Wmv](#Wmv) | Windows Media Video is het gecomprimeerde videoformaat ontwikkeld door Microsoft. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Serialisatieconstructor


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (kort voor MPEG-4 Part 14) is een bestandsformaat gebaseerd op ISO/IEC 14496-12:2004 dat is gebaseerd op QuickTime File Format, maar formeel ondersteuning specificeert voor Initial Object Descriptors (IOD) en andere MPEG‑functies. Lees meer over dit bestandsformaat [hier](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


Het AVI‑bestandsformaat is een audio‑video multimedia‑containerbestandsformaat dat werd geïntroduceerd door Microsoft. Het bevat de audio‑ en videogegevens die zijn gemaakt en gecomprimeerd met verschillende codecs (coders/decoders) zoals XVid en DivX. Lees meer over dit bestandsformaat [hier](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) is een containerbestandsformaat met de .flv-extensie. FLV wordt gebruikt om audio‑/videocontent via het internet te leveren met behulp van Adobe Flash Player of Adobe Air. Lees meer over dit bestandsformaat [hier](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) is een multimediacontainer die vergelijkbaar is met het MOV- en AVI-formaat, maar het ondersteunt meer dan één audio- en ondertiteltrack in hetzelfde bestand. Een MKV‑bestand is het Matroska‑multimediacontainerformaat dat voor video wordt gebruikt. Meer informatie over dit bestandsformaat [hier](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV of QuickTime-bestandsformaat is een multimediacontainer die door Apple is ontwikkeld: bevat één of meer tracks, waarbij elke track een bepaald type gegevens bevat, zoals video, audio, tekst, enz. Meer informatie over dit bestandsformaat [hier](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


Een bestand met de extensie .webm is een videobestand gebaseerd op het open, royalty‑vrije WebM‑bestandsformaat. Het is ontworpen voor het delen van video op het web en definieert de bestandcontainerstructuur, inclusief video‑ en audioformaten. Meer informatie over dit bestandsformaat [hier](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video is het gecomprimeerde videoformaat ontwikkeld door Microsoft. Na de standaardisatie door de Society of Motion Picture and Television Engineers (SMPTE) wordt WMV nu beschouwd als een open standaardformaat. Meer informatie over dit bestandsformaat [hier](../https://docs.fileformat.com/video/wmv/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
