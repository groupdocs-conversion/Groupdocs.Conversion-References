---
title: "WatermarkImageOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk mengatur watermark pada dokumen yang dikonversi"
type: docs
weight: 2290
url: /id/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

Opsi untuk mengatur watermark pada dokumen yang dikonversi

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | Buat kelas WatermarkOptions dan atur teks watermark |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Skala otomatis watermark. Jika nilai true posisi dan ukuran secara otomatis dihitung agar sesuai dengan ukuran halaman. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Menunjukkan bahwa watermark dicap sebagai latar belakang. Jika nilai true, watermark diletakkan di bagian bawah. Secara default false dan watermark diletakkan di atas. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Tinggi watermark |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | Watermark gambar |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Posisi kiri watermark |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Sudut rotasi watermark |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Posisi atas watermark |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Transparansi watermark. Nilai antara 0 dan 1. Nilai 0 sepenuhnya terlihat, nilai 1 tidak terlihat. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Lebar watermark |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Kloning instance saat ini |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
