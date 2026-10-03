---
title: "AudioFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents audio. Inclut les types suivants          En savoir plus sur les formats audio ici."
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Définit les documents audio. Inclut les types suivants : , , , , , , , , , En savoir plus sur les formats audio [ici](../https://docs.fileformat.com/audio/).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Mp3](#Mp3) | Les fichiers avec l'extension .mp3 sont des formats de fichiers audio numériquement encodés, basés officiellement sur MPEG-1 Audio Layer III ou MPEG-2 Audio Layer III. |
|
|  | [Aac](#Aac) | AAC (Advanced Audio Coding) désigne une norme de codage audio numérique qui représente les fichiers audio basés sur une compression audio avec perte. |
|
|  | [Aiff](#Aiff) | Le AIFF (Audio Interchange File Format) est un format de fichier audio non compressé développé par Apple en 1998, mais basé sur EA IFF 85. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/aiff/). |
|
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) est un format de codage audio à compression sans perte développé par la Xiph.Org Foundation. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/flac/). |
|
|  | [M4a](#M4a) | Le format de fichier M4A est un fichier audio créé en utilisant le AAC (Advanced Audio Coding), qui est connu comme une compression avec perte. |
|
|  | [Wma](#Wma) | Un fichier avec l'extension .wma représente un fichier audio enregistré au format Advanced Systems Format (ASF). |
|
|  | [Ac3](#Ac3) | Un fichier avec l'extension .ac3 est un fichier Audio Codec 3, introduit par Dolby Laboratories. |
|
|  | [Ogg](#Ogg) | OGG est un fichier audio compressé Ogg Vorbis qui est enregistré avec l'extension .ogg. |
|
|  | [Wav](#Wav) | WAV, connu pour WAVE (Waveform Audio File Format), est un sous-ensemble de la spécification Resource Interchange File Format (RIFF) de Microsoft\\u2019s pour le stockage de fichiers audio numériques. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Constructeur de sérialisation


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


Les fichiers avec l'extension .mp3 sont des formats de fichiers audio encodés numériquement, basés formellement sur MPEG-1 Audio Layer III ou MPEG-2 Audio Layer III. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/mp3/).


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) désigne une norme de codage audio numérique qui représente des fichiers audio basés sur une compression audio avec perte. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/aac/).


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


Le AIFF (Audio Interchange File Format) est un format de fichier audio non compressé développé par Apple en 1998, mais basé sur EA IFF 85. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/aiff/).


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) est un format de codage audio à compression sans perte développé par la Xiph.Org Foundation. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/flac/).


### M4a {#M4a}
```
public static final AudioFileType M4a
```


Le format de fichier M4A est un fichier audio créé en utilisant le AAC (Advanced Audio Coding), qui est connu comme une compression avec perte. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/m4a/).


### Wma {#Wma}
```
public static final AudioFileType Wma
```


Un fichier avec l'extension .wma représente un fichier audio enregistré au format Advanced Systems Format (ASF). En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/wma/).


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


Un fichier avec l'extension .ac3 est un fichier Audio Codec 3, introduit par Dolby Laboratories. C'est un format audio pouvant contenir jusqu'à six canaux de sortie audio. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/ac3/).


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG est un fichier audio compressé Ogg Vorbis qui est enregistré avec l'extension .ogg. Les fichiers OGG sont utilisés pour stocker des données audio et peuvent également inclure des informations d'artiste, de piste et des métadonnées. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/ogg/).


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, connu pour WAVE (Waveform Audio File Format), est un sous-ensemble de la spécification Resource Interchange File Format (RIFF) de Microsoft\\u2019s pour le stockage de fichiers audio numériques. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/audio/ogg/).


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
