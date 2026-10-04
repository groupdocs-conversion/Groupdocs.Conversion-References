---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Argumen yang diteruskan ke ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /id/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Argumen yang diteruskan ke [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Nama file (atau id placeholder) disematkan sebagai URI gambar dalam output Markdown. Tetapkan untuk menulis ulang URI. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Aliran tujuan yang akan ditulisi byte gambar oleh konverter setelah callback ini kembali. Ganti dengan aliran yang dapat ditulisi milik Anda (mis., FileStream untuk penyimpanan disk atau MemoryStream yang akan Anda baca setelahnya). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Ketika false (default), konverter menutup [`ImageStream`](./imagestream) setelah menulis — umum untuk pengganti FileStream yang harus di-flush ke disk. Atur ke true untuk menjaga aliran tetap terbuka setelah konversi selesai (biasanya untuk MemoryStream yang ingin Anda baca sendiri); pemanggil kemudian bertanggung jawab atas pembuangan. |

### Lihat Juga

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
