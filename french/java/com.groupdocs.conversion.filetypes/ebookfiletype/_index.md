---
title: "EBookFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents CAD (Conception Assistée par Ordinateur) qui sont utilisés pour des formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D."
type: docs
weight: 14
url: /fr/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Définit les documents CAD (Conception Assistée par Ordinateur) qui sont utilisés pour les formats de fichiers graphiques 3D et peuvent contenir des conceptions 2D ou 3D.
Inclut les types suivants :
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
En savoir plus sur les formats CAD [ici](../https://wiki.fileformat.com/cad).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Epub](#Epub) | L'extension EPUB est un format de fichier e-book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. |
|
|  | [Mobi](#Mobi) | Le format de fichier MOBI est l'un des formats de livre électronique les plus largement utilisés. |
|
|  | [Azw3](#Azw3) | AZW3, également connu sous le nom de Kindle Format 8 (KF8), est la version modifiée du format de fichier numérique AZW ebook développé pour les appareils Amazon Kindle. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Constructeur de sérialisation


### Epub {#Epub}
```
public static final EBookFileType Epub
```


L'extension EPUB est un format de fichier e-book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. Ce format est désormais si répandu qu'il est pris en charge par de nombreux lecteurs électroniques et applications logicielles. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Le format de fichier MOBI est l'un des formats de livre électronique les plus largement utilisés. Ce format est une amélioration du vieux format OEB (Open Ebook Format) et était utilisé comme format propriétaire pour le lecteur Mobipocket. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, également connu sous le nom de Kindle Format 8 (KF8), est la version modifiée du format de fichier numérique AZW ebook développé pour les appareils Amazon Kindle. Ce format est une amélioration des anciens fichiers AZW et n'est utilisé que sur les appareils Kindle Fire, tout en restant compatible avec les formats ancêtres, à savoir MOBI et AZW. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/ebook/azw3/).


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
