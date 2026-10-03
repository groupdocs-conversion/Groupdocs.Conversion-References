---
title: "PdfFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les documents PDF."
type: docs
weight: 21
url: /fr/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Définit les documents Pdf. Inclut les types de fichiers suivants :
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Pdf](#Pdf) | Le Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Constructeur de sérialisation


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Le Portable Document Format (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation de documents et d'autres matériels de référence dans un format indépendant du logiciel applicatif, du matériel ainsi que du système d'exploitation.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/view/pdf).


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
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
