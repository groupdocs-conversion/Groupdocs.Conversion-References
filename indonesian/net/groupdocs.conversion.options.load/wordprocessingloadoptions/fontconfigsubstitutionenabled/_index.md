---
title: "FontConfigSubstitutionEnabled"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Secara otomatis menggantikan font yang hilang berdasarkan FontConfig di sistem. Default false."
type: docs
weight: 120
url: /id/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled/
---
## WordProcessingLoadOptions.FontConfigSubstitutionEnabled property

Secara otomatis menggantikan font yang hilang berdasarkan FontConfig di sistem. Default: false.

```csharp
public bool FontConfigSubstitutionEnabled { get; set; }
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
