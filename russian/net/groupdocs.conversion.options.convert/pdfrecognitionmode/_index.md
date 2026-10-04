---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Позволяет контролировать, как PDF‑документ преобразуется в документ текстового процессора."
type: docs
weight: 2160
url: /ru/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Позволяет контролировать, как PDF‑документ преобразуется в документ текстового процессора.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Сравнивает текущий объект с другим. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Определяет, равны ли два экземпляра объекта. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Служит функцией хеширования по умолчанию. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Возвращает строку, представляющую текущий объект. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Полный режим распознавания, движок выполняет группировку и многоуровневый анализ, чтобы восстановить намерения автора оригинального документа и создать максимально редактируемый документ. Недостаток заключается в том, что полученный документ может выглядеть иначе, чем оригинальный PDF‑файл. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Этот режим быстрый и хорошо сохраняет оригинальный внешний вид PDF‑файла, но редактируемость полученного документа может быть ограничена. Каждый визуально сгруппированный блок текста в оригинальном PDF‑файле преобразуется в текстовое поле в результирующем документе. Это обеспечивает максимальное сходство выходного документа с оригинальным PDF‑файлом. Выходной документ будет выглядеть хорошо, однако он будет полностью состоять из текстовых полей, что может сильно усложнить дальнейшее редактирование документа в Microsoft Word. Это режим по умолчанию. |

### См. также

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
