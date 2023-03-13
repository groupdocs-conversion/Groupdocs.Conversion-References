---
title: Converter
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Rappresenta la classe principale che controlla il processo di conversione dei documenti.
type: docs
weight: 730
url: /it/net/groupdocs.conversion/converter/
---
## Converter class

Rappresenta la classe principale che controlla il processo di conversione dei documenti.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Converter](converter#constructor)() | Inizializza una nuova istanza di[`Converter`](../converter) classe per l'impostazione della conversione fluente. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_7)(string) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inizializza una nuova istanza di[`Converter`](../converter) classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva il documento convertito pagina per pagina. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Converte il documento di origine. Salva l'intero documento convertito. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Rilascia risorse. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Ottiene informazioni sul documento di origine: numero di pagine e altre proprietà del documento specifiche per il tipo di file. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Ottiene le possibili conversioni per il documento di origine. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Configura il flusso del documento di origine |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Configura set di flussi di documenti di origine |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Configura il documento di origine per la conversione |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Configura set di documenti di origine |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Configura le impostazioni di conversione |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Ottiene tutte le conversioni supportate |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Ottiene le conversioni supportate per l'estensione del documento fornita |

### Guarda anche

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* spazio dei nomi [GroupDocs.Conversion](../../groupdocs.conversion)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
