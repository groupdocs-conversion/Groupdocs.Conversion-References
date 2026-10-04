---
title: "GisFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert GIS‑documenten. Bevat de volgende bestandstypen Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /nl/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Definieert GIS‑documenten. Bevat de volgende bestandstypen: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GisFileType](gisfiletype)() | Serialisatie‑constructor |

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
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI‑bestand Geodatabase (FileGDB) is een verzameling bestanden in een map op schijf die gerelateerde georuimtelijke gegevens bevatten, zoals feature‑datasets, feature‑klassen en bijbehorende tabellen. Het vereist dat bepaalde andere bestanden naast het .gdb‑bestand in dezelfde map worden bewaard om te kunnen functioneren. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON is een op JSON gebaseerd formaat dat is ontworpen om geografische kenmerken met hun niet‑ruimtelijke attributen weer te geven. Dit formaat definieert verschillende JSON (JavaScript Object Notation)-objecten en hun samenvoegingswijze. Het JSON‑formaat vertegenwoordigt een verzamelde informatie over de geografische kenmerken, hun ruimtelijke omvang en eigenschappen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence is een stroom van onafhankelijke GeoJSON‑records in plaats van één omvattend document, waarbij elk record wordt gescheiden door een regeleinde of door het RS‑besturingskarakter. Het wordt gebruikt voor feeds die in de loop van de tijd worden aangevuld, waarbij het einde van de collectie niet bekend is wanneer het schrijven begint. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML staat voor Geography Markup Language en is gebaseerd op XML‑specificaties ontwikkeld door het Open Geospatial Consortium (OGC). Het formaat wordt gebruikt om geografische gegevenskenmerken op te slaan voor uitwisseling tussen verschillende bestandsformaten. Het dient zowel als modellerings­taal voor geografische systemen als een open uitwisselingsformaat voor geografische transacties op internet. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Bestanden met de .gpx-extensie vertegenwoordigen het GPS Exchange‑formaat voor uitwisseling van GPS‑gegevens tussen applicaties en webservices op internet. Het is een lichtgewicht XML‑bestandformaat dat GPS‑gegevens bevat, zoals waypoints, routes en tracks, die door meerdere programma’s geïmporteerd en gelezen kunnen worden. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) bevat georuimtelijke informatie in XML-notatie. Bestanden die als KML zijn opgeslagen kunnen worden geopend in Geographic Information System (GIS)-applicaties, mits ze dit ondersteunen. Veel applicaties zijn begonnen met het bieden van ondersteuning voor het KML‑bestandformaat nadat het is aangenomen als internationale standaard. KML maakt gebruik van een tag‑gebaseerde structuur met geneste elementen en attributen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ is een ZIP-archief dat een KML-document bevat, bij conventie genaamd doc.kml in de hoofdmap van het archief, samen met alle bronnen waar het document naar verwijst. Het comprimeren van de markup is het doel: een KML-feed van elke grootte krimpt drastisch, wat de reden is dat uitgevers KMZ distribueren in plaats van KML. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Het OSM-bestandsformaat is een gestructureerd gegevensformaat dat wordt gebruikt om geografische data op te slaan in het OpenStreetMap-project. OSM-bestanden zijn doorgaans in XML-formaat en bevatten informatie zoals de locatie van wegen, gebouwen, bezienswaardigheden en andere kenmerken op de kaart. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP is de bestandsextensie voor een van de primaire bestandstypen die worden gebruikt voor de weergave van ESRI Shapefile. Het vertegenwoordigt georuimtelijke informatie in de vorm van vectorgegevens die door Geographic Information Systems (GIS)-toepassingen worden gebruikt. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON is een uitbreiding van GeoJSON die topologie codeert. In plaats van geometrieën afzonderlijk weer te geven, worden geometrieën in TopoJSON-bestanden aan elkaar gekoppeld vanuit gedeelde lijnsegmenten die arcs worden genoemd. |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
