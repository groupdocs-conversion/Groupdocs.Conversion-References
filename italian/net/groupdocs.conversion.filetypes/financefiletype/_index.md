---
title: FinanceFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i documenti finanziari Include i seguenti tipi Xbrl./financefiletype/xbrlIXbrl./financefiletype/ixbrlOfx./financefiletype/ofx Ulteriori informazioni sui formati finanziariQuihttps//docs.fileformat.com/finance/ .
type: docs
weight: 940
url: /it/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Definisce i documenti finanziari Include i seguenti tipi: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) Ulteriori informazioni sui formati finanziari[Qui](https://docs.fileformat.com/finance/) .

```csharp
public sealed class FinanceFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FinanceFileType](financefiletype)() | Costruttore di serializzazione |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia di file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina se due istanze di oggetto sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funge da funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione di stringa |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | All'interno di iXBRL, i contenuti di XBRL sono racchiusi nel formato di file xHTML che utilizza tag XML. Come XBRL, è l'elemento radice dei file iXBRL. Il formato XHTML rappresenta i suoi contenuti come raccolta di diversi tipi di documenti e moduli. Tutti i file in XHTML sono basati sul formato di file XML e sono conformi agli standard dei documenti XML. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/finance/ixbrl/) . |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) è un formato di flusso di dati per lo scambio di informazioni finanziarie che si è evoluto dai formati di file Open Financial Connectivity (OFC) di Microsoft e Open Exchange di Intuit. Ulteriori informazioni su questo formato di file[Qui](https://en.wikipedia.org/wiki/Open_Financial_Exchange) . |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL è uno standard internazionale aperto per il reporting aziendale digitale ampiamente utilizzato a livello globale. È un linguaggio basato su XML che utilizza elementi XBRL, noti come tag, per descrivere ogni elemento dei dati aziendali per formulare i dati per l'ordinamento e l'analisi dei report. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/finance/xbrl/) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->