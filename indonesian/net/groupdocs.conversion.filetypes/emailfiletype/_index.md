---
title: EmailFileType
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Menentukan format file Email yang digunakan oleh aplikasi email untuk menyimpan berbagai data termasuk pesan email lampiran folder buku alamat dll. Termasuk jenis file berikut Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Pelajari lebih lanjut tentang format EmailDi Sinihttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /id/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Menentukan format file Email yang digunakan oleh aplikasi email untuk menyimpan berbagai data termasuk pesan email, lampiran, folder, buku alamat, dll. Termasuk jenis file berikut: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Pelajari lebih lanjut tentang format Email[Di Sini](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [EmailFileType](emailfiletype)() | Konstruktor serialisasi |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi jenis file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Keterangan |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan yang lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Menentukan apakah dua instance objek sama. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi lain yang relevan. Hampir semua klien email mendukung format file ini karena sesuai dengan Standar Format Pesan Internet RFC-822. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Format file MBox adalah istilah umum yang mewakili wadah untuk kumpulan pesan surat elektronik. Pesan disimpan di dalam wadah beserta lampirannya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji temu, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST atau File Penyimpanan Offline menunjukkan data kotak surat pengguna dalam mode offline di mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | File dengan ekstensi .PST mewakili File Penyimpanan Pribadi Outlook (disebut juga Tabel Penyimpanan Pribadi) yang menyimpan berbagai informasi pengguna. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi populer. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/vcf) . |

### Lihat juga

* class [FileType](../filetype)
* ruang nama [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
