---
title: "EmailFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i formati di file Email che sono utilizzati dalle applicazioni di posta elettronica per memorizzare i vari dati, inclusi messaggi email, allegati, cartelle, rubriche, ecc. Include i seguenti tipi di file Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. Scopri di più sui formati Email quihttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /it/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definisce i formati di file Email utilizzati dalle applicazioni di posta per memorizzare i vari dati, inclusi messaggi email, allegati, cartelle, rubriche ecc. Include i seguenti tipi di file: [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). Per saperne di più sui formati Email [qui](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [EmailFileType](emailfiletype)() | Costruttore di serializzazione |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Il formato di file EML rappresenta i messaggi email salvati con Outlook e altre applicazioni pertinenti. Quasi tutti i client di posta supportano questo formato di file per la sua conformità allo Standard RFC-822 Internet Message Format. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Il formato di file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per esportare le email. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Il formato di file ICS (iCalendar) è usato per rappresentare e scambiare informazioni di calendario e programmazione, come eventi, attività e dati di disponibilità libero/occupato. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Il formato di file MBox è un termine generico che rappresenta un contenitore per una collezione di messaggi di posta elettronica. I messaggi sono memorizzati all'interno del contenitore insieme ai loro allegati. Per saperne di più su questo formato di file [qui](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG è un formato di file utilizzato da Microsoft Outlook e Exchange per memorizzare messaggi email, contatti, appuntamenti o altre attività. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Un file con estensione .olm è un file Microsoft Outlook per il sistema operativo Mac. Un file OLM memorizza messaggi email, diari, dati di calendario e altri tipi di dati dell'applicazione. Questi sono simili ai file PST utilizzati da Outlook su Windows. Tuttavia, i file OLM creati da Outlook per Mac non possono essere aperti in Outlook per Windows. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST o Offline Storage Files rappresentano i dati della casella di posta dell'utente in modalità offline sulla macchina locale dopo la registrazione al server Exchange tramite Microsoft Outlook. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | I file con estensione .PST rappresentano i Outlook Personal Storage Files (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione di informazioni di contatto. Il formato è ampiamente utilizzato per lo scambio di dati tra le popolari applicazioni di scambio informazioni. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/email/vcf). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
