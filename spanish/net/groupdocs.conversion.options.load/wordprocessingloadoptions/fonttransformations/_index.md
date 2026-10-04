---
title: "FontTransformations"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Transforma las fuentes existentes después de que la carga del documento y la sustitución de fuentes se completen. Las transformaciones de fuentes pueden modificar cualquier fuente en el documento, incluidas las fuentes que se cargaron correctamente."
type: docs
weight: 160
url: /es/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations/
---
## WordProcessingLoadOptions.FontTransformations property

Transforma las fuentes existentes después de que la carga del documento y la sustitución de fuentes se completen. Las transformaciones de fuentes pueden modificar cualquier fuente en el documento, incluidas las fuentes que se cargaron correctamente.

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### Observaciones

**Note:** Font transformations are applied after all font substitution steps are complete.

Las transformaciones se procesan en el orden en que aparecen en la lista.

Casos de uso: cambios de estilo, requisitos de marca, mejoras de accesibilidad.

### Ver también

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
