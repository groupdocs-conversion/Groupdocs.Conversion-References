---
title: "groupdocs.conversion.fluent"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Tipe di bawah groupdocs.conversion.fluent."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


Tipe di bawah `groupdocs.conversion.fluent`.

### Kelas
| Kelas | Deskripsi |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | Menangani halaman konversi selesai. |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | Menangani penyelesaian konversi atau mengeksekusi konversi. |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | Menyediakan antarmuka fluida setelah `OnConversionFailed` diatur untuk konversi halaman. Memungkinkan pengaturan `OnConversionCompleted` atau melanjutkan ke `Convert`/`Compress`. |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | Mewakili antarmuka fluida setelah `OnConversionCompleted` diatur untuk konversi halaman, memungkinkan konfigurasi `OnConversionFailed` atau melanjutkan ke `Convert`/`Compress`. |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | Menyediakan antarmuka fluida untuk mengatur hanya penangan konversi per halaman. |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | Menyediakan antarmuka fluida untuk mengatur penangan konversi halaman. |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | Mewakili tahap penangan konversi per halaman yang diratakan. |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | Antarmuka fluida untuk mengatur opsi konversi per halaman atau penyiapan penangan. |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | Menangani konversi selesai. |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | Menangani konversi selesai atau mengeksekusi konversi. |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | Mengompres semua hasil konversi menjadi satu arsip. |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | Menangani kompresi selesai. |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | Lanjutan setelah `Compress(...)`. Lanjutkan langsung dengan `Convert`; [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) yang diwarisi sudah usang — daftarkan penangan pada tahap masuk melalui [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) sebagai gantinya. |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | Eksekusi konversi. |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | Mewakili opsi konversi. |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | Mewakili opsi konversi, penanganan penyelesaian, atau eksekusi untuk sebuah konversi. |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | Mewakili opsi konversi, penanganan penyelesaian, atau eksekusi. |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | Mewakili opsi konversi. |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | Kompres atau konversi. |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | Menyiapkan sumber untuk konversi. |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file. |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | Mendapatkan konversi yang memungkinkan untuk dokumen sumber. |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | Mewakili antarmuka fluida setelah `OnConversionFailed` diatur, memungkinkan pengaturan `OnConversionCompleted` atau melanjutkan ke `Convert`/`Compress`. |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | Menyediakan antarmuka fluida setelah `OnConversionCompleted` diatur, memungkinkan konfigurasi `OnConversionFailed` atau melanjutkan ke `Convert`/`Compress`. |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | Menyediakan antarmuka fluida untuk mengatur hanya penangan konversi. |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | Menyediakan antarmuka fluida untuk mengatur penangan konversi. Memungkinkan pengaturan `OnConversionCompleted` dan/atau `OnConversionFailed` dalam urutan apa pun, masing‑masing paling banyak sekali, atau melewatkan keduanya. |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | Mewakili tahap penangan konversi yang diratakan. |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | Memeriksa apakah dokumen sumber dilindungi kata sandi. |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | Mewakili opsi pemuatan konversi. |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | Mewakili opsi pemuatan konversi atau tindakan dengan dokumen yang dimuat. |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | Menyediakan antarmuka fluida untuk mengatur hanya opsi konversi. |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | Mewakili opsi konversi atau pengaturan penangan konversi. |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | Menyiapkan pengaturan konversi atau peristiwa pada tahap masuk (sebelum `Load`). |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | Mewakili pengaturan konversi atau sumber konversi. |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | Menyediakan tindakan yang mungkin dengan dokumen yang dimuat. |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | Mengatur bagaimana dokumen yang dikonversi disimpan. |
