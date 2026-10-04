---
title: "CadLayoutScope"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Representa qué espacios de dibujo selecciona una conversión CAD: el espacio modelo, los diseños de espacio papel o ambos."
type: docs
weight: 2420
url: /es/net/groupdocs.conversion.options.load/cadlayoutscope/
---
## CadLayoutScope class

Representa qué espacios de dibujo selecciona una conversión CAD: el espacio modelo, los diseños del espacio de papel o ambos.

```csharp
public class CadLayoutScope : Enumeration
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Devuelve una cadena que representa el objeto actual. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Both](../../groupdocs.conversion.options.load/cadlayoutscope/both) | Selecciona el espacio modelo y cada diseño de espacio papel. Este es el valor predeterminado y no restringe la conversión: el dibujo se renderiza exactamente como está cuando no se expresa ningún alcance. |
| static readonly [Layouts](../../groupdocs.conversion.options.load/cadlayoutscope/layouts) | Selecciona solo los diseños de espacio papel. El espacio modelo se excluye. |
| static readonly [Model](../../groupdocs.conversion.options.load/cadlayoutscope/model) | Selecciona solo el espacio modelo. |

### Ver también

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
