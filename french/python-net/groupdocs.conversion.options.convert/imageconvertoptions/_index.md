---
title: "classe ImageConvertOptions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Représente les options de conversion d’un document vers un type de fichier image."
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Représente les options de conversion d’un document vers un type de fichier image.

Le type ImageConvertOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Initialise une nouvelle instance d'ImageConvertOptions. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | La couleur d'arrière-plan à utiliser lorsque le format source le prend en charge. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | L'ajustement de la luminosité de l'image. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | La propriété limite la résolution de rendu PDF par page à la résolution raster native de la page, empêchant le rendu à un DPI supérieur à celui de l'image intégrée et émettant la page à ses dimensions de pixels natives (plus petites) et DPI dans le résultat final. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | L'ajustement du contraste appliqué à l'image. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | La zone de recadrage de l'image raster après conversion. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | Le mode de retournement de l'image. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | L'ajustement du gamma de l'image. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | L'option indiquant s'il faut convertir l'image en niveaux de gris. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | La hauteur d'image souhaitée après conversion. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | La résolution horizontale d'image souhaitée après conversion ; par défaut, celle du fichier d'entrée ou 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | Les options de conversion spécifiques au JPEG. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | La limite inférieure par axe appliquée au DPI de rendu limité lorsque [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) est activée. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Le numéro de page à partir duquel commencer la conversion. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | La liste des index de pages à convertir. Doit être spécifiée pour convertir des pages spécifiques. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Le nombre de pages à convertir à partir de `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | Les options de conversion spécifiques au PSD. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | L'angle de rotation de l'image. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Les options de conversion spécifiques au Tiff. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | La propriété UsePdf. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | La résolution verticale d'image souhaitée après conversion. La résolution par défaut est celle du fichier d'entrée ou 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Les options spécifiques au filigrane. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | Les options de conversion spécifiques au WebP. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | La largeur d'image souhaitée après conversion. |

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
Guides de tâches utilisant `ImageConvertOptions` :

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Voir aussi
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
