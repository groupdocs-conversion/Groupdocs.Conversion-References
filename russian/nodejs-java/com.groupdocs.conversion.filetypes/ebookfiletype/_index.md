---
title: "EBookFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет документы CAD (Computer Aided Design), которые используются для 3D графических форматов файлов и могут содержать 2D или 3D проекты."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Определяет CAD‑документы (Computer Aided Design), используемые для форматов файлов 3D‑графики и может содержать 2D или 3D‑дизайны. Включает следующие типы: [Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Epub), [Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Mobi), [Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype\#Azw3), Узнайте больше о CAD‑форматах [here][].


[here]: https://wiki.fileformat.com/cad
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EBookFileType()](#EBookFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Epub](#Epub) | Расширение EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и потребителей. |
| [Mobi](#Mobi) | Формат файла MOBI является одним из наиболее широко используемых форматов электронных книг. |
| [Azw3](#Azw3) | AZW3, также известный как Kindle Format 8 (KF8), является модифицированной версией цифрового формата электронных книг AZW, разработанной для устройств Amazon Kindle. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Конструктор сериализации

### Epub {#Epub}
```
public static final EBookFileType Epub
```


Расширение EPUB — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и потребителей. Этот формат стал настолько распространённым, что поддерживается многими электронными читалками и программными приложениями. Узнайте больше об этом формате файлов [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Формат файла MOBI является одним из наиболее широко используемых форматов электронных книг. Этот формат представляет собой улучшение старого формата OEB (Open Ebook Format) и использовался как проприетарный формат для Mobipocket Reader. Узнайте больше об этом формате файлов [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, также известный как Kindle Format 8 (KF8), является модифицированной версией цифрового формата электронных книг AZW, разработанной для устройств Amazon Kindle. Этот формат представляет собой улучшение более старых файлов AZW и используется только на устройствах Kindle Fire с обратной совместимостью с предшествующими форматами, то есть MOBI и AZW. Узнайте больше об этом формате файлов [here][].


[here]: https://docs.fileformat.com/ebook/azw3/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
