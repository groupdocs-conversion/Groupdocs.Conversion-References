---
title: "FontFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos de fuentes Incluye los siguientes tipos Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Obtén más información sobre los formatos de fuentes aquíhttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /es/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Define documentos de fuentes Incluye los siguientes tipos: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Obtén más información sobre los formatos de fuentes [aquí](https://docs.fileformat.com/font/).

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
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | Un archivo con extensión .cff es un Formato de Fuente Compacta y también se conoce como PostScript Type 1, o CIDFont. CFF actúa como un contenedor para almacenar múltiples fuentes juntas en una única unidad conocida como FontSet. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | Un archivo con extensión .eot es una fuente OpenType que se incrusta en un documento. Estas se usan mayormente en archivos web como una página web. Fue creado por Microsoft y es compatible con productos de Microsoft, incluyendo presentaciones PowerPoint .pps. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | Un archivo con extensión .otf se refiere al formato de fuente OpenType. El formato de fuente OTF es más escalable y amplía las características existentes de los formatos TTF para la tipografía digital. Desarrollado por Microsoft y Adobe, OTF combina las características de los formatos de fuentes PostScript y TrueType. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | Un archivo con extensión .ttf representa archivos de fuentes basados en la tecnología de fuentes según las especificaciones TrueType. Fue diseñado e introducido inicialmente por Apple Computer, Inc para Mac OS y luego adoptado por Microsoft para Windows OS. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Las fuentes Type 1 son una tecnología de Adobe obsoleta que se usó ampliamente en software de publicación de escritorio e impresoras que podían usar PostScript. Aunque las fuentes Type 1 no son compatibles con muchas plataformas modernas, navegadores web y sistemas operativos móviles, todavía son compatibles en algunos sistemas operativos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | Un archivo con extensión .woff es un archivo de fuente web basado en el Formato de Fuente Web Abierto (WOFF). Tiene un contenedor comprimido específico del formato basado en fuentes TrueType (.TTF) o OpenType (.OTT). Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | Un archivo con extensión .woff es un archivo de fuente web basado en el Formato de Fuente Web Abierto (WOFF). Tiene un contenedor comprimido específico del formato basado en fuentes TrueType (.TTF) o OpenType (.OTT). Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/font/woff/). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
