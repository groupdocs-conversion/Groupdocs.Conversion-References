---
title: "DiagramFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i documenti Diagram. Include i seguenti tipi Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /it/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definisce i documenti Diagram. Include i seguenti tipi: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Costruttore di serializzazione |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Un file con estensione DRAWIO è un diagramma creato con diagrams.net (precedentemente draw.io). È memorizzato in formato XML con l'elemento radice mxfile e contiene il contenuto e la formattazione degli elementi del diagramma come testo, immagini, layout, forme e posizionamento. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Un file con estensione MMD è un diagramma scritto nel linguaggio di markup Mermaid. È memorizzato come documento di testo semplice che inizia con la dichiarazione del diagramma, come flowchart o sequenceDiagram, seguita dalla definizione dei nodi e delle connessioni tra di essi. Scopri di più su questo formato di file [qui](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW è il formato di file Visio Graphics Service che specifica i flussi e le memorie necessarie per il rendering di un disegno Web. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Qualsiasi disegno o grafico creato in Microsoft Visio, ma salvato in formato XML, ha estensione .VDX. Un file XML di disegno Visio è creato nel software Visio, sviluppato da Microsoft. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | I file VSD sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e le loro interconnessioni. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | I file con estensione VSDM sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma offrono anche la possibilità di eseguire macro quando il file viene aperto. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | I file con estensione .VSDX rappresentano il formato di file Microsoft Visio introdotto a partire da Microsoft Office 2013. È stato sviluppato per sostituire il formato di file binario, .VSD, supportato dalle versioni precedenti di Microsoft Visio. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | I VSS sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. I file stencil forniscono oggetti di disegno che possono essere inclusi in un disegno Visio .VSD. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | I file con estensione .VSSM sono file stencil di Microsoft Visio che supportano le macro. Un file VSSM, quando aperto, consente di eseguire le macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | I file con estensione .VSSX sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. Il formato di file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per la rappresentazione di una varietà di elementi di disegno, come collezioni di forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | I file con estensione VST sono file immagine vettoriali creati con Microsoft Visio e fungono da modello per creare altri file. Questi file modello sono in formato binario e contengono il layout e le impostazioni predefinite utilizzate per la creazione di nuovi disegni Visio. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | I file con estensione VSTM sono file modello creati con Microsoft Visio che supportano le macro. A differenza dei file VSDX, i file creati da modelli VSTM possono eseguire macro sviluppate in codice Visual Basic for Applications (VBA). Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | I file con estensione VSTX sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono un punto di partenza per creare disegni Visio, salvati come file .VSDX, con layout e impostazioni predefinite. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | I file con estensione .VSX si riferiscono a stencil che consistono in disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX sono salvati in formato XML e sono stati supportati fino a Visio 2013. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Un file con estensione VTX è un modello di disegno Microsoft Visio salvato su disco in formato XML. Il modello è pensato per fornire un file con impostazioni di base che può essere usato per creare più file Visio con le stesse impostazioni. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/image/vtx). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
