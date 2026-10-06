---
title: "propiedad on_font_substituted"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "El evento que se dispara cuando una fuente referenciada por el documento fuente no está disponible y se sustituye (ya sea por una regla FontSubstitute proporcionada por el cliente, por la fuente predeterminada configurada, o por el…"
type: docs
url: /es/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

El evento se dispara cuando una fuente referenciada por el documento de origen no está disponible y se sustituye (ya sea por una regla proporcionada por el cliente [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/), por la fuente predeterminada configurada, o por la alternativa interna del pipeline de conversión).

El evento se desduplicado por `(SourceFileName, OriginalFontName)` dentro de una única llamada `Converter.Convert(...)` — los suscriptores reciben como máximo una notificación por fuente faltante por documento fuente. Se dispara de forma síncrona en el hilo de conversión. No se genera para conversiones de imágenes.

Para documentos de presentación, la sustitución de fuentes solo se detecta en Windows, porque el motor la resuelve mediante coincidencia de fuentes específica de la plataforma que no está disponible en otros sistemas operativos.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Ver también
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
