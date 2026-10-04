---
title: "VectorizationOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la vettorizzazione delle immagini."
type: docs
weight: 2900
url: /it/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Opzioni per la vettorizzazione delle immagini.

```csharp
public class VectorizationOptions : ValueObject
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Costruttore predefinito per VectorizationOptions. |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo. Il valore predefinito è bianco trasparente. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Ottiene o imposta il numero massimo di colori usati per quantizzare un'immagine. Il valore predefinito è 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Abilita la vettorizzazione delle immagini. Il valore predefinito è false. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Ottiene o imposta la dimensione massima dell'immagine determinata dalla moltiplicazione della larghezza e dell'altezza dell'immagine. La dimensione dell'immagine verrà scalata in base a questa proprietà. Il valore predefinito è 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Ottiene o imposta lo spessore della linea. Il valore di questo parametro è influenzato dalla scala grafica. Il valore predefinito è 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Imposta la gravità del levigatore di tracciamento dell'immagine |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
