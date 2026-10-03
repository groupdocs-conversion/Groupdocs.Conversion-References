---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert diagramdocumenten."
type: docs
weight: 13
url: /nl/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Definieert Diagram‑documenten. Bevat de volgende typen:
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

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Vsd](#Vsd) | VSD‑bestanden zijn tekeningen die met de Microsoft Visio‑applicatie zijn gemaakt om een verscheidenheid aan grafische objecten en de onderlinge verbinding daartussen weer te geven. |
|
|  | [Vsdx](#Vsdx) | Bestanden met de extensie .VSDX vertegenwoordigen het Microsoft Visio‑bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. |
|
|  | [Vss](#Vss) | VSS zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio 2007 en eerdere versies. |
|
|  | [Vst](#Vst) | Bestanden met de VST‑extensie zijn vectorafbeeldingsbestanden die met Microsoft Visio zijn gemaakt en dienen als sjabloon voor het aanmaken van verdere bestanden. |
|
|  | [Vsx](#Vsx) | Bestanden met de .VSX‑extensie verwijzen naar sjablonen die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. |
|
|  | [Vtx](#Vtx) | Een bestand met de VTX‑extensie is een Microsoft Visio‑tekeningssjabloon dat op schijf wordt opgeslagen in XML‑bestandsformaat. |
|
|  | [Vdw](#Vdw) | VDW is het Visio Graphics Service‑bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. |
|
|  | [Vdx](#Vdx) | Elke tekening of grafiek die in Microsoft Visio is gemaakt, maar in XML‑formaat is opgeslagen, heeft de .VDX‑extensie. |
|
|  | [Vssx](#Vssx) | Bestanden met de .VSSX‑extensie zijn tekeningssjablonen die zijn gemaakt met Microsoft Visio 2013 en hoger. |
|
|  | [Vstx](#Vstx) | Bestanden met de VSTX‑extensies zijn tekeningssjabloonbestanden die zijn gemaakt met Microsoft Visio 2013 en hoger. |
|
|  | [Vsdm](#Vsdm) | Bestanden met de VSDM‑extensie zijn tekeningsbestanden die met de Microsoft Visio‑applicatie zijn gemaakt en macro's ondersteunen. |
|
|  | [Vssm](#Vssm) | Bestanden met de .VSSM‑extensie zijn Microsoft Visio‑sjabloonbestanden die ondersteuning bieden voor macro's. |
|
|  | [Vstm](#Vstm) | Bestanden met de VSTM‑extensie zijn sjabloonbestanden die met Microsoft Visio zijn gemaakt en macro's ondersteunen. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Serialisatieconstructor


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD‑bestanden zijn tekeningen die met de Microsoft Visio‑applicatie zijn gemaakt om een verscheidenheid aan grafische objecten en de onderlinge verbinding daartussen weer te geven.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Bestanden met de .VSDX‑extensie vertegenwoordigen het Microsoft Visio‑bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. Het is ontwikkeld om het binaire bestandsformaat .VSD te vervangen, dat wordt ondersteund door eerdere versies van Microsoft Visio.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio 2007 en eerdere versies. Sjabloonbestanden bieden tekenobjecten die kunnen worden opgenomen in een .VSD‑Visio‑tekening.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Bestanden met de VST‑extensie zijn vectorafbeeldingsbestanden die met Microsoft Visio zijn gemaakt en dienen als sjabloon voor het aanmaken van verdere bestanden. Deze sjabloonbestanden zijn in binair bestandsformaat en bevatten de standaardlay-out en -instellingen die worden gebruikt voor het maken van nieuwe Visio‑tekeningen.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Bestanden met de .VSX‑extensie verwijzen naar sjablonen die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX‑bestanden worden opgeslagen in XML‑bestandsformaat en werden ondersteund tot Visio 2013.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Een bestand met de VTX‑extensie is een Microsoft Visio‑tekeningssjabloon dat op schijf wordt opgeslagen in XML‑bestandsformaat. Het sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio‑bestanden met dezelfde instellingen te maken.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW is het Visio Graphics Service‑bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening.
Meer informatie over dit bestandsformaat vind je [hier](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Elke tekening of diagram die is gemaakt in Microsoft Visio, maar opgeslagen in XML-indeling, heeft de .VDX-extensie. Een Visio-teken XML‑bestand wordt aangemaakt in Visio‑software, die is ontwikkeld door Microsoft.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Bestanden met de .VSSX-extensie zijn tekensjablonen die zijn gemaakt met Microsoft Visio 2013 en hoger. Het VSSX-bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio‑bestanden staan bekend om de weergave van diverse tekenelementen, zoals een verzameling vormen, connectoren, stroomdiagrammen, netwerklay-outs, UML‑diagrammen,
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Bestanden met VSTX-extensies zijn tekensjabloonbestanden die zijn gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX‑bestanden bieden een startpunt voor het maken van Visio‑tekeningen, opgeslagen als .VSDX‑bestanden, met een standaardindeling en -instellingen.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Bestanden met de VSDM-extensie zijn tekenbestanden die zijn gemaakt met de Microsoft Visio‑applicatie die macro's ondersteunt. VSDM‑bestanden zijn OPC/XML‑tekeningen die vergelijkbaar zijn met VSDX, maar ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Bestanden met de .VSSM-extensie zijn Microsoft Visio‑sjabloonbestanden die ondersteuning bieden voor macro's. Een VSSM‑bestand maakt bij openen het uitvoeren van macro's mogelijk om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Bestanden met de VSTM-extensie zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio en macro's ondersteunen. In tegenstelling tot VSDX‑bestanden kunnen bestanden die zijn gemaakt vanuit VSTM‑sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/image/vstm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype


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
