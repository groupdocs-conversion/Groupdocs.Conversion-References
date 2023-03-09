---
title: CompressionFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define formatos de compresión. Incluye los siguientes tipos de archivo Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Más información sobre los formatos de compresiónaquíhttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /es/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Define formatos de compresión. Incluye los siguientes tipos de archivo: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Más información sobre los formatos de compresión[aquí](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | El archivo family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 son archivos comprimidos generados con el método de compresión de código abierto BZIP2, principalmente en sistemas UNIX o Linux. Se utiliza para la compresión de un solo archivo y no para archivar varios archivos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Un archivo con extensión .cab pertenece a un archivo contenedor de Windows que pertenece a la categoría de archivos del sistema. Es un archivo que se guarda en formato de archivo comprimido en las versiones de Microsoft Windows que admiten algoritmos de datos comprimidos, como LZX, Quantum y ZIP. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio es una utilidad general de archivado de archivos y su formato de archivo asociado. Se instala principalmente en sistemas operativos de computadora similares a Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Un archivo GZ es un archivo comprimido que se crea utilizando el algoritmo de compresión estándar gzip (GNU zip). Puede contener múltiples archivos comprimidos, directorios y apéndices de archivos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Un archivo Gzip es un archivo comprimido que se crea utilizando el algoritmo de compresión estándar gzip (GNU zip). Puede contener múltiples archivos comprimidos, directorios y apéndices de archivos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Un archivo con extensión .lz es un archivo comprimido creado con Lzip, que es una herramienta de línea de comandos gratuita para la compresión. Admite concatenación para comprimir archivos de soporte. Los archivos LZ tienen una aplicación de tipo multimedia/lzip y admiten índices de compresión más altos que BZ2. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Un archivo con extensión .lzma es un archivo comprimido creado con el método de compresión LZMA (algoritmo de cadena Lempel-Ziv-Markov). Estos se encuentran/utilizan principalmente en el sistema operativo Unix y son similares a otros algoritmos de compresión como ZIP para minimizar el tamaño del archivo. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Los archivos con extensión .rar son archivos de almacenamiento que se crean para almacenar información en forma comprimida o normal. RAR, que significa Roshal ARchive file format. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z es un formato de archivo para comprimir archivos y carpetas con una alta relación de compresión. Se basa en una arquitectura de código abierto que permite utilizar cualquier algoritmo de compresión y cifrado. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Los archivos con extensión .tar son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Varios archivos se almacenan en un formato sin comprimir con la posibilidad de agregar archivos y carpetas al archivo. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ es un formato de archivo comprimido que utiliza el algoritmo de compresión LZMA2. Fue diseñado como un reemplazo para los populares formatos gzip y bzip2 y ofrece una serie de ventajas sobre estos estándares más antiguos. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | El archivo AZ es una categoría de archivos que pertenecen a los archivos de datos comprimidos de UNIX. Los archivos Unix comprimidos son el tipo de extensión más popular y ampliamente utilizado del archivo Z. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Un archivo con extensión .zip es un archivo que puede contener uno o más archivos o directorios. El archivo puede tener compresión aplicada a los archivos incluidos para reducir el tamaño del archivo ZIP. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/compression/zip/) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
