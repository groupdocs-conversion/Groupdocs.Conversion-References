---
title: "PublisherFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет документы Publisher."
type: docs
weight: 24
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Определяет документы Publisher. Включает следующие типы: [Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype\#Pub), Узнайте больше о форматах шрифтов [here][].


[here]: https://wiki.fileformat.com/publisher
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PublisherFileType()](#PublisherFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Pub](#Pub) | Файл PUB — это формат документа Microsoft Publisher. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Конструктор сериализации

### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Файл PUB — это формат документа Microsoft Publisher. Он используется для создания различных типов дизайн‑макетов, таких как информационные бюллетени, листовки, брошюры, открытки и т.д. Файлы PUB могут содержать текст, растровые и векторные изображения. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/publisher/pub/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Подготовлены параметры загрузки по умолчанию для исходного типа файла

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
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
