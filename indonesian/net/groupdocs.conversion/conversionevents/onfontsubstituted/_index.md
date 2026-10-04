---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Dipicu ketika font yang dirujuk oleh dokumen sumber tidak tersedia dan diganti baik oleh aturan FontSubstitutegroupdocs.conversion.contracts/fontsubstitute yang disediakan pelanggan, oleh font default yang dikonfigurasi, atau oleh fallback internal pipeline konversi."
type: docs
weight: 80
url: /id/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Dipicu ketika font yang dirujuk oleh dokumen sumber tidak tersedia dan diganti (baik oleh aturan [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute) yang disediakan pelanggan, oleh font default yang dikonfigurasi, atau oleh fallback internal pipeline konversi).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Catatan

Acara ini didedupikasi per `(SourceFileName, OriginalFontName)` dalam satu panggilan `Converter.Convert(...)` — pelanggan menerima paling banyak satu notifikasi per font yang hilang per dokumen sumber. Dipicu secara sinkron pada thread konversi. Tidak diaktifkan untuk konversi gambar.

Untuk dokumen presentasi, substitusi font hanya terdeteksi di Windows, karena mesin menyelesaikannya melalui pencocokan font spesifik platform yang tidak tersedia di sistem operasi lain.

### Lihat Juga

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
