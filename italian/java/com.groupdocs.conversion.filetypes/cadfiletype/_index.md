---
title: "CadFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti CAD (Computer Aided Design) che sono usati per formati di file grafici 3D e possono contenere progetti 2D o 3D."
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Definisce documenti CAD (Computer Aided Design) che sono utilizzati per formati di file grafici 3D e possono contenere progetti 2D o 3D.
Include i seguenti tipi:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
Scopri di più sui formati CAD [qui](../https://wiki.fileformat.com/cad).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format, o Drawing Exchange Format, è una rappresentazione di dati etichettati di file di disegno AutoCAD. |
|
|  | [Dwg](#Dwg) | I file con estensione DWG rappresentano file binari proprietari usati per contenere dati di progettazione 2D e 3D. |
|
|  | [Dgn](#Dgn) | DGN, Design, sono file di disegno creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) rappresenta disegni 2D/3D in formato compresso per visualizzare, revisionare o stampare file di progetto. |
|
|  | [Stl](#Stl) | STL, abbreviazione di stereolitografia, è un formato di file intercambiabile che rappresenta la geometria di superficie tridimensionale. |
|
|  | [Ifc](#Ifc) | I file con estensione IFC si riferiscono al formato di file Industry Foundation Classes (IFC) che stabilisce standard internazionali per importare ed esportare oggetti edilizi e le loro proprietà. |
|
|  | [Plt](#Plt) | Il formato di file PLT è un file plotter basato su vettori introdotto da Autodesk, Inc. |
|
|  | [Igs](#Igs) | Formato documento Igs |
|
|  | [Dwt](#Dwt) | Un file DWT è un modello di disegno AutoCAD usato come punto di partenza per creare disegni che possono essere salvati come file DWG. |
|
|  | [Dwfx](#Dwfx) | Il file DWFX è un disegno 2D o 3D creato con il software CAD di Autodesk. |
|
|  | [Cf2](#Cf2) | File Common File Format. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Costruttore di serializzazione


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, o Drawing Exchange Format, è una rappresentazione di dati etichettati di file di disegno AutoCAD.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


I file con estensione DWG rappresentano file binari proprietari usati per contenere dati di progettazione 2D e 3D. Come DXF, che sono file ASCII, DWG rappresenta il formato di file binario per disegni CAD (Computer Aided Design).
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design, sono file di disegno creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) rappresenta disegni 2D/3D in formato compresso per visualizzare, revisionare o stampare file di progetto. Contiene grafica e testo come parte dei dati di progetto e riduce la dimensione del file grazie al suo formato compresso.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, abbreviazione di stereolitografia, è un formato di file intercambiabile che rappresenta la geometria di superficie tridimensionale. Il formato di file trova impiego in diversi settori come la prototipazione rapida, la stampa 3D e la produzione assistita da computer.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


I file con estensione IFC si riferiscono al formato di file Industry Foundation Classes (IFC) che stabilisce standard internazionali per importare ed esportare oggetti edilizi e le loro proprietà. Questo formato di file fornisce interoperabilità tra diverse applicazioni software.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Il formato di file PLT è un file plotter vettoriale introdotto da Autodesk, Inc. e contiene informazioni per un determinato file CAD. I dettagli di stampa richiedono accuratezza e precisione nella produzione, e l'uso del file PLT garantisce ciò poiché tutte le immagini vengono stampate usando linee anziché punti.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Formato documento Igs


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Un file DWT è un modello di disegno AutoCAD usato come punto di partenza per creare disegni che possono essere salvati come file DWG.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


Il file DWFX è un disegno 2D o 3D creato con il software CAD di Autodesk. Viene salvato nel formato DWFx, simile a un file .DWF, ma formattato utilizzando la XML Paper Specification (XPS) di Microsoft.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


File Common File Format. File CAD che contiene progetti di pacchetti 3D o altri dati di modello; può essere elaborato e tagliato da una macchina CAD/CAM, come un dispositivo di punzonatura.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opzioni di conversione predefinite preparate per il tipo di file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
