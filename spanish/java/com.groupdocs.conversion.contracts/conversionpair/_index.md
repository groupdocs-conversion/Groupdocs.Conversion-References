---
title: "ConversionPair"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Representa un par de conversión"
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Representa un par de conversión

## Campos

| Campo | Descripción |
| --- | --- |
| [NULL](#NULL) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crea el par de conversión primaria |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Crea los pares de conversión primarios |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Crea el par de conversión secundaria |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Crea los pares de conversión secundarios |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Componentes de igualdad |
|
|  | [toString()](#toString--) | Representación en cadena del par de conversión |
|
|  | [getSource()](#getSource--) | Formato de archivo de origen |
|
|  | [getTarget()](#getTarget--) | Formato de archivo de destino |
|
|  | [isPrimary()](#isPrimary--) | Par de conversión principal o no |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Crea el par de conversión primaria


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | origen |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | destino |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Crea los pares de conversión primarios


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | orígenes | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | tipo de archivo de orígenes |
|
|  | destinos | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | tipo de archivo de destinos |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - pares de conversión principales

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orígenes | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| destinos | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Crea el par de conversión secundaria


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo de archivo fuente |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo de archivo objetivo |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Crea los pares de conversión secundarios


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | orígenes | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | tipo de archivo de orígenes |
|
|  | destinos | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | tipo de archivo de destinos |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - pares de conversión secundarios

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Componentes de igualdad


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - componentes de igualdad

### toString() {#toString--}
```
public String toString()
```


Representación en cadena del par de conversión


**Returns:**
java.lang.String - cadena

### getSource() {#getSource--}
```
public FileType getSource()
```


Formato de archivo de origen


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Formato de archivo de destino


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Par de conversión principal o no


**Returns:**
boolean - verdadero si es principal, de lo contrario si no

