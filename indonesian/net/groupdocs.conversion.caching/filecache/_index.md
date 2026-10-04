---
title: "FileCache"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Perilaku caching file. Artinya cache disimpan di sistem file"
type: docs
weight: 10
url: /id/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

Perilaku caching file. Artinya cache disimpan di sistem file

```csharp
public sealed class FileCache : ICache
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FileCache](filecache)(string) | Membuat instance baru dari kelas FileCache |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | Mengembalikan semua kunci yang cocok dengan filter. |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | Menyisipkan entri cache ke dalam cache. |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | Mendapatkan entri yang terkait dengan kunci ini jika ada. |

### Catatan

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### Lihat Juga

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
