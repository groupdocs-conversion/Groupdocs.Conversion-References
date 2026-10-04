---
title: "CompressionFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define formatos de compresión. Incluye los siguientes tipos de archivo Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Obtenga más información sobre los formatos de compresión aquíhttps//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /es/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Define formatos de compresión. Incluye los siguientes tipos de archivo: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Obtenga más información sobre los formatos de compresión [aquí](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Define si el formato admite varios archivos/carpetas en un solo archivo comprimido. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Un archivo con extensión .aar es un Apple Archive, el contenedor que Apple incluye con macOS para agrupar archivos y carpetas. Cada entrada se comprime de forma independiente, generalmente con LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Un archivo con extensión .alz es un archivo ALZip, un formato de ESTsoft que se utiliza ampliamente en Corea del Sur. Las entradas pueden estar cifradas individualmente con una contraseña. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | Los archivos BZ2 son archivos comprimidos generados mediante el método de compresión de código abierto BZIP2, principalmente en sistemas UNIX o Linux. Se utilizan para comprimir un solo archivo y no están destinados al archivado de múltiples archivos. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Un archivo con extensión .cab pertenece a un archivo cabinet de Windows que forma parte de la categoría de archivos del sistema. Es un archivo que se guarda en el formato de archivo comprimido en las versiones de Microsoft Windows que admiten algoritmos de datos comprimidos, como LZX, Quantum y ZIP. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio es una utilidad general de archivado de archivos y su formato asociado. Se instala principalmente en sistemas operativos tipo Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Un archivo GZ es un archivo comprimido creado con el algoritmo de compresión estándar gzip (GNU zip). Puede contener varios archivos comprimidos, directorios y archivos de marcador. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Un archivo Gzip es un archivo comprimido creado con el algoritmo de compresión estándar gzip (GNU zip). Puede contener varios archivos comprimidos, directorios y archivos de marcador. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Un archivo con extensión .iso es un archivo de imagen de disco de archivo sin comprimir que representa el contenido de todos los datos en un disco óptico como CD o DVD. Basado en el estándar ISO-9660, el formato de archivo de imagen ISO contiene los datos del disco junto con la información del sistema de archivos que se almacena en él. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Un archivo con extensión .lzh y .lha generalmente se refiere a un formato de archivo de compresión de archivo. Este formato de archivo es el mismo que otros formatos de compresión como ZIP, RAR, etc. El objetivo principal de estos formatos de archivo es reducir el tamaño del archivo para enviarlo fácilmente, así como mantenerlos juntos en forma comprimida. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Un archivo con extensión .lz es un archivo de archivo comprimido creado con Lzip, que es una herramienta de línea de comandos gratuita para compresión. Soporta concatenación para comprimir archivos de soporte. Los archivos LZ tienen tipo de medio application/lzip y admiten una mayor relación de compresión que BZ2. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Un archivo con extensión .lz4 es un archivo de archivo comprimido creado con aplicaciones/utilidades que soportan compresión LZ4. El algoritmo LZ4 se centra en el equilibrio entre velocidad y relación de compresión. Los archivos LZ4 comprimidos pueden crearse usando la utilidad de línea de comandos LZ4 y pueden descomprimirse con la misma. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Un archivo con extensión .lzma es un archivo de archivo comprimido creado usando el método de compresión LZMA (Algoritmo de cadena de Markov de Lempel-Ziv). Estos se encuentran/usan principalmente en sistemas operativos Unix y son similares a otros algoritmos de compresión como ZIP para minimizar el tamaño del archivo. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | Los archivos con extensión .rar son archivos de archivo que se crean para almacenar información en forma comprimida o normal. RAR, que significa formato de archivo Roshal ARchive. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z es un formato de archivado para comprimir archivos y carpetas con una alta relación de compresión. Se basa en una arquitectura de código abierto que permite usar cualquier algoritmo de compresión y cifrado. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | Los archivos con extensión .tar son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Múltiples archivos se almacenan en un formato sin comprimir con soporte para añadir archivos y carpetas al archivo. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Un archivo uuencoded es un archivo o colección de archivos que han sido codificados usando el esquema de codificación Unix-to-Unix (uuencode). Este método de codificación convierte datos binarios en un formato de texto, lo que facilita el envío de archivos a través de canales que solo admiten texto, como el correo electrónico. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Un archivo con extensión .wim es un archivo de Windows Imaging Format, una imagen de disco basada en archivos que Microsoft usa para implementar Windows. Un solo archivo contiene una o más imágenes y almacena cada archivo una sola vez, sin importar cuántas imágenes lo referencien. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Un archivo con extensión .xar es un eXtensible ARchive, un formato construido alrededor de una tabla de contenidos almacenada como XML comprimido. Se utiliza para distribuir paquetes instaladores de macOS y mantiene cada entrada comprimida por separado. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ es un formato de archivo comprimido que utiliza el algoritmo de compresión LZMA2. Fue diseñado como reemplazo de los populares formatos gzip y bzip2, y ofrece una serie de ventajas sobre estos estándares más antiguos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Un archivo Z es una categoría de archivos que pertenecen a los archivos de datos comprimidos UNIX. Los archivos Unix comprimidos son el tipo de extensión más popular y ampliamente usado del archivo Z. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Un archivo con extensión .zip es un archivo comprimido que puede contener uno o más archivos o directorios. Al archivo se le puede aplicar compresión a los archivos incluidos para reducir el tamaño del archivo ZIP. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Un archivo ZST es un archivo comprimido que se genera con el algoritmo de compresión Zstandard (zstd). Es un archivo comprimido que se crea con compresión sin pérdida mediante el algoritmo. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/compression/zst/). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
