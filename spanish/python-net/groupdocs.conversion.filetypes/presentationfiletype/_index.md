---
title: "Clase PresentationFileType"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Representa formatos de archivo de presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados."
type: docs
url: /es/python-net/groupdocs.conversion.filetypes/presentationfiletype/
is_root: false
weight: 160
---


## PresentationFileType class

Representa formatos de archivo de presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados.

Incluye los siguientes tipos de archivo:
- [`PresentationFileType.odp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/)
- [`PresentationFileType.otp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/)
- [`PresentationFileType.pot`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/)
- [`PresentationFileType.potm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/)
- [`PresentationFileType.potx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/)
- [`PresentationFileType.pps`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/)
- [`PresentationFileType.ppsm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/)
- [`PresentationFileType.ppsx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/)
- [`PresentationFileType.ppt`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/)
- [`PresentationFileType.pptm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/)
- [`PresentationFileType.pptx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/).

Obtenga más información sobre los formatos de presentación en https://wiki.fileformat.com/presentation.

El tipo PresentationFileType expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/__init__/) | Inicializa un PresentationFileType para serialización. |

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
| [PPT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/) | Un archivo con extensión PPT representa un archivo PowerPoint que consiste en una colección de diapositivas para mostrarse como presentación. Especifica el Formato de Archivo Binario utilizado por Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo aquí. |
| [PPS](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/) | Los archivos PPS, PowerPoint Slide Show, se crean con Microsoft PowerPoint para presentaciones. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo aquí. |
| [PPTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/) | Los archivos con extensión PPTX son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de presentación Open XML de Microsoft PowerPoint. Obtenga más información sobre este formato de archivo aquí. |
| [PPSX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/) | Los archivos PPSX, Power Point Slide Show, se crean con Microsoft PowerPoint 2007 y versiones posteriores para presentaciones. Obtenga más información sobre este formato de archivo aquí. |
| [ODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/) | Los archivos con extensión ODP representan el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Obtenga más información sobre este formato de archivo aquí. |
| [OTP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/) | Los archivos con extensión .OTP representan plantillas de presentación creadas por aplicaciones en el formato estándar OASIS OpenDocument. Obtenga más información sobre este formato de archivo aquí. |
| [POTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/) | Los archivos con extensión .POTX representan presentaciones de plantilla de Microsoft PowerPoint creadas con Microsoft PowerPoint 2007 y versiones posteriores. Obtenga más información sobre este formato de archivo aquí. |
| [POT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/) | Los archivos con extensión .POT representan plantillas de Microsoft PowerPoint creadas con versiones PowerPoint 97-2003. Obtenga más información sobre este formato de archivo aquí. |
| [POTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/) | Los archivos con extensión POTM son plantillas de Microsoft PowerPoint con soporte para macros. Los archivos POTM se crean con PowerPoint 2007 o versiones posteriores y contienen configuraciones predeterminadas que pueden usarse para crear más archivos de presentación. Obtenga más información sobre este formato de archivo aquí. |
| [PPTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/) | Los archivos con extensión PPTM son presentaciones habilitadas para macros creadas con Microsoft PowerPoint 2007 o versiones superiores. Obtenga más información sobre este formato de archivo aquí. |
| [PPSM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/) | Los archivos con extensión PPSM representan el formato de presentación de diapositivas habilitado para macros creado con Microsoft PowerPoint 2007 o versiones superiores. Obtenga más información sobre este formato de archivo aquí. |
| [FODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/fodp/) | Los archivos con extensión FODP representan una presentación OpenDocument Flat XML. El archivo de presentación se guarda en formato OpenDocument, pero usando un formato XML plano en lugar del contenedor .ZIP utilizado por los archivos .ODP estándar. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo de archivo desconocido (heredado de [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Ver también
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
