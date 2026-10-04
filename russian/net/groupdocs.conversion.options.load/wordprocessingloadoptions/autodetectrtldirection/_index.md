---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Когда значение true, абзацы и пробеги по умолчанию, текст которых преимущественно направлен справа налево, будут иметь исправленные bidi‑флаги перед конвертацией. Это соответствует эвристике, применяемой Microsoft Word и LibreOffice, и исправляет отображение арабских/ивритских документов, созданных генераторами, в частности Google Docs, которые генерируют OOXML без ltwbidi/gt и с ltwrtl wval0/gt в пробегах, содержащих только RTL‑скрипт. Установите false, чтобы сохранить строгую интерпретацию OOXML исходной разметки."
type: docs
weight: 20
url: /ru/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Если true (по умолчанию), абзацы и участки текста, в которых преобладает направление справа налево, будут иметь исправленные bidi‑флаги до конвертации. Это соответствует эвристике, используемой Microsoft Word и LibreOffice, и исправляет отображение арабских/ивритских документов, созданных генераторами (в частности Google Docs), которые генерируют OOXML без &lt;w:bidi/&gt; и с &lt;w:rtl w:val=\"0\"/&gt; в участках, содержащих только RTL‑скрипт. Установите false, чтобы сохранить строгую интерпретацию OOXML исходной разметки.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### См. также

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
