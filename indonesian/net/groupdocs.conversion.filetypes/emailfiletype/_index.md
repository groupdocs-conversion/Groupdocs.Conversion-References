---
title: "EmailFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan format file Email yang digunakan oleh aplikasi email untuk menyimpan berbagai data mereka termasuk pesan email, lampiran, folder, buku alamat, dll. Mencakup tipe file berikut Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Pelajari lebih lanjut tentang format Email di sinihttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /id/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Mendefinisikan format file Email yang digunakan oleh aplikasi email untuk menyimpan berbagai data mereka termasuk pesan email, lampiran, folder, buku alamat, dll. Menyertakan jenis file berikut: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Pelajari lebih lanjut tentang format Email [di sini](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EmailFileType](emailfiletype)() | Konstruktor Serialisasi |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi tipe file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Mengimplementasikan [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. Hampir semua klien email mendukung format file ini karena kepatuhannya terhadap Standar Format Pesan Internet RFC-822. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Format file ICS (iCalendar) digunakan untuk merepresentasikan dan menukar informasi kalender serta penjadwalan seperti acara, tugas, dan data bebas/sibuk. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Format file MBox adalah istilah umum yang merepresentasikan wadah untuk kumpulan pesan surat elektronik. Pesan-pesan disimpan di dalam wadah bersama lampirannya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | File dengan ekstensi .olm adalah file Microsoft Outlook untuk Sistem Operasi Mac. File OLM menyimpan pesan email, jurnal, data kalender, dan jenis data aplikasi lainnya. Ini mirip dengan file PST yang digunakan oleh Outlook pada Sistem Operasi Windows. Namun, file OLM yang dibuat oleh Outlook untuk Mac tidak dapat dibuka di Outlook untuk Windows. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST atau Offline Storage Files mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | File dengan ekstensi .PST mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi populer. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/vcf). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
