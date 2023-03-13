---
title: DiagramFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar diagramdokument. Inkluderar följande typer Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 900
url: /sv/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definierar diagramdokument. Inkluderar följande typer: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialiseringskonstruktor |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW är filformatet Visio Graphics Service som anger de strömmar och lagringar som krävs för att rendera en webbritning. Läs mer om detta filformat[här](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Alla ritningar eller diagram skapade i Microsoft Visio, men sparade i XML-format, har filtillägget .VDX. En Visio-ritnings-XML-fil skapas i Visio-programvaran, som är utvecklad av Microsoft. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD-filer är ritningar skapade med Microsoft Visio-applikationen för att representera olika grafiska objekt och kopplingen mellan dessa. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Filer med VSDM-tillägg är ritfiler skapade med Microsoft Visio-applikationen som stöder makron. VSDM-filer är OPC/XML-ritningar som liknar VSDX, men som också ger möjlighet att köra makron när filen öppnas. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Filer med filtillägget .VSDX representerar filformatet Microsoft Visio som introducerats från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöds av tidigare versioner av Microsoft Visio. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS är stencilfiler skapade med Microsoft Visio 2007 och tidigare. Stencilfiler tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio-ritning. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Filer med filtillägget .VSSM är Microsoft Visio Stencil-filer som stöder ger stöd för makron. En VSSM-fil när den öppnas gör det möjligt att köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Filer med tillägget .VSSX är ritschabloner skapade med Microsoft Visio 2013 och senare. VSSX-filformatet kan öppnas med Visio 2013 och högre. Visio-filer är kända för representation av en mängd olika ritningselement som samling av former, kopplingar, flödesscheman, nätverkslayout, UML-diagram, Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Filer med VST-tillägg är vektorbildfiler skapade med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Dessa mallfiler är i binärt filformat och innehåller standardlayout och inställningar som används för att skapa nya Visio-ritningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Filer med VSTM-tillägg är mallfiler skapade med Microsoft Visio som stöder makron. Till skillnad från VSDX-filer kan filer skapade från VSTM-mallar köra makron som är utvecklade i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Filer med VSTX-tillägg är ritmallsfiler skapade med Microsoft Visio 2013 och senare. Dessa VSTX-filer ger en startpunkt för att skapa Visio-ritningar, sparade som .VSDX-filer, med standardlayout och inställningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Filer med filtillägget .VSX avser schabloner som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX-filer sparas i XML-filformat och stöddes till Visio 2013. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | En fil med VTX-tillägg är en Microsoft Visio-ritmall som sparas på skiva i XML-filformat. Mallen syftar till att tillhandahålla en fil med grundläggande inställningar som kan användas för att skapa flera Visio-filer med samma inställningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vtx) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
