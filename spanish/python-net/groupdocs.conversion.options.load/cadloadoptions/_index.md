---
title: "Clase CadLoadOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Proporciona opciones para cargar documentos CAD."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/cadloadoptions/
is_root: false
weight: 60
---


## CadLoadOptions class

Proporciona opciones para cargar documentos CAD.

El tipo CadLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/__init__/) | Inicializa una nueva instancia de la clase [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/). |

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
| [background_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/background_color/) | El color de fondo. |
| [ctb_sources](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/ctb_sources/) | Los recursos CTB. |
| [draw_color](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_color/) | El color de primer plano. |
| [draw_type](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/draw_type/) | El tipo de dibujo. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/format/) | El tipo de archivo del documento de entrada. |
| [layout_names](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) | Los nombres de diseño a convertir. |
| [layout_scope](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/) | El alcance de diseño que determina qué espacios de dibujo se convierten. Por defecto es [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), lo que no restringe la conversión. Se ignora cuando se proporciona [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/), porque los nombres de diseño explícitos siempre prevalecen. Un valor `None` se trata como [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/). |

### Ver también
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
