---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Параметры конвертации в тип файла Email."
type: docs
weight: 1800
url: /ru/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Параметры конвертации в тип файла Email.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Инициализирует новый экземпляр класса [`EmailConvertOptions`](../emailconvertoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Делегат для обработки пользовательских вложений электронной почты. Делегат принимает имя вложения, тип содержимого и исходный поток вложения в качестве параметров и возвращает изменённый поток вложения. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Желаемый тип файла, в который следует преобразовать входной документ. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Реализует [`Format`](../iconvertoptions/format) |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Клонирует текущий экземпляр параметров. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
