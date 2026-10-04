---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Определяет, проверять ли ограничения Excel‑файла, когда пользователь изменяет объекты, связанные с ячейками. Например, Excel не позволяет вводить строковое значение длиной более 32K. Когда вы вводите значение длиннее 32K, если это свойство равно true, вы получите Exception. Если это свойство равно false, мы примем введённую строку как значение ячейки, чтобы позже вы могли вывести полное строковое значение в другие форматы файлов, такие как CSV. Однако если вы задали такое значение, которое недопустимо для формата Excel, вы не должны сохранять книгу позже в формате Excel. В противном случае может возникнуть непредвиденная ошибка в сгенерированном файле Excel."
type: docs
weight: 40
url: /ru/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Проверять ограничения файла Excel, когда пользователь изменяет связанные с ячейками объекты. Например, Excel не позволяет вводить строковое значение длиной более 32K. Когда вы вводите значение длиннее 32K, если это свойство истинно, вы получите Exception. Если это свойство ложно, мы примем введённую строку как значение ячейки, чтобы позже вы могли вывести полное строковое значение в другие форматы файлов, такие как CSV. Однако, если вы задали значение, недопустимое для формата файла Excel, не следует сохранять рабочую книгу в формате Excel позже. В противном случае может возникнуть непредвиденная ошибка в сгенерированном файле Excel.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### См. также

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
