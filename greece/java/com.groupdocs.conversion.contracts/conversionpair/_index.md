---
title: "ConversionPair"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει το ζεύγος μετατροπής"
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Αντιπροσωπεύει το ζεύγος μετατροπής

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [NULL](#NULL) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Δημιουργεί το κύριο ζεύγος μετατροπής |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Δημιουργεί τα κύρια ζεύγη μετατροπής |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Δημιουργεί το δευτερεύον ζεύγος μετατροπής |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Δημιουργεί τα δευτερεύοντα ζεύγη μετατροπής |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | Στοιχεία ισότητας |
|
|  | [toString()](#toString--) | Αναπαράσταση συμβολοσειράς ζεύγους μετατροπής |
|
|  | [getSource()](#getSource--) | Μορφή αρχείου προέλευσης |
|
|  | [getTarget()](#getTarget--) | Μορφή αρχείου προορισμού |
|
|  | [isPrimary()](#isPrimary--) | Πρωτεύον ζεύγος μετατροπής ή όχι |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Δημιουργεί το κύριο ζεύγος μετατροπής


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | προέλευση |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | προορισμός |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Δημιουργεί τα κύρια ζεύγη μετατροπής


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | πηγές | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | τύπος αρχείου πηγών |
|
|  | προορισμοί | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | τύπος αρχείου προορισμών |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - πρωτεύοντα ζεύγη μετατροπής

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| πηγές | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| προορισμοί | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Δημιουργεί το δευτερεύον ζεύγος μετατροπής


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | τύπος πηγαίου αρχείου |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | τύπος αρχείου προορισμού |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Δημιουργεί τα δευτερεύοντα ζεύγη μετατροπής


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | πηγές | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | τύπος αρχείου πηγών |
|
|  | προορισμοί | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | τύπος αρχείου προορισμών |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - δευτερεύοντα ζεύγη μετατροπής

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Στοιχεία ισότητας


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - συστατικά ισότητας

### toString() {#toString--}
```
public String toString()
```


Αναπαράσταση συμβολοσειράς ζεύγους μετατροπής


**Returns:**
java.lang.String - συμβολοσειρά

### getSource() {#getSource--}
```
public FileType getSource()
```


Μορφή αρχείου προέλευσης


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Μορφή αρχείου προορισμού


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Πρωτεύον ζεύγος μετατροπής ή όχι


**Returns:**
boolean - αληθές αν είναι πρωτεύον, αλλιώς όχι

