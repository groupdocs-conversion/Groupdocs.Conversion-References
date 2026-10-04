---
title: "LayoutScope"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengambil atau mengatur ruang gambar mana yang dikonversi. Default ke Bothgroupdocs.conversion.options.load/cadlayoutscope/both yang tidak membatasi konversi. Diabaikan ketika LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames disediakan karena nama tata letak eksplisit selalu menang. Nilai null diperlakukan sebagai Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /id/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Mengambil atau mengatur ruang gambar mana yang dikonversi. Default ke [`Both`](../../cadlayoutscope/both), yang tidak membatasi konversi. Diabaikan ketika [`LayoutNames`](../layoutnames) disediakan, karena nama tata letak eksplisit selalu menang. Nilai `null` diperlakukan sebagai [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Catatan

Ruang lingkup yang tidak memilih satu pun lembar yang ditawarkan gambar menyebabkan konversi gagal dengan [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) yang menyebutkan ruang lingkup dan lembar yang ada, alih-alih menampilkan ruang yang dikecualikan oleh ruang lingkup. Gambar yang tidak menawarkan lembar apa pun tidak terpengaruh dan tetap dikonversi sebagai satu unit. Tidak dihormati saat mengonversi ke PDF/UA-1, karena alasan yang diberikan pada [`LayoutNames`](../layoutnames).

### Lihat Juga

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
