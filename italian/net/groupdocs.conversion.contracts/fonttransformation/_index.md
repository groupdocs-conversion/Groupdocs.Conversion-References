---
title: "FontTransformation"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Descrive la configurazione della trasformazione dei font, inclusi gli attributi dei font. Le trasformazioni dei font vengono applicate dopo il caricamento del documento e la sostituzione dei font."
type: docs
weight: 260
url: /it/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Descrive la configurazione della trasformazione dei font, inclusi gli attributi dei font. Le trasformazioni dei font vengono applicate dopo il caricamento del documento e la sostituzione dei font.

```csharp
public class FontTransformation : ValueObject
```

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Quando vero, corrisponde a qualsiasi dimensione del carattere per il nome del carattere originale. Quando falso, corrisponde esattamente alla dimensione del carattere specificata in OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Quando vero, corrisponde a qualsiasi stile del carattere (grassetto, corsivo, sottolineato) per il carattere originale. Quando falso, corrisponde esattamente allo stile del carattere specificato in OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | La specifica del carattere originale da confrontare e sostituire. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | La specifica del carattere di sostituzione. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Crea una trasformazione del carattere con corrispondenza esatta (dimensione e stile devono corrispondere). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Crea una trasformazione del carattere solo per nome, corrispondendo a qualsiasi dimensione e stile. Il carattere di sostituzione conserverà la dimensione e lo stile del carattere originale. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Crea una trasformazione del carattere con opzioni di corrispondenza flessibili. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
