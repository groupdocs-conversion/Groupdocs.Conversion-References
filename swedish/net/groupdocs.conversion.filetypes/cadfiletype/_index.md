---
title: CadFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar CADdokument Computer Aided Design som används för 3Dgrafikfilformat och kan innehålla 2D eller 3Ddesign. Innehåller följande typer Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Läs mer om CADformathärhttps//wiki.fileformat.com/cad .
type: docs
weight: 800
url: /sv/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Definierar CAD-dokument (Computer Aided Design) som används för 3D-grafikfilformat och kan innehålla 2D- eller 3D-design. Innehåller följande typer: [`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Läs mer om CAD-format[här](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CadFileType](cadfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypsbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filtillägget |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format File. CAD-fil som innehåller 3D-paketdesigner eller annan modelldata; kan bearbetas och skäras av en CAD/CAM-maskin, såsom en stansanordning. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, filer är ritningar skapade av och stöds av CAD-applikationer som MicroStation och Intergraph Interactive Graphics Design System. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) representerar 2D/3D-ritning i komprimerat format för att visa, granska eller skriva ut designfiler. Den innehåller grafik och text som en del av designdata och minskar storleken på filen på grund av dess komprimerade format. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX-fil är en 2D- eller 3D-ritning skapad med Autodesk CAD-programvara. Den sparas i DWFx-formatet, som liknar en . DWF-fil, men är formaterad med Microsofts XML Paper Specification (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Filer med DWG-tillägg representerar proprietära binära filer som används för att innehålla 2D- och 3D-designdata. Liksom DXF, som är ASCII-filer, representerar DWG det binära filformatet för CAD-ritningar (Computer Aided Design). Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | En DWT-fil är en AutoCAD ritmallsfil som används som start för att skapa ritningar som kan sparas som DWG-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format eller Drawing Exchange Format, är en taggat datarepresentation av AutoCAD-ritningsfil. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Filer med IFC-tillägg hänvisar till filformatet Industry Foundation Classes (IFC) som fastställer internationella standarder för att importera och exportera byggnadsobjekt och deras egenskaper. Detta filformat ger interoperabilitet mellan olika programvaror. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs-dokumentformat |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT-filformatet är en vektorbaserad plotterfil som introducerats av Autodesk, Inc. och innehåller information för en viss CAD-fil. Plottdetaljer kräver noggrannhet och precision i produktionen, och användning av PLT-fil garanterar detta eftersom alla bilder skrivs ut med linjer istället för prickar. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, förkortning för stereolitrografi, är ett utbytbart filformat som representerar 3-dimensionell ytgeometri. Filformatet finner sin användning inom flera områden som snabb prototypframställning, 3D-utskrift och datorstödd tillverkning. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/stl) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
