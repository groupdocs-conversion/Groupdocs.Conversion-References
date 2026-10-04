---
title: "PageLayoutOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Describe los modos de diseño de página al cargar documentos web."
type: docs
weight: 2720
url: /es/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

Describe los modos de diseño de página al cargar documentos web.

```csharp
public class PageLayoutOptions : FlagsEnumeration
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
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | Combina dos banderas de [`PageLayoutOptions`](../pagelayoutoptions) usando OR a nivel de bits. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | Valor predeterminado |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | Esta bandera indica que el contenido del documento se escalará para ajustarse a la altura de la primera página. Todo el contenido del documento se colocará únicamente en una sola página. |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | Indica que el contenido del documento se escalará para ajustarse a la página donde la diferencia entre el ancho disponible de la página y el contenido superpuesto sea mayor. |

### Ver también

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
