---
title: "DetectNumberingWithWhitespaces"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto plano. El valor predeterminado es true."
type: docs
weight: 30
url: /es/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

Permite especificar cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto plano. El valor predeterminado es true.

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### Observaciones

Si esta opción se establece en false, el algoritmo de reconocimiento de listas detecta los párrafos de lista, cuando los números de lista terminan con un punto, corchete derecho o símbolos de viñeta (como "•", "*", "-" o "o").

Si esta opción se establece en true, los espacios en blanco también se usan como delimitadores de números de lista: el algoritmo de reconocimiento de listas para numeración al estilo árabe (1., 1.1.2.) utiliza tanto los espacios en blanco como el punto (".") símbolos.

### Ver también

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
