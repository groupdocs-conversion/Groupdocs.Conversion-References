---
title: CompressionFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Defines compression formats."
type: docs
url: /python-net/groupdocs.conversion.filetypes/compressionfiletype/
is_root: false
weight: 30
---


## CompressionFileType class

Defines compression formats.

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

Learn more about compression formats https://docs.fileformat.com/compression/.

The CompressionFileType type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Compares current object to other. (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implements the equality comparison defined by [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) |  (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Gets the FileType for the provided file extension. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Returns FileType for specified file_name. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Returns FileType for provided document stream. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) |  (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Provides the default hash function. (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | String representation of file type. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Properties
| Property | Description |
| :- | :- |
| [is_multi_file_archive](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/is_multi_file_archive/) | The format supports multiple files/folders in a single archive. |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | The file type description. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | The file extension. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | The file family. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | The file format. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Fields
| Field | Description |
| :- | :- |
| [ZIP](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zip/) | A file with .zip extension is an archive that can hold one or more files or directories. The archive can have compression applied to the included files in order to reduce the ZIP file size. Learn more about this file format here. |
| [RAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/rar/) | Files with .rar extension are archive files that are created for storing information in compressed or normal form. RAR, which stands for Roshal ARchive file format. Learn more about this file format here. |
| [SEVEN_Z](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/seven_z/) | 7z is an archiving format for compressing files and folders with a high compression ratio. It is based on Open Source architecture which makes it possible to use any compression and encryption algorithms. Learn more about this file format here. |
| [TAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/tar/) | Files with .tar extension are archives created with Unix-based utility for collecting one or more files. Multiple files are stored in an uncompressed format with the support of adding files as well as folders to the archive. Learn more about this file format here. |
| [GZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gz/) | A GZ file is a compressed archive that is created using the standard gzip (GNU zip) compression algorithm. It may contain multiple compressed files, directories and file stubs. Learn more about this file format here. |
| [GZIP](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gzip/) | A Gzip file is a compressed archive that is created using the standard gzip (GNU zip) compression algorithm. It may contain multiple compressed files, directories and file stubs. Learn more about this file format here. |
| [BZ2](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/bz2/) | BZ2 are compressed files generated using the BZIP2 open source compression method, mostly on UNIX or Linux system. It is used for compression of a single file and is not meant for archiving of multiple files. Learn more about this file format here. |
| [LZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz/) | A file with .lz extension is a compressed archive file created with Lzip, which is a free command-line tool for compression. It supports concatenation to compress support files. LZ files have media type application/lzip and support higher compression rations than BZ2. Learn more about this file format here. |
| [Z](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/z/) | A Z file is a category of files belonging to the UNIX Compressed data files. Compressed Unix files are the most popular and widely used extension type of the Z file. Learn more about this file format here. |
| [XZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xz/) | XZ is a compressed file format that utilizes the LZMA2 compression algorithm. It was designed as a replacement for the popular gzip and bzip2 formats, and offers a number of advantages over these older standards. Learn more about this file format here. |
| [CPIO](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cpio/) | Cpio is a general file archiver utility and its associated file format. It is primarily installed on Unix-like computer operating systems. |
| [CAB](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cab/) | A file with a .cab extension belongs to a windows cabinet file that belongs to the category of system files. It is a file that is saved in the archive file format in the versions of Microsoft Windows that support compressed data algorithms, such as the LZX, Quantum, and ZIP. Learn more about this file format here. |
| [LZMA](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lzma/) | A file with .lzma extension is a compressed archive file created using the LZMA (Lempel-Ziv-Markov chain Algorithm) compression method. These are mainly found/used on Unix operating system and are similar to other compression algorithms such as ZIP for minimising file size. Learn more about this file format here. |
| [ZST](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zst/) | A ZST file is a compressed file that is generated with the Zstandard (zstd) compression algorithm. It is a compressed file that is created with lossless compression by the algorithm. Learn more about this file format here. |
| [ISO](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/iso/) | A file with .iso extension is an uncompressed archive disk image file that represents the contents of entire data on an optical disc such as CD or DVD. Based on the ISO-9660 standard, the ISO image file format contains the disc data along with the filesystem information that is stored in it. Learn more about this file format here. |
| [UUE](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/uue/) | A uuencoded archive is a file or collection of files that have been encoded using the Unix-to-Unix encoding scheme (uuencode). This encoding method converts binary data into a text format, which makes it easier to send files over channels that only support text, such as email. |
| [LHA](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lha/) | A file with .lzh and .lha extension usually relates to archive compression file format. This file format is the same as other file compression formats like ZIP, RAR, etc. The main purpose of these file formats is to reduce the size of the format for easily sending as well as to keep them together in compressed form. |
| [LZ4](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz4/) | A file with .lz4 extension is a compressed archive file created with applications/utilities that support LZ4 compression. The LZ4 algorithm focuses on trade-off between speed and compression ratio. Compressed LZ4 archives can be created using the LZ4 command-line utility and can be decompressed using the same. Learn more about this file format here. |
| [XAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xar/) | A file with .xar extension is an eXtensible ARchive, a format built around a table of contents stored as compressed XML. It is used to distribute macOS installer packages and keeps each entry compressed on its own. Learn more about this file format here. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unknown file type (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### See Also
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
