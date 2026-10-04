---
title: "PresentationFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i formati di file di Presentazione che memorizzano una raccolta di record per contenere dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati. Include i seguenti tipi di file Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Per saperne di più sui formati di Presentazione quihttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /it/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definisce i formati di file di Presentazione che memorizzano una raccolta di record per contenere dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati. Include i seguenti tipi di file: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Per saperne di più sui formati di Presentazione [qui](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Costruttore di serializzazione |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | I file con estensione FODP rappresentano una Presentazione OpenDocument Flat XML. File di presentazione salvato nel formato OpenDocument, ma salvato usando un formato XML flat invece del contenitore .ZIP utilizzato dai file .ODP standard. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | I file con estensione ODP rappresentano il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | I file con estensione .OTP rappresentano file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | I file con estensione .POT rappresentano file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | I file con estensione POTM sono file modello di Microsoft PowerPoint con supporto per macro. I file POTM sono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere usate per creare ulteriori file di presentazione. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | I file con estensione .POTX rappresentano presentazioni modello di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | I file PPS, PowerPoint Slide Show, sono creati usando Microsoft PowerPoint per scopi di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | I file con estensione PPSM rappresentano il formato di file Slide Show abilitato alle macro, creato con Microsoft PowerPoint 2007 o versioni successive. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | I file PPSX, Power Point Slide Show, sono creati usando Microsoft PowerPoint 2007 e versioni successive per scopi di presentazione. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Un file con estensione PPT rappresenta un file PowerPoint che consiste in una raccolta di diapositive per la visualizzazione come presentazione. Specifica il formato binario di file utilizzato da Microsoft PowerPoint 97-2003. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | I file con estensione PPTM sono file di presentazione abilitati alle macro, creati con Microsoft PowerPoint 2007 o versioni successive. Per saperne di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | I file con estensione PPTX sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT, che era binario, il formato PPTX si basa sul formato di presentazione Open XML di Microsoft PowerPoint. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/presentation/pptx). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
