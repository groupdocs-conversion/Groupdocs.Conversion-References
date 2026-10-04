---
title: "GmlLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Gml."
type: docs
weight: 2550
url: /it/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

Opzioni per il caricamento di documenti Gml.

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | Inizializza una nuova istanza della classe [`GmlLoadOptions`](../gmlloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | Tipo di file del documento di input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Imposta l'altezza della pagina desiderata per la conversione del documento GIS. Il valore predefinito è 1000. |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Determina se la Conversione è autorizzata a caricare lo schema XML da Internet. Se impostato su false, gli schemi con URI assoluti che non iniziano con ‘file://’ non verranno caricati. Il valore predefinito è false. |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | Determina se la Conversione è autorizzata a analizzare gli attributi in un file Gml in cui lo schema XML è mancante o non può essere caricato. Se impostato su true, il lettore della Conversione non richiede la presenza di uno schema XML. Il valore predefinito è false. |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | Elenco di coppie di URI separati da spazi. Il primo URI di ogni coppia è l'URI dello spazio dei nomi, il secondo URI è un percorso allo schema XML dello spazio dei nomi. Se impostato su null, la Conversione proverà a leggere schemaLocation dall'elemento radice del documento. Il valore predefinito è null. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Imposta la larghezza della pagina desiderata per la conversione del documento GIS. Il valore predefinito è 1000. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
