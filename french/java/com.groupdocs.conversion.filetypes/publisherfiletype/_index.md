---
title: "PublisherFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents Publisher."
type: docs
weight: 24
url: /fr/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Définit les documents Publisher.
Inclut les types suivants :
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
En savoir plus sur les formats de police [ici](../https://wiki.fileformat.com/publisher).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Pub](#Pub) | Un fichier PUB est un format de fichier de document Microsoft Publisher. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Constructeur de sérialisation


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Un fichier PUB est un format de fichier de document Microsoft Publisher. Il est utilisé pour créer plusieurs types de documents de mise en page tels que des bulletins, des flyers, des brochures, des cartes postales, etc. Les fichiers PUB peuvent contenir du texte, des images raster et vectorielles. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
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
