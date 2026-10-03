---
title: "PresentationFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i formati di file di Presentazione che memorizzano una raccolta di record per contenere dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati."
type: docs
weight: 22
url: /it/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Definisce i formati di file di presentazione che memorizzano una raccolta di record per gestire dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati.
Include i seguenti tipi di file:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
Scopri di più sui formati di Presentazione [qui](../https://wiki.fileformat.com/presentation).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Ppt](#Ppt) | Un file con estensione PPT rappresenta un file PowerPoint che consiste in una raccolta di diapositive da visualizzare come SlideShow. |
|
|  | [Pps](#Pps) | PPS, PowerPoint Slide Show, i file vengono creati utilizzando Microsoft PowerPoint per scopi di Slide Show. |
|
|  | [Pptx](#Pptx) | I file con estensione PPTX sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. |
|
|  | [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, i file vengono creati utilizzando Microsoft PowerPoint 2007 e versioni successive per scopi di Slide Show. |
|
|  | [Odp](#Odp) | I file con estensione ODP rappresentano il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. |
|
|  | [Otp](#Otp) | I file con estensione .OTP rappresentano file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. |
|
|  | [Potx](#Potx) | I file con estensione .POTX rappresentano presentazioni modello di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. |
|
|  | [Pot](#Pot) | I file con estensione .POT rappresentano file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. |
|
|  | [Potm](#Potm) | I file con estensione POTM sono file modello di Microsoft PowerPoint con supporto per macro. |
|
|  | [Pptm](#Pptm) | I file con estensione PPTM sono file di presentazione abilitati alle macro creati con Microsoft PowerPoint 2007 o versioni successive. |
|
|  | [Ppsm](#Ppsm) | I file con estensione PPSM rappresentano il formato di file Slide Show abilitato alle macro creato con Microsoft PowerPoint 2007 o versioni successive. |
|
|  | [Fodp](#Fodp) | I file con estensione FODP rappresentano una presentazione OpenDocument Flat XML. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Costruttore di serializzazione


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Un file con estensione PPT rappresenta un file PowerPoint che consiste in una raccolta di diapositive da visualizzare come SlideShow. Specifica il formato di file binario utilizzato da Microsoft PowerPoint 97-2003.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slide Show, i file vengono creati utilizzando Microsoft PowerPoint per scopi di Slide Show. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


I file con estensione PPTX sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT, che era binario, il formato PPTX si basa sul formato di file di presentazione Open XML di Microsoft PowerPoint.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, Power Point Slide Show, i file vengono creati utilizzando Microsoft PowerPoint 2007 e versioni successive per scopi di Slide Show.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


I file con estensione ODP rappresentano il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


I file con estensione .OTP rappresentano file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


I file con estensione .POTX rappresentano presentazioni modello di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


I file con estensione .POT rappresentano file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


I file con estensione POTM sono file modello di Microsoft PowerPoint con supporto per le macro. I file POTM sono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere utilizzate per creare ulteriori file di presentazione.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


I file con estensione PPTM sono file di presentazione abilitati alle macro creati con Microsoft PowerPoint 2007 o versioni successive.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


I file con estensione PPSM rappresentano il formato di file Slide Show abilitato alle macro creato con Microsoft PowerPoint 2007 o versioni successive.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


I file con estensione FODP rappresentano una presentazione OpenDocument Flat XML. Il file di presentazione è salvato nel formato OpenDocument, ma utilizzando un formato XML flat invece del contenitore .ZIP usato dai file .ODP standard.


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
