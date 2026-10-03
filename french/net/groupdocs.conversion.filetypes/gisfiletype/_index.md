---
title: "GisFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les documents GIS. Inclut les types de fichiers suivants Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /fr/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Définit les documents GIS. Inclut les types de fichiers suivants : [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GisFileType](gisfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | Le Geodatabase de fichiers ESRI (FileGDB) est une collection de fichiers dans un dossier sur disque qui contient des données géospatiales liées telles que des ensembles de jeux de données, des classes d'entités et des tables associées. Il nécessite certains autres fichiers à être conservés à côté du fichier .gdb dans le même répertoire pour fonctionner. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON est un format basé sur JSON conçu pour représenter les entités géographiques avec leurs attributs non spatiaux. Ce format définit différents objets JSON (JavaScript Object Notation) et leur mode d'association. Le format JSON représente des informations collectives sur les entités géographiques, leurs étendues spatiales et leurs propriétés. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | GeoJSON Text Sequence est un flux d'enregistrements GeoJSON indépendants plutôt qu'un document unique englobant, chaque enregistrement étant délimité par un saut de ligne ou par le caractère de contrôle RS. Il est utilisé pour des flux qui sont augmentés au fil du temps, où la fin de la collection n'est pas connue au moment du démarrage de l'écriture. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML signifie Geography Markup Language, qui est basé sur des spécifications XML développées par l'Open Geospatial Consortium (OGC). Le format est utilisé pour stocker des entités de données géographiques afin de les échanger entre différents formats de fichiers. Il sert de langage de modélisation pour les systèmes géographiques ainsi que de format d'échange ouvert pour les transactions géographiques sur Internet. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Les fichiers avec l'extension GPX représentent le format d'échange GPS pour l'échange de données GPS entre applications et services web sur Internet. C'est un format de fichier XML léger qui contient des données GPS, c'est-à-dire des points de passage, des itinéraires et des traces à importer et à lire par plusieurs programmes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | KML (Keyhole Markup Language) contient des informations géospatiales en notation XML. Les fichiers enregistrés au format KML peuvent être ouverts dans des applications de système d'information géographique (SIG) à condition qu'elles le supportent. De nombreuses applications ont commencé à prendre en charge le format de fichier KML après son adoption comme norme internationale. KML utilise une structure basée sur des balises avec des éléments et attributs imbriqués. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | KMZ est une archive ZIP contenant un document KML, généralement nommé doc.kml à la racine de l'archive, ainsi que toutes les ressources auxquelles le document fait référence. La compression du balisage est l'objectif : un flux KML de n'importe quelle taille se réduit considérablement, ce qui explique pourquoi les éditeurs distribuent des KMZ plutôt que des KML. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Le format de fichier OSM est un format de données structuré utilisé pour stocker des données géographiques dans le projet OpenStreetMap. Les fichiers OSM sont généralement au format XML et contiennent des informations telles que l'emplacement des routes, des bâtiments, des points d'intérêt et d'autres caractéristiques de la carte. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | SHP est l'extension de fichier pour l'un des principaux types de fichiers utilisés pour la représentation du Shapefile ESRI. Il représente des informations géospatiales sous forme de données vectorielles à utiliser par les applications de systèmes d'information géographique (SIG). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | TopoJSON est une extension de GeoJSON qui encode la topologie. Plutôt que de représenter les géométries de manière distincte, les géométries dans les fichiers TopoJSON sont assemblées à partir de segments de ligne partagés appelés arcs. |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
