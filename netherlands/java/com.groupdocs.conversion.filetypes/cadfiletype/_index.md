---
title: "CadFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert CAD‑documenten (Computer Aided Design) die worden gebruikt voor 3D‑grafische bestandsformaten en die 2D‑ of 3D‑ontwerpen kunnen bevatten."
type: docs
weight: 11
url: /nl/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Definieert CAD-documenten (Computer Aided Design) die worden gebruikt voor 3D-graphicsbestandsformaten en 2D- of 3D-ontwerpen kunnen bevatten.
Bevat de volgende typen:
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
Meer informatie over CAD‑formaten [hier](../https://wiki.fileformat.com/cad).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format, of Drawing Exchange Format, is een getagde gegevensrepresentatie van een AutoCAD‑tekenbestand. |
|
|  | [Dwg](#Dwg) | DFiles met de DWG‑extensie vertegenwoordigen propriëtaire binaire bestanden die 2D‑ en 3D‑ontwerpgegevens bevatten. |
|
|  | [Dgn](#Dgn) | DGN, Design‑bestanden zijn tekeningen die zijn gemaakt door en ondersteund worden door CAD‑toepassingen zoals MicroStation en Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) vertegenwoordigt 2D/3D‑tekeningen in een gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van ontwerpbestanden. |
|
|  | [Stl](#Stl) | STL, afkorting voor stereolithografie, is een uitwisselbaar bestandsformaat dat 3‑dimensionale oppervlakgeometrie weergeeft. |
|
|  | [Ifc](#Ifc) | Bestanden met de IFC‑extensie verwijzen naar het Industry Foundation Classes (IFC) bestandsformaat dat internationale normen vastlegt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. |
|
|  | [Plt](#Plt) | Het PLT‑bestandsformaat is een vectorgebaseerd plotter‑bestand geïntroduceerd door Autodesk, Inc. |
|
|  | [Igs](#Igs) | Igs‑documentformaat |
|
|  | [Dwt](#Dwt) | Een DWT‑bestand is een AutoCAD‑tekeningssjabloon dat wordt gebruikt als startpunt voor het maken van tekeningen die kunnen worden opgeslagen als DWG‑bestanden. |
|
|  | [Dwfx](#Dwfx) | DWFX‑bestand is een 2D‑ of 3D‑tekening gemaakt met Autodesk CAD‑software. |
|
|  | [Cf2](#Cf2) | Common File Format‑bestand. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Serialisatieconstructor


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, of Drawing Exchange Format, is een getagde gegevensrepresentatie van een AutoCAD‑tekenbestand.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DFiles met de DWG‑extensie vertegenwoordigen propriëtaire binaire bestanden die 2D‑ en 3D‑ontwerpgegevens bevatten. Net als DXF, dat ASCII‑bestanden zijn, vertegenwoordigt DWG het binaire bestandsformaat voor CAD‑(Computer Aided Design) tekeningen.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design‑bestanden zijn tekeningen die zijn gemaakt door en ondersteund worden door CAD‑toepassingen zoals MicroStation en Intergraph Interactive Graphics Design System.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) vertegenwoordigt 2D/3D‑tekeningen in een gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van ontwerpbestanden. Het bevat grafische elementen en tekst als onderdeel van ontwerpgegevens en verkleint de bestandsgrootte dankzij het gecomprimeerde formaat.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, afkorting voor stereolithografie, is een uitwisselbaar bestandsformaat dat 3‑dimensionale oppervlaktegeometrie weergeeft. Het bestandsformaat wordt gebruikt in verschillende vakgebieden zoals rapid prototyping, 3D‑printen en computer‑aided manufacturing.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Bestanden met de extensie IFC verwijzen naar het Industry Foundation Classes (IFC) bestandsformaat dat internationale normen vaststelt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. Dit bestandsformaat biedt interoperabiliteit tussen verschillende softwaretoepassingen.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Het PLT‑bestandsformaat is een vectorgebaseerd plotterbestand geïntroduceerd door Autodesk, Inc. en bevat informatie voor een bepaald CAD‑bestand. Plotdetails vereisen nauwkeurigheid en precisie in de productie, en het gebruik van een PLT‑bestand garandeert dit omdat alle afbeeldingen worden afgedrukt met lijnen in plaats van stippen.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs‑documentformaat


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Een DWT‑bestand is een AutoCAD‑tekeningssjabloon dat wordt gebruikt als startpunt voor het maken van tekeningen die kunnen worden opgeslagen als DWG‑bestanden.
Lees meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX‑bestand is een 2D‑ of 3D‑tekening gemaakt met Autodesk CAD‑software. Het wordt opgeslagen in het DWFx‑formaat, dat vergelijkbaar is met een .DWF‑bestand, maar geformatteerd is met Microsoft’s XML Paper Specification (XPS).


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format‑bestand. CAD‑bestand dat 3D‑pakketontwerpen of andere modelgegevens bevat; kan worden verwerkt en gesneden door een CAD/CAM‑machine, zoals een stansapparaat.


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
