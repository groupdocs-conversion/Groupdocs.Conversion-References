---
title: "ConversionPair"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يمثل زوج التحويل"
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

يمثل زوج التحويل

## الحقول

| حقل | الوصف |
| --- | --- |
| [NULL](#NULL) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | ينشئ زوج التحويل الأساسي |
|
|  | [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | ينشئ أزواج التحويل الأساسية |
|
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
|  | [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | ينشئ زوج التحويل الثانوي |
|
|  | [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | ينشئ أزواج التحويل الثانوية |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | مكونات المساواة |
|
|  | [toString()](#toString--) | تمثيل سلسلة زوج التحويل |
|
|  | [getSource()](#getSource--) | تنسيق ملف المصدر |
|
|  | [getTarget()](#getTarget--) | تنسيق ملف الهدف |
|
|  | [isPrimary()](#isPrimary--) | زوج التحويل الأساسي أم لا |
|
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


ينشئ زوج التحويل الأساسي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | المصدر |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | الهدف |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


ينشئ أزواج التحويل الأساسية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المصادر | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | نوع ملف المصادر |
|
|  | الأهداف | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | نوع ملف الأهداف |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - أزواج التحويل الأساسية

### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المصادر | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| الأهداف | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


ينشئ زوج التحويل الثانوي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف المصدر |
|
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | نوع ملف الهدف |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair

### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


ينشئ أزواج التحويل الثانوية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المصادر | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | نوع ملف المصادر |
|
|  | الأهداف | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | نوع ملف الأهداف |
|

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - أزواج التحويل الثانوية

### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


مكونات المساواة


**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - مكونات المساواة

### toString() {#toString--}
```
public String toString()
```


تمثيل سلسلة زوج التحويل


**Returns:**
java.lang.String - سلسلة

### getSource() {#getSource--}
```
public FileType getSource()
```


تنسيق ملف المصدر


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format

### getTarget() {#getTarget--}
```
public FileType getTarget()
```


تنسيق ملف الهدف


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


زوج التحويل الأساسي أم لا


**Returns:**
boolean - صحيح إذا كان أساسيًا، وإلا إذا لم يكن

