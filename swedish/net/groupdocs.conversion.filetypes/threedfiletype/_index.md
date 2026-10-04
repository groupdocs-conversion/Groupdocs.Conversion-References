---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar 3D-dokument. Inkluderar följande typer Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb. Läs mer om 3D-format härhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /sv/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definierar 3D-dokument. Inkluderar följande typer: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Läs mer om 3D-format [här](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | En AMF-fil består av riktlinjer för objektsbeskrivning för att kunna användas av additiv tillverkning. Den innehåller en öppnings‑XML‑tagg och avslutas med ett element. Detta föregås av en XML‑deklarationsrad som specificerar XML‑versionen och kodningen för filen. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | En fil med .ase‑tillägg är ett Autodesk ASCII Scene Export‑filformat som är en ASCII‑representation av en scen, innehållande 2D‑ eller 3D‑information vid export av scendata med Autodesk. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | En DAE‑fil är ett Digital Asset Exchange‑filformat som används för att utbyta data mellan interaktiva 3D‑applikationer. Detta filformat är baserat på COLLADA (COLLAborative Design Activity)‑XML‑schemat, som är ett öppet standard‑XML‑schema för utbyte av digitala tillgångar mellan grafikprogramvaror. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | En fil med .drc‑tillägg är ett komprimerat 3D‑filformat skapat med Google Draco‑biblioteket. Google erbjuder Draco som ett öppen‑källkodsbibliotek för komprimering och dekomprimering av 3D‑geometriska nät och punktmoln, och förbättrar lagring och överföring av 3D‑grafik. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, är ett populärt 3D‑filformat som ursprungligen utvecklades av Kaydara för MotionBuilder. Det förvärvades av Autodesk Inc år 2006 och är nu ett av de viktigaste 3D‑utbytesformaten som används av många 3D‑verktyg. FBX finns både i binärt och ASCII‑filformat. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB är den binära filformatrepresentationen av 3D‑modeller sparade i GL Transmission Format (glTF). Detta binära format lagrar glTF‑tillgången (JSON, .bin och bilder) i en binär blob. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) är ett 3D‑filformat som lagrar 3D‑modellinformation i JSON‑format. Användningen av JSON minskar både storleken på 3D‑tillgångar och den körningstid som behövs för att packa upp och använda dessa tillgångar. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) är ett effektivt, branschfokuserat och flexibelt ISO‑standardiserat 3D‑dataformat utvecklat av Siemens PLM Software. Mekaniska CAD‑områden inom flyg, bilindustri och tung utrustning använder JT som sitt främsta 3D‑visualiseringsformat. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | En fil med .ma‑tillägg är en 3D‑projektfil skapad med Autodesk Maya‑applikationen. Den innehåller en stor lista med textkommandon för att specificera information om filen. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | En fil med .mb‑tillägg är en binär projektfil skapad med Autodesk Maya‑applikationen. Till skillnad från MA‑filformatet, som är i ASCII‑filformat, lagras MB‑filer i binärt filformat. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ-filer används av Wavefronts Advanced Visualizer‑applikation för att definiera och lagra de geometriska objekten. Bakåt- och framåtriktad överföring av geometrisk data möjliggörs genom OBJ-filer. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, representerar ett 3D‑filformat som lagrar grafiska objekt beskrivna som en samling polygoner. Syftet med detta filformat var att skapa en enkel och lätt filtyp som är tillräckligt generell för att vara användbar för ett brett spektrum av modeller. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM‑datafiler är relaterade till AVEVA PDMS. RVM‑filen är en AVEVA Plant Design Management System Model‑projektfil. AVEVAs Plant Design Management System (PDMS) är det mest populära 3D‑designsystemet som använder datacentric teknik för att hantera projekt. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | En fil med .3ds‑ändelse representerar 3D Sudio (DOS) mesh‑filformat som används av Autodesk 3D Studio. Autodesk 3D Studio har varit på 3D‑filformatmarknaden sedan 1990‑talen och har nu utvecklats till 3D Studio MAX för arbete med 3D‑modellering, animation och rendering. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, används av applikationer för att rendera 3D‑objektmodeller till en mängd andra applikationer, plattformar, tjänster och skrivare. Det skapades för att undvika begränsningar och problem i andra 3D‑filformat, som STL, när man arbetar med de senaste versionerna av 3D‑skrivare. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) är ett komprimerat filformat och datastruktur för 3D‑datorgrafik. Det innehåller 3D‑modellinformation såsom triangulära meshar, belysning, skuggning, rörelsedata, linjer och punkter med färg och struktur. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | En fil med .usd‑ändelse är ett Universal Scene Description‑filformat som kodar data för att möjliggöra datautbyte och förstärkning mellan applikationer för digitalt innehållsskapande. Utvecklat av Pixar ger USD möjlighet att utbyta elementära tillgångar (såsom modeller) eller animation. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | En fil med .usdz är ett okomprimerat och okrypterat ZIP‑arkiv för USD (Universal Scene Description)-filformatet som innehåller och proxyar filer av andra format (såsom texturer och animationer) inbäddade i arkivet och kör dem direkt med USD‑körningsmiljön utan behov av uppackning. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Den Virtual Reality Modeling Language (VRML) är ett filformat för representation av interaktiva 3D‑världsobjekt på World Wide Web (www). Det används för att skapa tredimensionella representationer av komplexa scener såsom illustrationer, definitioner och virtuella verklighetspresentationer. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | En fil med .x‑tillägg avser DirectX 3D Graphics äldre filformat som introducerades med Microsoft DirectX 2.0. Den användes för 3D‑grafikrendering i spel och specificerar strukturerna för mesh‑nät, texturer, animationer och användardefinierade objekt. Den har varit föråldrad sedan 2014 eftersom Autodesk FBX‑filformatet fungerar bättre som ett mer modernt format. Läs mer om detta filformat [här](https://docs.fileformat.com/3d/x). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
