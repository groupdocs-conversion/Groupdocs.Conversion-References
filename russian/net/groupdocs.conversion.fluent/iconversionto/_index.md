---
title: IConversionTo
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Укажите способ хранения преобразованного документа
type: docs
weight: 1310
url: /ru/net/groupdocs.conversion.fluent/iconversionto/
---
## IConversionTo interface

Укажите способ хранения преобразованного документа

```csharp
public interface IConversionTo
```

## Методы

| Имя | Описание |
| --- | --- |
| [ConvertByPageTo](../../groupdocs.conversion.fluent/iconversionto/convertbypageto#convertbypageto_1)(Func&lt;int, FileType, Stream&gt;) | Сохранить преобразованную страницу как поток по типу |
| [ConvertByPageTo](../../groupdocs.conversion.fluent/iconversionto/convertbypageto#convertbypageto)(Func&lt;int, Stream&gt;) | Сохранить конвертированную страницу как stream |
| [ConvertTo](../../groupdocs.conversion.fluent/iconversionto/convertto#convertto_1)(Func&lt;FileType, Stream&gt;) | Сохранить конвертированный документ как поток по типу |
| [ConvertTo](../../groupdocs.conversion.fluent/iconversionto/convertto#convertto)(Func&lt;Stream&gt;) | Сохранить преобразованный документ как stream |
| [ConvertTo](../../groupdocs.conversion.fluent/iconversionto/convertto#convertto_2)(string) | Сохранить преобразованный документ как файл |

### Смотрите также

* пространство имен [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
