---
title: CompressionFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines compression formats. Includes the following file types Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Learn more about compression formats herehttps//docs.fileformat.com/compression/.
type: docs
weight: 990
url: /net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Defines compression formats. Includes the following file types: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). Learn more about compression formats [here](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Defines if the format supports multiple files/folders in a single archive. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implements [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 are compressed files generated using the BZIP2 open source compression method, mostly on UNIX or Linux system. It is used for compression of a single file and is not meant for archiving of multiple files. Learn more about this file format [here](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | A file with a .cab extension belongs to a windows cabinet file that belongs to the category of system files. It is a file that is saved in the archive file format in the versions of Microsoft Windows that support compressed data algorithms, such as the LZX, Quantum, and ZIP. Learn more about this file format [here](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio is a general file archiver utility and its associated file format. It is primarily installed on Unix-like computer operating systems. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | A GZ file is a compressed archive that is created using the standard gzip (GNU zip) compression algorithm. It may contain multiple compressed files, directories and file stubs. Learn more about this file format [here](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | A Gzip file is a compressed archive that is created using the standard gzip (GNU zip) compression algorithm. It may contain multiple compressed files, directories and file stubs. Learn more about this file format [here](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | A file with .iso extension is an uncompressed archive disk image file that represents the contents of entire data on an optical disc such as CD or DVD. Based on the ISO-9660 standard, the ISO image file format contains the disc data along with the filesystem information that is stored in it. Learn more about this file format [here](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | A file with .lzh and .lha extension usually relates to archive compression file format. This file format is the same as other file compression formats like ZIP, RAR, etc. The main purpose of these file formats is to reduce the size of the format for easily sending as well as to keep them together in compressed form. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | A file with .lz extension is a compressed archive file created with Lzip, which is a free command-line tool for compression. It supports concatenation to compress support files. LZ files have media type application/lzip and support higher compression rations than BZ2. Learn more about this file format [here](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | A file with .lz4 extension is a compressed archive file created with applications/utilities that support LZ4 compression. The LZ4 algorithm focuses on trade-off between speed and compression ratio. Compressed LZ4 archives can be created using the LZ4 command-line utility and can be decompressed using the same. Learn more about this file format [here](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | A file with .lzma extension is a compressed archive file created using the LZMA (Lempel-Ziv-Markov chain Algorithm) compression method. These are mainly found/used on Unix operating system and are similar to other compression algorithms such as ZIP for minimising file size. Learn more about this file format [here](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Files with .rar extension are archive files that are created for storing information in compressed or normal form. RAR, which stands for Roshal ARchive file format. Learn more about this file format [here](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z is an archiving format for compressing files and folders with a high compression ratio. It is based on Open Source architecture which makes it possible to use any compression and encryption algorithms. Learn more about this file format [here](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Files with .tar extension are archives created with Unix-based utility for collecting one or more files. Multiple files are stored in an uncompressed format with the support of adding files as well as folders to the archive. Learn more about this file format [here](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | A uuencoded archive is a file or collection of files that have been encoded using the Unix-to-Unix encoding scheme (uuencode). This encoding method converts binary data into a text format, which makes it easier to send files over channels that only support text, such as email. |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ is a compressed file format that utilizes the LZMA2 compression algorithm. It was designed as a replacement for the popular gzip and bzip2 formats, and offers a number of advantages over these older standards. Learn more about this file format [here](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | A Z file is a category of files belonging to the UNIX Compressed data files. Compressed Unix files are the most popular and widely used extension type of the Z file. Learn more about this file format [here](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | A file with .zip extension is an archive that can hold one or more files or directories. The archive can have compression applied to the included files in order to reduce the ZIP file size. Learn more about this file format [here](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | A ZST file is a compressed file that is generated with the Zstandard (zstd) compression algorithm. It is a compressed file that is created with lossless compression by the algorithm. Learn more about this file format [here](https://docs.fileformat.com/compression/zst/). |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
