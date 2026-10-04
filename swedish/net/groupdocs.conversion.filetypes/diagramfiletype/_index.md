---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar Diagram-dokument. Inkluderar följande typer Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /sv/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Definierar Diagram-dokument. Inkluderar följande typer: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | En fil med DRAWIO-extension är ett diagram skapat med diagrams.net (tidigare draw.io). Den lagras i XML-filformat med mxfile-rootelementet och innehåller innehållet och formateringen av diagrammets element såsom text, bilder, layout, former och positionering. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | En fil med MMD-extension är ett diagram skrivet i Mermaid-markeringsspråket. Den lagras som ett vanligt textdokument som börjar med diagramdeklarationen, såsom flowchart eller sequenceDiagram, följt av definitionen av noderna och anslutningarna mellan dem. Läs mer om detta filformat [här](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW är Visio Graphics Service-filformatet som specificerar de strömmar och lagringar som krävs för att rendera en webbritning. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Alla ritningar eller diagram som skapats i Microsoft Visio, men sparats i XML-format har .VDX-extension. En Visio-ritnings-XML-fil skapas i Visio-programvaran, som utvecklats av Microsoft. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD-filer är ritningar som skapats med Microsoft Visio‑applikationen för att representera en mängd grafiska objekt och deras sammankoppling. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Filer med VSDM‑extension är ritningsfiler som skapats med Microsoft Visio‑applikationen och som stöder makron. VSDM‑filer är OPC/XML‑ritningar som liknar VSDX, men ger också möjlighet att köra makron när filen öppnas. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Filer med .VSDX‑extension representerar Microsoft Visio‑filformatet som introducerades från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöds av tidigare versioner av Microsoft Visio. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS är stencil‑filer som skapats med Microsoft Visio 2007 och tidigare. Stencil‑filer tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio‑ritning. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Filer med .VSSM‑extension är Microsoft Visio‑stencil‑filer som ger stöd för makron. En VSSM‑fil som öppnas tillåter att köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Filer med .VSSX‑extension är ritningsstencil‑filer som skapats med Microsoft Visio 2013 och senare. VSSX‑filformatet kan öppnas med Visio 2013 och senare. Visio‑filer är kända för att representera en mängd ritningselement såsom samlingar av former, anslutningar, flödesscheman, nätverkslayouter, UML‑diagram. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Filer med VST‑extension är vektorbildfiler som skapats med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Dessa mallfiler är i binärt filformat och innehåller standardlayouten och -inställningarna som används för att skapa nya Visio‑ritningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Filer med VSTM‑extension är mallfiler som skapats med Microsoft Visio och som stöder makron. Till skillnad från VSDX‑filer kan filer som skapats från VSTM‑mallar köra makron som utvecklats i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Filer med VSTX‑extension är ritningsmall‑filer som skapats med Microsoft Visio 2013 och senare. Dessa VSTX‑filer ger en startpunkt för att skapa Visio‑ritningar, sparade som .VSDX‑filer, med standardlayout och -inställningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Filer med .VSX‑extension avser stencil‑filer som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX‑filer sparas i XML‑filformat och stöddes fram till Visio 2013. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | En fil med VTX‑extension är en Microsoft Visio‑ritmall som sparas på disk i XML‑filformat. Mallen är avsedd att tillhandahålla en fil med grundinställningar som kan användas för att skapa flera Visio‑filer med samma inställningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vtx). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
