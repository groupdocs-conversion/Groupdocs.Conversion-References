---
title: "ConversionPair"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta una coppia di conversione"
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Rappresenta una coppia di conversione

## Campi

| Campo | Descrizione |
| --- | --- |
| [NULL](#NULL) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crea coppia di conversione primaria |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Crea coppie di conversione primarie |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crea coppia di conversione secondaria |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Crea coppie di conversione secondarie |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Componenti di uguaglianza |
|
|  | [toString()](#toString--) | Rappresentazione stringa della coppia di conversione |
|
|  | [getSource()](#getSource--) | Formato file di origine |
|
|  | [getTarget()](#getTarget--) | Formato file di destinazione |
|
|  | [isPrimary()](#isPrimary--) | Coppia di conversione primaria o no |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Crea coppia di conversione primaria


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | origine |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | destinazione |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Crea coppie di conversione primarie


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | origini | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | tipo di file delle origini |
|
|  | destinazioni | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | tipo di file delle destinazioni |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - coppie di conversione primarie

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origini | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| destinazioni | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Crea coppia di conversione secondaria


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo di file sorgente |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo di file di destinazione |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Crea coppie di conversione secondarie


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | origini | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | tipo di file delle origini |
|
|  | destinazioni | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | tipo di file delle destinazioni |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - coppie di conversione secondarie

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Componenti di uguaglianza


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - componenti di uguaglianza

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa della coppia di conversione


**Returns:**
java.lang.String - stringa

### getSource() {#getSource--}
```
public FileType getSource()
```


Formato file di origine


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Formato file di destinazione


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Coppia di conversione primaria o no


**Returns:**
boolean - vero se primaria, altrimenti no

