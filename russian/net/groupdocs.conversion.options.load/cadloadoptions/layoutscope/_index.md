---
title: "LayoutScope"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получает или задает, какие пространства чертежа конвертируются. По умолчанию Bothgroupdocs.conversion.options.load/cadlayoutscope/both, что не ограничивает конвертацию. Игнорируется, когда указаны LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames, поскольку явные имена макетов всегда имеют приоритет. Значение null рассматривается как Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /ru/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Получает или задает, какие пространства чертежа конвертируются. По умолчанию [`Both`](../../cadlayoutscope/both), что не ограничивает конвертацию. Игнорируется, когда указаны [`LayoutNames`](../layoutnames), поскольку явные имена макетов всегда имеют приоритет. Значение `null` рассматривается как [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Примечания

Область, которая не выбирает ни один из листов, предлагаемых чертежом, приводит к ошибке конвертации с [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception), указывающей область и доступные листы, вместо рендеринга пространств, исключённых областью. Чертеж, не предлагающий ни одного листа, остаётся неизменным и всё равно конвертируется как единое целое. Не учитывается при конвертации в PDF/UA-1 по причине, указанной в [`LayoutNames`](../layoutnames).

### См. также

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
