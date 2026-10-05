---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert diagramdocumenten."
type: docs
weight: 13
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Definieert Diagram‑documenten. Bevat de volgende typen: [Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdw), [Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdx), [Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsd), [Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdm), [Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdx), [Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vss), [Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssm), [Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssx), [Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vst), [Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstm), [Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstx), [Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsx), [Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vtx).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DiagramFileType()](#DiagramFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Vsd](#Vsd) | VSD‑bestanden zijn tekeningen gemaakt met de Microsoft Visio‑applicatie om verschillende grafische objecten en de onderlinge verbindingen daartussen weer te geven. |
| [Vsdx](#Vsdx) | Bestanden met de extensie .VSDX vertegenwoordigen het Microsoft Visio‑bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. |
| [Vss](#Vss) | VSS‑bestanden zijn sjabloonbestanden die zijn gemaakt met Microsoft Visio 2007 en eerdere versies. |
| [Vst](#Vst) | Bestanden met de extensie VST zijn vectorafbeeldingsbestanden die met Microsoft Visio zijn gemaakt en dienen als sjabloon voor het maken van verdere bestanden. |
| [Vsx](#Vsx) | Bestanden met de extensie .VSX verwijzen naar sjablonen die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. |
| [Vtx](#Vtx) | Een bestand met de extensie VTX is een Microsoft Visio‑tekeningssjabloon dat op schijf wordt opgeslagen in XML‑bestandsformaat. |
| [Vdw](#Vdw) | VDW is het Visio Graphics Service‑bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. |
| [Vdx](#Vdx) | Elke tekening of grafiek die in Microsoft Visio is gemaakt, maar in XML‑formaat is opgeslagen, heeft de extensie .VDX. |
| [Vssx](#Vssx) | Bestanden met de .VSSX-extensie zijn tekenstencils gemaakt met Microsoft Visio 2013 en hoger. |
| [Vstx](#Vstx) | Bestanden met VSTX-extensies zijn tekensjabloonbestanden gemaakt met Microsoft Visio 2013 en hoger. |
| [Vsdm](#Vsdm) | Bestanden met VSDM-extensie zijn tekenbestanden gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. |
| [Vssm](#Vssm) | Bestanden met de .VSSM-extensie zijn Microsoft Visio-stencilbestanden die ondersteuning voor macro's bieden. |
| [Vstm](#Vstm) | Bestanden met VSTM-extensie zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. |
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


VSD-bestanden zijn tekeningen gemaakt met de Microsoft Visio-toepassing om een verscheidenheid aan grafische objecten en de onderlinge verbindingen weer te geven. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vsd

### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Bestanden met de .VSDX-extensie vertegenwoordigen het Microsoft Visio-bestandsformaat dat is geïntroduceerd vanaf Microsoft Office 2013. Het is ontwikkeld om het binaire bestandsformaat .VSD te vervangen, dat wordt ondersteund door eerdere versies van Microsoft Visio. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS zijn stencilbestanden gemaakt met Microsoft Visio 2007 en eerder. Stencilbestanden bieden tekenobjecten die kunnen worden opgenomen in een .VSD Visio-tekening. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vss

### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Bestanden met VST-extensie zijn vectorafbeeldingsbestanden gemaakt met Microsoft Visio en fungeren als sjabloon voor het maken van verdere bestanden. Deze sjabloonbestanden zijn in binair bestandsformaat en bevatten de standaardlay-out en instellingen die worden gebruikt voor het maken van nieuwe Visio-tekeningen. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vst

### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Bestanden met de .VSX-extensie verwijzen naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX-bestanden worden opgeslagen in XML-bestandsformaat en werden ondersteund tot Visio 2013. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vsx

### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Een bestand met VTX-extensie is een Microsoft Visio-tekenjabloon dat op schijf wordt opgeslagen in XML-bestandsformaat. Het sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio-bestanden met dezelfde instellingen te maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vtx

### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW is het Visio Graphics Service-bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/vdw

### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Elke tekening of grafiek gemaakt in Microsoft Visio, maar opgeslagen in XML-formaat, heeft de .VDX-extensie. Een Visio-teken-XML-bestand wordt gemaakt in Visio-software, die door Microsoft is ontwikkeld. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vdx

### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Bestanden met de .VSSX-extensie zijn tekenstencils gemaakt met Microsoft Visio 2013 en hoger. Het VSSX-bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio-bestanden staan bekend om de weergave van een verscheidenheid aan tekenelementen zoals een verzameling vormen, connectoren, stroomdiagrammen, netwerklay-out, UML-diagrammen, Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vssx

### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Bestanden met VSTX-extensies zijn tekenjabloonbestanden gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX-bestanden bieden een startpunt voor het maken van Visio-tekeningen, opgeslagen als .VSDX-bestanden, met standaardlay-out en instellingen. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vstx

### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Bestanden met VSDM-extensie zijn tekenbestanden gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. VSDM-bestanden zijn OPC/XML-tekeningen die vergelijkbaar zijn met VSDX, maar ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Bestanden met de .VSSM-extensie zijn Microsoft Visio-stencilbestanden die ondersteuning voor macro's bieden. Een VSSM-bestand maakt bij openen het uitvoeren van macro's mogelijk om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vssm

### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Bestanden met VSTM-extensie zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. In tegenstelling tot VSDX-bestanden kunnen bestanden die zijn gemaakt vanuit VSTM-sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vstm

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
