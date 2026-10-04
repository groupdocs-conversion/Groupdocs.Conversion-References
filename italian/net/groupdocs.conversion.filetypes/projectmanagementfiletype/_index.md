---
title: "ProjectManagementFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i formati di file di progetto creati da software di Project Management come Microsoft Project, Primavera P6 ecc. Un file di progetto è una raccolta di attività, risorse e la loro pianificazione per ottenere un risultato misurabile sotto forma di prodotto o servizio. Documenti di gestione del progetto. Include i seguenti tipi di file Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. Scopri di più sui formati di Project Management herehttps//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /it/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Definisce i formati di file di progetto creati da software di Project Management come Microsoft Project, Primavera P6 ecc. Un file di progetto è una raccolta di attività, risorse e la loro pianificazione per ottenere un risultato misurabile sotto forma di prodotto o servizio. Documenti di gestione del progetto. Include i seguenti tipi di file: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). Scopri di più sui formati di Project Management [qui](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Costruttore di serializzazione |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP è un file dati di Microsoft Project che memorizza informazioni relative alla gestione del progetto in modo integrato. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | I file modello di Microsoft Project contengono informazioni di base e struttura insieme alle impostazioni dei documenti per creare file .MPP. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format è un formato file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato file MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Il formato file XER è un formato file di progetto proprietario utilizzato dall'applicazione di pianificazione e gestione di progetto Primavera P6. Scopri di più su questo formato file [qui](https://docs.fileformat.com/project-management/xer). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
