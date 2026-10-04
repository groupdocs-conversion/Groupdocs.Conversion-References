---
title: "DefaultFont"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengatur font default untuk dokumen WordProcessing."
type: docs
weight: 90
url: /id/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Mengatur font default untuk dokumen WordProcessing.

```csharp
public string DefaultFont { get; set; }
```

### Catatan

**Note:** The order of substitution is as follows:

1) Secara otomatis menggantikan font yang hilang berdasarkan nama font (jika diaktifkan).

2) Secara otomatis menggantikan font yang hilang berdasarkan FontConfig (jika diaktifkan).

3) Gantikan font yang hilang berdasarkan FontSubstitutes (jika disetel).

4) Secara otomatis menggantikan font yang hilang berdasarkan FontInfo (jika diaktifkan).

5) Gantikan font yang hilang berdasarkan DefaultFont (jika disetel).

### Lihat Juga

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
