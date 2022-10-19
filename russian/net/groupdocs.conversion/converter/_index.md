---
title: Converter
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Представляет основной класс управляющий процессом преобразования документа.
type: docs
weight: 670
url: /ru/net/groupdocs.conversion/converter/
---
## Converter class

Представляет основной класс, управляющий процессом преобразования документа.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Converter](converter#constructor)() | Инициализирует новый экземпляр[`Converter`](../converter) класс для быстрой настройки преобразования. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_7)(string) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Инициализирует новый экземпляр[`Converter`](../converter) класс. |

## Методы

| Имя | Описание |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(SaveDocumentStream, ConvertOptions) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(SaveDocumentStream, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(SaveDocumentStreamForFileType, ConvertOptions) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(SaveDocumentStreamForFileType, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(SavePageStream, ConvertOptions) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(SavePageStream, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(SavePageStreamForFileType, ConvertOptions) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(SavePageStreamForFileType, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет весь преобразованный документ. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(SavePageStream, ConvertedPageStream, ConvertOptions) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) | Преобразует исходный документ. Сохраняет преобразованный документ страница за страницей. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Освобождает ресурсы. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Получает информацию об исходном документе — количество страниц и другие свойства документа, относящиеся к типу файла. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Получает возможные преобразования исходного документа. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Настроить исходный документ stream |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Настроить набор исходных документов streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Настроить исходный документ для преобразования |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Настроить набор исходных документов |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Настройка параметров преобразования |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Получает все поддерживаемые преобразования |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Получает поддерживаемые преобразования для указанного расширения документа |

### Смотрите также

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* пространство имен [GroupDocs.Conversion](../../groupdocs.conversion)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
