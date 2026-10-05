---
title: "PdfFileType"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет PDF‑документы."
type: docs
weight: 21
url: /ru/nodejs-java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Определяет PDF-документы. Включает следующие типы файлов: [Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype\#Pdf),
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileType()](#PdfFileType--) | Конструктор сериализации |
## Поля

| Поле | Описание |
| --- | --- |
| [Pdf](#Pdf) | Portable Document Format (PDF) — это тип документа, созданный Adobe в 1990‑х годах. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Конструктор сериализации

### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) — это тип документа, созданный Adobe в 1990‑х годах. Цель этого формата файла заключалась в введении стандарта представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/view/pdf

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
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
