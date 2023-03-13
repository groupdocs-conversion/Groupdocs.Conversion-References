---
title: Converter
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Vertegenwoordigt de hoofdklasse die het documentconversieproces regelt.
type: docs
weight: 730
url: /nl/net/groupdocs.conversion/converter/
---
## Converter class

Vertegenwoordigt de hoofdklasse die het documentconversieproces regelt.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Converter](converter#constructor)() | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse voor vloeiende conversie-instellingen. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_7)(string) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialiseert nieuw exemplaar van[`Converter`](../converter) klasse. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converteert brondocument. Slaat het hele geconverteerde document op. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Geeft bronnen vrij. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Haalt brondocumentinformatie op - aantal pagina's en andere documenteigenschappen die specifiek zijn voor het bestandstype. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Krijgt mogelijke conversies voor het brondocument. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Brondocumentstroom configureren |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Configureer set brondocumentenstromen |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Configureer brondocument voor conversie |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Set brondocumenten configureren |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Conversie-instellingen configureren |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Krijgt alle ondersteunde conversies |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Krijgt ondersteunde conversies voor opgegeven documentextensie |

### Zie ook

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* naamruimte [GroupDocs.Conversion](../../groupdocs.conversion)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
