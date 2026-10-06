---
title: "Clase EmailFileType"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Define formatos de archivo de correo electrónico utilizados por aplicaciones de correo para almacenar mensajes, archivos adjuntos, carpetas, libretas de direcciones y otros datos."
type: docs
url: /es/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

Define formatos de archivo de correo electrónico utilizados por aplicaciones de correo para almacenar mensajes, archivos adjuntos, carpetas, libretas de direcciones y otros datos.

Incluye los siguientes tipos de archivo:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

Obtén más información sobre los formatos de correo electrónico en https://wiki.fileformat.com/email.

El tipo EmailFileType expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | Inicializa un nuevo EmailFileType para serialización. |

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
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Obtén más información sobre este formato de archivo aquí. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. Casi todos los clientes de correo electrónico admiten este formato de archivo por su cumplimiento con el estándar RFC-822 Internet Message Format. Obtén más información sobre este formato de archivo aquí. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | El formato de archivo EMLX es implementado y desarrollado por Apple. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Obtén más información sobre este formato de archivo aquí. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Formato de Tarjeta Virtual) o vCard es un formato de archivo digital para almacenar información de contactos. El formato se usa ampliamente para el intercambio de datos entre aplicaciones populares de intercambio de información. Obtén más información sobre este formato de archivo aquí. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico. Los mensajes se almacenan dentro del contenedor junto con sus archivos adjuntos. Obtén más información sobre este formato de archivo aquí. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | Los archivos con extensión .PST representan Archivos de Almacenamiento Personal de Outlook (también llamados Personal Storage Table) que almacenan una variedad de información del usuario. Obtén más información sobre este formato de archivo aquí. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST o Archivos de Almacenamiento Offline representan los datos del buzón del usuario en modo offline en la máquina local tras el registro con Exchange Server usando Microsoft Outlook. Obtén más información sobre este formato de archivo aquí. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | Un archivo con extensión .olm es un archivo de Microsoft Outlook para el sistema operativo Mac. Un archivo OLM almacena mensajes de correo electrónico, diarios, datos de calendario y otros tipos de datos de aplicación. Estos son similares a los archivos PST usados por Outlook en el sistema operativo Windows. Sin embargo, los archivos OLM creados por Outlook para Mac no pueden abrirse en Outlook para Windows. Obtén más información sobre este formato de archivo aquí. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | El formato de archivo ICS (iCalendar) se usa para representar e intercambiar información de calendario y programación, como eventos, tareas y datos de disponibilidad. Obtén más información sobre este formato de archivo aquí. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo de archivo desconocido (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ver también
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
