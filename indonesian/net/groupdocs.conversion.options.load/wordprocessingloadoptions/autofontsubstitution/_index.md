---
title: AutoFontSubstitution
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Jika AutoFontSubstitution dinonaktifkan GroupDocs.Conversion menggunakan DefaultFont untuk mengganti font yang hilang. Jika AutoFontSubstitution diaktifkan GroupDocs.Conversion mengevaluasi semua bidang terkait di FontInfo Panose Sig dll. untuk font yang hilang dan menemukan kecocokan terdekat di antara sumber font yang tersedia. Perhatikan bahwa mekanisme penggantian font akan menggantikan DefaultFont jika FontInfo untuk font yang hilang tersedia di dokumen. Nilai defaultnya adalah True.
type: docs
weight: 20
url: /id/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autofontsubstitution/
---
## WordProcessingLoadOptions.AutoFontSubstitution property

Jika AutoFontSubstitution dinonaktifkan, GroupDocs.Conversion menggunakan DefaultFont untuk mengganti font yang hilang. Jika AutoFontSubstitution diaktifkan, GroupDocs.Conversion mengevaluasi semua bidang terkait di FontInfo (Panose, Sig, dll.) untuk font yang hilang dan menemukan kecocokan terdekat di antara sumber font yang tersedia. Perhatikan bahwa mekanisme penggantian font akan menggantikan DefaultFont jika FontInfo untuk font yang hilang tersedia di dokumen. Nilai defaultnya adalah True.

```csharp
public bool AutoFontSubstitution { get; set; }
```

### Lihat juga

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* ruang nama [GroupDocs.Conversion.Options.Load](../../wordprocessingloadoptions)
* perakitan [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->