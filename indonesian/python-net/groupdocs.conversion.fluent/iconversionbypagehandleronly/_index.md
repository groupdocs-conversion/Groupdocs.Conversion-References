---
title: "Kelas IConversionByPageHandlerOnly"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menyediakan antarmuka fluida untuk mengatur hanya penangan konversi per halaman."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Menyediakan antarmuka fluida untuk mengatur hanya penangan konversi per halaman.

Mewarisi [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) untuk `Convert`/`Compress`; overload `OnConversion*` yang bertahap dipertahankan melalui kata kunci `new` untuk menjaga kompatibilitas mundur.

Tipe IConversionByPageHandlerOnly menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Mengompres hasil konversi; daftarkan handler aliran‑terkompresi pada tahap masuk melalui [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (menetapkan `OnCompressionCompleted`) alih-alih menggunakan metode rantai lancar yang usang. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Jalankan rantai konversi. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Mendaftarkan callback yang akan dipanggil ketika konversi halaman selesai dengan sukses. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Mendaftarkan callback yang akan dipanggil ketika konversi halaman gagal. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Lihat Juga
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
