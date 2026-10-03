---
title: "ConversionPair"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente une paire de conversion"
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Représente une paire de conversion

## Champs

| Champ | Description |
| --- | --- |
| [NULL](#NULL) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crée la paire de conversion principale |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Crée les paires de conversion principales |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crée la paire de conversion secondaire |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Crée les paires de conversion secondaires |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Composants d'égalité |
|
|  | [toString()](#toString--) | Représentation sous forme de chaîne de la paire de conversion |
|
|  | [getSource()](#getSource--) | Format de fichier source |
|
|  | [getTarget()](#getTarget--) | Format de fichier cible |
|
|  | [isPrimary()](#isPrimary--) | Paire de conversion principale ou non |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Crée la paire de conversion principale


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | source |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | cible |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Crée les paires de conversion principales


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | sources | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | type de fichier source |
|
|  | cibles | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | type de fichier cible |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - paires de conversion principales

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sources | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| cibles | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Crée la paire de conversion secondaire


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | type de fichier source |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | type de fichier cible |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Crée les paires de conversion secondaires


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | sources | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | type de fichier source |
|
|  | cibles | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | type de fichier cible |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - paires de conversion secondaires

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Composants d'égalité


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - composants d'égalité

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de la paire de conversion


**Returns:**
java.lang.String - chaîne

### getSource() {#getSource--}
```
public FileType getSource()
```


Format de fichier source


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Format de fichier cible


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Paire de conversion principale ou non


**Returns:**
boolean - vrai si principal, sinon

