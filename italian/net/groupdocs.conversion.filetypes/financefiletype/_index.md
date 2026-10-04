---
title: "FinanceFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i documenti Finance Include i seguenti tipi Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx Per saperne di più sui formati Finance qui https//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /it/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Definisce i documenti Finance Include i seguenti tipi: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) Per saperne di più sui formati Finance [qui](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [FinanceFileType](financefiletype)() | Costruttore di serializzazione |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia del file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione stringa |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Nell'iXBRL, i contenuti di XBRL sono avvolti nel formato di file xHTML che utilizza tag XML. Come XBRL, è l'elemento radice dei file iXBRL. Il formato XHTML rappresenta i suoi contenuti come una collezione di diversi tipi di documenti e moduli. Tutti i file in XHTML si basano sul formato di file XML e sono conformi agli standard dei documenti XML. Per saperne di più su questo formato di file [qui](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) è un formato di flusso di dati per lo scambio di informazioni finanziarie che è evoluto dall'Open Financial Connectivity (OFC) di Microsoft e dai formati di file Open Exchange di Intuit. Per saperne di più su questo formato di file [qui](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL è uno standard internazionale aperto per la rendicontazione aziendale digitale ampiamente utilizzato a livello globale. È un linguaggio basato su XML che utilizza gli elementi XBRL, noti come tag, per descrivere ogni elemento di dati aziendali al fine di formulare dati per l'ordinamento e l'analisi dei report. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/finance/xbrl/). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
