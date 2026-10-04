---
title: "FontTransformation"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Describe la configuración de transformación de fuentes, incluidos los atributos de la fuente. Las transformaciones de fuentes se aplican después de la carga del documento y la sustitución de fuentes."
type: docs
weight: 260
url: /es/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Describe la configuración de transformación de fuentes, incluidos los atributos de la fuente. Las transformaciones de fuentes se aplican después de la carga del documento y la sustitución de fuentes.

```csharp
public class FontTransformation : ValueObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Cuando es verdadero, coincide con cualquier tamaño de fuente para el nombre de la fuente original. Cuando es falso, coincide con el tamaño exacto de fuente especificado en OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Cuando es verdadero, coincide con cualquier estilo de fuente (negrita, cursiva, subrayado) para la fuente original. Cuando es falso, coincide con el estilo exacto de fuente especificado en OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | La especificación de la fuente original para coincidir y reemplazar. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | La especificación de la fuente de reemplazo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Crea una transformación de fuente con coincidencia exacta de fuente (el tamaño y el estilo deben coincidir). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Crea una transformación de fuente solo por nombre, coincidiendo con cualquier tamaño y estilo. La fuente de reemplazo preservará el tamaño y el estilo de la fuente original. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Crea una transformación de fuente con opciones de coincidencia flexibles. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
