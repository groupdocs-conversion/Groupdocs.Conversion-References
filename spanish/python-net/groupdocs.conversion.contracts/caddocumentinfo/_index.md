---
title: "Clase CadDocumentInfo"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Contiene metadatos del documento Cad."
type: docs
url: /es/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Contiene metadatos del documento Cad.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Sin [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) explícitos, esas hojas son el espacio modelo, que siempre es trazable y por lo tanto siempre es una hoja, más cada diseño de espacio de papel cuya configuración de página almacenada tiene un ancho y alto positivos, limitado por [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Los nombres de diseño explícitos ganan directamente: entonces las hojas son los nombres suministrados que lleva el dibujo, emparejados ordinalmente, sin que el alcance ni la configuración de página los filtren.

Para un DWF se informa el conjunto de páginas publicado. El recuento de uno por debajo de uno es cero, informado cuando el alcance solicitado no coincide con ninguna hoja de un dibujo que ofrezca una: los metadatos aún describen el dibujo, y cero indica que el alcance no selecciona nada en lugar de fallar al llamador que preguntó qué contiene el dibujo. Una conversión bajo esas mismas opciones de carga falla.

Por lo tanto, el recuento no es el tamaño de [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), que enumera cada configuración de trazado que lleva el dibujo, incluidas aquellas de las que no se puede publicar ninguna hoja, y no predice cuántas páginas emitirá una conversión particular.

El tipo CadDocumentInfo expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | La fecha de creación del documento. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | El formato del documento. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | La altura del documento CAD. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Las capas del documento. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Los diseños del documento. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | El recuento de páginas del documento. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | El enumerado de todas las propiedades que pueden recuperarse para la información actual del documento. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | El tamaño del documento en bytes. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | El ancho del documento CAD. |

### Ver también
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
