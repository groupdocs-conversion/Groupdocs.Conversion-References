---
title: "Clase WordProcessingLoadOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Proporciona opciones para cargar documentos WordProcessing."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Proporciona opciones para cargar documentos WordProcessing.

Pipeline de procesamiento de fuentes:

Fase 1 - Sustitución de fuentes (durante la carga del documento):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Fase 2 - Reemplazo de fuentes (después de la carga del documento):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

El tipo WordProcessingLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Inicializa una nueva instancia de [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina si dos instancias de objeto son iguales. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Sirve como la función hash predeterminada. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | La propiedad auto_detect_rtl_direction determina si los párrafos y ejecuciones con texto predominantemente de derecha a izquierda tienen sus banderas bidi reparadas antes de la conversión. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Las opciones de marcadores. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | La bandera que indica si las propiedades de documento incorporadas se borran al cargar un documento de procesamiento de Word. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | La propiedad ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | El modo de visualización de comentarios especifica cómo deben mostrarse los comentarios en el documento de salida. El valor predeterminado es `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | La propiedad implementa [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). El valor predeterminado es False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | La bandera convert_owner indica si se debe convertir al propietario del documento. El valor predeterminado es True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | La fuente predeterminada para un documento WordProcessing. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | La profundidad de las opciones de carga del contenedor de documentos. El valor predeterminado es 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | La propiedad embed_true_type_fonts determina si las fuentes TrueType se incrustan en el documento de salida. El valor predeterminado es True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | La propiedad habilita la sustitución automática de fuentes faltantes basada en el FontConfig del sistema. El valor predeterminado es False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | La bandera que habilita la sustitución automática de fuentes faltantes basada en FontInfo en el documento. Predeterminado: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | La propiedad indica si las fuentes faltantes se sustituyen automáticamente según el nombre de la fuente. Predeterminado: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | Los sustitutos de fuentes utilizados al convertir un documento WordProcessing. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Las transformaciones de fuentes aplicadas después de que la carga del documento y la sustitución de fuentes se completan, permitiendo la modificación de cualquier fuente en el documento, incluidas las que se cargaron correctamente. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | El tipo de archivo del documento de entrada. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | La propiedad hide_word_tracked_changes oculta el marcado y el seguimiento de cambios para documentos Word. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Las opciones de guionización para documentos WordProcessing. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | La propiedad keep_date_field_original_value determina si se conserva el valor original de un campo de fecha. El valor predeterminado es False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Los ajustes de margen. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | La bandera de generación de numeración de páginas para el documento convertido (predeterminado: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | La contraseña para desproteger un documento protegido. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | La bandera que indica si la estructura del documento debe preservarse al convertir a PDF (el valor predeterminado es False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | La propiedad indica si los campos de formulario de Microsoft Word se conservan como campos de formulario en el PDF resultante o se convierten a texto. El valor predeterminado es False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | El nombre completo del comentarista se muestra en los comentarios cuando se establece en True. El valor predeterminado es False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Los ajustes de tamaño para el documento WordProcessing ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | La bandera que determina si se omiten los recursos externos al cargar un documento. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | La opción de actualizar los campos después de cargar. Predeterminado: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | El diseño de página se actualiza después de cargar. Predeterminado: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | La propiedad indica si se debe usar un modelador de texto para una mejor visualización del kerning. El valor predeterminado es False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Los recursos en la lista blanca para cargar contenido externo, implementando [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Ejemplo

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Guías de tareas que usan `WordProcessingLoadOptions`:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Ver también
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
