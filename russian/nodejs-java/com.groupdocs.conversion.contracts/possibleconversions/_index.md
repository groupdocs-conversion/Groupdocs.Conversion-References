---
title: "PossibleConversions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Представляет сопоставление, какие пары конвертации поддерживаются для конкретного формата исходного файла"
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Представляет сопоставление, какие пары конвертации поддерживаются для конкретного формата исходного файла
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Создает список возможных конвертаций для указанного формата исходного файла |
## Поля

| Поле | Описание |
| --- | --- |
| [NULL](#NULL) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) | Предопределенные параметры загрузки, которые могут быть использованы для конвертации из текущего типа |
| [getAll()](#getAll--) | Все типы целевых файлов и флаг основной/вторичный |
| [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Возвращает целевую конвертацию для указанного типа целевого файла |
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
| [getPrimary()](#getPrimary--) | Основные типы целевых файлов |
| [getSecondary()](#getSecondary--) | Вторичные типы целевых файлов |
| [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Добавить пару преобразования |
| [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Найти пару преобразования в текущем списке для целевого типа файла |
| [getSource()](#getSource--) | Форматы исходных файлов |
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Создает список возможных конвертаций для указанного формата исходного файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | тип исходного файла |

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Предопределенные параметры загрузки, которые могут быть использованы для конвертации из текущего типа

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options
### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Все типы целевых файлов и флаг основной/вторичный

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Итерация [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Возвращает целевую конвертацию для указанного типа целевого файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | целевой тип файла |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions
### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Основные типы целевых файлов

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - основные целевые типы файлов
### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Вторичные типы целевых файлов

**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - вторичные целевые типы файлов
### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Добавить пару преобразования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | пара преобразования |

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Найти пару преобразования в текущем списке для целевого типа файла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | целевой тип файла |

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair
### getSource() {#getSource--}
```
public FileType getSource()
```


Форматы исходных файлов

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats
