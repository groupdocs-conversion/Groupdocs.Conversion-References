---
title: PresentationFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i formati di file di presentazione che memorizzano la raccolta di record per ospitare dati di presentazione come diapositive forme testo animazioni video audio e oggetti incorporati. Include i seguenti tipi di file Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Ulteriori informazioni sui formati di presentazioneQuihttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /it/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definisce i formati di file di presentazione che memorizzano la raccolta di record per ospitare dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati. Include i seguenti tipi di file: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Ulteriori informazioni sui formati di presentazione[Qui](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Costruttore di serializzazione |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | I file con estensione FODP rappresentano OpenDocument Flat XML Presentation. File di presentazione salvato nel formato OpenDocument, ma salvato utilizzando un formato XML flat anziché il contenitore .ZIP utilizzato dai file .ODP standard |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | I file con estensione ODP rappresentano il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | I file con estensione .OTP rappresentano i file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. Ulteriori informazioni su questo formato file[Qui](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | I file con estensione .POT rappresentano i file modello Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | I file con estensione POTM sono file modello di Microsoft PowerPoint con supporto per le macro. I file POTM vengono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere utilizzate per creare ulteriori file di presentazione. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | I file con estensione .POTX rappresentano le presentazioni dei modelli di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, i file vengono creati utilizzando Microsoft PowerPoint a scopo di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | I file con estensione PPSM rappresentano il formato di file di presentazione con attivazione macro creato con Microsoft PowerPoint 2007 o versioni successive. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, PowerPoint Slide Show, il file viene creato utilizzando Microsoft PowerPoint 2007 e versioni successive per lo scopo della presentazione. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Un file con estensione PPT rappresenta un file PowerPoint costituito da una raccolta di diapositive da visualizzare come SlideShow. Specifica il formato di file binario utilizzato da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | I file con estensione PPTM sono file di presentazione con attivazione macro creati con Microsoft PowerPoint 2007 o versioni successive. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | I file con estensione PPTX sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT che era binario, il formato PPTX si basa sul formato di file di presentazione XML aperto di Microsoft PowerPoint. Ulteriori informazioni su questo formato di file[Qui](https://wiki.fileformat.com/presentation/pptx) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
