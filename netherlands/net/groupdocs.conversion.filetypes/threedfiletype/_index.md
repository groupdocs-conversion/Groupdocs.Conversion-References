---
title: ThreeDFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert 3Ddocumenten Bevat de volgende typen Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/x Meer informatie over 3Dformatenhierhttps//wiki.fileformat.com/3d .
type: docs
weight: 1060
url: /nl/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definieert 3D-documenten Bevat de volgende typen: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x) Meer informatie over 3D-formaten[hier](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serialisatie-constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstype omschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt huidige object met andere. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Tekenreeksweergave |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Een AMF-bestand bestaat uit richtlijnen voor objectbeschrijving om te worden gebruikt door Additive Manufacturing-processen. Het bevat een openende XML-tag en eindigt met een element. Dit wordt voorafgegaan door een XML-declaratieregel die de XML-versie en codering van het bestand specificeert. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Een bestand met de extensie .ase is een Autodesk ASCII Scene Export-bestandsindeling die een ASCII-representatie is van een scène, die 2D- of 3D-informatie bevat tijdens het exporteren van scènegegevens met behulp van Autodesk. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Een DAE-bestand is een Digital Asset Exchange-bestandsindeling die wordt gebruikt voor het uitwisselen van gegevens tussen interactieve 3D-toepassingen. Deze bestandsindeling is gebaseerd op het COLLADA (COLLAborative Design Activity) XML-schema, een open standaard XML-schema voor de uitwisseling van digitale activa tussen grafische softwaretoepassingen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Een bestand met de extensie .drc is een gecomprimeerd 3D-bestandsformaat gemaakt met de Google Draco-bibliotheek. Google biedt Draco aan als open source-bibliotheek voor het comprimeren en decomprimeren van 3D geometrische mazen en puntenwolken, en verbetert de opslag en overdracht van 3D-afbeeldingen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, is een populair 3D-bestandsformaat dat oorspronkelijk is ontwikkeld door Kaydara voor MotionBuilder. Het werd in 2006 overgenomen door Autodesk Inc en is nu een van de belangrijkste 3D-uitwisselingsformaten zoals gebruikt door veel 3D-tools. FBX is beschikbaar in zowel binaire als ASCII-bestandsindeling. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) is een 3D-bestandsindeling waarin 3D-modelinformatie in JSON-indeling wordt opgeslagen. Het gebruik van JSON minimaliseert zowel de grootte van 3D-assets als de runtime-verwerking die nodig is om die assets uit te pakken en te gebruiken. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) is een efficiënt, industriegericht en flexibel ISO-gestandaardiseerd 3D-gegevensformaat, ontwikkeld door Siemens PLM Software. Mechanische CAD-domeinen van de lucht- en ruimtevaart, de auto-industrie en zwaar materieel gebruiken JT als hun meest toonaangevende 3D-visualisatieformaat. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ-bestanden worden gebruikt door Wavefront's Advanced Visualizer-toepassing om de geometrische objecten te definiëren en op te slaan. Achterwaartse en voorwaartse verzending van geometrische gegevens wordt mogelijk gemaakt door middel van OBJ-bestanden. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, vertegenwoordigt een 3D-bestandsindeling waarin grafische objecten worden opgeslagen die worden beschreven als een verzameling polygonen. Het doel van deze bestandsindeling was om een eenvoudig en gemakkelijk bestandstype tot stand te brengen dat algemeen genoeg is om bruikbaar te zijn voor een breed scala aan modellen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM-gegevensbestanden zijn gerelateerd aan AVEVA PDMS. RVM-bestand is een AVEVA Plant Design Management System Model-projectbestand. AVEVA's Plant Design Management System (PDMS) is het populairste 3D-ontwerpsysteem dat gebruikmaakt van datacentrische technologie voor het beheren van projecten. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Een bestand met de extensie .3ds vertegenwoordigt de 3D Sudio (DOS) mesh-bestandsindeling die wordt gebruikt door Autodesk 3D Studio. Autodesk 3D Studio is sinds 1990 actief op de markt voor 3D-bestandsindelingen en is nu geëvolueerd naar 3D Studio MAX voor het werken met 3D-modellering, animatie en weergave. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, wordt door toepassingen gebruikt om 3D-objectmodellen weer te geven voor een groot aantal andere toepassingen, platforms, services en printers. Het is gebouwd om de beperkingen en problemen in andere 3D-bestandsindelingen, zoals STL, te vermijden voor het werken met de nieuwste versies van 3D-printers. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) is een gecomprimeerde bestandsindeling en gegevensstructuur voor 3D-computergraphics. Het bevat 3D-modelinformatie zoals driehoeksmazen, verlichting, schaduw, bewegingsgegevens, lijnen en punten met kleur en structuur. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Een bestand met de extensie .usd is een Universal Scene Description-bestandsindeling die gegevens codeert met als doel gegevens uit te wisselen en te vergroten tussen toepassingen voor het maken van digitale inhoud. USD, ontwikkeld door Pixar, biedt de mogelijkheid om elementaire activa (zoals modellen) of animatie uit te wisselen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Een bestand met .usdz is een niet-gecomprimeerd en niet-versleuteld ZIP-archief voor de bestandsindeling USD (Universal Scene Description) dat proxy's bevat voor bestanden van andere indelingen (zoals texturen en animaties) die zijn ingesloten in het archief en deze rechtstreeks uitvoert met de USD runtime zonder uitpakken. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | De Virtual Reality Modeling Language (VRML) is een bestandsindeling voor weergave van interactieve 3D-wereldobjecten via het World Wide Web (www). Het wordt gebruikt bij het creëren van driedimensionale weergaven van complexe scènes, zoals illustraties, definities en virtual reality-presentaties. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Een bestand met de extensie .x verwijst naar het oude DirectX 3D Graphics-bestandsformaat dat werd geïntroduceerd met Microsoft DirectX 2.0. Het werd gebruikt voor het weergeven van 3D-afbeeldingen in games en specificeert de structuren voor mazen, texturen, animaties en door de gebruiker gedefinieerde objecten. Het is sinds 2014 verouderd omdat het Autodesk FBX-bestandsformaat beter werkt als een moderner formaat. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/3d/x) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
