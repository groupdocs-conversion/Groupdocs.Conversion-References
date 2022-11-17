---
title: ThreeDFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar 3Ddokument Inkluderar följande typer Fbx./threedfiletype/fbx Lär dig mer om 3Dformathärhttps//wiki.fileformat.com/3d .
type: docs
weight: 940
url: /sv/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definierar 3D-dokument Inkluderar följande typer: [`Fbx`](./fbx) Lär dig mer om 3D-format[här](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | En AMF-fil består av riktlinjer för objektbeskrivning för att kunna användas av Additive Manufacturing-processer. Den innehåller en öppnings-XML-tagg och slutar med ett element. Detta föregås av en XML-deklarationsrad som anger XML-versionen och kodningen av filen. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | En fil med filtillägget .ase är ett Autodesk ASCII Scene Export-filformat som är en ASCII-representation av en scen, som innehåller 2D- eller 3D-information samtidigt som scendata exporteras med Autodesk. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | En DAE-fil är ett Digital Asset Exchange-filformat som används för att utbyta data mellan interaktiva 3D-applikationer. Det här filformatet är baserat på COLLADA (COLLAborative Design Activity) XML-schema som är ett öppet standard-XML-schema för utbyte av digitala tillgångar mellan grafikprogram. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | En fil med filtillägget .drc är ett komprimerat 3D-filformat skapat med Google Draco-bibliotek. Google erbjuder Draco som bibliotek med öppen källkod för att komprimera och dekomprimera geometriska 3D-nät och punktmoln, och förbättrar lagring och överföring av 3D-grafik. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, är ett populärt 3D-filformat som ursprungligen utvecklades av Kaydara för MotionBuilder. Det förvärvades av Autodesk Inc 2006 och är nu ett av de viktigaste 3D-utbytesformaten som används av många 3D-verktyg. FBX är tillgängligt i både binärt och ASCII-filformat. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) är ett 3D-filformat som lagrar 3D-modellinformation i JSON-format. Användningen av JSON minimerar både storleken på 3D-tillgångar och den körtidsbearbetning som krävs för att packa upp och använda dessa tillgångar. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) är ett effektivt, industrifokuserat och flexibelt ISO-standardiserat 3D-dataformat utvecklat av Siemens PLM Software. Mekaniska CAD-domäner inom flyg-, bilindustrin och tung utrustning använder JT som sitt mest ledande 3D-visualiseringsformat. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ-filer används av Wavefronts Advanced Visualizer-applikation för att definiera och lagra de geometriska objekten. Bakåt- och framåtöverföring av geometriska data är möjlig genom OBJ-filer. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, representerar 3D-filformat som lagrar grafiska objekt som beskrivs som en samling polygoner. Syftet med detta filformat var att skapa en enkel och enkel filtyp som är tillräckligt allmän för att vara användbar för ett brett utbud av modeller. Lär dig mer om detta filformat[här](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM-datafiler är relaterade till AVEVA PDMS. RVM-fil är en projektfil för AVEVA Plant Design Management System Model. AVEVAs Plant Design Management System (PDMS) är det mest populära 3D-designsystemet som använder datacentrerad teknologi för att hantera projekt. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | En fil med filtillägget .3ds representerar 3D Sudio (DOS) mesh-filformat som används av Autodesk 3D Studio. Autodesk 3D Studio har funnits på marknaden för 3D-filformat sedan 1990-talet och har nu utvecklats till 3D Studio MAX för att arbeta med 3D-modellering, animering och rendering. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, används av applikationer för att återge 3D-objektmodeller till en mängd andra applikationer, plattformar, tjänster och skrivare. Den byggdes för att undvika begränsningar och problem i andra 3D-filformat, som STL, för att arbeta med de senaste versionerna av 3D-skrivare. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) är ett komprimerat filformat och datastruktur för 3D-datorgrafik. Den innehåller 3D-modellinformation som triangelnät, belysning, skuggning, rörelsedata, linjer och punkter med färg och struktur. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | En fil med filtillägget .usd är ett filformat för universell scenbeskrivning som kodar data i syfte att datautbyte och utöka mellan applikationer för att skapa digitalt innehåll. Utvecklat av Pixar ger USD möjligheten att byta ut elementära tillgångar (som modeller) eller animering. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | En fil med .usdz är ett okomprimerat och okrypterat ZIP-arkiv för filformatet USD (Universal Scene Description) som innehåller och proxyservrar för filer av andra format (som texturer och animationer) inbäddade i arkivet och kör dem direkt med USD körtid utan att behöva packa upp. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | The Virtual Reality Modeling Language (VRML) är ett filformat för representation av interaktiva 3D-världsobjekt över World Wide Web (www). Den finner sin användning i att skapa tredimensionella representationer av komplexa scener som illustrationer, definitioner och presentationer av virtuell verklighet. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | En fil med filtillägget .x hänvisar till det äldre filformatet DirectX 3D Graphics som introducerades med Microsoft DirectX 2.0. Den användes för 3D-grafikrendering i spel och specificerar strukturerna för maskor, texturer, animationer och användardefinierade objekt. Det har blivit utfasat sedan 2014 eftersom Autodesk FBX-filformatet fungerar bättre som ett modernare format. Läs mer om detta filformat[här](https://docs.fileformat.com/3d/x) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
