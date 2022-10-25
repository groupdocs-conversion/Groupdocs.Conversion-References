---
title: PresentationFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define formatos de archivo de presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas formas texto animaciones video audio y objetos incrustados. Incluye los siguientes tipos de archivo Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Obtenga más información sobre los formatos de presentaciónaquíhttps//wiki.fileformat.com/presentation .
type: docs
weight: 910
url: /es/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Define formatos de archivo de presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados. Incluye los siguientes tipos de archivo: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Obtenga más información sobre los formatos de presentación[aquí](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | El archivo family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Los archivos con extensión FODP representan la presentación XML plana de OpenDocument. Archivo de presentación guardado en formato OpenDocument, pero guardado con un formato XML plano en lugar del contenedor .ZIP que usan los archivos .ODP estándar |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Los archivos con extensión ODP representan el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Los archivos con extensión .OTP representan archivos de plantilla de presentación creados por aplicaciones en formato estándar OASIS OpenDocument. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Los archivos con la extensión .POT representan archivos de plantilla de Microsoft PowerPoint creados por las versiones de PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Los archivos con extensión POTM son archivos de plantilla de Microsoft PowerPoint compatibles con macros. Los archivos POTM se crean con PowerPoint 2007 o superior y contienen configuraciones predeterminadas que se pueden usar para crear más archivos de presentación. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Los archivos con la extensión .POTX representan presentaciones de plantilla de Microsoft PowerPoint creadas con Microsoft PowerPoint 2007 y superior. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, presentación de diapositivas de PowerPoint, los archivos se crean utilizando Microsoft PowerPoint para fines de presentación de diapositivas. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Los archivos con la extensión PPSM representan un formato de archivo de presentación de diapositivas habilitado para macros creado con Microsoft PowerPoint 2007 o superior. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, presentación de diapositivas de Power Point, el archivo se crea con Microsoft PowerPoint 2007 y superior para fines de presentación de diapositivas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Un archivo con extensión PPT representa un archivo de PowerPoint que consta de una colección de diapositivas para mostrarlas como presentación de diapositivas. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Los archivos con la extensión PPTM son archivos de presentación habilitados para macros que se crean con Microsoft PowerPoint 2007 o versiones superiores. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Los archivos con extensión PPTX son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de archivo de presentación XML abierto de Microsoft PowerPoint. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/presentation/pptx) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
