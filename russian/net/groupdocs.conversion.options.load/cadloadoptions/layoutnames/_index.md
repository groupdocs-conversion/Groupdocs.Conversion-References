---
title: "LayoutNames"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Указывает, какие макеты CAD следует преобразовать"
type: docs
weight: 70
url: /ru/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Указывает, какие макеты CAD следует преобразовать

```csharp
public string[] LayoutNames { get; set; }
```

### Примечания

Не учитывается при конвертации в PDF/UA-1. Эта цель отображает чертеж как одну помеченную страницу, которая не может содержать отдельный лист для выбранного макета, поэтому вместо этого конвертируется весь чертеж и здесь ничего не применяется. Все остальные цели, включая PDF, учитывают выбор. На этих целях имена сравниваются точно с макетами, присутствующими в чертеже, поэтому имя, отличающееся только регистром, считается другим именем. Имя, которое ни с чем не совпадает, отбрасывается, и вызывающий платит только за этот лист; список, в котором ничего не совпадает, приводит к ошибке конвертации с [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception), указывающей имена, которые не найдены, и макеты, присутствующие в чертеже, вместо рендеринга листов, которые вызывающий не запрашивал. Чертеж, не содержащий никаких макетов, исключён: для имени нет чего сопоставлять, поэтому ни одно не отклоняется.

### См. также

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
