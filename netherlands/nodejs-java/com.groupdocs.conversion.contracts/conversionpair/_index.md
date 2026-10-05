---
title: "ConversionPair"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Stelt een conversie‑paar voor"
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Stelt een conversie‑paar voor
## Velden

| Veld | Beschrijving |
| --- | --- |
| [NULL](#NULL) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Maakt primaire conversie‑paar |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Maakt primaire conversie‑paren |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
| [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Maakt secundaire conversie‑paar |
| [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Maakt secundaire conversieparen |
| [getEqualityComponents()](#getEqualityComponents--) | Gelijkheidscomponenten |
| [toString()](#toString--) | Stringrepresentatie van conversiepaars |
| [getSource()](#getSource--) | Bronbestandformaat |
| [getTarget()](#getTarget--) | Doelbestandformaat |
| [isPrimary()](#isPrimary--) | Primaire conversiepaars of niet |
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Maakt primaire conversie‑paar

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | bron |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | doel |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Maakt primaire conversie‑paren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bronnen | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | bestandstype van bronnen |
| doelen | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | bestandstype van doelen |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - primaire conversieparen
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bronnen | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| doelen | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Maakt secundaire conversie‑paar

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | bronbestandstype |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | doelfiletype |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair
### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Maakt secundaire conversieparen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bronnen | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | bestandstype van bronnen |
| doelen | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | bestandstype van doelen |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - secundaire conversieparen
### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Gelijkheidscomponenten

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - gelijkheidscomponenten
### toString() {#toString--}
```
public String toString()
```


Stringrepresentatie van conversiepaars

**Returns:**
java.lang.String - tekenreeks
### getSource() {#getSource--}
```
public FileType getSource()
```


Bronbestandformaat

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format
### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Doelbestandformaat

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Primaire conversiepaars of niet

**Returns:**
boolean - true als primair, anders niet
