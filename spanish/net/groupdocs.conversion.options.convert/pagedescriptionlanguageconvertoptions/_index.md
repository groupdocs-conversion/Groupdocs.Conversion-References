---
title: "PageDescriptionLanguageConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para la conversión al tipo de archivo de lenguaje de descripciones de página."
type: docs
weight: 2030
url: /es/net/groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/
---
## PageDescriptionLanguageConvertOptions class

Opciones para la conversión al tipo de archivo de lenguaje de descripciones de página.

```csharp
public class PageDescriptionLanguageConvertOptions : 
    CommonConvertOptions<PageDescriptionLanguageFileType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PageDescriptionLanguageConvertOptions](pagedescriptionlanguageconvertoptions)() | Inicializa una nueva instancia de [`PageDescriptionLanguageConvertOptions`](../pagedescriptionlanguageconvertoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [Height](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/height) { get; set; } | Altura de página deseada después de la conversión, en píxeles independientes del dispositivo de 1/96 de pulgada cada uno. Déjelo en 0 para que el objetivo mantenga la altura de página que derive por sí mismo. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Width](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/width) { get; set; } | Ancho de página deseado después de la conversión, en píxeles independientes del dispositivo de 1/96 de pulgada cada uno. Déjelo en 0 para que el objetivo mantenga el ancho de página que derive por sí mismo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PageDescriptionLanguageFileType](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
