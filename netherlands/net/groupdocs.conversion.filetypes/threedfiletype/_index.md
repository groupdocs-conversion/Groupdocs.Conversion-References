---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert 3D-documenten Bevat de volgende typen Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Meer informatie over 3D-formaten hierhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /nl/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definieert 3D-documenten Bevat de volgende typen: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Meer informatie over 3D-formaten [hier](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialisatie‑constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Een AMF-bestand bestaat uit richtlijnen voor objectbeschrijvingen om te worden gebruikt door Additive Manufacturing-processen. Het bevat een openings‑XML‑tag en eindigt met een element. Dit wordt voorafgegaan door een XML‑declaratielijn die de XML‑versie en codering van het bestand specificeert. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Een bestand met de extensie .ase is een Autodesk ASCII Scene Export-bestandsformaat dat een ASCII‑representatie van een scène is, met 2D‑ of 3D‑informatie bij het exporteren van scenedata met Autodesk. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Een DAE-bestand is een Digital Asset Exchange-bestandsformaat dat wordt gebruikt voor het uitwisselen van gegevens tussen interactieve 3D‑applicaties. Dit bestandsformaat is gebaseerd op het COLLADA (COLLAborative Design Activity) XML‑schema, een open standaard XML‑schema voor de uitwisseling van digitale assets tussen grafische softwaretoepassingen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Een bestand met de extensie .drc is een gecomprimeerd 3D‑bestandsformaat gemaakt met de Google Draco‑bibliotheek. Google biedt Draco aan als open‑source‑bibliotheek voor het comprimeren en decomprimeren van 3D‑geometrische meshes en puntwolken, en verbetert de opslag en transmissie van 3D‑graphics. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, is een populair 3D‑bestandsformaat dat oorspronkelijk werd ontwikkeld door Kaydara voor MotionBuilder. Het werd in 2006 overgenomen door Autodesk Inc en is nu een van de belangrijkste 3D‑uitwisselingsformaten die door veel 3D‑tools worden gebruikt. FBX is beschikbaar in zowel binair als ASCII‑bestandsformaat. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB is de binaire bestandsformaatrepresentatie van 3D‑modellen opgeslagen in het GL Transmission Format (glTF). Dit binaire formaat slaat de glTF‑asset (JSON, .bin en afbeeldingen) op in een binaire blob. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) is een 3D‑bestandsformaat dat 3D‑modelinformatie opslaat in JSON‑formaat. Het gebruik van JSON minimaliseert zowel de grootte van 3D‑assets als de runtime‑verwerking die nodig is om die assets uit te pakken en te gebruiken. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) is een efficiënt, op de industrie gericht en flexibel ISO‑gestandaardiseerd 3D‑dataformaat ontwikkeld door Siemens PLM Software. Mechanische CAD‑domeinen in de lucht‑ en ruimtevaart, de auto‑industrie en zware apparatuur gebruiken JT als hun toonaangevende 3D‑visualisatieformaat. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | Een bestand met de extensie .ma is een 3D‑projectbestand gemaakt met de Autodesk Maya‑applicatie. Het bevat een lange lijst met tekstuele commando's om informatie over het bestand te specificeren. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | Een bestand met de extensie .mb is een binair projectbestand dat is gemaakt met de Autodesk Maya-toepassing. In tegenstelling tot het MA-bestandsformaat, dat in ASCII-indeling is, worden MB-bestanden opgeslagen in binaire indeling. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ-bestanden worden gebruikt door de Advanced Visualizer-toepassing van Wavefront om geometrische objecten te definiëren en op te slaan. Voorwaartse en achterwaartse overdracht van geometrische gegevens is mogelijk gemaakt via OBJ-bestanden. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, is een 3D-bestandsformaat dat grafische objecten opslaat die worden beschreven als een verzameling polygonen. Het doel van dit bestandsformaat was om een eenvoudig en gemakkelijk type bestand te creëren dat algemeen genoeg is om bruikbaar te zijn voor een breed scala aan modellen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM-gegevensbestanden zijn gerelateerd aan AVEVA PDMS. Een RVM-bestand is een projectbestand van het AVEVA Plant Design Management System Model. Het Plant Design Management System (PDMS) van AVEVA is het meest populaire 3D-ontwerpsysteem dat datacentric technologie gebruikt voor projectbeheer. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Een bestand met de extensie .3ds vertegenwoordigt het 3D Sudio (DOS) mesh-bestandsformaat dat wordt gebruikt door Autodesk 3D Studio. Autodesk 3D Studio is sinds de jaren 90 actief op de 3D-bestandsformaatmarkt en is inmiddels geëvolueerd naar 3D Studio MAX voor 3D-modellering, animatie en rendering. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, wordt door toepassingen gebruikt om 3D-objectmodellen te renderen naar diverse andere toepassingen, platforms, services en printers. Het is ontwikkeld om de beperkingen en problemen van andere 3D-bestandsformaten, zoals STL, te vermijden bij het werken met de nieuwste versies van 3D-printers. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) is een gecomprimeerd bestandsformaat en datastructuur voor 3D-computergraphics. Het bevat 3D-modelinformatie zoals driehoeksmesh‑s, verlichting, schaduwen, bewegingsdata, lijnen en punten met kleur en structuur. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Een bestand met de extensie .usd is een Universal Scene Description-bestandsformaat dat gegevens codeert voor het uitwisselen en verrijken tussen toepassingen voor digitale contentcreatie. Ontwikkeld door Pixar, biedt USD de mogelijkheid om elementaire assets (zoals modellen) of animaties uit te wisselen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Een bestand met .usdz is een niet‑gecomprimeerd en niet‑versleuteld ZIP‑archief voor het USD (Universal Scene Description)-bestandsformaat dat bestanden van andere formaten (zoals textures en animaties) bevat en als proxy dient, ingebed in het archief, en ze direct uitvoert met de USD-runtime zonder dat uitpakken nodig is. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | De Virtual Reality Modeling Language (VRML) is een bestandsformaat voor de weergave van interactieve 3D-wereldobjecten op het World Wide Web (www). Het wordt gebruikt voor het maken van driedimensionale weergaven van complexe scènes, zoals illustraties, definities en virtual‑reality‑presentaties. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Een bestand met de extensie .x verwijst naar het legacy DirectX 3D Graphics-bestandsformaat dat werd geïntroduceerd met Microsoft DirectX 2.0. Het werd gebruikt voor 3D-graphics rendering in games en specificeert de structuren voor meshes, textures, animaties en door de gebruiker gedefinieerde objecten. Het is sinds 2014 verouderd omdat het Autodesk FBX‑bestandsformaat beter voldoet als een moderner formaat. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/3d/x). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
