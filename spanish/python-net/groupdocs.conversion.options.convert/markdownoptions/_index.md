---
title: "Clase MarkdownOptions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Representa opciones para la conversión al tipo de archivo markdown."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/markdownoptions/
is_root: false
weight: 290
---


## MarkdownOptions class

Representa opciones para la conversión al tipo de archivo markdown.

El tipo MarkdownOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/__init__/) | Inicializa una nueva instancia de [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/) clase. |

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
| [export_images_as_base64](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) | La opción export_images_as_base64 determina si las imágenes se exportan como base64. |
| [image_saving_callback](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/) | La devolución de llamada invocada una vez por imagen al guardar Markdown. Permite al llamador persistir imágenes externamente y sustituir el URI incrustado en el documento. Tiene precedencia sobre [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) cuando no es None. |

### Ver también
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
