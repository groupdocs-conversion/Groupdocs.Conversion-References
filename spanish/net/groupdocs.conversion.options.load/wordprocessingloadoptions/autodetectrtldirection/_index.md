---
title: "AutoDetectRtlDirection"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Cuando es true, los párrafos y ejecuciones predeterminados cuyo texto es predominantemente de derecha a izquierda tendrán sus banderas bidi reparadas antes de la conversión. Esto coincide con la heurística que aplican Microsoft Word y LibreOffice y corrige la renderización de documentos en árabe/hebreo generados por herramientas, en particular Google Docs, que emiten OOXML sin ltwbidi/gt y con ltwrtl wval0/gt en ejecuciones que contienen solo script RTL. Establezca en false para preservar una interpretación estricta de OOXML del marcado fuente."
type: docs
weight: 20
url: /es/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Cuando es true (valor predeterminado), los párrafos y ejecuciones cuyo texto es predominantemente de derecha a izquierda tendrán sus banderas bidi reparadas antes de la conversión. Esto coincide con la heurística que aplican Microsoft Word y LibreOffice y corrige la renderización de documentos en árabe/hebreo generados por creadores (en particular Google Docs) que emiten OOXML sin &lt;w:bidi/&gt; y con &lt;w:rtl w:val="0"/&gt; en ejecuciones que contienen solo script RTL. Establezca a false para preservar la interpretación estricta de OOXML del marcado de origen.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### Ver también

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
