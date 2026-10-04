---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Ketika diatur, membatasi resolusi render PDF per halaman ke resolusi raster asli halaman sehingga sebuah halaman tidak pernah dirender pada DPI yang lebih tinggi daripada gambar tersemat yang sebenarnya dimilikinya dan mengeluarkan halaman tersebut dengan dimensi piksel asli yang lebih kecil serta DPI asli dalam output akhir alih-alih memperbesarnya ke DPI yang diminta. Hanya halaman pemindaian yang didominasi gambar yang terpengaruh; halaman dengan teks atau konten vektor tidak pernah dilunakkan dan dikeluarkan pada DPI yang diminta. Dilewati ketika output eksplisit Widthgroupdocs.conversion.options.convert/imageconvertoptions/width atau Heightgroupdocs.conversion.options.convert/imageconvertoptions/height diatur. Defaultnya adalah false (tanpa pembatasan); setiap halaman dirender dan dikeluarkan pada DPI yang diminta)."
type: docs
weight: 40
url: /id/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

Ketika diatur, membatasi resolusi render PDF per halaman ke resolusi raster asli halaman sehingga sebuah halaman tidak pernah dirender pada DPI yang lebih tinggi daripada gambar tersemat yang sebenarnya dimilikinya, dan mengeluarkan halaman tersebut dengan dimensi piksel asli (lebih kecil) serta DPI asli dalam output akhir alih-alih memperbesarnya kembali ke DPI yang diminta. Hanya halaman yang didominasi gambar (pemindaian) yang terpengaruh; halaman dengan teks atau konten vektor tidak pernah dilunakkan dan dikeluarkan pada DPI yang diminta. Dilewati ketika output eksplisit [`Width`](../width) atau [`Height`](../height) diatur. Defaultnya adalah `false` (tanpa pembatasan; setiap halaman dirender dan dikeluarkan pada DPI yang diminta).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### Lihat Juga

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
