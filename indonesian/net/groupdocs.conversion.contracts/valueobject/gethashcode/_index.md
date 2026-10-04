---
title: "GetHashCode"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Berfungsi sebagai fungsi hash default."
type: docs
weight: 20
url: /id/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

Berfungsi sebagai fungsi hash default.

```csharp
public override int GetHashCode()
```

### Nilai Kembali

Kode hash untuk objek saat ini.

### Catatan

Komponen array, list, dan dictionary di-hash berdasarkan isinya, sesuai dengan cara kesetaraan membandingkannya, sehingga dua objek yang dianggap sama juga menghasilkan hash yang sama dan dapat digunakan sebagai kunci dictionary atau anggota set. Ini TIDAK berlaku untuk komponen yang merupakan IEnumerable lain: komponen semacam itu di-hash berdasarkan referensi, dan yang diekspos sebagai iterator malas menghasilkan nilai yang berbeda pada setiap akses, sehingga objek yang membawanya tidak dapat digunakan sebagai kunci sama sekali. Koleksi bersarang juga dibandingkan dan di-hash berdasarkan referensi bukan secara rekursif. Konsekuensi lainnya adalah memodifikasi koleksi yang diungkapkan oleh objek nilai — menambahkan ke daftar halaman, atau menulis ke array nama‑layout — mengubah hash objek tersebut, sehingga instance yang sudah disimpan dalam hash container menjadi tidak dapat dijangkau. Perlakukan objek nilai sebagai beku setelah digunakan sebagai kunci.

### Lihat Juga

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
