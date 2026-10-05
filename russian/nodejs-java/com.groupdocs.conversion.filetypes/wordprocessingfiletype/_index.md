---
title: "WordProcessingFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет файлы обработки текста, содержащие пользовательскую информацию в простом тексте или в формате RTF."
type: docs
weight: 28
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/wordprocessingfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WordProcessingFileType extends FileType implements Serializable
```

Определяет файлы обработки текста, содержащие пользовательскую информацию в формате обычного текста или форматированного текста. Формат обычного текста содержит неформатированный текст и не позволяет применять шрифты или настройки страницы и т.д. В отличие от этого, формат форматированного текста позволяет использовать параметры форматирования, такие как выбор типа шрифтов, стили (жирный, курсив, подчёркнутый и т.д.), поля страницы, заголовки, маркеры и нумерацию, а также ряд других функций форматирования. Включает следующие типы файлов: [Doc](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Doc), [Docm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docm), [Docx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Docx), [Dot](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dot), [Dotm](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotm), [Dotx](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Dotx), [Odt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Odt), [Ott](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Ott), [Rtf](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Rtf), [Txt](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Txt), [Md](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype\#Md), Узнайте больше о форматах обработки текста [here][].


[here]: https://wiki.fileformat.com/word-processing
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingFileType()](#WordProcessingFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Doc](#Doc) | Файлы с расширением .doc представляют документы, созданные Microsoft Word или другими программами обработки текста, в бинарном формате. |
| [Docm](#Docm) | Файлы DOCM — это документы, созданные в Microsoft Word 2007 и более новых версиях, с возможностью выполнения макросов. |
| [Docx](#Docx) | DOCX — известный формат документов Microsoft Word. |
| [Dot](#Dot) | Файлы с расширением .DOT являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно настроенные параметры для создания последующих файлов DOC или DOCX. |
| [Dotm](#Dotm) | Файл с расширением DOTM представляет собой шаблонный файл, созданный в Microsoft Word 2007 и более новых версиях. |
| [Dotx](#Dotx) | Файлы с расширением DOTX являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно настроенные параметры для создания последующих файлов DOCX. |
| [Rtf](#Rtf) | Введённый и задокументированный Microsoft, Rich Text Format (RTF) представляет собой метод кодирования форматированного текста и графики для использования в приложениях. |
| [Odt](#Odt) | Файлы ODT — это тип документов, создаваемых в приложениях обработки текста и основанных на формате OpenDocument Text. |
| [Ott](#Ott) | Файлы с расширением OTT представляют собой шаблонные документы, генерируемые приложениями в соответствии со стандартным форматом OpenDocument от OASIS. |
| [Txt](#Txt) | Файл с расширением .TXT представляет собой текстовый документ, содержащий обычный текст в виде строк. |
| [Md](#Md) | Текстовые файлы, созданные с использованием диалектов языка Markdown, сохраняются с расширением .MD или .MARKDOWN. |
| [Ml](#Ml) | Ml file |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WordProcessingFileType() {#WordProcessingFileType--}
```
public WordProcessingFileType()
```


Конструктор сериализации

### Doc {#Doc}
```
public static final WordProcessingFileType Doc
```


Файлы с расширением .doc представляют документы, созданные Microsoft Word или другими программами обработки текста, в бинарном формате. Узнайте больше об этом формате файлов [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### Docm {#Docm}
```
public static final WordProcessingFileType Docm
```


Файлы DOCM — это документы, созданные в Microsoft Word 2007 и более новых версиях, с возможностью выполнения макросов. Узнайте больше об этом формате файлов [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### Docx {#Docx}
```
public static final WordProcessingFileType Docx
```


DOCX — известный формат документов Microsoft Word. Представлен в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого бинарного на комбинацию XML и бинарных файлов. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/docx

### Dot {#Dot}
```
public static final WordProcessingFileType Dot
```


Файлы с расширением .DOT являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно отформатированные настройки для создания последующих файлов DOC или DOCX. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/dot

### Dotm {#Dotm}
```
public static final WordProcessingFileType Dotm
```


Файл с расширением DOTM представляет собой шаблонный файл, созданный в Microsoft Word 2007 или более новой версии. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### Dotx {#Dotx}
```
public static final WordProcessingFileType Dotx
```


Файлы с расширением DOTX являются шаблонными файлами, созданными Microsoft Word, содержащими предварительно отформатированные настройки для создания последующих файлов DOCX. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### Rtf {#Rtf}
```
public static final WordProcessingFileType Rtf
```


Введённый и задокументированный Microsoft, формат Rich Text Format (RTF) представляет метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### Odt {#Odt}
```
public static final WordProcessingFileType Odt
```


Файлы ODT — это тип документов, создаваемых в текстовых процессорах, основанных на формате OpenDocument Text. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/odt

### Ott {#Ott}
```
public static final WordProcessingFileType Ott
```


Файлы с расширением OTT представляют собой шаблонные документы, генерируемые приложениями в соответствии со стандартным форматом OpenDocument от OASIS. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/ott

### Txt {#Txt}
```
public static final WordProcessingFileType Txt
```


Файл с расширением .TXT представляет собой текстовый документ, содержащий обычный текст в виде строк. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/txt

### Md {#Md}
```
public static final WordProcessingFileType Md
```


Текстовые файлы, созданные с использованием диалектов языка Markdown, сохраняются с расширением .MD или .MARKDOWN. Файлы MD сохраняются в формате обычного текста, использующего язык Markdown, который также включает встроенные текстовые символы, определяющие форматирование текста, такие как отступы, таблицы, шрифты и заголовки. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/md

### Ml {#Ml}
```
public static final WordProcessingFileType Ml
```


Ml file

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions<WordProcessingFileType> getConvertOptions()
```


Подготовлены параметры конвертации по умолчанию для типа файла

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
