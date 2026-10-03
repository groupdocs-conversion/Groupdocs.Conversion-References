---
title: "ConversionPair"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar konverteringspar"
type: docs
weight: 10
url: /sv/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Representerar konverteringspar

## Fält

| Fält | Beskrivning |
| --- | --- |
| [NULL](#NULL) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Skapar primär konverteringspar |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Skapar primära konverteringspar |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Skapar sekundärt konverteringspar |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Skapar sekundära konverteringspar |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Likhetskomponenter |
|
|  | [toString()](#toString--) | Strängrepresentation av konverteringspar |
|
|  | [getSource()](#getSource--) | Källfilformat |
|
|  | [getTarget()](#getTarget--) | Målfilsformat |
|
|  | [isPrimary()](#isPrimary--) | Primärt konverteringspar eller inte |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Skapar primär konverteringspar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | källa |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | mål |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Skapar primära konverteringspar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | källor | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | källors filtyp |
|
|  | mål | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | målens filtyp |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - primära konverteringspar

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källor | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| mål | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Skapar sekundärt konverteringspar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | källfiltyp |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | målfiltyp |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Skapar sekundära konverteringspar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | källor | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | källors filtyp |
|
|  | mål | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | målens filtyp |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - sekundära konverteringspar

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Likhetskomponenter


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - likhetskomponenter

### toString() {#toString--}
```
public String toString()
```


Strängrepresentation av konverteringspar


**Returns:**
java.lang.String - sträng

### getSource() {#getSource--}
```
public FileType getSource()
```


Källfilformat


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Målfilsformat


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Primärt konverteringspar eller inte


**Returns:**
boolean - sant om primär, annars falskt

