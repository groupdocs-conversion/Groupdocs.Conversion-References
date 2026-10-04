---
title: "Muat"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Atur nama file dokumen sumber"
type: docs
weight: 10
url: /id/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Atur nama file dokumen sumber

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Dokumen sumber |

### Lihat Juga

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Atur array dokumen sumber

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String[] | Kumpulan dokumen sumber |

### Lihat Juga

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Atur aliran dokumen sumber

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Penyedia aliran dokumen sumber |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Jika validasi pengaturan konverter gagal, pengecualian ini akan dilemparkan |

### Lihat Juga

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Atur array aliran dokumen sumber

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Penyedia aliran dokumen sumber |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Jika validasi pengaturan konverter gagal, pengecualian ini akan dilemparkan |

### Lihat Juga

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
