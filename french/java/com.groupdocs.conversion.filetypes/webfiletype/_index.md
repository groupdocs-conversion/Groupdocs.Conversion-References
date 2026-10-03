---
title: "WebFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents Web."
type: docs
weight: 27
url: /fr/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Définit les documents Web.
Inclut les types suivants :
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
En savoir plus sur les formats Web [ici](../https://wiki.fileformat.com/web).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Xml](#Xml) | XML signifie Extensible Markup Language, qui est similaire à HTML mais différent dans l'utilisation des balises pour définir des objets. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) est un format de fichier standard ouvert pour le partage de données qui utilise du texte lisible par l'homme pour stocker et transmettre les données. |
|
|  | [Html](#Html) | HTML (Hyper Text Markup Language) est l'extension des pages Web créées pour être affichées dans les navigateurs. |
|
|  | [Htm](#Htm) | HTM (Hyper Text Markup Language) est l'extension des pages Web créées pour être affichées dans les navigateurs. |
|
|  | [Mht](#Mht) | Les fichiers avec l'extension MHTML représentent un format d'archive de page Web qui peut être créé par plusieurs applications différentes. |
|
|  | [Mhtml](#Mhtml) | Les fichiers avec l'extension MHTML représentent un format d'archive de page Web qui peut être créé par plusieurs applications différentes. |
|
|  | [Chm](#Chm) | Le format de fichier CHM représente le fichier d'aide Microsoft HTML qui se compose d'une collection de pages HTML. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Constructeur de sérialisation


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML signifie Extensible Markup Language, qui est similaire à HTML mais différent dans l'utilisation des balises pour définir des objets. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/xml).


### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) est un format de fichier standard ouvert pour le partage de données qui utilise du texte lisible par l'homme pour stocker et transmettre les données. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/json).


### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) est l'extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/html).


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) est l'extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/html).


### Mht {#Mht}
```
public static final WebFileType Mht
```


Les fichiers avec l'extension MHTML représentent un format d'archive de page Web qui peut être créé par plusieurs applications différentes. Ce format est connu comme un format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/mhtml).


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Les fichiers avec l'extension MHTML représentent un format d'archive de page Web qui peut être créé par plusieurs applications différentes. Ce format est connu comme un format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/mhtml).


### Chm {#Chm}
```
public static final WebFileType Chm
```


Le format de fichier CHM représente le fichier d'aide Microsoft HTML qui se compose d'une collection de pages HTML. Il fournit un index pour accéder rapidement aux sujets et une navigation vers différentes parties du document d'aide. En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/chm).


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
