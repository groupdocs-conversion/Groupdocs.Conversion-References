---
title: "WatermarkImageOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per impostare la filigrana nel documento convertito"
type: docs
weight: 2290
url: /it/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

Opzioni per impostare la filigrana nel documento convertito

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | Crea la classe WatermarkOptions e imposta il testo della filigrana |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Scala automaticamente la filigrana. Se il valore è true, la posizione e le dimensioni sono calcolate automaticamente per adattarsi alle dimensioni della pagina. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Indica che la filigrana è stampata come sfondo. Se il valore è true, la filigrana è posizionata in basso. Per impostazione predefinita è false e la filigrana è posizionata in alto. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Altezza della filigrana |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | Filigrana immagine |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Posizione sinistra della filigrana |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Angolo di rotazione della filigrana |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Posizione superiore della filigrana |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Trasparenza della filigrana. Valore compreso tra 0 e 1. Il valore 0 è completamente visibile, il valore 1 è invisibile. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Larghezza della filigrana |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Clona l'istanza corrente |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
