---
title: "ConversionPair"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Представляет пару конвертации"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/conversionpair/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class ConversionPair extends ValueObject
```

Представляет пару конвертации
## Поля

| Поле | Описание |
| --- | --- |
| [NULL](#NULL) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createPrimary(FileType source, FileType target)](#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Создаёт основную пару преобразования |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--) | Создаёт основные пары преобразования |
| [createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)](#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----) |  |
| [createSecondary(FileType source, FileType target)](#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-) | Создаёт вторичную пару преобразования |
| [createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)](#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--) | Создает вторичные пары преобразования |
| [getEqualityComponents()](#getEqualityComponents--) | Компоненты равенства |
| [toString()](#toString--) | Строковое представление пары преобразования |
| [getSource()](#getSource--) | Формат исходного файла |
| [getTarget()](#getTarget--) | Формат целевого файла |
| [isPrimary()](#isPrimary--) | Основная пара преобразования или нет |
### NULL {#NULL}
```
public static final ConversionPair NULL
```


### createPrimary(FileType source, FileType target) {#createPrimary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createPrimary(FileType source, FileType target)
```


Создаёт основную пару преобразования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | исходный |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | целевой |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - ConversionPair
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets)
```


Создаёт основные пары преобразования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исходные | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | тип файлов-источников |
| целевые | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> | тип целевых файлов |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - основные пары преобразования
### createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs) {#createPrimary-java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--java.util.List---extends-com.groupdocs.conversion.filetypes.FileType--com.groupdocs.conversion.contracts.Pair-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType----}
```
public static List<ConversionPair> createPrimary(List<? extends FileType> sources, List<? extends FileType> targets, Pair<FileType,FileType>[] excludedPairs)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исходные | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| целевые | java.util.List<? extends com.groupdocs.conversion.filetypes.FileType> |  |
| excludedPairs | com.groupdocs.conversion.contracts.Pair<com.groupdocs.conversion.filetypes.FileType,com.groupdocs.conversion.filetypes.FileType>[] |  |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair>
### createSecondary(FileType source, FileType target) {#createSecondary-com.groupdocs.conversion.filetypes.FileType-com.groupdocs.conversion.filetypes.FileType-}
```
public static ConversionPair createSecondary(FileType source, FileType target)
```


Создаёт вторичную пару преобразования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | тип исходного файла |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | целевой тип файла |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - secondary conversion pair
### createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets) {#createSecondary-java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--java.lang.Iterable---extends-com.groupdocs.conversion.filetypes.FileType--}
```
public static List<ConversionPair> createSecondary(Iterable<? extends FileType> sources, Iterable<? extends FileType> targets)
```


Создает вторичные пары преобразования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исходные | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | тип файлов-источников |
| целевые | java.lang.Iterable<? extends com.groupdocs.conversion.filetypes.FileType> | тип целевых файлов |

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.ConversionPair> - вторичные пары преобразования
### getEqualityComponents() {#getEqualityComponents--}
```
public System.Collections.Generic.IGenericEnumerable getEqualityComponents()
```


Компоненты равенства

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable - компоненты равенства
### toString() {#toString--}
```
public String toString()
```


Строковое представление пары преобразования

**Returns:**
java.lang.String - строка
### getSource() {#getSource--}
```
public FileType getSource()
```


Формат исходного файла

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - source file format
### getTarget() {#getTarget--}
```
public FileType getTarget()
```


Формат целевого файла

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - target file format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Основная пара преобразования или нет

**Returns:**
boolean - true если основной, иначе нет
