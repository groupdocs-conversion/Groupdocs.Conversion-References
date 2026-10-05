---
title: "Classe GisFileType"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Les définitions des types de documents GIS."
type: docs
url: /fr/python-net/groupdocs.conversion.filetypes/gisfiletype/
is_root: false
weight: 110
---


## GisFileType class

Les définitions des types de documents GIS.

Inclut les types de fichiers suivants : [`GisFileType.shp`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/), [`GisFileType.geo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/), [`GisFileType.gdb`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/), [`GisFileType.gml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/), [`GisFileType.kml`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/), [`GisFileType.gpx`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/), [`GisFileType.topo_json`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/), [`GisFileType.osm`](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/).

Le type GisFileType expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/__init__/) | Initialise un GisFileType pour la sérialisation. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Compare l'objet actuel à un autre. (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implémente la comparaison d'égalité définie par [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Obtient le FileType pour l'extension de fichier fournie. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Renvoie le FileType pour le file_name spécifié. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Renvoie le FileType pour le flux de document fourni. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Fournit la fonction de hachage par défaut. (hérité de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Représentation sous forme de chaîne du type de fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La description du type de fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | L'extension du fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La famille du fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Le format du fichier. (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Champs
| Champ | Description |
| :- | :- |
| [SHP](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/shp/) | SHP est l'extension de fichier pour l'un des principaux types de fichiers utilisés pour la représentation du Shapefile ESRI. Il représente des informations géospatiales sous forme de données vectorielles à utiliser par les applications de systèmes d'information géographique (GIS). En savoir plus sur ce format de fichier ici. |
| [GEO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/geo_json/) | GeoJSON est un format basé sur JSON conçu pour représenter les caractéristiques géographiques avec leurs attributs non spatiaux. Ce format définit différents objets JSON (JavaScript Object Notation) et leur mode d'association. Le format JSON représente des informations collectives sur les caractéristiques géographiques, leurs étendues spatiales et leurs propriétés. En savoir plus sur ce format de fichier ici. |
| [GDB](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gdb/) | La géodatabase de fichiers ESRI (FileGDB) est une collection de fichiers dans un dossier sur le disque qui contient des données géospatiales liées telles que des ensembles de jeux d'entités, des classes d'entités et des tables associées. Elle nécessite que certains autres fichiers soient conservés à côté du fichier .gdb dans le même répertoire pour fonctionner. En savoir plus sur ce format de fichier ici. |
| [GML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gml/) | GML signifie Geography Markup Language, qui est basé sur des spécifications XML développées par l'Open Geospatial Consortium (OGC). Le format est utilisé pour stocker des caractéristiques de données géographiques afin de les échanger entre différents formats de fichiers. Il sert de langage de modélisation pour les systèmes géographiques ainsi que de format d'échange ouvert pour les transactions géographiques sur Internet. En savoir plus sur ce format de fichier ici. |
| [KML](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/kml/) | KML (Keyhole Markup Language) contient des informations géospatiales en notation XML. Les fichiers enregistrés au format KML peuvent être ouverts dans des applications de système d'information géographique (SIG) à condition qu'elles le prennent en charge. De nombreuses applications ont commencé à prendre en charge le format de fichier KML après son adoption comme norme internationale. KML utilise une structure basée sur des balises avec des éléments et attributs imbriqués. En savoir plus sur ce format de fichier ici. |
| [GPX](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/gpx/) | Les fichiers avec l'extension GPX représentent le format GPS Exchange pour l'échange de données GPS entre les applications et les services web sur Internet. Il s'agit d'un format de fichier XML léger qui contient des données GPS, c'est‑à‑dire des points de cheminement, des itinéraires et des traces à importer et à lire par plusieurs programmes. En savoir plus sur ce format de fichier ici. |
| [TOPO_JSON](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/topo_json/) | TopoJSON est une extension de GeoJSON qui encode la topologie. Plutôt que de représenter les géométries de façon distincte, les géométries dans les fichiers TopoJSON sont assemblées à partir de segments de ligne partagés appelés arcs. |
| [OSM](/conversion/python-net/groupdocs.conversion.filetypes/gisfiletype/osm/) | Le format de fichier OSM est un format de données structuré utilisé pour stocker des données géographiques dans le projet OpenStreetMap. Les fichiers OSM sont généralement au format XML et contiennent des informations telles que l'emplacement des routes, des bâtiments, des points d'intérêt et d'autres caractéristiques sur la carte. En savoir plus sur ce format de fichier ici. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Type de fichier inconnu (hérité de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Voir aussi
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
