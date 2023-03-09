---
title: ImageConvertOptions
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Opsi untuk konversi ke jenis file Gambar.
type: docs
weight: 1630
url: /id/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Opsi untuk konversi ke jenis file Gambar.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Menginisialisasi instance baru[`ImageConvertOptions`](../imageconvertoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Mengatur warna latar belakang yang didukung oleh format sumber |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Menyesuaikan kecerahan gambar. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Menyesuaikan kontras gambar. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Mode membalik gambar. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Jenis file yang diinginkan untuk konversi dokumen masukan. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Jenis file yang diinginkan untuk konversi dokumen masukan. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Menyesuaikan gamma gambar. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Menunjukkan apakah akan diubah menjadi gambar skala abu-abu. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Tinggi gambar yang diinginkan setelah konversi. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Resolusi horizontal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Opsi konversi khusus Jpeg. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Nomor halaman untuk memulai konversi. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Jumlah halaman yang akan dikonversi mulai dari`Nomor halaman` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Opsi konversi khusus psd. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Sudut rotasi gambar. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Opsi konversi khusus Tiff. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Jika`BENAR` , input terlebih dahulu dikonversi ke PDF dan setelah itu ke format yang diinginkan. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Resolusi vertikal gambar yang diinginkan setelah konversi. Resolusi default adalah resolusi file input atau 96 dpi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opsi khusus tanda air |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Opsi konversi khusus webp. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Lebar gambar yang diinginkan setelah konversi. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klon instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* ruang nama [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
