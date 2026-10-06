---
title: "Clase EmailLoadOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Proporciona opciones para cargar documentos de correo electrónico."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/emailloadoptions/
is_root: false
weight: 130
---


## EmailLoadOptions class

Proporciona opciones para cargar documentos de correo electrónico.

El tipo EmailLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/clone/) | Clona la instancia actual. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina si dos instancias de objeto son iguales. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Sirve como la función hash predeterminada. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/attachment_icons/) | La lista de íconos de adjuntos, que puede personalizarse para proporcionar íconos específicos para diferentes tipos de archivo. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owned/) | La propiedad implementa [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). El valor predeterminado es True. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owner/) | La propiedad convert_owner implementa [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). El valor predeterminado es True. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/custom_css_style/) | El estilo CSS personalizado, que implementa [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/default_font/) | La fuente predeterminada para un documento de correo electrónico. Esta fuente se usará si falta una fuente requerida. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/depth/) | La profundidad de las opciones de carga del contenedor de documentos. |
| [display_attachments](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_attachments/) | La opción de mostrar u ocultar los archivos adjuntos en el encabezado. Predeterminado: True. |
| [display_bcc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_bcc_email_address/) | La opción de mostrar u ocultar la dirección de correo Bcc. Predeterminado: False. |
| [display_cc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_cc_email_address/) | La opción de mostrar u ocultar la dirección de correo "Cc", con valor predeterminado False. |
| [display_email_addresses](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_email_addresses/) | La opción de controlar si las direcciones de correo se muestran junto a los nombres. Predeterminado es True. |
| [display_from_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_from_email_address/) | La opción de mostrar u ocultar la dirección de correo "from". Predeterminado: True. |
| [display_header](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_header/) | La opción de mostrar u ocultar el encabezado del correo. Predeterminado: True. |
| [display_sent](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_sent/) | La opción de mostrar u ocultar la fecha/hora de envío en el encabezado. Predeterminado es True. |
| [display_subject](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_subject/) | La opción de mostrar u ocultar el asunto en el encabezado. Predeterminado es True. |
| [display_to_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_to_email_address/) | La opción de mostrar u ocultar la dirección de correo "to". Predeterminado: True. |
| [field_text_map](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/field_text_map/) | La asignación entre el mensaje de correo [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield/) y la representación de texto del campo. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/font_substitutes/) | La lista de sustitutos de fuentes. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/format/) | El tipo de archivo del documento de entrada. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/margin_settings/) | Los ajustes de margen. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/orientation_settings/) | Los ajustes de orientación. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/page_layout_options/) | La propiedad implementa [`IPageLayoutOptions.page_layout_options`](/conversion/python-net/groupdocs.conversion.options.load/ipagelayoutoptions/page_layout_options/). |
| [preserve_original_date](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/preserve_original_date/) | La propiedad determina si se mantiene la cadena original del encabezado de fecha en el mensaje de correo al guardar. El valor predeterminado es True. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/resource_loading_timeout/) | El tiempo de espera para cargar recursos externos. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/size_settings/) | La configuración del tamaño de página para la operación de carga de correo. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/skip_external_resources/) | La propiedad que implementa [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [time_zone_offset](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/time_zone_offset/) | El desplazamiento de Tiempo Universal Coordinado (UTC) para las fechas de los mensajes. |
| [use_default_attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/use_default_attachment_icons/) | La bandera que indica si se utilizan los íconos de adjuntos predeterminados (predeterminado es True). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/whitelisted_resources/) | La propiedad implementa [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Ver también
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
