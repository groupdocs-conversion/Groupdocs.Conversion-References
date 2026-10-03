---
title: "ConversionPair"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt ein Konvertierungspaar dar"
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Stellt ein Konvertierungspaar dar

## Felder

| Feld | Beschreibung |
| --- | --- |
| [NULL](#NULL) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Erstellt primäres Konvertierungspaar |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Erstellt primäre Konvertierungspaare |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Erstellt sekundäres Konvertierungspaar |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Erstellt sekundäre Konvertierungspaare |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Gleichheitskomponenten |
|
|  | [toString()](#toString--) | Stringdarstellung des Konvertierungspaares |
|
|  | [getSource()](#getSource--) | Quelldateiformat |
|
|  | [getTarget()](#getTarget--) | Zieldateiformat |
|
|  | [isPrimary()](#isPrimary--) | Primäres Konvertierungspaar oder nicht |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Erstellt primäres Konvertierungspaar


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Quelle |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Ziel |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Erstellt primäre Konvertierungspaare


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Quellen | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | Dateityp der Quellen |
|
|  | Ziele | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | Dateityp der Ziele |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - primäre Konvertierungspaare

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Quellen | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| Ziele | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Erstellt sekundäres Konvertierungspaar


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Quell-Dateityp |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Ziel-Dateityp |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Erstellt sekundäre Konvertierungspaare


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Quellen | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | Dateityp der Quellen |
|
|  | Ziele | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | Dateityp der Ziele |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - sekundäre Konvertierungspaare

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Gleichheitskomponenten


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - Gleichheitskomponenten

### toString() {#toString--}
```
public String toString()
```


Stringdarstellung des Konvertierungspaares


**Returns:**
java.lang.String - Zeichenkette

### getSource() {#getSource--}
```
public FileType getSource()
```


Quelldateiformat


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Zieldateiformat


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Primäres Konvertierungspaar oder nicht


**Returns:**
boolean - wahr, wenn primär, sonst wenn nicht

