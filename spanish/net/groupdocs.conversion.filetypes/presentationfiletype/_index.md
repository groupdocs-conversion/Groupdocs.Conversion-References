---
title: "PresentationFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define los formatos de archivo de Presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados. Incluye los siguientes tipos de archivo Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Obtén más información sobre los formatos de Presentación aquíhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /es/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Define los formatos de archivo de Presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados. Incluye los siguientes tipos de archivo: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Obtén más información sobre los formatos de Presentación [aquí](https://wiki.fileformat.com/presentation).

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
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Los archivos con extensión FODP representan una Presentación OpenDocument Flat XML. Archivo de presentación guardado en el formato OpenDocument, pero guardado usando un formato XML plano en lugar del contenedor .ZIP utilizado por los archivos .ODP estándar. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Los archivos con extensión ODP representan el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Los archivos con extensión .OTP representan archivos de plantilla de presentación creados por aplicaciones en el formato estándar OASIS OpenDocument. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Los archivos con extensión .POT representan archivos de plantilla de Microsoft PowerPoint creados por versiones de PowerPoint 97-2003. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Los archivos con extensión POTM son archivos de plantilla de Microsoft PowerPoint con soporte para macros. Los archivos POTM se crean con PowerPoint 2007 o superior y contienen configuraciones predeterminadas que pueden usarse para crear más archivos de presentación. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Los archivos con extensión .POTX representan presentaciones de plantilla de Microsoft PowerPoint creadas con Microsoft PowerPoint 2007 y versiones posteriores. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, los archivos se crean usando Microsoft PowerPoint con fines de presentación de diapositivas. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Los archivos con extensión PPSM representan el formato de archivo de presentación de diapositivas con macros creado con Microsoft PowerPoint 2007 o superior. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slide Show, los archivos se crean usando Microsoft PowerPoint 2007 y versiones posteriores con fines de presentación de diapositivas. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | Un archivo con extensión PPT representa un archivo de PowerPoint que consiste en una colección de diapositivas para mostrarse como presentación. Especifica el formato binario de archivo utilizado por Microsoft PowerPoint 97-2003. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Los archivos con extensión PPTM son archivos de presentación con macros que se crean con Microsoft PowerPoint 2007 o versiones superiores. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Los archivos con extensión PPTX son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de archivo de presentación Open XML de Microsoft PowerPoint. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/presentation/pptx). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
