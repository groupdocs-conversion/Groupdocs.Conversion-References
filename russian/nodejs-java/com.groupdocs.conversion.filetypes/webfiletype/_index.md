---
title: "WebFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет веб‑документы."
type: docs
weight: 27
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Определяет веб‑документы. Включает следующие типы: [Xml](../../com.groupdocs.conversion.filetypes/webfiletype\#Xml), [Json](../../com.groupdocs.conversion.filetypes/webfiletype\#Json), [Html](../../com.groupdocs.conversion.filetypes/webfiletype\#Html), [Htm](../../com.groupdocs.conversion.filetypes/webfiletype\#Htm), [Mht](../../com.groupdocs.conversion.filetypes/webfiletype\#Mht), [Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype\#Mhtml), [Chm](../../com.groupdocs.conversion.filetypes/webfiletype\#Chm), Узнайте больше о веб‑форматах [here][].


[here]: https://wiki.fileformat.com/web
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WebFileType()](#WebFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Xml](#Xml) | XML расшифровывается как Extensible Markup Language и похож на HTML, но отличается использованием тегов для определения объектов. |
| [Json](#Json) | JSON (JavaScript Object Notation) — это открытый стандартный формат файла для обмена данными, использующий человекочитаемый текст для хранения и передачи данных. |
| [Html](#Html) | HTML (Hyper Text Markup Language) — это расширение для веб‑страниц, созданных для отображения в браузерах. |
| [Htm](#Htm) | HTM (Hyper Text Markup Language) — это расширение для веб‑страниц, созданных для отображения в браузерах. |
| [Mht](#Mht) | Файлы с расширением MHTML представляют формат архива веб‑страницы, который может быть создан различными приложениями. |
| [Mhtml](#Mhtml) | Файлы с расширением MHTML представляют формат архива веб‑страницы, который может быть создан различными приложениями. |
| [Chm](#Chm) | Формат файла CHM представляет справочный файл Microsoft HTML, состоящий из набора HTML‑страниц. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Конструктор сериализации

### Xml {#Xml}
```
public static final WebFileType Xml
```


XML расшифровывается как Extensible Markup Language и похож на HTML, но отличается использованием тегов для определения объектов. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/xml

### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) — это открытый стандартный формат файла для обмена данными, использующий человекочитаемый текст для хранения и передачи данных. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/web/json

### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) — это расширение для веб‑страниц, созданных для отображения в браузерах. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/html

### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) — это расширение для веб‑страниц, созданных для отображения в браузерах. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/html

### Mht {#Mht}
```
public static final WebFileType Mht
```


Файлы с расширением MHTML представляют формат архива веб‑страницы, который может быть создан различными приложениями. Этот формат известен как архивный, потому что сохраняет веб‑HTML‑код и связанные ресурсы в одном файле. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


Файлы с расширением MHTML представляют формат архива веб‑страницы, который может быть создан различными приложениями. Этот формат известен как архивный, потому что сохраняет веб‑HTML‑код и связанные ресурсы в одном файле. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### Chm {#Chm}
```
public static final WebFileType Chm
```


Формат файла CHM представляет собой справочный файл Microsoft HTML, состоящий из набора HTML‑страниц. Он предоставляет индекс для быстрого доступа к темам и навигацию по различным частям справочного документа. Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/web/chm

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
