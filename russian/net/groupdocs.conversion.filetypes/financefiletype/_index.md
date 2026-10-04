---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет финансовые документы. Включает следующие типы Xbrl./financefiletype/xbrl IXbrl./financefiletype/ixbrl Ofx./financefiletype/ofx. Узнайте больше о финансовых форматах здесьhttps//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /ru/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Определяет финансовые документы. Включает следующие типы: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx). Узнайте больше о финансовых форматах [здесь](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FinanceFileType](financefiletype)() | Конструктор сериализации |

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Описание типа файла |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Расширение файла |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Семейство файлов |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Формат файла |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Реализует [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Строковое представление |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Внутри iXBRL содержимое XBRL обернуто в формат файла xHTML, который использует XML‑теги. Как и XBRL, он является корневым элементом файлов iXBRL. Формат XHTML представляет его содержимое как коллекцию различных типов документов и модулей. Все файлы в XHTML основаны на формате файла XML и соответствуют стандартам XML‑документов. Узнайте больше об этом формате файла [здесь](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) — это потоковый формат данных для обмена финансовой информацией, который возник из форматов файлов Microsoft Open Financial Connectivity (OFC) и Intuit Open Exchange. Узнайте больше об этом формате файла [здесь](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL — это открытый международный стандарт цифровой бизнес‑отчётности, широко используемый по всему миру. Это язык на основе XML, который использует элементы XBRL, известные как теги, для описания каждого элемента бизнес‑данных с целью формирования данных для сортировки и анализа отчётов. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/finance/xbrl/). |

### См. также

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
