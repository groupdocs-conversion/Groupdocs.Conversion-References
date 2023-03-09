---
title: FontFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define documentos de fuente Incluye los siguientes tipos Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Obtenga más información sobre los formatos de fuenteaquíhttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /es/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Define documentos de fuente Incluye los siguientes tipos: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Obtenga más información sobre los formatos de fuente[aquí](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontFileType](fontfiletype)() | Constructor de serialización |

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Un archivo con la extensión .cff es un formato de fuente compacto y también se conoce como PostScript Tipo 1 o CIDFont. CFF actúa como un contenedor para almacenar varias fuentes juntas en una sola unidad conocida como FontSet. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Un archivo con extensión .eot es una fuente OpenType que está incrustada en un documento. Estos se utilizan principalmente en archivos web, como una página web. Fue creado por Microsoft y es compatible con los productos de Microsoft, incluido el archivo .pps de presentación de PowerPoint. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Un archivo con extensión .otf se refiere al formato de fuente OpenType. El formato de fuente OTF es más escalable y amplía las características existentes de los formatos TTF para tipografía digital. Desarrollado por Microsoft y Adobe, OTF combina las características de los formatos de fuente PostScript y TrueType. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Un archivo con la extensión .ttf representa archivos de fuentes basados en la tecnología de fuentes de especificaciones TrueType. Inicialmente fue diseñado y lanzado por Apple Computer, Inc para Mac OS y luego fue adoptado por Microsoft para Windows OS. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Las fuentes Type 1 son una tecnología obsoleta de Adobe que se usaba ampliamente en el software de publicación de escritorio y en las impresoras que podían usar PostScript. Aunque las fuentes Tipo 1 no son compatibles con muchas plataformas modernas, navegadores web y sistemas operativos móviles, aún son compatibles con algunos de los sistemas operativos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Un archivo con la extensión .woff es un archivo de fuente web basado en el formato de fuente abierta web (WOFF). Tiene un contenedor comprimido de formato específico basado en tipos de fuente TrueType (.TTF) u OpenType (.OTT). Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Un archivo con la extensión .woff es un archivo de fuente web basado en el formato de fuente abierta web (WOFF). Tiene un contenedor comprimido de formato específico basado en tipos de fuente TrueType (.TTF) u OpenType (.OTT). Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/font/woff/) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
