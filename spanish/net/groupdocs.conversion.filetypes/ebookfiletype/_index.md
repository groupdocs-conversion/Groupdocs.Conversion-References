---
title: "EBookFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos EBook. Incluye los siguientes tipos de archivo Epub./ebookfiletype/epubMobi./ebookfiletype/mobiAzw3./ebookfiletype/azw3"
type: docs
weight: 1110
url: /es/net/groupdocs.conversion.filetypes/ebookfiletype/
---
## EBookFileType class

Define documentos EBook. Incluye los siguientes tipos de archivo: [`Epub`](./epub)[`Mobi`](./mobi)[`Azw3`](./azw3)

```csharp
public sealed class EBookFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EBookFileType](ebookfiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |

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
| static readonly [Azw3](../../groupdocs.conversion.filetypes/ebookfiletype/azw3) | AZW3, también conocido como Kindle Format 8 (KF8), es la versión modificada del formato de archivo digital AZW desarrollado para dispositivos Amazon Kindle. El formato es una mejora respecto a los archivos AZW más antiguos y se utiliza únicamente en dispositivos Kindle Fire, con compatibilidad retroactiva para el formato ancestral, es decir, MOBI y AZW. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.conversion.filetypes/ebookfiletype/epub) | La extensión EPUB es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. El formato se ha vuelto tan común que ahora es compatible con muchos lectores electrónicos y aplicaciones de software. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/ebook/epub). |
| static readonly [Mobi](../../groupdocs.conversion.filetypes/ebookfiletype/mobi) | El formato de archivo MOBI es uno de los formatos de libro electrónico más ampliamente utilizados. El formato es una mejora del antiguo formato OEB (Open Ebook Format) y se utilizó como formato propietario para el lector Mobipocket. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/ebook/mobi). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
