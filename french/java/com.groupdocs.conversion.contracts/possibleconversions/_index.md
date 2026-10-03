---
title: "PossibleConversions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente un mappage des paires de conversion prises en charge pour un format de fichier source spécifique"
type: docs
weight: 13
url: /fr/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Représente un mappage des paires de conversion prises en charge pour un format de fichier source spécifique

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Crée une liste de conversions possibles pour le format de fichier source spécifié |
|
## Champs

| Champ | Description |
| --- | --- |
| [NULL](#NULL) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Options de chargement prédéfinies pouvant être utilisées pour convertir depuis le type actuel |
|
|  | [getAll()](#getAll--) | Tous les types de fichiers cibles et le drapeau primaire/secondaire |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Renvoie la conversion cible pour le type de fichier cible spécifié |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Types de fichiers cibles primaires |
|
|  | [getSecondary()](#getSecondary--) | Types de fichiers cibles secondaires |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Ajouter une paire de conversion |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Trouver la paire de conversion dans la liste actuelle pour le type de fichier cible |
|
|  | [getSource()](#getSource--) | Formats de fichiers source |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Crée une liste de conversions possibles pour le format de fichier source spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | type de fichier source |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement prédéfinies pouvant être utilisées pour convertir depuis le type actuel


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Tous les types de fichiers cibles et le drapeau primaire/secondaire


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Itérable de [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Renvoie la conversion cible pour le type de fichier cible spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | type de fichier cible |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extension | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Types de fichiers cibles primaires


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - types de fichiers cibles principaux

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Types de fichiers cibles secondaires


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - types de fichiers cibles secondaires

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Ajouter une paire de conversion


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | paire de conversion |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Trouver la paire de conversion dans la liste actuelle pour le type de fichier cible


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | type de fichier cible |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Formats de fichiers source


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

