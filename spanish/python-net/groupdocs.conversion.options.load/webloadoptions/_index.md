---
title: "Clase WebLoadOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Proporciona opciones para cargar documentos web."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
weight: 550
---


## WebLoadOptions class

Proporciona opciones para cargar documentos web.

El tipo WebLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/) | Inicializa una nueva instancia de [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/). |

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
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | La ruta/base URL para el HTML. |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | La acción utilizada para configurar los encabezados de la solicitud, donde el primer parámetro es el Uri. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | El proveedor de credenciales para el Uri. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/custom_css_style/) | La propiedad implementa [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | La codificación a usar al cargar el documento web. Si se establece en None, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format/) | El tipo de archivo del documento de entrada. |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | El modo de renderizado HTML controla cómo se renderiza el contenido HTML. Predeterminado: AbsolutePositioning. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/margin_settings/) | Los ajustes de margen. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/orientation_settings/) | Los ajustes de orientación. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_layout_options/) | Las opciones de diseño de página usadas al cargar documentos web. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering/) | La bandera que habilita o deshabilita la generación de numeración de páginas en el documento convertido. Predeterminado: False. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | El tiempo de espera para cargar recursos externos. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/size_settings/) | Los ajustes de tamaño. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources/) | La propiedad implementa [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | La propiedad indica si usar PDF para la conversión (predeterminado: False). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources/) | La propiedad de recursos en lista blanca implementa [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | El nivel de zoom como un porcentaje aplicado a la etiqueta `<body>` del documento antes de la conversión, escalando la apariencia visual del documento. |

### Ver también
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
