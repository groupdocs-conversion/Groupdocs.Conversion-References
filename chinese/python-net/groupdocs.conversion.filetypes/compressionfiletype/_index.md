---
title: "CompressionFileType 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "定义压缩格式。"
type: docs
url: /zh/python-net/groupdocs.conversion.filetypes/compressionfiletype/
is_root: false
weight: 30
---


## CompressionFileType class

定义压缩格式。

- [`CompressionFileType.zip`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zip/)
- [`CompressionFileType.rar`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/rar/)
- [`CompressionFileType.seven_z`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/seven_z/)
- [`CompressionFileType.tar`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/tar/)
- [`CompressionFileType.gz`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gz/)
- [`CompressionFileType.gzip`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gzip/)
- [`CompressionFileType.bz2`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/bz2/)
- [`CompressionFileType.lz`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz/)
- [`CompressionFileType.z`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/z/)
- [`CompressionFileType.xz`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xz/)
- [`CompressionFileType.cpio`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cpio/)
- [`CompressionFileType.cab`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cab/)
- [`CompressionFileType.lzma`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lzma/)
- [`CompressionFileType.zst`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zst/)
- [`CompressionFileType.uue`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/uue/)
- [`CompressionFileType.lha`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lha/)
- [`CompressionFileType.lz4`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz4/)
- [`CompressionFileType.xar`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xar/)

了解更多关于压缩格式的信息 https://docs.fileformat.com/compression/。

CompressionFileType 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 比较当前对象与其他对象。（继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | 实现由 [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) 定义的相等比较。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | （继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 获取提供的文件扩展名对应的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 返回指定 file_name 的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 返回提供的文档流的 FileType。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | （继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | （继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | 提供默认的哈希函数。（继承自 [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)） |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | 文件类型的字符串表示。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [is_multi_file_archive](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/is_multi_file_archive/) | 该格式支持在单个归档中包含多个文件/文件夹。 |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | 文件类型描述。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | 文件扩展名。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | 文件族。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | 文件格式。（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 字段
| 字段 | 描述 |
| :- | :- |
| [ZIP](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zip/) | 扩展名为 .zip 的文件是一个归档，可以容纳一个或多个文件或目录。该归档可以对包含的文件进行压缩，以减小 ZIP 文件大小。了解更多关于此文件格式的信息，请点击此处。 |
| [RAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/rar/) | 扩展名为 .rar 的文件是用于以压缩或普通形式存储信息的归档文件。RAR 代表 Roshal ARchive 文件格式。了解更多关于此文件格式的信息，请点击此处。 |
| [SEVEN_Z](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/seven_z/) | 7z 是一种用于高压缩比压缩文件和文件夹的归档格式。它基于开源架构，使得可以使用任何压缩和加密算法。了解更多关于此文件格式的信息，请点击此处。 |
| [TAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/tar/) | 扩展名为 .tar 的文件是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。多个文件以未压缩格式存储，并支持向归档中添加文件以及文件夹。了解更多关于此文件格式的信息，请点击此处。 |
| [GZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gz/) | GZ 文件是一种使用标准 gzip（GNU zip）压缩算法创建的压缩归档。它可能包含多个压缩文件、目录和文件占位符。了解更多关于此文件格式的信息，请点击此处。 |
| [GZIP](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gzip/) | Gzip 文件是一种使用标准 gzip（GNU zip）压缩算法创建的压缩归档。它可能包含多个压缩文件、目录和文件占位符。了解更多关于此文件格式的信息，请点击此处。 |
| [BZ2](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/bz2/) | BZ2 是使用 BZIP2 开源压缩方法生成的压缩文件，主要在 UNIX 或 Linux 系统上使用。它用于单个文件的压缩，不适用于多个文件的归档。了解更多关于此文件格式的信息，请点击此处。 |
| [LZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz/) | 扩展名为 .lz 的文件是使用 Lzip 创建的压缩归档文件，Lzip 是一个免费的命令行压缩工具。它支持串联压缩支持文件。LZ 文件的媒体类型为 application/lzip，并且比 BZ2 支持更高的压缩比。了解更多关于此文件格式的信息，请点击此处。 |
| [Z](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/z/) | Z 文件是一类属于 UNIX 压缩数据文件的文件。压缩的 Unix 文件是 Z 文件最流行且使用最广的扩展类型。了解更多关于此文件格式的信息，请点击此处。 |
| [XZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xz/) | XZ 是一种利用 LZMA2 压缩算法的压缩文件格式。它被设计为流行的 gzip 和 bzip2 格式的替代品，并在这些旧标准上提供了多项优势。了解更多关于此文件格式的信息，请点击此处。 |
| [CPIO](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cpio/) | Cpio 是一种通用文件归档实用程序及其关联的文件格式。它主要安装在类 Unix 的计算机操作系统上。 |
| [CAB](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cab/) | 扩展名为 .cab 的文件属于 Windows cabinet 文件，属于系统文件类别。它是以归档文件格式保存的文件，适用于支持压缩数据算法（如 LZX、Quantum 和 ZIP）的 Microsoft Windows 版本。了解更多关于此文件格式的信息，请点击此处。 |
| [LZMA](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lzma/) | 扩展名为 .lzma 的文件是使用 LZMA（Lempel-Ziv-Markov 链算法）压缩方法创建的压缩归档文件。这些文件主要在 Unix 操作系统上发现/使用，并且类似于其他压缩算法，如 ZIP，用于最小化文件大小。了解更多关于此文件格式的信息，请点击此处。 |
| [ZST](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zst/) | ZST 文件是一种使用 Zstandard（zstd）压缩算法生成的压缩文件。它是通过该算法进行无损压缩创建的压缩文件。了解更多关于此文件格式的信息，请点击此处。 |
| [ISO](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/iso/) | 扩展名为 .iso 的文件是一个未压缩的归档磁盘映像文件，表示光盘（如 CD 或 DVD）上整个数据的内容。基于 ISO-9660 标准，ISO 镜像文件格式包含光盘数据以及其中存储的文件系统信息。了解更多关于此文件格式的信息，请点击此处。 |
| [UUE](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/uue/) | uuencode 归档是一种使用 Unix-to-Unix 编码方案（uuencode）对文件或文件集合进行编码的文件。此编码方法将二进制数据转换为文本格式，使其更容易通过仅支持文本的渠道（如电子邮件）发送文件。 |
| [LHA](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lha/) | 带有 .lzh 和 .lha 扩展名的文件通常属于归档压缩文件格式。该文件格式与其他文件压缩格式如 ZIP、RAR 等相同。这些文件格式的主要目的是减小文件大小，以便于发送，并将它们以压缩形式保存在一起。 |
| [LZ4](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz4/) | 带有 .lz4 扩展名的文件是使用支持 LZ4 压缩的应用程序/工具创建的压缩归档文件。LZ4 算法侧重于速度与压缩率之间的平衡。可以使用 LZ4 命令行工具创建压缩的 LZ4 归档，并可使用同一工具进行解压。了解更多关于此文件格式的信息，请点击此处。 |
| [XAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xar/) | 带有 .xar 扩展名的文件是 eXtensible ARchive（可扩展归档），一种围绕以压缩 XML 形式存储的目录表构建的格式。它用于分发 macOS 安装包，并将每个条目单独压缩。了解更多关于此文件格式的信息，请点击此处。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 未知文件类型（继承自 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)） |

### 另见
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
