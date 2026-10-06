---
title: "Clase ProjectManagementFileType"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Define formatos de archivo de Project que son creados por software de gestión de proyectos como Microsoft Project, Primavera P6, etc."
type: docs
url: /es/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Define formatos de archivo de Project que son creados por software de gestión de proyectos como Microsoft Project, Primavera P6, etc.

Un archivo de proyecto es una colección de tareas, recursos y su programación para obtener un resultado medible en forma de producto o servicio. Documentos de gestión de proyectos. Incluye los siguientes tipos de archivo: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). Obtén más información sobre los formatos de gestión de proyectos aquí: https://wiki.fileformat.com/project-management.

El tipo ProjectManagementFileType expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Inicializa un ProjectManagementFileType para serialización. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Los archivos de plantilla de Microsoft Project contienen información básica y estructura junto con la configuración de documentos para crear archivos .MPP. Obtén más información sobre este formato de archivo aquí. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de manera integrada. Obtén más información sobre este formato de archivo aquí. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format es un formato de archivo ASCII para la transferencia de información de proyectos entre Microsoft Project (MSP) y otras aplicaciones que admiten el formato de archivo MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating. Obtén más información sobre este formato de archivo aquí. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | El formato de archivo XER es un formato de archivo de proyecto propietario utilizado por la aplicación de planificación y gestión de proyectos Primavera P6. Obtén más información sobre este formato de archivo aquí. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo de archivo desconocido (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ver también
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
