---
title: "DiagramFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce documenti Diagram."
type: docs
weight: 13
url: /it/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Definisce i documenti Diagram. Include i seguenti tipi:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Vsd](#Vsd) | I file VSD sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e le loro interconnessioni. |
|
|  | [Vsdx](#Vsdx) | I file con estensione .VSDX rappresentano il formato file di Microsoft Visio introdotto a partire da Microsoft Office 2013. |
|
|  | [Vss](#Vss) | I VSS sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. |
|
|  | [Vst](#Vst) | I file con estensione VST sono file di immagini vettoriali creati con Microsoft Visio e fungono da modello per la creazione di ulteriori file. |
|
|  | [Vsx](#Vsx) | I file con estensione .VSX si riferiscono a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. |
|
|  | [Vtx](#Vtx) | Un file con estensione VTX è un modello di disegno Microsoft Visio salvato su disco in formato file XML. |
|
|  | [Vdw](#Vdw) | VDW è il formato file del Visio Graphics Service che specifica i flussi e le memorie necessarie per il rendering di un disegno Web. |
|
|  | [Vdx](#Vdx) | Qualsiasi disegno o grafico creato in Microsoft Visio, ma salvato in formato XML, ha estensione .VDX. |
|
|  | [Vssx](#Vssx) | I file con estensione .VSSX sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. |
|
|  | [Vstx](#Vstx) | I file con estensione VSTX sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. |
|
|  | [Vsdm](#Vsdm) | I file con estensione VSDM sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. |
|
|  | [Vssm](#Vssm) | I file con estensione .VSSM sono file stencil di Microsoft Visio che forniscono supporto per le macro. |
|
|  | [Vstm](#Vstm) | I file con estensione VSTM sono file modello creati con Microsoft Visio che supportano le macro. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Costruttore di serializzazione


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


I file VSD sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e le loro interconnessioni.
Scopri di più su questo formato file [qui](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


I file con estensione .VSDX rappresentano il formato file di Microsoft Visio introdotto a partire da Microsoft Office 2013. È stato sviluppato per sostituire il formato file binario, .VSD, supportato dalle versioni precedenti di Microsoft Visio.
Scopri di più su questo formato file [qui](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


I VSS sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. I file stencil forniscono oggetti di disegno che possono essere inclusi in un disegno .VSD di Visio.
Scopri di più su questo formato file [qui](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


I file con estensione VST sono file di immagini vettoriali creati con Microsoft Visio e fungono da modello per la creazione di ulteriori file. Questi file modello sono in formato file binario e contengono il layout predefinito e le impostazioni utilizzate per la creazione di nuovi disegni Visio.
Scopri di più su questo formato file [qui](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


I file con estensione .VSX si riferiscono a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX sono salvati in formato XML e sono stati supportati fino a Visio 2013.
Scopri di più su questo formato file [qui](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Un file con estensione VTX è un modello di disegno Microsoft Visio salvato su disco in formato XML. Il modello è pensato per fornire un file con impostazioni di base che può essere usato per creare più file Visio con le stesse impostazioni.
Scopri di più su questo formato file [qui](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW è il formato file del Visio Graphics Service che specifica i flussi e le memorie necessarie per il rendering di un disegno Web.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Qualsiasi disegno o diagramma creato in Microsoft Visio, ma salvato in formato XML, ha estensione .VDX. Un file XML di disegno Visio è creato nel software Visio, sviluppato da Microsoft.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


I file con estensione .VSSX sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. Il formato di file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per la rappresentazione di una varietà di elementi di disegno come collezioni di forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML,
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


I file con estensione VSTX sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono un punto di partenza per creare disegni Visio, salvati come file .VSDX, con layout e impostazioni predefinite.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


I file con estensione VSDM sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma offrono anche la possibilità di eseguire macro quando il file viene aperto.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


I file con estensione .VSSM sono file Stencil di Microsoft Visio che forniscono supporto per le macro. Un file VSSM, quando aperto, consente di eseguire le macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


I file con estensione VSTM sono file modello creati con Microsoft Visio che supportano le macro. A differenza dei file VSDX, i file creati da modelli VSTM possono eseguire macro sviluppate in codice Visual Basic for Applications (VBA).
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/image/vstm).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
