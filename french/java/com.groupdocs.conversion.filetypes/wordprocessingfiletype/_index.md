---
title: "WordProcessingFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les fichiers de traitement de texte qui contiennent les informations de l'utilisateur en texte brut ou au format texte enrichi."
type: docs
weight: 28
url: /fr/java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Définit les fichiers de traitement de texte qui contiennent des informations utilisateur en texte brut ou au format texte enrichi. Un format de fichier texte brut contient du texte non formaté et aucune police ou réglage de page, etc. ne peut être appliqué. En revanche, un format de fichier texte enrichi permet des options de mise en forme telles que le réglage du type de police, les styles (gras, italique, souligné, etc.), les marges de page, les titres, les puces et les numéros, ainsi que plusieurs autres fonctionnalités de mise en forme.
Inclut les types de fichiers suivants :
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
En savoir plus sur les formats de traitement de texte [ici](../https://wiki.fileformat.com/word-processing).


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingFileType()](#WordProcessingFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Doc](#Doc) | Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres traitements de texte au format de fichier binaire. |
|
|  | [Docm](#Docm) | Les fichiers DOCM sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la capacité d'exécuter des macros. |
|
|  | [Docx](#Docx) | DOCX est un format bien connu pour les documents Microsoft Word. |
|
|  | [Dot](#Dot) | Les fichiers avec l'extension .DOT sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés lors de la génération de futurs fichiers DOC ou DOCX. |
|
|  | [Dotm](#Dotm) | Un fichier avec l'extension DOTM représente un modèle créé avec Microsoft Word 2007 ou version ultérieure. |
|
|  | [Dotx](#Dotx) | Les fichiers avec l'extension DOTX sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés lors de la génération de futurs fichiers DOCX. |
|
|  | [Rtf](#Rtf) | Introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d'encodage de texte formaté et de graphiques pour une utilisation dans les applications. |
|
|  | [Odt](#Odt) | Les fichiers ODT sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier OpenDocument Text. |
|
|  | [Ott](#Ott) | Les fichiers avec l'extension OTT représentent des documents modèles générés par des applications conformes au format standard OpenDocument d'OASIS. |
|
|  | [Txt](#Txt) | Un fichier avec l'extension .TXT représente un document texte contenant du texte brut sous forme de lignes. |
|
|  | [Md](#Md) | Les fichiers texte créés avec des dialectes du langage Markdown sont enregistrés avec l'extension .MD ou .MARKDOWN. |
|
|  | [Ml](#Ml) | Fichier Ml |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Constructeur de sérialisation


### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


Les fichiers avec l'extension .doc représentent des documents générés par Microsoft Word ou d'autres traitements de texte au format de fichier binaire.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/doc).


### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


Les fichiers DOCM sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la capacité d'exécuter des macros.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/docm).


### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée du binaire brut à une combinaison de fichiers XML et binaires.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/docx).


### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Les fichiers avec l'extension .DOT sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés lors de la génération de futurs fichiers DOC ou DOCX.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/dot).


### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Un fichier avec l'extension DOTM représente un modèle créé avec Microsoft Word 2007 ou version ultérieure.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/dotm).


### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Les fichiers avec l'extension DOTX sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés lors de la génération de futurs fichiers DOCX.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/dotx).


### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d'encodage de texte formaté et de graphiques pour une utilisation dans les applications.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/rtf).


### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


Les fichiers ODT sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier OpenDocument Text.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/odt).


### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Les fichiers avec l'extension OTT représentent des documents modèles générés par des applications conformes au format standard OpenDocument d'OASIS.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/ott).


### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Un fichier avec l'extension .TXT représente un document texte contenant du texte brut sous forme de lignes.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/txt).


### Md {#Md}
```
public static final WordProcessingFileType Md
```


Les fichiers texte créés avec les dialectes du langage Markdown sont enregistrés avec l'extension de fichier .MD ou .MARKDOWN. Les fichiers MD sont enregistrés au format texte brut qui utilise le langage Markdown, qui comprend également des symboles de texte en ligne, définissant comment un texte peut être formaté, comme les indentations, la mise en forme des tableaux, les polices et les en-têtes. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/md).


### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Fichier Ml


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
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
