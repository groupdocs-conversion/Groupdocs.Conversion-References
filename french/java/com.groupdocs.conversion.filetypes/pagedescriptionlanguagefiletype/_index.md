---
title: "PageDescriptionLanguageFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents de description de page."
type: docs
weight: 20
url: /fr/java/com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PageDescriptionLanguageFileType extends FileType implements Serializable
```

Définit les documents de description de page.
Inclut les types suivants :
[Svg](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Svg),
[Eps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Eps),
[Cgm](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Cgm),
[Xps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Xps),
[Tex](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Tex),
[Ps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Ps),
[Pcl](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Pcl),
[Oxps](../../com.groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype#Oxps),

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PageDescriptionLanguageFileType()](#PageDescriptionLanguageFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Svg](#Svg) | Un fichier SVG est un fichier Scalar Vector Graphics qui utilise un format texte basé sur XML pour décrire l'apparence d'une image. |
|
|  | [Eps](#Eps) | Les fichiers avec l'extension EPS décrivent essentiellement un programme de langage Encapsulated PostScript qui décrit l'apparence d'une seule page. |
|
|  | [Cgm](#Cgm) | Computer Graphics Metafile (CGM) est un format de métafichier gratuit, indépendant de la plateforme, norme internationale pour le stockage et l'échange de graphiques vectoriels (2D), de graphiques raster et de texte. |
|
|  | [Xps](#Xps) | Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. |
|
|  | [Tex](#Tex) | TeX est un langage qui comprend des fonctionnalités de programmation ainsi que de balisage, utilisé pour composer des documents. |
|
|  | [Ps](#Ps) | PostScript (PS) est un langage de description de page à usage général utilisé dans le domaine de la publication de bureau et électronique. |
|
|  | [Pcl](#Pcl) | PCL signifie Printer Command Language, qui est un langage de description de page introduit par Hewlett Packard (HP). |
|
|  | [Oxps](#Oxps) | Le format de fichier OXPS est connu sous le nom d'Open XML Paper Specification. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PageDescriptionLanguageFileType() {#PageDescriptionLanguageFileType--}
```
public PageDescriptionLanguageFileType()
```


Constructeur de sérialisation


### Svg {#Svg}
```
public static final PageDescriptionLanguageFileType Svg
```


Un fichier SVG est un fichier Scalar Vector Graphics qui utilise un format texte basé sur XML pour décrire l'apparence d'une image. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/svg).


### Eps {#Eps}
```
public static final PageDescriptionLanguageFileType Eps
```


Les fichiers avec l'extension EPS décrivent essentiellement un programme en langage Encapsulated PostScript qui décrit l'apparence d'une page unique. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/eps).


### Cgm {#Cgm}
```
public static final PageDescriptionLanguageFileType Cgm
```


Computer Graphics Metafile (CGM) est un format de métafichier gratuit, indépendant de la plateforme, norme internationale pour le stockage et l'échange de graphiques vectoriels (2D), graphiques raster et texte. CGM utilise une approche orientée objet et de nombreuses fonctions pour la production d'images. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/cgm).


### Xps {#Xps}
```
public static final PageDescriptionLanguageFileType Xps
```


Un fichier XPS représente des fichiers de mise en page basés sur les XML Paper Specifications créées par Microsoft. Ce format a été développé par Microsoft comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/xps).


### Tex {#Tex}
```
public static final PageDescriptionLanguageFileType Tex
```


TeX est un langage qui comprend des fonctionnalités de programmation ainsi que de balisage, utilisé pour composer des documents. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/tex).


### Ps {#Ps}
```
public static final PageDescriptionLanguageFileType Ps
```


PostScript (PS) est un langage de description de page à usage général utilisé dans le domaine de la publication de bureau et électronique. L'objectif principal de PostScript (PS) est de faciliter la conception graphique bidimensionnelle. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/ps).


### Pcl {#Pcl}
```
public static final PageDescriptionLanguageFileType Pcl
```


PCL signifie Printer Command Language, qui est un langage de description de page introduit par Hewlett Packard (HP). En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/pcl).


### Oxps {#Oxps}
```
public static final PageDescriptionLanguageFileType Oxps
```


Le format de fichier OXPS est connu sous le nom d'Open XML Paper Specification. C’est un langage de description de page et un format de document. Microsoft est le développeur de ce format. Le format de fichier OXPS est très similaire aux fichiers PDF. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/page-description-language/oxps).


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
