---
title: "com.groupdocs.conversion.contracts"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Пространство имен GroupDocs.Conversion.Contracts предоставляет члены для создания и освобождения выходного документа, управления заменой шрифтов и т.д."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/
---

Пространство имён GroupDocs.Conversion.Contracts предоставляет члены для создания и освобождения выходного документа, управления заменой шрифтов и т.д.


## Классы

| Класс | Описание |
| --- | --- |
| [ConversionPair](../com.groupdocs.conversion.contracts/conversionpair) | Представляет пару конвертации |
| [Enumeration](../com.groupdocs.conversion.contracts/enumeration) | Обобщённый класс перечисления. |
| [FontSubstitute](../com.groupdocs.conversion.contracts/fontsubstitute) | Описывает замену отсутствующего шрифта. |
| [PossibleConversions](../com.groupdocs.conversion.contracts/possibleconversions) | Представляет сопоставление, какие пары конвертации поддерживаются для конкретного формата исходного файла |
| [TargetConversion](../com.groupdocs.conversion.contracts/targetconversion) | Представляет возможную целевую конвертацию и флаг, является ли она основной или вторичной |
| [ValueObject](../com.groupdocs.conversion.contracts/valueobject) | Абстрактный класс объект-значения. |

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [ConvertOptionsProvider](../com.groupdocs.conversion.contracts/convertoptionsprovider) | Описывает делегат, предоставляющий параметры конвертации для конкретного исходного документа. |
| [ConvertedDocumentStream](../com.groupdocs.conversion.contracts/converteddocumentstream) | Описывает делегат, получающий поток конвертированного документа. |
| [ConvertedPageStream](../com.groupdocs.conversion.contracts/convertedpagestream) | Описывает делегат, получающий поток конвертированной страницы. |
| [ConverterSettingsProvider](../com.groupdocs.conversion.contracts/convertersettingsprovider) | Поставщик для ConverterSettings |
| [DocumentStreamProvider](../com.groupdocs.conversion.contracts/documentstreamprovider) | Поставщик для InputStream |
| [DocumentStreamsProvider](../com.groupdocs.conversion.contracts/documentstreamsprovider) | Поставщик для массива InputStream |
| [SaveDocumentStream](../com.groupdocs.conversion.contracts/savedocumentstream) | Описывает делегат для сохранения преобразованного документа в выходной поток. |
| [SaveDocumentStreamForFileType](../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Описывает делегат для сохранения преобразованного документа в поток. |
| [SavePageStream](../com.groupdocs.conversion.contracts/savepagestream) | Описывает делегат для сохранения страницы преобразованного документа в поток. |
| [SavePageStreamForFileType](../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Описывает делегат для сохранения страницы преобразованного документа в поток. |
