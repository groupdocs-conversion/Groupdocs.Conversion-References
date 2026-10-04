---
title: "NoConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Clase de opción de conversión especial que indica al convertidor que copie el documento fuente sin ningún procesamiento"
type: docs
weight: 2020
url: /es/net/groupdocs.conversion.options.convert/noconvertoptions/
---
## NoConvertOptions class

Clase de opción de conversión especial, que instruye al convertidor a copiar el documento fuente sin ningún procesamiento

```csharp
public sealed class NoConvertOptions : ConvertOptions<FileType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [NoConvertOptions](noconvertoptions)() | Inicializa una nueva instancia de la clase [`NoConvertOptions`](../noconvertoptions) con el formato predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
