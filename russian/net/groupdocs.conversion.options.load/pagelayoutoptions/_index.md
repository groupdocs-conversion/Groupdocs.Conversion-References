---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Описывает режимы макета страниц при загрузке веб‑документов."
type: docs
weight: 2720
url: /ru/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Описывает режимы макета страниц при загрузке веб‑документов.

```csharp
public class PageLayoutOptions : FlagsEnumeration
```

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Проверяет, имеет ли текущий флаг указанный флаг. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Проверяет, имеет ли текущий флаг указанное значение. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Преобразует текущий объект в строку. |
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Объединяет два флага [`PageLayoutOptions`](../pagelayoutoptions) с помощью побитового ИЛИ. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Значение по умолчанию. |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Этот флаг указывает, что содержимое документа будет масштабировано до высоты первой страницы. Всё содержимое документа будет размещено только на одной странице. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Указывает, что содержимое документа будет масштабировано до страницы, где разница между доступной шириной страницы и перекрывающимся содержимым наибольшая. |

### См. также

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
