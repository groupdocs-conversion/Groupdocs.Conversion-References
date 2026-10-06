---
title: "Clase FinanceFileType"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Define tipos de documentos financieros."
type: docs
url: /es/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Define tipos de documentos financieros.

Incluye los siguientes tipos: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Obtén más información sobre los formatos financieros aquí: https://docs.fileformat.com/finance/.

El tipo FinanceFileType expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Inicializa un FinanceFileType para serialización. |

### Métodos
| Método | Descripción |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Compara el objeto actual con otro. (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementa la comparación de igualdad definida por [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Obtiene el FileType para la extensión de archivo proporcionada. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Devuelve el FileType para el file_name especificado. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Devuelve el FileType para el flujo de documento proporcionado. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Proporciona la función hash predeterminada. (heredado de [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Representación en cadena del tipo de archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La descripción del tipo de archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | La extensión del archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La familia del archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | El formato del archivo. (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL es un estándar internacional abierto para la presentación digital de informes empresariales que se utiliza ampliamente a nivel mundial. Es un lenguaje basado en XML que usa elementos XBRL, conocidos como etiquetas, para describir cada elemento de datos empresariales y formular datos para la clasificación y análisis de informes. Obtén más información sobre este formato de archivo aquí. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | Dentro del iXBRL, el contenido de XBRL está envuelto en formato de archivo xHTML que utiliza etiquetas XML. Al igual que XBRL, es el elemento raíz de los archivos iXBRL. El formato XHTML representa su contenido como una colección de diferentes tipos de documentos y módulos. Todos los archivos en XHTML se basan en el formato de archivo XML y cumplen con los estándares de documentos XML. Obtén más información sobre este formato de archivo aquí. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) es un formato de flujo de datos para intercambiar información financiera que evolucionó a partir de Open Financial Connectivity (OFC) de Microsoft y los formatos de archivo Open Exchange de Intuit. Obtén más información sobre este formato de archivo aquí. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo de archivo desconocido (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ver también
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
