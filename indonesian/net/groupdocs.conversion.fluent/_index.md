---
title: "GroupDocs.Conversion.Fluent"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Namespace menyediakan antarmuka untuk konversi fluent."
type: docs
weight: 60
url: /id/net/groupdocs.conversion.fluent/
---
Namespace menyediakan antarmuka untuk konversi fluent.

## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IConversionByPageCompleted](./iconversionbypagecompleted) | Penanganan halaman konversi selesai |
| [IConversionByPageCompletedOrConvert](./iconversionbypagecompletedorconvert) | Tangani konversi selesai atau jalankan konversi |
| [IConversionByPageHandlerOnly](./iconversionbypagehandleronly) | Antarmuka fluida untuk mengatur hanya handler konversi per halaman. Handler tersebut didaftarkan melalui [`IConversionByPageHandlersStage`](../groupdocs.conversion.fluent/iconversionbypagehandlersstage). |
| [IConversionByPageHandlersStage](./iconversionbypagehandlersstage) | Tahap handler konversi per halaman yang diratakan. Cermin per halaman dari [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionByPageOptionsOrHandlerSetup](./iconversionbypageoptionsorhandlersetup) | Antarmuka fluida untuk mengatur opsi konversi per halaman atau penyiapan handler. Memungkinkan mengatur opsi atau handler dalam urutan apa pun, tetapi hanya satu kali masing‑masing, atau melewatkan keduanya. |
| [IConversionCompleted](./iconversioncompleted) | Tangani konversi selesai |
| [IConversionCompletedOrConvert](./iconversioncompletedorconvert) | Tangani konversi selesai atau jalankan konversi |
| [IConversionCompressResult](./iconversioncompressresult) | Dapat mengompres semua hasil konversi dalam satu arsip |
| [IConversionCompressResultCompletedOrConvert](./iconversioncompressresultcompletedorconvert) | Lanjutan setelah `Compress(...)`. Lanjutkan dengan `Convert`; daftarkan handler aliran terkompresi pada tahap masuk melalui [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents). |
| [IConversionConvert](./iconversionconvert) | Jalankan konversi |
| [IConversionConvertByPageOptions](./iconversionconvertbypageoptions) | Opsi konversi |
| [IConversionConvertOptionOrCompletedOrConvert](./iconversionconvertoptionorcompletedorconvert) | Opsi konversi atau konversi selesai atau jalankan |
| [IConversionConvertOptionOrPageCompletedOrConvert](./iconversionconvertoptionorpagecompletedorconvert) | Opsi konversi atau konversi selesai atau jalankan |
| [IConversionConvertOptions](./iconversionconvertoptions) | Opsi konversi |
| [IConversionConvertOrCompress](./iconversionconvertorcompress) | Kompres atau konversi |
| [IConversionFrom](./iconversionfrom) | Siapkan sumber untuk konversi |
| [IConversionGetDocumentInfo](./iconversiongetdocumentinfo) | Mendapatkan info dokumen sumber - jumlah halaman dan properti dokumen lain yang spesifik untuk tipe file. |
| [IConversionGetPossibleConversions](./iconversiongetpossibleconversions) | Mendapatkan konversi yang memungkinkan untuk dokumen sumber. |
| [IConversionHandlerOnly](./iconversionhandleronly) | Antarmuka fluida untuk mengatur hanya handler konversi. Handler tersebut didaftarkan melalui [`IConversionHandlersStage`](../groupdocs.conversion.fluent/iconversionhandlersstage). |
| [IConversionHandlersStage](./iconversionhandlersstage) | Tahap handler konversi yang diratakan. Memungkinkan mengatur `OnConversionCompleted` atau `OnConversionFailed` dalam urutan apa pun dan berulang kali, sebelum melanjutkan ke `Convert` / `Compress`. Event harus didaftarkan pada tahap awal melalui [`WithEvents`](../groupdocs.conversion.fluent/iconversionsettings/withevents) bukan pada tahap ini. |
| [IConversionIsPasswordProtected](./iconversionispasswordprotected) | Memeriksa apakah dokumen sumber dilindungi kata sandi |
| [IConversionLoadOptions](./iconversionloadoptions) | Opsi pemuatan konversi |
| [IConversionLoadOptionsOrSourceDocumentLoaded](./iconversionloadoptionsorsourcedocumentloaded) | Opsi pemuatan konversi atau tindakan dengan dokumen yang dimuat |
| [IConversionOptionsOnly](./iconversionoptionsonly) | Antarmuka fluida untuk mengatur hanya opsi konversi. |
| [IConversionOptionsOrHandlerSetup](./iconversionoptionsorhandlersetup) | Opsi konversi atau penyiapan handler konversi. |
| [IConversionSettings](./iconversionsettings) | Siapkan pengaturan konversi atau event pada tahap masuk (sebelum `Load`). |
| [IConversionSettingsOrConversionFrom](./iconversionsettingsorconversionfrom) | Pengaturan konversi atau sumber konversi |
| [IConversionSourceDocumentLoaded](./iconversionsourcedocumentloaded) | Menyediakan tindakan yang memungkinkan dengan dokumen yang dimuat |
| [IConversionTo](./iconversionto) | Atur bagaimana dokumen yang dikonversi disimpan |

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
