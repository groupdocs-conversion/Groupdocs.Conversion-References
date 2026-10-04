---
title: "FlagsEnumeration"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Representa una clase base abstracta para crear enumeraciones que admiten operaciones de banderas a nivel de bits."
type: docs
weight: 220
url: /es/net/groupdocs.conversion.contracts/flagsenumeration/
---
## FlagsEnumeration class

Representa una clase base abstracta para crear enumeraciones que admiten operaciones de banderas a nivel de bits.

```csharp
public abstract class FlagsEnumeration : Enumeration
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | Comprueba si la bandera actual tiene la bandera especificada. |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | Comprueba si la bandera actual tiene el valor especificado. |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | Convierte el objeto actual a una cadena. |
| static [Combine&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/combine)(T, T) | Combina dos enumeraciones de banderas en una. |

### Ver también

* class [Enumeration](../enumeration)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
