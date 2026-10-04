---
title: "CadFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i documenti CAD (Computer Aided Design) che sono utilizzati per formati di file grafica 3D e possono contenere progetti 2D o 3D. Include i seguenti tipi Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Scopri di più sui formati CAD quihttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /it/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definisce i documenti CAD (Computer Aided Design) che sono utilizzati per formati di file grafica 3D e possono contenere progetti 2D o 3D. Include i seguenti tipi: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Scopri di più sui formati CAD [qui](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CadFileType](cadfiletype)() | Costruttore di serializzazione |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | File Common File Format. File CAD che contiene progetti di pacchetti 3D o altri dati di modello; può essere processato e tagliato da una macchina CAD/CAM, come un dispositivo di taglio a punzonatura. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | I file DGN, Design, sono disegni creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) rappresenta disegni 2D/3D in formato compresso per visualizzare, revisionare o stampare file di progetto. Contiene grafica e testo come parte dei dati di progetto e riduce le dimensioni del file grazie al suo formato compresso. Scopri di più su questo formato di file [qui](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | Il file DWFX è un disegno 2D o 3D creato con il software CAD di Autodesk. Viene salvato nel formato DWFx, che è simile a un file .DWF, ma è formattato utilizzando la Specifica XML Paper di Microsoft (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | I file con estensione DWG rappresentano file binari proprietari utilizzati per contenere dati di progettazione 2D e 3D. Come i DXF, che sono file ASCII, i DWG rappresentano il formato file binario per i disegni CAD (Computer Aided Design). Scopri di più su questo formato file [qui](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Un file DWT è un modello di disegno AutoCAD utilizzato come punto di partenza per creare disegni che possono essere salvati come file DWG. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, o Drawing Exchange Format, è una rappresentazione di dati etichettati di un file di disegno AutoCAD. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | I file con estensione IFC si riferiscono al formato file Industry Foundation Classes (IFC) che stabilisce standard internazionali per importare ed esportare oggetti edilizi e le loro proprietà. Questo formato file garantisce l'interoperabilità tra diverse applicazioni software. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Formato documento Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Il formato file PLT è un file plotter basato su vettori introdotto da Autodesk, Inc. e contiene informazioni per un determinato file CAD. I dettagli della stampa richiedono accuratezza e precisione nella produzione, e l'uso del file PLT garantisce ciò poiché tutte le immagini vengono stampate con linee anziché punti. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abbreviazione di stereolitografia, è un formato file intercambiabile che rappresenta la geometria di superficie tridimensionale. Questo formato file è utilizzato in diversi settori come la prototipazione rapida, la stampa 3D e la produzione assistita da computer. Scopri di più su questo formato file [qui](https://wiki.fileformat.com/cad/stl). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
