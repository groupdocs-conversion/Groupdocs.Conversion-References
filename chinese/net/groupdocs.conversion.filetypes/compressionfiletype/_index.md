---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义压缩格式。包括以下文件类型 Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. 了解更多压缩格式，请访问这里https//docs.fileformat.com/compression/。"
type: docs
weight: 1080
url: /zh/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

定义压缩格式。包括以下文件类型：[`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). 了解更多压缩格式，请点击[此处](https://docs.fileformat.com/compression/)。

```csharp
public sealed class CompressionFileType : FileType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | 定义该格式是否支持在单个归档中包含多个文件/文件夹。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 实现 [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | .aar 扩展名的文件是 Apple Archive，这是 Apple 在 macOS 中提供的用于组织文件和文件夹的容器。每个条目都会单独压缩，通常使用 LZFSE。 |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | .alz 扩展名的文件是 ALZip 存档，是 ESTsoft 提供的格式，在韩国被广泛使用。条目可以单独使用密码加密。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 是使用 BZIP2 开源压缩方法生成的压缩文件，主要在 UNIX 或 Linux 系统上使用。它用于单个文件的压缩，而不用于多个文件的归档。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab 扩展名的文件属于 Windows Cabinet 文件，属于系统文件类别。它是以归档文件格式保存的文件，适用于支持压缩数据算法（如 LZX、Quantum 和 ZIP）的 Microsoft Windows 版本。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio 是一种通用文件归档实用程序及其关联的文件格式。它主要安装在类 Unix 的计算机操作系统上。 |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ 文件是一种使用标准 gzip（GNU zip）压缩算法创建的压缩归档。它可能包含多个压缩文件、目录和文件占位符。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip 文件是一种使用标准 gzip（GNU zip）压缩算法创建的压缩归档。它可能包含多个压缩文件、目录和文件占位符。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | .iso 扩展名的文件是未压缩的光盘映像归档文件，表示光盘（如 CD 或 DVD）上整个数据的内容。基于 ISO-9660 标准，ISO 镜像文件格式包含光盘数据以及其中存储的文件系统信息。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | .lzh 和 .lha 扩展名通常与归档压缩文件格式相关。该格式与 ZIP、RAR 等其他文件压缩格式相同。这些文件格式的主要目的是减小文件大小，以便轻松发送并以压缩形式一起保存。 |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz 扩展名的文件是使用 Lzip 创建的压缩归档文件，Lzip 是一个免费的命令行压缩工具。它支持串联压缩支持文件。LZ 文件的媒体类型为 application/lzip，且比 BZ2 提供更高的压缩比率。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | .lz4 扩展名的文件是使用支持 LZ4 压缩的应用程序/实用工具创建的压缩归档文件。LZ4 算法在速度和压缩比之间进行权衡。可以使用 LZ4 命令行工具创建压缩的 LZ4 归档，并可使用相同工具进行解压。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma 扩展名的文件是使用 LZMA（Lempel‑Ziv‑Markov chain Algorithm）压缩方法创建的压缩归档文件。这些文件主要在 Unix 操作系统上使用，类似于 ZIP 等其他压缩算法，用于减小文件大小。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar 扩展名的文件是用于以压缩或普通形式存储信息的归档文件。RAR 代表 Roshal ARchive（罗沙尔归档）文件格式。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z 是一种用于高压缩比压缩文件和文件夹的归档格式。它基于开源架构，能够使用任何压缩和加密算法。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar 扩展名的文件是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。多个文件以未压缩格式存储，并支持将文件和文件夹添加到归档中。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | uuencoded 归档是一种使用 Unix-to-Unix 编码方案（uuencode）对文件或文件集合进行编码的方式。此编码方法将二进制数据转换为文本格式，便于在仅支持文本的渠道（如电子邮件）中发送文件。 |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | .wim 扩展名的文件是 Windows Imaging Format（WIM）归档，是 Microsoft 用于部署 Windows 的基于文件的磁盘映像。单个归档可包含一个或多个映像，并且每个文件只存储一次，无论有多少映像引用它。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | .xar 扩展名的文件是 eXtensible ARchive（可扩展归档），一种围绕以压缩 XML 存储的目录表构建的格式。它用于分发 macOS 安装包，并将每个条目单独压缩。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ 是一种使用 LZMA2 压缩算法的压缩文件格式。它被设计为流行的 gzip 和 bzip2 格式的替代品，并在多个方面优于这些旧标准。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Z 文件是一类属于 UNIX 压缩数据文件的文件。压缩的 Unix 文件是 Z 文件最流行且使用最广泛的扩展类型。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip 扩展名的文件是一种可以容纳一个或多个文件或目录的归档。该归档可以对包含的文件进行压缩，以减小 ZIP 文件大小。了解更多关于此文件格式的信息，请点击[here](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | ZST 文件是一种使用 Zstandard (zstd) 压缩算法生成的压缩文件。它是通过该算法进行无损压缩创建的压缩文件。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/compression/zst/)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
