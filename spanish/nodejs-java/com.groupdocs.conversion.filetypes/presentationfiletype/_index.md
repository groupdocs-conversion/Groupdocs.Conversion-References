---
title: "PresentationFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define los formatos de archivo de Presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados."
type: docs
weight: 22
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Define los formatos de archivo de Presentación que almacenan una colección de registros para acomodar datos de presentación como diapositivas, formas, texto, animaciones, video, audio y objetos incrustados. Incluye los siguientes tipos de archivo: [Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Odp), [Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Otp), [Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pot), [Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potm), [Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potx), [Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pps), [Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsm), [Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsx), [Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppt), [Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptm), [Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptx). Obtén más información sobre los formatos de Presentación [here][].


[here]: https://wiki.fileformat.com/presentation
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationFileType()](#PresentationFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Ppt](#Ppt) | Un archivo con extensión PPT representa un archivo PowerPoint que consta de una colección de diapositivas para mostrarse como presentación. |
| [Pps](#Pps) | PPS, PowerPoint Slide Show, los archivos se crean usando Microsoft PowerPoint con fines de presentación. |
| [Pptx](#Pptx) | Los archivos con extensión PPTX son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. |
| [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, los archivos se crean usando Microsoft PowerPoint 2007 o superior con fines de presentación. |
| [Odp](#Odp) | Los archivos con extensión ODP representan el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. |
| [Otp](#Otp) | Los archivos con extensión .OTP representan archivos de plantilla de presentación creados por aplicaciones en el formato estándar OASIS OpenDocument. |
| [Potx](#Potx) | Los archivos con extensión .POTX representan plantillas de presentación de Microsoft PowerPoint que se crean con Microsoft PowerPoint 2007 o superior. |
| [Pot](#Pot) | Los archivos con extensión .POT representan archivos de plantilla de Microsoft PowerPoint creados por versiones de PowerPoint 97-2003. |
| [Potm](#Potm) | Los archivos con extensión POTM son archivos de plantilla de Microsoft PowerPoint con soporte para macros. |
| [Pptm](#Pptm) | Los archivos con extensión PPTM son archivos de presentación con macros habilitadas que se crean con Microsoft PowerPoint 2007 o versiones superiores. |
| [Ppsm](#Ppsm) | Los archivos con extensión PPSM representan el formato de archivo de presentación con macros habilitadas creado con Microsoft PowerPoint 2007 o superior. |
| [Fodp](#Fodp) | Los archivos con extensión FODP representan una presentación OpenDocument Flat XML. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Constructor de serialización

### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Un archivo con extensión PPT representa un archivo PowerPoint que consta de una colección de diapositivas para mostrarse como presentación. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slide Show, los archivos se crean usando Microsoft PowerPoint con fines de presentación. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Los archivos con extensión PPTX son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de presentación Open XML de Microsoft PowerPoint. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


Los archivos PPSX, Power Point Slide Show, se crean usando Microsoft PowerPoint 2007 y versiones posteriores con el propósito de presentación de diapositivas. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Los archivos con extensión ODP representan el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Los archivos con extensión .OTP representan plantillas de presentación creadas por aplicaciones en el formato estándar OASIS OpenDocument. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Los archivos con extensión .POTX representan presentaciones de plantilla de Microsoft PowerPoint que se crean con Microsoft PowerPoint 2007 y versiones posteriores. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Los archivos con extensión .POT representan archivos de plantilla de Microsoft PowerPoint creados por las versiones PowerPoint 97-2003. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Los archivos con extensión POTM son archivos de plantilla de Microsoft PowerPoint con soporte para macros. Los archivos POTM se crean con PowerPoint 2007 o posterior y contienen configuraciones predeterminadas que pueden usarse para crear más archivos de presentación. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Los archivos con extensión PPTM son archivos de presentación con macros habilitadas que se crean con Microsoft PowerPoint 2007 o versiones superiores. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Los archivos con extensión PPSM representan el formato de archivo de presentación de diapositivas con macros habilitadas creado con Microsoft PowerPoint 2007 o posterior. Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Los archivos con extensión FODP representan una presentación OpenDocument Flat XML. El archivo de presentación se guarda en el formato OpenDocument, pero usando un formato XML plano en lugar del contenedor .ZIP utilizado por los archivos .ODP estándar.

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
