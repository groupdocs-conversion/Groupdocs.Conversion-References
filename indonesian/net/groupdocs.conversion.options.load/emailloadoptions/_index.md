---
title: EmailLoadOptions
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Opsi untuk memuat dokumen Email.
type: docs
weight: 2110
url: /id/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Opsi untuk memuat dokumen Email.

```csharp
public sealed class EmailLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Menginisialisasi instance baru[`EmailLoadOptions`](../emailloadoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Opsi untuk mengontrol apakah dokumen yang dimiliki dalam wadah dokumen harus dikonversi |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Opsi untuk mengontrol apakah wadah dokumen itu sendiri harus dikonversi Jika properti ini true, wadah dokumen akan menjadi dokumen pertama yang dikonversi |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Opsi untuk mengontrol berapa banyak level secara mendalam untuk melakukan konversi |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Opsi untuk menampilkan atau menyembunyikan alamat email "Bcc". Bawaan: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Opsi untuk menampilkan atau menyembunyikan alamat email "Cc". Bawaan: false. |
| [DisplayEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddress) { get; set; } | Opsi untuk menampilkan atau menyembunyikan alamat email. Bawaan: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Opsi untuk menampilkan atau menyembunyikan alamat email "dari". Bawaan: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Opsi untuk menampilkan atau menyembunyikan header email. Bawaan: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Opsi untuk menampilkan atau menyembunyikan alamat email "ke". Bawaan: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Pemetaan antar pesan email[`EmailField`](../emailfield) dan representasi teks bidang |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Jenis file dokumen masukan. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Jenis file dokumen masukan. |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Menentukan apakah perlu menyimpan string header tanggal asli dalam pesan email saat menyimpan atau tidak (Nilai default adalah true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Batas waktu untuk memuat sumber daya eksternal |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Mendapatkan atau menyetel offset Waktu Universal Terkoordinasi (UTC) untuk tanggal pesan. Properti ini menentukan perbedaan zona waktu, antara waktu lokal dan UTC. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Mengkloning instance saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* ruang nama [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
