---
title: "PossibleConversions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Representa un mapeo de qué pares de conversión son compatibles para un formato de archivo fuente específico"
type: docs
weight: 510
url: /es/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Representa un mapeo de qué pares de conversión son compatibles para un formato de archivo fuente específico

```csharp
public sealed class PossibleConversions : ValueObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Todos los tipos de archivo de destino y la bandera primaria/secundaria IEnumerable de [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Devuelve la conversión de destino para el tipo de archivo de destino especificado (2 indexadores) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Opciones de carga predefinidas que podrían usarse para convertir desde el tipo actual |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Tipos de archivo de destino primarios |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Tipos de archivo de destino secundarios |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Formatos de archivo de origen |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
