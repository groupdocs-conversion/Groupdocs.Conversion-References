---
title: EmailFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i formati di file di posta elettronica utilizzati dalle applicazioni di posta elettronica per archiviare i vari dati inclusi messaggi di posta elettronica allegati cartelle rubriche ecc. Include i seguenti tipi di file Eml./emailfiletype/eml  Emlx./emailfiletype/emlx  Msg./emailfiletype/msg  Vcf./emailfiletype/vcf . Mbox./emailfiletype/mbox . Pst./emailfiletype/pst . Ost./emailfiletype/ost . Ulteriori informazioni sui formati di posta elettronicaQuihttps//wiki.fileformat.com/email .
type: docs
weight: 920
url: /it/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Definisce i formati di file di posta elettronica utilizzati dalle applicazioni di posta elettronica per archiviare i vari dati inclusi messaggi di posta elettronica, allegati, cartelle, rubriche ecc. Include i seguenti tipi di file: [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Vcf`](./vcf) . [`Mbox`](./mbox) . [`Pst`](./pst) . [`Ost`](./ost) . Ulteriori informazioni sui formati di posta elettronica[Qui](https://wiki.fileformat.com/email) .

```csharp
public sealed class EmailFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmailFileType](emailfiletype)() | Costruttore di serializzazione |

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
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Il formato di file EML rappresenta i messaggi di posta elettronica salvati utilizzando Outlook e altre applicazioni pertinenti. Quasi tutti i client di posta elettronica supportano questo formato di file per la sua conformità con RFC-822 Internet Message Format Standard. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/email/eml) . |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Il formato file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per l'esportazione delle e-mail. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/email/emlx) . |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Formato file MBox è un termine generico che rappresenta un contenitore per la raccolta di messaggi di posta elettronica. I messaggi vengono archiviati all'interno del contenitore insieme ai relativi allegati. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG è un formato di file utilizzato da Microsoft Outlook ed Exchange per archiviare messaggi e-mail, contatti, appuntamenti o altre attività. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/email/msg) . |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | OST o Offline Storage Files rappresentano i dati della cassetta postale dell'utente in modalità offline sulla macchina locale al momento della registrazione con Exchange Server utilizzando Microsoft Outlook. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/email/ost) . |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | I file con estensione .PST rappresentano i file di archiviazione personale di Outlook (chiamati anche tabella di archiviazione personale) che memorizzano una varietà di informazioni utente. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/email/pst) . |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione delle informazioni di contatto. Il formato è ampiamente utilizzato per lo scambio di dati tra le applicazioni di scambio di informazioni più diffuse. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/email/vcf) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
