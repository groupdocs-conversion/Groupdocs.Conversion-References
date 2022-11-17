---
title: CadFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i documenti CAD Computer Aided Design che vengono utilizzati per i formati di file di grafica 3D e possono contenere disegni 2D o 3D. Include i seguenti tipi Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Ulteriori informazioni sui formati CADquihttps//wiki.fileformat.com/cad .
type: docs
weight: 800
url: /it/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definisce i documenti CAD (Computer Aided Design) che vengono utilizzati per i formati di file di grafica 3D e possono contenere disegni 2D o 3D. Include i seguenti tipi: [`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Ulteriori informazioni sui formati CAD[qui](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CadFileType](cadfiletype)() | Costruttore di serializzazione |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | File formato file comune. File CAD che contiene progetti di pacchetti 3D o altri dati del modello; può essere lavorato e tagliato da una macchina CAD/CAM, come un dispositivo di fustellatura. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, i file sono disegni creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) rappresenta il disegno 2D/3D in formato compresso per la visualizzazione, la revisione o la stampa di file di progettazione. Contiene grafica e testo come parte dei dati di progettazione e riduce le dimensioni del file grazie al suo formato compresso. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Il file DWFX è un disegno 2D o 3D creato con il software CAD Autodesk. Viene salvato nel formato DWFx, che è simile a un . DWF, ma è formattato utilizzando XML Paper Specification (XPS) di Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | I file con estensione DWG rappresentano file binari proprietari utilizzati per contenere dati di progettazione 2D e 3D. Come i DXF, che sono file ASCII, i DWG rappresentano il formato di file binario per i disegni CAD (Computer Aided Design). Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Un file DWT è un file modello di disegno di AutoCAD utilizzato come base per la creazione di disegni che possono essere salvati come file DWG. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, o Drawing Exchange Format, è una rappresentazione di dati con tag del file di disegno di AutoCAD. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | I file con estensione IFC si riferiscono al formato di file Industry Foundation Classes (IFC) che stabilisce gli standard internazionali per importare ed esportare oggetti di costruzione e le loro proprietà. Questo formato di file fornisce l'interoperabilità tra diverse applicazioni software. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Formato documento Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Il formato file PLT è un file plotter basato su vettori introdotto da Autodesk, Inc. e contiene informazioni per un determinato file CAD. I dettagli di plottaggio richiedono accuratezza e precisione nella produzione e l'utilizzo del file PLT lo garantisce poiché tutte le immagini vengono stampate utilizzando linee anziché punti. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abbreviazione di stereolitografia, è un formato di file intercambiabile che rappresenta la geometria della superficie tridimensionale. Il formato file trova il suo utilizzo in diversi campi come la prototipazione rapida, la stampa 3D e la produzione assistita da computer. Ulteriori informazioni su questo formato file[qui](https://wiki.fileformat.com/cad/stl) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
