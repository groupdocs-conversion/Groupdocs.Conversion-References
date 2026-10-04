---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры загрузки XML‑документов."
type: docs
weight: 2960
url: /ru/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Параметры загрузки XML‑документов.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Инициализирует новый экземпляр класса [`XmlLoadOptions`](../xmlloadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Базовый путь/URL для html |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Действие для настройки заголовков запроса. Первый параметр действия — Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Поставщик учётных данных для Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Реализует [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Получает или задаёт кодировку, используемую при загрузке веб‑документа. Если свойство равно null, кодировка будет определена из атрибута набора символов документа. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Тип файла входного документа. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Тип файла входного документа. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Управляет тем, как отображается HTML‑контент. По умолчанию: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Настройки полей страницы |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Настройки ориентации страницы |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Указывает параметры макета страницы при загрузке веб‑документов. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Включает или отключает генерацию нумерации страниц в конвертированном документе. По умолчанию: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Тайм‑аут для загрузки внешних ресурсов |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Настройки размера страницы |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Реализует [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Использовать Xml‑документ в качестве источника данных |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Использовать pdf для конвертации. По умолчанию: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Реализует [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | Поток XSL-FO документа для преобразования XML с использованием файла разметки XSL-FO. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | Поток XSLT документа для преобразования XML, выполняющего XSL‑трансформацию в HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Указывает уровень масштабирования в процентах. Уровень масштабирования применяется к тегу &lt;body&gt; документа перед конвертацией, изменяя визуальное отображение документа. Значение 100 % соответствует оригинальному размеру. Значение по умолчанию — 100. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
