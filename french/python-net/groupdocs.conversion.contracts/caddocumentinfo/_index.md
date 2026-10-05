---
title: "Classe CadDocumentInfo"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Contient les métadonnées du document Cad."
type: docs
url: /fr/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Contient les métadonnées du document Cad.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Sans l'option explicite [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/), ces feuilles sont l'espace modèle, qui est toujours traçable et donc toujours une feuille, ainsi que chaque mise en page papier dont la configuration de page stockée possède une largeur et une hauteur positives, restreinte par [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Les noms de mise en page explicites l'emportent complètement : les feuilles sont alors les noms fournis que le dessin possède, correspondants ordinalement, sans que le scope ou la configuration de page ne les filtrent.

Pour un DWF, l'ensemble de pages publié est indiqué. Le compte inférieur à un est zéro, indiqué lorsque le scope demandé ne correspond à aucune feuille d'un dessin qui en propose une : les métadonnées décrivent toujours le dessin, et zéro signifie que le scope ne sélectionne rien plutôt que d'échouer l'appelant qui demandait ce que le dessin contient. Une conversion avec ces mêmes options de chargement échoue.

Le compte n'est donc pas la taille de [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), qui répertorie chaque configuration d'impression que le dessin possède, y compris celles dont aucune feuille ne peut être publiée, et il ne prédit pas le nombre de pages qu'une conversion particulière génère.

Le type CadDocumentInfo expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | La date de création du document. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Le format du document. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | La hauteur du document CAD. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Les calques du document. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Les mises en page du document. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Le nombre de pages du document. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | L'énumérable de toutes les propriétés pouvant être récupérées pour les informations du document actuel. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | La taille du document en octets. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | La largeur du document CAD. |

### Voir aussi
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
