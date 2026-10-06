---
title: "Clase FontTransformation"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Describe la configuración de transformación de fuentes, incluidos los atributos de fuente, aplicada después de la carga del documento y la sustitución de fuentes."
type: docs
url: /es/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 200
---


## FontTransformation class

Describe la configuración de transformación de fuentes, incluidos los atributos de fuente, aplicada después de la carga del documento y la sustitución de fuentes.

El tipo FontTransformation expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Crea una transformación de fuente con coincidencia exacta de fuente (el tamaño y el estilo deben coincidir). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Crea una transformación de fuente solo por nombre, coincidiendo con cualquier tamaño y estilo, con la fuente de reemplazo que conserva el tamaño y estilo de la fuente original. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Crea una transformación de fuente con opciones de coincidencia flexibles. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina si dos instancias de objeto son iguales. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Sirve como la función hash predeterminada. (heredado de [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | La propiedad indica si se coincide con cualquier tamaño de fuente para el nombre de la fuente original (true) o solo con el tamaño exacto especificado en `OriginalFont` (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | La propiedad determina si se coincide con cualquier estilo de fuente (negrita, cursiva, subrayado) de la fuente original (True) o si se requiere el estilo exacto especificado en `OriginalFont` (False). |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | La especificación de la fuente original para coincidir y reemplazar. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | La especificación de la fuente de reemplazo. |

### Ver también
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
