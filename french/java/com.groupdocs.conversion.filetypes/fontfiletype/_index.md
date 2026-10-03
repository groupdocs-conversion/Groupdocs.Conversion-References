---
title: "FontFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents de police."
type: docs
weight: 17
url: /fr/java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Définit les documents de police.
Inclut les types suivants :
[Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype#Ttf),
[Eot](../../com.groupdocs.conversion.filetypes/fontfiletype#Eot),
[Otf](../../com.groupdocs.conversion.filetypes/fontfiletype#Otf),
[Cff](../../com.groupdocs.conversion.filetypes/fontfiletype#Cff),
[Type1](../../com.groupdocs.conversion.filetypes/fontfiletype#Type1),
[Woff](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff),
[Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype#Woff2),
En savoir plus sur les formats de police [ici](../https://wiki.fileformat.com/font).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FontFileType()](#FontFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Ttf](#Ttf) | Un fichier avec l'extension .ttf représente des fichiers de police basés sur la technologie de police selon les spécifications TrueType. |
|
|  | [Eot](#Eot) | Un fichier avec l'extension .eot est une police OpenType intégrée dans un document. |
|
|  | [Otf](#Otf) | Un fichier avec l'extension .otf fait référence au format de police OpenType. |
|
|  | [Cff](#Cff) | Un fichier avec l'extension .cff est un Compact Font Format, également connu sous le nom de PostScript Type 1 ou CIDFont. |
|
|  | [Type1](#Type1) | Les polices Type 1 sont une technologie Adobe obsolète qui était largement utilisée dans les logiciels de publication assistée par ordinateur et les imprimantes capables d'utiliser PostScript. |
|
|  | [Woff](#Woff) | Un fichier avec l'extension .woff est un fichier de police web basé sur le Web Open Font Format (WOFF). |
|
|  | [Woff2](#Woff2) | Un fichier avec l'extension .woff est un fichier de police web basé sur le Web Open Font Format (WOFF). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Constructeur de sérialisation


### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Un fichier avec l'extension .ttf représente des fichiers de police basés sur la technologie de police selon les spécifications TrueType. Il a été initialement conçu et lancé par Apple Computer, Inc pour macOS et a ensuite été adopté par Microsoft pour Windows. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/ttf/).


### Eot {#Eot}
```
public static final FontFileType Eot
```


Un fichier avec l'extension .eot est une police OpenType intégrée dans un document. Elles sont principalement utilisées dans les fichiers web tels qu'une page Web. Il a été créé par Microsoft et est pris en charge par les produits Microsoft, y compris les présentations PowerPoint au format .pps. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/eot/).


### Otf {#Otf}
```
public static final FontFileType Otf
```


Un fichier avec l'extension .otf fait référence au format de police OpenType. Le format de police OTF est plus évolutif et étend les fonctionnalités existantes des formats TTF pour la typographie numérique. Développé par Microsoft et Adobe, OTF combine les caractéristiques des formats de police PostScript et TrueType. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/otf/).


### Cff {#Cff}
```
public static final FontFileType Cff
```


Un fichier avec l'extension .cff est un Compact Font Format, également connu sous le nom de PostScript Type 1 ou CIDFont. Le CFF agit comme un conteneur permettant de stocker plusieurs polices ensemble dans une unité unique appelée FontSet. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/cff/).


### Type1 {#Type1}
```
public static final FontFileType Type1
```


Les polices Type 1 sont une technologie Adobe obsolète qui était largement utilisée dans les logiciels de publication assistée par ordinateur et les imprimantes capables d'utiliser PostScript. Bien que les polices Type 1 ne soient pas prises en charge par de nombreuses plateformes modernes, navigateurs web et systèmes d'exploitation mobiles, elles restent supportées sur certains systèmes d'exploitation. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/type1/).


### Woff {#Woff}
```
public static final FontFileType Woff
```


Un fichier avec l'extension .woff est un fichier de police web basé sur le Web Open Font Format (WOFF). Il possède un conteneur compressé spécifique au format, basé soit sur les polices TrueType (.TTF) soit sur les polices OpenType (.OTT). En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/woff/).


### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Un fichier avec l'extension .woff est un fichier de police web basé sur le Web Open Font Format (WOFF). Il possède un conteneur compressé spécifique au format, basé soit sur les polices TrueType (.TTF) soit sur les polices OpenType (.OTT). En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/font/woff/).


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
