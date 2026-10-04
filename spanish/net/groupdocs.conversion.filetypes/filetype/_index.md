---
title: "FileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Clase base de tipo de archivo"
type: docs
weight: 1130
url: /es/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Clase base de tipo de archivo

```csharp
public class FileType : Enumeration
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileType](filetype)() | Constructor de serialización |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Obtiene FileType para la fileExtension proporcionada |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Devuelve FileType para el fileName especificado |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Devuelve FileType para el flujo de documento proporcionado |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Devuelve todos los valores de enumeración. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Conversión implícita a string |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Tipo de archivo desconocido |

### Ver también

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
