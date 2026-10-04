---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Позволяет указать, как распознаются элементы нумерованного списка при конвертации простого текстового документа. Значение по умолчанию: true."
type: docs
weight: 30
url: /ru/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Позволяет указать, как распознаются элементы нумерованного списка при конвертации простого текстового документа. Значение по умолчанию: true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Примечания

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или маркерами (например, "•", "*", "-" или "o").

Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") в качестве символов.

### См. также

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
