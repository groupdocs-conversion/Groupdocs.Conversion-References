---
title: "classe FontSubstitutionContext"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Décrit une substitution unique de police qui s'est produite lors du chargement ou du rendu d'un document source."
type: docs
url: /fr/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Décrit une substitution unique de police qui s'est produite lors du chargement ou du rendu d'un document source.

Les instances sont transmises à [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Le type FontSubstitutionContext expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Initialise un nouveau FontSubstitutionContext. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Le nom de la police référencée par le document source mais indisponible pour le pipeline de conversion. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Le message de substitution exactement tel que rapporté par le pipeline de conversion, mot à mot et non analysé. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Le nom de fichier du document source en cours de conversion. Lorsque la source a été fournie sous forme de flux qui n'est pas un `io.RawIOBase`, cela contient un identifiant généré plutôt qu'un vrai nom de fichier. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Le nom de la police utilisée comme substitut. Peut être None pour les documents dont le moteur signale la substitution uniquement sous forme de texte descriptif — dans ce cas, lisez [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Voir aussi
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
