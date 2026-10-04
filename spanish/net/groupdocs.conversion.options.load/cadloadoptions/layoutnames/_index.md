---
title: "LayoutNames"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Especifica qué diseños CAD se convertirán"
type: docs
weight: 70
url: /es/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

Especifica qué diseños CAD se convertirán

```csharp
public string[] LayoutNames { get; set; }
```

### Observaciones

No se respeta al convertir a PDF/UA-1. Ese destino representa el dibujo como una única página etiquetada, que no puede contener una hoja por cada diseño seleccionado, por lo que se convierte todo el dibujo y nada aquí se aplica. Todos los demás destinos, incluido PDF, respetan la selección. En esos destinos, los nombres se comparan exactamente con los diseños que lleva el dibujo, de modo que un nombre que difiere solo en mayúsculas/minúsculas es un nombre diferente. Un nombre que no coincide con nada se descarta y solo cuesta al llamador esa hoja; una lista en la que nada coincide hace que la conversión falle con una [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) que nombra los nombres que fallaron y los diseños que el dibujo sí lleva, en lugar de renderizar hojas que el llamador no solicitó. Un dibujo que no lleva ningún diseño queda exento: no hay nada que un nombre pueda coincidir, por lo que ninguno es rechazado.

### Ver también

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
