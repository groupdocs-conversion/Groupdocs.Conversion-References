---
title: "LayoutScope"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Obtiene o establece qué espacios de dibujo se convierten. El valor predeterminado es Bothgroupdocs.conversion.options.load/cadlayoutscope/both, que no restringe la conversión. Se ignora cuando se proporciona LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames porque los nombres de diseño explícitos siempre prevalecen. Un valor nulo se trata como Bothgroupdocs.conversion.options.load/cadlayoutscope/both."
type: docs
weight: 80
url: /es/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

Obtiene o establece qué espacios de dibujo se convierten. El valor predeterminado es [`Both`](../../cadlayoutscope/both), que no restringe la conversión. Se ignora cuando se suministra [`LayoutNames`](../layoutnames), porque los nombres de diseño explícitos siempre prevalecen. Un valor `null` se trata como [`Both`](../../cadlayoutscope/both).

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### Observaciones

Un alcance que no selecciona ninguna de las hojas que ofrece un dibujo hace que la conversión falle con una [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) que nombra el alcance y las hojas que existen, en lugar de renderizar los espacios excluidos por el alcance. Un dibujo que no ofrece ninguna hoja no se ve afectado y sigue convirtiéndose como una única unidad. No se respeta al convertir a PDF/UA-1, por la razón indicada en [`LayoutNames`](../layoutnames).

### Ver también

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
