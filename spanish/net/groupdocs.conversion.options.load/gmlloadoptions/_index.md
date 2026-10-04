---
title: "GmlLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos Gml."
type: docs
weight: 2550
url: /es/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Opciones para cargar documentos Gml.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Inicializa una nueva instancia de la clase [`GmlLoadOptions`](../gmlloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Establece la altura de página deseada para la conversión del documento GIS. El valor predeterminado es 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Determina si Conversion puede cargar esquemas XML desde Internet. Si se establece en false, los esquemas con URIs absolutas que no comiencen con ‘file://’ no se cargarán. El valor predeterminado es false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Determina si Conversion puede analizar atributos en un archivo Gml en el que falta un esquema XML o no se puede cargar. Si se establece en true, el lector de Conversion no requiere la presencia de un esquema XML. El valor predeterminado es false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Lista de pares de URI separados por espacios. La primera URI de cada par es la URI del espacio de nombres, la segunda URI es una ruta al esquema XML del espacio de nombres. Si se establece en null, Conversion intentará leer schemaLocation del elemento raíz del documento. El valor predeterminado es null. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Establece el ancho de página deseado para la conversión del documento GIS. El valor predeterminado es 1000. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
