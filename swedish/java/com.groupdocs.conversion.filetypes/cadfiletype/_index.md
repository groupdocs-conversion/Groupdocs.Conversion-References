---
title: "CadFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar CAD‑dokument (Computer Aided Design) som används för 3D‑grafikfilformat och kan innehålla 2D‑ eller 3D‑designer."
type: docs
weight: 11
url: /sv/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Definierar CAD-dokument (Computer Aided Design) som används för 3D-grafikfilformat och kan innehålla 2D- eller 3D-design.
Inkluderar följande typer:
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
Läs mer om CAD‑format [här](../https://wiki.fileformat.com/cad).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format, eller Drawing Exchange Format, är en taggad datarapresentation av AutoCAD‑ritningsfil. |
|
|  | [Dwg](#Dwg) | Filer med DWG‑ändelse representerar proprietära binära filer som används för att innehålla 2D‑ och 3D‑designdata. |
|
|  | [Dgn](#Dgn) | DGN, Design, filer är ritningar skapade av och stöds av CAD‑applikationer såsom MicroStation och Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) representerar 2D/3D‑ritningar i komprimerat format för visning, granskning eller utskrift av designfiler. |
|
|  | [Stl](#Stl) | STL, förkortning för stereolitografi, är ett utbytbart filformat som representerar tredimensionell ytgometri. |
|
|  | [Ifc](#Ifc) | Filer med IFC‑ändelse hänvisar till Industry Foundation Classes (IFC) filformat som fastställer internationella standarder för import och export av byggnadsobjekt och deras egenskaper. |
|
|  | [Plt](#Plt) | PLT‑filformatet är en vektorbaserad plotterfil introducerad av Autodesk, Inc. |
|
|  | [Igs](#Igs) | Igs-dokumentformat |
|
|  | [Dwt](#Dwt) | En DWT‑fil är en AutoCAD‑ritningsmall som används som utgångspunkt för att skapa ritningar som kan sparas som DWG‑filer. |
|
|  | [Dwfx](#Dwfx) | DWFX‑fil är en 2D‑ eller 3D‑ritning skapad med Autodesk CAD‑programvara. |
|
|  | [Cf2](#Cf2) | Common File Format‑fil. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Serialiseringskonstruktor


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, eller Drawing Exchange Format, är en taggad datarapresentation av AutoCAD‑ritningsfil.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


Filer med DWG‑ändelse representerar proprietära binära filer som används för att innehålla 2D‑ och 3D‑designdata. Till skillnad från DXF, som är ASCII‑filer, representerar DWG det binära filformatet för CAD‑ritningar (Computer Aided Design).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design, filer är ritningar skapade av och stöds av CAD‑applikationer såsom MicroStation och Intergraph Interactive Graphics Design System.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) representerar 2D/3D-ritningar i komprimerat format för visning, granskning eller utskrift av designfiler. Det innehåller grafik och text som en del av designdata och minskar filens storlek på grund av dess komprimerade format.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, förkortning för stereolitografi, är ett utbytbart filformat som representerar tredimensionell ytgometri. Filformatet används inom flera områden såsom snabb prototypframtagning, 3D-utskrift och datorstödd tillverkning.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Filer med filändelsen IFC hänvisar till Industry Foundation Classes (IFC)-filformatet som fastställer internationella standarder för import och export av byggnadsobjekt och deras egenskaper. Detta filformat möjliggör interoperabilitet mellan olika mjukvaruapplikationer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


PLT-filformatet är en vektorbaserad plotterfil som introducerades av Autodesk, Inc. och innehåller information för en viss CAD-fil. Plottdetaljer kräver noggrannhet och precision i produktionen, och användning av PLT-filer garanterar detta eftersom alla bilder skrivs ut med linjer istället för punkter.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Igs-dokumentformat


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


En DWT‑fil är en AutoCAD‑ritningsmall som används som utgångspunkt för att skapa ritningar som kan sparas som DWG‑filer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


DWFX-filen är en 2D- eller 3D-ritning skapad med Autodesk CAD-programvara. Den sparas i DWFx-formatet, som liknar en .DWF-fil, men är formaterad med Microsofts XML Paper Specification (XPS).


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Common File Format-fil. CAD-fil som innehåller 3D-paketdesigner eller annan modelldata; kan bearbetas och skäras av en CAD/CAM-maskin, såsom en stansmaskin.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
