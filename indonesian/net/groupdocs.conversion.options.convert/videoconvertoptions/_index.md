---
title: "VideoConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe Video."
type: docs
weight: 2280
url: /id/net/groupdocs.conversion.options.convert/videoconvertoptions/
---
## VideoConvertOptions class

Opsi untuk konversi ke tipe Video.

```csharp
public sealed class VideoConvertOptions : ConvertOptions<VideoFileType>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [VideoConvertOptions](videoconvertoptions)() | Menginisialisasi instance baru dari kelas [`VideoConvertOptions`](../videoconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AudioFormat](../../groupdocs.conversion.options.convert/videoconvertoptions/audioformat) { get; set; } | Format audio apa yang akan digunakan |
| [ExtractAudioOnly](../../groupdocs.conversion.options.convert/videoconvertoptions/extractaudioonly) { get; set; } | Jika diatur ke true, mengekstrak audio dari video |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [FramesPerSecond](../../groupdocs.conversion.options.convert/videoconvertoptions/framespersecond) { get; set; } | Frame per detik. Default adalah 30. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [VideoFileType](../../groupdocs.conversion.filetypes/videofiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
