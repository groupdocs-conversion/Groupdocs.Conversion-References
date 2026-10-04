---
title: "ConvertTo"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Simpan dokumen yang dikonversi sebagai file"
type: docs
weight: 20
url: /id/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Simpan dokumen yang dikonversi sebagai file

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Dokumen yang dikonversi |

### Nilai Kembali

Opsi atau antarmuka penyiapan penangan untuk melanjutkan pembangunan konversi

### Lihat Juga

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Simpan dokumen yang dikonversi sebagai aliran

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Penyedia aliran dokumen yang dikonversi Konteks penyimpanan |

### Nilai Kembali

Opsi atau antarmuka penyiapan penangan untuk melanjutkan pembangunan konversi

### Lihat Juga

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
