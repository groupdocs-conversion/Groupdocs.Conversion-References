---
title: "com.groupdocs.conversion.contracts"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Пространство имён GroupDocs.Conversion.Contracts предоставляет члены для создания и освобождения выходного документа, управления заменой шрифтов и т.д."
type: docs
weight: 12
url: /ru/java/com.groupdocs.conversion.contracts/
---

Пространство имен GroupDocs.Conversion.Contracts предоставляет члены для создания и освобождения выходного документа, управления заменой шрифтов и т.д.



## Классы

| Класс | Описание |
| --- | --- |
| [ConversionPair](../com.groupdocs.conversion.contracts/conversionpair) | Представляет пару преобразования |
| [Enumeration](../com.groupdocs.conversion.contracts/enumeration) | Обобщённый класс перечисления. |
| [FontSubstitute](../com.groupdocs.conversion.contracts/fontsubstitute) | Описывает замену отсутствующего шрифта. |
| [PossibleConversions](../com.groupdocs.conversion.contracts/possibleconversions) | Представляет сопоставление, какие пары преобразования поддерживаются для конкретного формата исходного файла |
| [TargetConversion](../com.groupdocs.conversion.contracts/targetconversion) | Представляет возможное целевое преобразование и флаг, является ли оно первичным или вторичным |
| [ValueObject](../com.groupdocs.conversion.contracts/valueobject) | Абстрактный класс объекта‑значения. |

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [ConvertOptionsProvider](../com.groupdocs.conversion.contracts/convertoptionsprovider) | Описывает делегат, предоставляющий параметры преобразования для конкретного исходного документа. |
| [ConvertedDocumentStream](../com.groupdocs.conversion.contracts/converteddocumentstream) | Описывает делегат для получения потока преобразованного документа. |
| [ConvertedPageStream](../com.groupdocs.conversion.contracts/convertedpagestream) | Описывает делегат для получения потока преобразованной страницы. |
| [ConverterSettingsProvider](../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик для ConverterSettings |
| [DocumentStreamProvider](../com.groupdocs.conversion.contracts/documentstreamprovider) | Поставщик для InputStream |
| [DocumentStreamsProvider](../com.groupdocs.conversion.contracts/documentstreamsprovider) | Поставщик для массива InputStream |
| [IDocument](../com.groupdocs.conversion.contracts/idocument) | Интерфейс для документов |
| [SaveDocumentStream](../com.groupdocs.conversion.contracts/savedocumentstream) | Описывает делегат для сохранения преобразованного документа в выходной поток. |
| [SaveDocumentStreamForFileType](../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Описывает делегат для сохранения преобразованного документа в поток. |
| [SavePageStream](../com.groupdocs.conversion.contracts/savepagestream) | Описывает делегат для сохранения страницы преобразованного документа в поток. |
| [SavePageStreamForFileType](../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Описывает делегат для сохранения страницы преобразованного документа в поток. |
