---
title: "EmailFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan format file Email yang digunakan oleh aplikasi email untuk menyimpan berbagai data mereka termasuk pesan email, lampiran, folder, buku alamat, dll."
type: docs
weight: 15
url: /id/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Mendefinisikan format file Email yang digunakan oleh aplikasi email untuk menyimpan berbagai data mereka termasuk pesan email, lampiran, folder, buku alamat, dll.
Menyertakan jenis file berikut:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Pelajari lebih lanjut tentang format Email [di sini](../https://wiki.fileformat.com/email).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Msg](#Msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. |
|
|  | [Eml](#Eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. |
|
|  | [Emlx](#Emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. |
|
|  | [Mbox](#Mbox) | Format file MBox adalah istilah umum yang mewakili kontainer untuk kumpulan pesan surat elektronik. |
|
|  | [Pst](#Pst) | File dengan ekstensi .PST mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. |
|
|  | [Ost](#Ost) | OST atau Offline Storage Files mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. |
|
|  | [Olm](#Olm) | File dengan ekstensi .olm adalah file Microsoft Outlook untuk sistem operasi Mac. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Konstruktor serialisasi


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. Hampir semua klien email mendukung format file ini karena kepatuhannya terhadap Standar Format Pesan Internet RFC-822.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi populer.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


Format file MBox adalah istilah umum yang mewakili wadah untuk kumpulan pesan email elektronik. Pesan-pesan disimpan di dalam wadah beserta lampirannya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


File dengan ekstensi .PST mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST atau Offline Storage Files mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


File dengan ekstensi .olm adalah file Microsoft Outlook untuk sistem operasi Mac. File OLM menyimpan pesan email, jurnal, data kalender, dan jenis data aplikasi lainnya. File ini mirip dengan file PST yang digunakan oleh Outlook pada sistem operasi Windows. Namun, file OLM yang dibuat oleh Outlook untuk Mac tidak dapat\\u2019 dibuka di Outlook untuk Windows. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
