---
title: "OnFontSubstituted"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Se dispara cuando una fuente referenciada por el documento fuente no está disponible y se sustituye ya sea por una regla FontSubstitutegroupdocs.conversion.contracts/fontsubstitute proporcionada por el cliente, por la fuente predeterminada configurada o por el fallback interno de la canalización de conversión."
type: docs
weight: 80
url: /es/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Se dispara cuando una fuente referenciada por el documento fuente no está disponible y se sustituye (ya sea por una regla [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute) proporcionada por el cliente, por la fuente predeterminada configurada, o por el fallback interno de la canalización de conversión).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Observaciones

El evento se deduplica por `(SourceFileName, OriginalFontName)` dentro de una única llamada `Converter.Convert(...)` — los suscriptores reciben como máximo una notificación por fuente faltante por documento fuente. Se dispara de forma síncrona en el hilo de conversión. No se genera para conversiones de imágenes.

Para documentos de presentación, la sustitución de fuentes se detecta solo en Windows, porque el motor lo resuelve mediante coincidencia de fuentes específica de la plataforma que no está disponible en otros sistemas operativos.

### Ver también

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
