---
title: ProjectManagementFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i formati di file di progetto creati da software di Project Management come Microsoft Project Primavera P6 ecc. Un file di progetto è una raccolta di attività risorse e la relativa pianificazione per ottenere un output misurabile sotto forma di un prodotto o un servizio. Documenti di gestione del progetto. Include i seguenti tipi di file Mpp./projectmanagementfiletype/mpp  Mpt./projectmanagementfiletype/mpt  Mpx./projectmanagementfiletype/mpx . Ulteriori informazioni sui formati di Project Managementquihttps//wiki.fileformat.com/projectmanagement .
type: docs
weight: 920
url: /it/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Definisce i formati di file di progetto creati da software di Project Management come Microsoft Project, Primavera P6 ecc. Un file di progetto è una raccolta di attività, risorse e la relativa pianificazione per ottenere un output misurabile sotto forma di un prodotto o un servizio. Documenti di gestione del progetto. Include i seguenti tipi di file: [`Mpp`](./mpp) , [`Mpt`](./mpt) , [`Mpx`](./mpx) . Ulteriori informazioni sui formati di Project Management[qui](https://wiki.fileformat.com/project-management) .

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Costruttore di serializzazione |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina se due istanze di oggetto sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serve come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione di stringa |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP è un file di dati di Microsoft Project che memorizza le informazioni relative alla gestione dei progetti in modo integrato. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/project-management/mpp) . |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | File modello di Microsoft Project, contengono informazioni e struttura di base insieme alle impostazioni del documento per la creazione di file .MPP. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/project-management/mpt) . |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format, è un formato file ASCII per il trasferimento delle informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato file MPX come Primavera Project Planner, Sciforma e Timerline Precision Estimating. Ulteriori informazioni su questo formato file[qui](https://wiki.fileformat.com/project-management/mpx) . |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Il formato di file XER è un formato di file di progetto proprietario utilizzato dall'applicazione di gestione e pianificazione del progetto Primavera P6. Ulteriori informazioni su questo formato di file[qui](https://docs.fileformat.com/project-management/xer) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->