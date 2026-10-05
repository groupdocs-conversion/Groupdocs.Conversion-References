---
title: "FontFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет документы шрифтов."
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/fontfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class FontFileType extends FileType implements Serializable
```

Определяет документы шрифтов. Включает следующие типы: [Ttf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Ttf), [Eot](../../com.groupdocs.conversion.filetypes/fontfiletype\#Eot), [Otf](../../com.groupdocs.conversion.filetypes/fontfiletype\#Otf), [Cff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Cff), [Type1](../../com.groupdocs.conversion.filetypes/fontfiletype\#Type1), [Woff](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff), [Woff2](../../com.groupdocs.conversion.filetypes/fontfiletype\#Woff2), Узнайте больше о форматах шрифтов [здесь][].


[here]: https://wiki.fileformat.com/font
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontFileType()](#FontFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Ttf](#Ttf) | Файл с расширением .ttf представляет шрифтовые файлы, основанные на технологии шрифтов TrueType. |
| [Eot](#Eot) | Файл с расширением .eot — это шрифт OpenType, встроенный в документ. |
| [Otf](#Otf) | Файл с расширением .otf относится к формату шрифтов OpenType. |
| [Cff](#Cff) | Файл с расширением .cff — это Compact Font Format, также известный как PostScript Type 1 или CIDFont. |
| [Type1](#Type1) | Шрифты Type 1 — устаревшая технология Adobe, которая широко использовалась в настольных издательских программах и принтерах, поддерживающих PostScript. |
| [Woff](#Woff) | Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). |
| [Woff2](#Woff2) | Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### FontFileType() {#FontFileType--}
```
public FontFileType()
```


Конструктор сериализации

### Ttf {#Ttf}
```
public static final FontFileType Ttf
```


Файл с расширением .ttf представляет шрифтовые файлы, основанные на технологии шрифтов TrueType. Изначально он был разработан и выпущен компанией Apple Computer, Inc для Mac OS, а позже принят Microsoft для Windows OS. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/ttf/

### Eot {#Eot}
```
public static final FontFileType Eot
```


Файл с расширением .eot — это шрифт OpenType, встроенный в документ. Они в основном используются в веб‑файлах, таких как веб‑страницы. Был создан Microsoft и поддерживается продуктами Microsoft, включая презентацию PowerPoint в формате .pps. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/eot/

### Otf {#Otf}
```
public static final FontFileType Otf
```


Файл с расширением .otf относится к формату шрифтов OpenType. Формат OTF более масштабируем и расширяет существующие возможности форматов TTF для цифровой типографии. Разработанный Microsoft и Adobe, OTF сочетает функции форматов шрифтов PostScript и TrueType. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/otf/

### Cff {#Cff}
```
public static final FontFileType Cff
```


Файл с расширением .cff — это Compact Font Format, также известный как PostScript Type 1 или CIDFont. CFF служит контейнером для хранения нескольких шрифтов вместе в единой единице, известной как FontSet. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/cff/

### Type1 {#Type1}
```
public static final FontFileType Type1
```


Шрифты Type 1 — устаревшая технология Adobe, которая широко использовалась в настольных издательских программах и принтерах, поддерживающих PostScript. Хотя шрифты Type 1 не поддерживаются во многих современных платформах, веб‑браузерах и мобильных операционных системах, они всё ещё поддерживаются в некоторых операционных системах. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/type1/

### Woff {#Woff}
```
public static final FontFileType Woff
```


Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). Он имеет специфичный для формата сжатый контейнер, основанный либо на шрифтах TrueType (.TTF), либо OpenType (.OTT). Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/woff/

### Woff2 {#Woff2}
```
public static final FontFileType Woff2
```


Файл с расширением .woff — это веб‑шрифт, основанный на формате Web Open Font Format (WOFF). Он имеет специфичный для формата сжатый контейнер, основанный либо на шрифтах TrueType (.TTF), либо OpenType (.OTT). Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/font/woff/

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
