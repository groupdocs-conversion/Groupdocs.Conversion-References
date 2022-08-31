---
title: CompressionFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines compression formats. Includes the following file types Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Learn more about compression formats herehttps//docs.fileformat.com/compression/.
type: docs
weight: 1220
url: /net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Defines compression formats. Includes the following file types: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). Learn more about compression formats [here](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Serialization constructor |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determines whether two object instances are equal. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 are compressed files generated using the BZIP2 open source compression method, mostly on UNIX or Linux system. It is used for compression of a single file and is not meant for archiving of multiple files. Learn more about this file format [here](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | A GZ file is a compressed archive that is created using the standard gzip (GNU zip) compression algorithm. It may contain multiple compressed files, directories and file stubs. Learn more about this file format [here](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | A Gzip file is a compressed archive that is created using the standard gzip (GNU zip) compression algorithm. It may contain multiple compressed files, directories and file stubs. Learn more about this file format [here](https://docs.fileformat.com/compression/gz/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Files with .rar extension are archive files that are created for storing information in compressed or normal form. RAR, which stands for Roshal ARchive file format. Learn more about this file format [here](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z is an archiving format for compressing files and folders with a high compression ratio. It is based on Open Source architecture which makes it possible to use any compression and encryption algorithms. Learn more about this file format [here](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Files with .tar extension are archives created with Unix-based utility for collecting one or more files. Multiple files are stored in an uncompressed format with the support of adding files as well as folders to the archive. Learn more about this file format [here](https://docs.fileformat.com/compression/tar/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | A file with .zip extension is an archive that can hold one or more files or directories. The archive can have compression applied to the included files in order to reduce the ZIP file size. Learn more about this file format [here](https://docs.fileformat.com/compression/zip/). |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
