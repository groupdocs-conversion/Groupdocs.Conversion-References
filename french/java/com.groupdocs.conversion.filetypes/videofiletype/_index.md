---
title: "VideoFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents vidéo. Inclut les types suivants        En savoir plus sur les formats vidéo ici."
type: docs
weight: 26
url: /fr/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Définit les documents vidéo. Inclut les types suivants : , , , , , , , En savoir plus sur les formats vidéo [ici](../https://docs.fileformat.com/video/).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (abréviation de MPEG-4 Part 14) est un format de fichier basé sur ISO/IEC 14496-12:2004 qui repose sur le QuickTime File Format mais spécifie formellement la prise en charge des Descripteurs d'Objet Initiaux (IOD) et d'autres fonctionnalités MPEG. |
|
|  | [Avi](#Avi) | Le format de fichier AVI est un conteneur multimédia Audio Vidéo qui a été introduit par Microsoft. |
|
|  | [Flv](#Flv) | FLV (Flash Video) est un format de fichier conteneur avec l'extension .flv. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) est un conteneur multimédia similaire aux formats MOV et AVI mais il prend en charge plusieurs pistes audio et sous-titres dans le même fichier. |
|
|  | [Mov](#Mov) | Le format de fichier MOV ou QuickTime est un conteneur multimédia développé par Apple : il contient une ou plusieurs pistes, chaque piste contenant un type de données particulier, par exemple. |
|
|  | [Webm](#Webm) | Un fichier avec l'extension .webm est un fichier vidéo basé sur le format de fichier ouvert et gratuit WebM. |
|
|  | [Wmv](#Wmv) | Windows Media Video est le format vidéo compressé développé par Microsoft. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Constructeur de sérialisation


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (abréviation de MPEG-4 Part 14) est un format de fichier basé sur ISO/IEC 14496-12:2004 qui repose sur le QuickTime File Format mais spécifie formellement la prise en charge des Descripteurs d'Objet Initiaux (IOD) et d'autres fonctionnalités MPEG. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


Le format de fichier AVI est un conteneur multimédia Audio Vidéo qui a été introduit par Microsoft. Il contient les données audio et vidéo créées et compressées à l'aide de plusieurs codecs (codeurs/décodeurs) tels que XVid et DivX. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) est un format de fichier conteneur avec l'extension .flv. FLV est utilisé pour diffuser du contenu audio/vidéo sur Internet en utilisant Adobe Flash Player ou Adobe Air. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) est un conteneur multimédia similaire aux formats MOV et AVI mais il prend en charge plus d'une piste audio et sous-titres dans le même fichier. Un fichier MKV est le format de conteneur multimédia Matroska utilisé pour la vidéo. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV ou le format de fichier QuickTime est un conteneur multimédia développé par Apple : il contient une ou plusieurs pistes, chaque piste contenant un type particulier de données, c’est‑à‑dire Vidéo, Audio, texte, etc. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


Un fichier avec l'extension .webm est un fichier vidéo basé sur le format de fichier ouvert et gratuit WebM. Il a été conçu pour le partage de vidéos sur le web et définit la structure du conteneur de fichiers incluant les formats vidéo et audio. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video est le format vidéo compressé développé par Microsoft. Après la normalisation par la Society of Motion Picture and Television Engineers (SMPTE), WMV est désormais considéré comme un format standard ouvert. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/video/wmv/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion par défaut préparées pour le type de fichier


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
