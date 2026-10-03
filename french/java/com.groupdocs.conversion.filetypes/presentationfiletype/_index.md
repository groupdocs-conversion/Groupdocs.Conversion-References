---
title: "PresentationFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les formats de fichiers de présentation qui stockent une collection d'enregistrements pour accueillir les données de présentation telles que les diapositives, les formes, le texte, les animations, la vidéo, l'audio et les objets incorporés."
type: docs
weight: 22
url: /fr/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Définit les formats de fichiers de présentation qui stockent une collection d'enregistrements pour contenir les données de présentation telles que les diapositives, les formes, le texte, les animations, la vidéo, l'audio et les objets incorporés.
Inclut les types de fichiers suivants :
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
En savoir plus sur les formats de présentation [ici](../https://wiki.fileformat.com/presentation).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Ppt](#Ppt) | Un fichier avec l'extension PPT représente un fichier PowerPoint qui consiste en une collection de diapositives à afficher en tant que diaporama. |
|
|  | [Pps](#Pps) | PPS, PowerPoint Slide Show, les fichiers sont créés à l'aide de Microsoft PowerPoint à des fins de diaporama. |
|
|  | [Pptx](#Pptx) | Les fichiers avec l'extension PPTX sont des fichiers de présentation créés avec l'application populaire Microsoft PowerPoint. |
|
|  | [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, les fichiers sont créés à l'aide de Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama. |
|
|  | [Odp](#Odp) | Les fichiers avec l'extension ODP représentent le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. |
|
|  | [Otp](#Otp) | Les fichiers avec l'extension .OTP représentent des modèles de présentation créés par des applications au format standard OASIS OpenDocument. |
|
|  | [Potx](#Potx) | Les fichiers avec l'extension .POTX représentent des présentations modèles Microsoft PowerPoint créées avec Microsoft PowerPoint 2007 et versions ultérieures. |
|
|  | [Pot](#Pot) | Les fichiers avec l'extension .POT représentent des fichiers modèles Microsoft PowerPoint créés par les versions PowerPoint 97-2003. |
|
|  | [Potm](#Potm) | Les fichiers avec l'extension POTM sont des fichiers modèles Microsoft PowerPoint avec prise en charge des macros. |
|
|  | [Pptm](#Pptm) | Les fichiers avec l'extension PPTM sont des fichiers de présentation compatibles macros créés avec Microsoft PowerPoint 2007 ou des versions supérieures. |
|
|  | [Ppsm](#Ppsm) | Les fichiers avec l'extension PPSM représentent le format de fichier diaporama compatible macros créé avec Microsoft PowerPoint 2007 ou ultérieur. |
|
|  | [Fodp](#Fodp) | Les fichiers avec l'extension FODP représentent la présentation OpenDocument Flat XML. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Constructeur de sérialisation


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Un fichier avec l'extension PPT représente un fichier PowerPoint qui consiste en une collection de diapositives à afficher en tant que diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slide Show, les fichiers sont créés à l'aide de Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Les fichiers avec l'extension PPTX sont des fichiers de présentation créés avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation Open XML de Microsoft PowerPoint.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, Power Point Slide Show, les fichiers sont créés à l'aide de Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Les fichiers avec l'extension ODP représentent le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Les fichiers avec l'extension .OTP représentent des modèles de présentation créés par des applications au format standard OASIS OpenDocument.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Les fichiers avec l'extension .POTX représentent des présentations modèles Microsoft PowerPoint créées avec Microsoft PowerPoint 2007 et versions ultérieures.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Les fichiers avec l'extension .POT représentent des fichiers modèles Microsoft PowerPoint créés par les versions PowerPoint 97-2003.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Les fichiers avec l'extension POTM sont des modèles Microsoft PowerPoint prenant en charge les macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou une version ultérieure et contiennent des paramètres par défaut qui peuvent être utilisés pour créer d'autres fichiers de présentation.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Les fichiers avec l'extension PPTM sont des fichiers de présentation compatibles macros créés avec Microsoft PowerPoint 2007 ou des versions supérieures.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Les fichiers avec l'extension PPSM représentent le format de fichier diaporama compatible macros créé avec Microsoft PowerPoint 2007 ou ultérieur.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Les fichiers avec l'extension FODP représentent une présentation OpenDocument Flat XML. Le fichier de présentation est enregistré au format OpenDocument, mais en utilisant un format XML plat au lieu du conteneur .ZIP utilisé par les fichiers .ODP standard.


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
