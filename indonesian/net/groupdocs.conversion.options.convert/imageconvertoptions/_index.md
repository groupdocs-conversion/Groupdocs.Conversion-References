---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Gambar."
type: docs
weight: 1950
url: /id/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opsi untuk konversi ke tipe file Gambar.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Menginisialisasi instance baru dari kelas [`ImageConvertOptions`](../imageconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Mengatur warna latar belakang bila didukung oleh format sumber |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Menyesuaikan kecerahan gambar. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Jika diatur, membatasi resolusi render PDF per halaman ke resolusi raster asli halaman sehingga sebuah halaman tidak pernah dirender pada DPI yang lebih tinggi daripada yang sebenarnya terkandung dalam gambar tersemat, dan mengeluarkan halaman tersebut dengan dimensi piksel asli (lebih kecil) dan DPI asli pada output akhir alih-alih memperbesarnya ke DPI yang diminta. Hanya halaman yang didominasi gambar (pemindaian) yang terpengaruh; halaman dengan teks atau konten vektor tidak pernah dilunakkan dan dikeluarkan pada DPI yang diminta. Dilewati ketika output eksplisit [`Width`](./width) atau [`Height`](./height) diatur. Nilai default adalah `false` (tidak ada pembatasan; setiap halaman dirender dan dikeluarkan pada DPI yang diminta). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Menyesuaikan kontras gambar. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Memotong area gambar raster setelah konversi |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Mode pembalikan gambar. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Menyesuaikan gamma gambar. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Menunjukkan apakah akan mengonversi menjadi gambar skala abu-abu. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Tinggi gambar yang diinginkan setelah konversi. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Resolusi horizontal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file masukan atau 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Opsi konversi khusus Jpeg. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | Batas bawah per‑sumbu yang diterapkan pada DPI render yang dibatasi ketika [`CapResolutionToPageContent`](./capresolutiontopagecontent) diaktifkan. DPI yang dibatasi tidak pernah diturunkan di bawah nilai ini. Nilai default adalah `0` (tanpa batas bawah). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Opsi konversi khusus Psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Sudut rotasi gambar. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Opsi konversi khusus Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Jika `true`, input pertama-tama dikonversi ke PDF dan kemudian ke format yang diinginkan. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Resolusi vertikal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file masukan atau 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Menerapkan [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Opsi konversi khusus Webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Lebar gambar yang diinginkan setelah konversi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
