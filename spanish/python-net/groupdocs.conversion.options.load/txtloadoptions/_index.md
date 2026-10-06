---
title: "Clase TxtLoadOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Opciones para cargar documentos Txt."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Opciones para cargar documentos Txt.

Configuración de fuente para texto sin formato:

Dado que los archivos TXT no contienen información de fuentes, use DefaultTextFont para especificar la fuente al renderizar el contenido de texto sin formato durante la conversión.

El tipo TxtLoadOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Inicializa una nueva instancia de [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

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
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | La fuente a usar al renderizar contenido de texto sin formato durante la conversión. Predeterminada: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | La propiedad especifica cómo se reconocen los elementos de listas numeradas cuando se convierte un documento de texto sin formato. El valor predeterminado es True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | La codificación utilizada al cargar un documento Txt. Puede ser None. El valor predeterminado es None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | El tipo de archivo del documento de entrada. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | La opción preferida para manejar los espacios iniciales. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | La configuración de márgenes, según lo definido por [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Las opciones de tamaño de página para cargar un documento TXT. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | La opción preferida para manejar los espacios finales. El valor predeterminado es [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Ver también
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
