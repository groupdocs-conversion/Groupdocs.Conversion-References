---
title: Converter
second_title: GroupDocs.Conversion for .NET API Referens
description: Representerar huvudklass som styr dokumentkonverteringsprocessen.
type: docs
weight: 730
url: /sv/net/groupdocs.conversion/converter/
---
## Converter class

Representerar huvudklass som styr dokumentkonverteringsprocessen.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Converter](converter#constructor)() | Initierar ny instans av[`Converter`](../converter) klass för flytande konverteringsinställningar. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_7)(string) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initierar ny instans av[`Converter`](../converter) class. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initierar ny instans av[`Converter`](../converter) class. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar det konverterade dokumentet sida för sida. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konverterar källdokument. Sparar hela det konverterade dokumentet. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Frigör resurser. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Får information om källdokument - antal sidor och andra dokumentegenskaper som är specifika för filtypen. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Får möjliga konverteringar för källdokumentet. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Konfigurera källdokument stream |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Konfigurera uppsättning källdokument streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Konfigurera källdokument för konvertering |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Konfigurera uppsättning källdokument |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Konfigurera konverteringsinställningar |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Får alla konverteringar som stöds |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Får stödda konverteringar för tillhandahållet dokumenttillägg |

### Se även

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* namnutrymme [GroupDocs.Conversion](../../groupdocs.conversion)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
