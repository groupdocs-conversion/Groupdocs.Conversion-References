---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Ketika true, paragraf dan run default yang teksnya dominan righttoleft akan memiliki flag bidi yang diperbaiki sebelum konversi. Ini cocok dengan heuristik yang diterapkan Microsoft Word dan LibreOffice serta memperbaiki rendering dokumen Arab/Ibrani yang dihasilkan oleh generator, terutama Google Docs, yang menghasilkan OOXML tanpa ltwbidi/gt dan dengan ltwrtl wval0/gt pada run yang hanya berisi skrip RTL. Atur ke false untuk mempertahankan interpretasi OOXML yang ketat dari markup sumber."
type: docs
weight: 20
url: /id/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Jika bernilai true (default), paragraf dan run yang teksnya dominan kanan-ke-kiri akan memiliki flag bidi yang diperbaiki sebelum konversi. Ini cocok dengan heuristik yang diterapkan oleh Microsoft Word dan LibreOffice serta memperbaiki rendering dokumen Arab/Hebrew yang dihasilkan oleh pembuat (khususnya Google Docs) yang menghasilkan OOXML tanpa &lt;w:bidi/&gt; dan dengan &lt;w:rtl w:val="0"/&gt; pada run yang hanya berisi skrip RTL. Atur ke false untuk mempertahankan interpretasi OOXML yang ketat dari markup sumber.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### Lihat Juga

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
