---
title: "GisFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar GIS-dokument. Inkluderar följande filtyper Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /sv/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Definierar GIS-dokument. Inkluderar följande filtyper: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GisFileType](gisfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | ESRI‑fil Geodatabase (FileGDB) är en samling filer i en mapp på disk som innehåller relaterade geospatiala data såsom funktionsdatamängder, funktionsklasser och tillhörande tabeller. Den kräver att vissa andra filer hålls bredvid .gdb‑filen i samma katalog för att fungera. Läs mer om detta filformat [här](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON är ett JSON‑baserat format utformat för att representera geografiska funktioner med deras icke‑rumsliga attribut. Detta format definierar olika JSON‑objekt (JavaScript Object Notation) och hur de kombineras. JSON‑formatet representerar samlad information om de geografiska funktionerna, deras rumsliga utbredning och egenskaper. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence är en ström av oberoende GeoJSON‑poster snarare än ett omslutande dokument, där varje post avgränsas av en radbrytning eller av kontrolltecknet RS. Den används för flöden som kompletteras över tid, där slutet på samlingen inte är känt när skrivandet påbörjas. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML står för Geography Markup Language och är baserat på XML‑specifikationer utvecklade av Open Geospatial Consortium (OGC). Formatet används för att lagra geografiska datafunktioner för utbyte mellan olika filformat. Det fungerar som ett modelleringsspråk för geografiska system samt ett öppet utbytesformat för geografiska transaktioner på internet. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Filer med GPX‑ändelse representerar GPS Exchange‑formatet för utbyte av GPS‑data mellan applikationer och webbtjänster på internet. Det är ett lättviktigt XML‑filformat som innehåller GPS‑data, t.ex. waypoints, rutter och spår, som kan importeras och läsas av flera program. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) innehåller geospatial information i XML‑notation. Filer sparade som KML kan öppnas i Geographic Information System (GIS)-applikationer förutsatt att de stöder det. Många applikationer har börjat stödja KML‑filformatet efter att det antagits som internationell standard. KML använder en taggbaserad struktur med nästlade element och attribut. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ är ett ZIP‑arkiv som bär ett KML‑dokument, enligt konventionen namngivet doc.kml i arkivets rot, tillsammans med alla resurser som dokumentet refererar till. Att komprimera markupen är poängen: ett KML‑flöde av vilken storlek som helst krymper dramatiskt, vilket är varför utgivare distribuerar KMZ snarare än KML. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | OSM‑filformatet är ett strukturerat dataformat som används för att lagra geografisk data i OpenStreetMap‑projektet. OSM‑filer är vanligtvis i XML‑format och innehåller information såsom placeringen av vägar, byggnader, intressanta punkter och andra funktioner på kartan. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP är filändelsen för en av de primära filtyperna som används för representation av ESRI Shapefile. Den representerar geospatial information i form av vektordata som ska användas av Geographic Information Systems (GIS)-applikationer. Läs mer om detta filformat [här](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON är en utökning av GeoJSON som kodar topologi. Istället för att representera geometrier separat, sys geometrier i TopoJSON‑filer ihop från delade linjesegment som kallas arcs. |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
