---
title: "PdfRecognitionMode"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto."
type: docs
weight: 2160
url: /es/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto.

```csharp
public sealed class PdfRecognitionMode : Enumeration
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
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Modo de reconocimiento completo, el motor realiza agrupación y análisis multinivel para restaurar la intención del autor del documento original y producir un documento lo más editable posible. La desventaja es que el documento de salida podría verse diferente del archivo PDF original. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Este modo es rápido y bueno para preservar al máximo el aspecto original del archivo PDF, pero la editabilidad del documento resultante podría ser limitada. Cada bloque de texto agrupado visualmente en el archivo PDF original se convierte en un cuadro de texto en el documento resultante. Esto logra una semejanza máxima del documento de salida con el archivo PDF original. El documento de salida tendrá buen aspecto, pero consistirá completamente de cuadros de texto y podría dificultar la edición posterior del documento en Microsoft Word. Este es el modo predeterminado. |

### Ver también

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
