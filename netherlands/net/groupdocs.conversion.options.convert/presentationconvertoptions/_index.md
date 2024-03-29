---
title: PresentationConvertOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Beschrijft opties voor conversie naar bestandstype Presentatie.
type: docs
weight: 1830
url: /nl/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

Beschrijft opties voor conversie naar bestandstype Presentatie.

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | Initialiseert nieuw exemplaar van[`PresentationConvertOptions`](../presentationconvertoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Het paginanummer vanaf waar de conversie moet worden gestart. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | De lijst met pagina-indexen die moeten worden geconverteerd. Moet worden opgegeven om specifieke pagina's te converteren. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Aantal pagina's om vanaf te converteren`Paginanummer` . |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | Stel deze eigenschap in als u het geconverteerde document met een wachtwoord wilt beveiligen. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Watermerkspecifieke opties |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | Specificeert het zoomniveau in procenten. Standaard is 100. Standaard zoom wordt ondersteund tot Microsoft Powerpoint 2010. Vanaf Microsoft Powerpoint 2013 is standaard zoom niet langer ingesteld op document, maar lijkt de zoomfactor te gebruiken van het laatst geopende document. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige optie-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* naamruimte [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
