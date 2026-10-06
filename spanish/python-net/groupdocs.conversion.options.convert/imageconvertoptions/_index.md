---
title: "ImageConvertOptions clase"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Representa opciones para convertir un documento a un tipo de archivo de imagen."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Representa opciones para convertir un documento a un tipo de archivo de imagen.

El tipo ImageConvertOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Inicializa una nueva instancia de ImageConvertOptions. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | El color de fondo a usar donde lo admita el formato de origen. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | El ajuste de brillo de la imagen. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | La propiedad limita la resolución de renderizado PDF por página a la resolución raster nativa de la página, evitando renderizar a un DPI más alto que la imagen incrustada y emitiendo la página con sus dimensiones de píxel y DPI nativos (más pequeños) en la salida final. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | El ajuste de contraste aplicado a la imagen. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | El área de recorte de la imagen raster después de la conversión. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | El modo de volteo de la imagen. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | El ajuste de gamma de la imagen. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | La opción que indica si convertir la imagen a escala de grises. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | La altura deseada de la imagen después de la conversión. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | La resolución horizontal deseada de la imagen después de la conversión; por defecto es la resolución del archivo de entrada o 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | Las opciones de conversión específicas de JPEG. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | El límite inferior por eje aplicado al DPI de renderizado limitado cuando [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) está habilitado. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | El número de página desde la cual iniciar la conversión. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | La lista de índices de página que se convertirán. Debe especificarse para convertir páginas específicas. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | El número de páginas a convertir a partir de `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | Las opciones de conversión específicas de PSD. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | El ángulo de rotación de la imagen. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Las opciones de conversión específicas de Tiff. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | La propiedad UsePdf. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | La resolución vertical deseada de la imagen después de la conversión. La resolución predeterminada es la resolución del archivo de entrada o 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Las opciones específicas de la marca de agua. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | Las opciones de conversión específicas de WebP. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | El ancho deseado de la imagen después de la conversión. |

### Ejemplo

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
Guías de tareas que usan `ImageConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Ver también
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
