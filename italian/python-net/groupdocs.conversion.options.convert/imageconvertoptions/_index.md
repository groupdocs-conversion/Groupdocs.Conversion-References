---
title: "classe ImageConvertOptions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Rappresenta le opzioni per convertire un documento in un tipo di file immagine."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

Rappresenta le opzioni per convertire un documento in un tipo di file immagine.

Il tipo ImageConvertOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | Inizializza una nuova istanza di ImageConvertOptions. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | Il colore di sfondo da utilizzare dove supportato dal formato di origine. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | La regolazione della luminosità dell'immagine. |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | La proprietà limita la risoluzione di rendering PDF per pagina alla risoluzione raster nativa della pagina, impedendo il rendering a un DPI più alto rispetto all'immagine incorporata e generando la pagina alle sue dimensioni pixel native (più piccole) e DPI nell'output finale. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | La regolazione del contrasto applicata all'immagine. |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | L'area di ritaglio dell'immagine raster dopo la conversione. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | La modalità di ribaltamento dell'immagine. |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | Il tipo di file desiderato in cui il documento di input dovrebbe essere convertito. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | La regolazione della gamma dell'immagine. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | L'opzione che indica se convertire l'immagine in scala di grigi. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | L'altezza desiderata dell'immagine dopo la conversione. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | La risoluzione orizzontale desiderata dell'immagine dopo la conversione; per impostazione predefinita è la risoluzione del file di input o 96 dpi. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | Le opzioni di conversione specifiche per JPEG. |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | Il limite inferiore per asse applicato al DPI di rendering limitato quando [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) è abilitato. |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | Il numero di pagina da cui iniziare la conversione. |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | L'elenco degli indici di pagina da convertire. Deve essere specificato per convertire pagine specifiche. |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | Il numero di pagine da convertire a partire da `PageNumber`. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | Le opzioni di conversione specifiche per PSD. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | L'angolo di rotazione dell'immagine. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Le opzioni di conversione specifiche per Tiff. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | La proprietà UsePdf. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | La risoluzione verticale desiderata dell'immagine dopo la conversione. La risoluzione predefinita è quella del file di input o 96 dpi. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | Le opzioni specifiche del watermark. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | Le opzioni di conversione specifiche per WebP. |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | La larghezza desiderata dell'immagine dopo la conversione. |

### Esempio

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
Guide operative che utilizzano `ImageConvertOptions`:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### Vedi anche
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
