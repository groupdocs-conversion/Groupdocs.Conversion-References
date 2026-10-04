---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Pengecualian GroupDocs yang dilempar ketika konversi tidak dapat dijalankan karena sebuah assembly yang menjadi dependensinya tidak ada dalam output aplikasi. Dokumen bukan penyebabnya."
type: docs
weight: 1030
url: /id/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

Pengecualian GroupDocs dilempar ketika konversi tidak dapat dijalankan karena sebuah assembly yang dibutuhkannya tidak ada dalam output aplikasi. Dokumen bukan penyebabnya.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Konstruktor default |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Membuat instance pengecualian dengan pesan |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Membuat instance pengecualian dengan pesan dan meneruskan pengecualian internal |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Membuat instance pengecualian yang menyebutkan assembly yang tidak dapat dimuat |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | Nama sederhana dari assembly yang tidak dapat dimuat, atau null ketika tidak dapat ditentukan. |

### Lihat Juga

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
