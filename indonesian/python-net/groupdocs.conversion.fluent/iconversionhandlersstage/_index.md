---
title: "Kelas IConversionHandlersStage"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mewakili tahap penangan konversi yang diratakan."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Mewakili tahap penangan konversi yang diratakan.

Mengizinkan pengaturan `OnConversionCompleted` atau `OnConversionFailed` dalam urutan apa pun dan berulang kali, sebelum melanjutkan ke `Convert` / `Compress`. Event harus didaftarkan pada tahap awal melalui [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) alih-alih pada tahap ini.

Tipe IConversionHandlersStage menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Mengompres hasil konversi. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Jalankan rantai konversi. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Mendaftarkan callback yang akan dipanggil ketika konversi dokumen selesai dengan sukses, menggantikan handler yang sebelumnya diatur pada pemanggilan ulang. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Mendaftarkan callback yang akan dipanggil ketika konversi dokumen gagal. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Lihat Juga
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
