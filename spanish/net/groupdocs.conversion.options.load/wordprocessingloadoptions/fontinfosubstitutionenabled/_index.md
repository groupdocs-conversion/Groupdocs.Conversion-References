---
title: "FontInfoSubstitutionEnabled"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Sustituye automáticamente las fuentes faltantes basándose en FontInfo en el documento. Predeterminado false."
type: docs
weight: 130
url: /es/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled/
---
## WordProcessingLoadOptions.FontInfoSubstitutionEnabled property

Sustituye automáticamente fuentes faltantes basándose en FontInfo del documento. Valor predeterminado: falso.

```csharp
public bool FontInfoSubstitutionEnabled { get; set; }
```

### Observaciones

**Note:** The order of substitution is as follows:

1) Sustituir automáticamente fuentes faltantes basándose en el nombre de la fuente (si está habilitado).

2) Sustituir automáticamente fuentes faltantes basándose en FontConfig (si está habilitado).

3) Sustituir fuentes faltantes basándose en FontSubstitutes (si está configurado).

4) Sustituir automáticamente fuentes faltantes basándose en FontInfo (si está habilitado).

5) Sustituir fuentes faltantes basándose en DefaultFont (si está configurado).

### Ver también

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
