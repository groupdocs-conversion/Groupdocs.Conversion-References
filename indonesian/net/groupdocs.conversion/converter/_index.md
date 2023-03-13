---
title: Converter
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Mewakili kelas utama yang mengontrol proses konversi dokumen.
type: docs
weight: 730
url: /id/net/groupdocs.conversion/converter/
---
## Converter class

Mewakili kelas utama yang mengontrol proses konversi dokumen.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Converter](converter#constructor)() | Menginisialisasi instance baru[`Converter`](../converter) kelas untuk penyiapan konversi yang lancar. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_7)(string) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Menginisialisasi instance baru[`Converter`](../converter) kelas. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan halaman dokumen yang dikonversi demi halaman. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Mengonversi dokumen sumber. Menyimpan seluruh dokumen yang dikonversi. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Merilis sumber daya. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Mendapat info dokumen sumber - jumlah halaman dan properti dokumen lainnya khusus untuk jenis file. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Mendapat kemungkinan konversi untuk dokumen sumber. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Konfigurasi aliran dokumen sumber |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Konfigurasi kumpulan aliran dokumen sumber |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Konfigurasi dokumen sumber untuk konversi |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Konfigurasi kumpulan dokumen sumber |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Konfigurasikan pengaturan konversi |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Mendapatkan semua konversi yang didukung |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Mendapatkan konversi yang didukung untuk ekstensi dokumen yang disediakan |

### Lihat juga

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* ruang nama [GroupDocs.Conversion](../../groupdocs.conversion)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
