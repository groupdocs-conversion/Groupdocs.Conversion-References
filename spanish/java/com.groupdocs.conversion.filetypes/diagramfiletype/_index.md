---
title: "DiagramFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define documentos de diagramas."
type: docs
weight: 13
url: /es/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Define documentos de Diagrama. Incluye los siguientes tipos:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Vsd](#Vsd) | Los archivos VSD son dibujos creados con la aplicación Microsoft Visio para representar una variedad de objetos gráficos y la interconexión entre ellos. |
|
|  | [Vsdx](#Vsdx) | Los archivos con extensión .VSDX representan el formato de archivo de Microsoft Visio introducido a partir de Microsoft Office 2013. |
|
|  | [Vss](#Vss) | VSS son archivos de plantilla creados con Microsoft Visio 2007 y versiones anteriores. |
|
|  | [Vst](#Vst) | Los archivos con extensión VST son archivos de imagen vectorial creados con Microsoft Visio y actúan como plantilla para crear más archivos. |
|
|  | [Vsx](#Vsx) | Los archivos con extensión .VSX se refieren a plantillas que consisten en dibujos y formas que se utilizan para crear diagramas en Microsoft Visio. |
|
|  | [Vtx](#Vtx) | Un archivo con extensión VTX es una plantilla de dibujo de Microsoft Visio que se guarda en disco en formato de archivo XML. |
|
|  | [Vdw](#Vdw) | VDW es el formato de archivo del Visio Graphics Service que especifica los flujos y almacenes necesarios para renderizar un dibujo web. |
|
|  | [Vdx](#Vdx) | Cualquier dibujo o gráfico creado en Microsoft Visio, pero guardado en formato XML, tiene la extensión .VDX. |
|
|  | [Vssx](#Vssx) | Los archivos con extensión .VSSX son plantillas de dibujo creadas con Microsoft Visio 2013 y posteriores. |
|
|  | [Vstx](#Vstx) | Los archivos con extensiones VSTX son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y posteriores. |
|
|  | [Vsdm](#Vsdm) | Los archivos con extensión VSDM son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. |
|
|  | [Vssm](#Vssm) | Los archivos con extensión .VSSM son archivos de plantilla de Microsoft Visio que proporcionan soporte para macros. |
|
|  | [Vstm](#Vstm) | Los archivos con extensión VSTM son archivos de plantilla creados con Microsoft Visio que admiten macros. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Constructor de serialización


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


Los archivos VSD son dibujos creados con la aplicación Microsoft Visio para representar una variedad de objetos gráficos y la interconexión entre ellos.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Los archivos con extensión .VSDX representan el formato de archivo de Microsoft Visio introducido a partir de Microsoft Office 2013. Fue desarrollado para reemplazar el formato de archivo binario, .VSD, que es compatible con versiones anteriores de Microsoft Visio.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS son archivos de plantilla creados con Microsoft Visio 2007 y versiones anteriores. Los archivos de plantilla proporcionan objetos de dibujo que pueden incluirse en un dibujo .VSD de Visio.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Los archivos con extensión VST son archivos de imagen vectorial creados con Microsoft Visio y actúan como plantilla para crear más archivos. Estos archivos de plantilla están en formato de archivo binario y contienen el diseño y la configuración predeterminados que se utilizan para la creación de nuevos dibujos de Visio.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Los archivos con extensión .VSX se refieren a plantillas que consisten en dibujos y formas que se utilizan para crear diagramas en Microsoft Visio. Los archivos VSX se guardan en formato de archivo XML y fueron compatibles hasta Visio 2013.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


Un archivo con extensión VTX es una plantilla de dibujo de Microsoft Visio que se guarda en disco en formato de archivo XML. La plantilla está diseñada para proporcionar un archivo con configuraciones básicas que pueden usarse para crear múltiples archivos de Visio con los mismos ajustes.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW es el formato de archivo del Visio Graphics Service que especifica los flujos y almacenes necesarios para renderizar un dibujo web.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Cualquier dibujo o diagrama creado en Microsoft Visio, pero guardado en formato XML, tiene la extensión .VDX. Un archivo XML de dibujo de Visio se crea en el software Visio, que es desarrollado por Microsoft.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Los archivos con extensión .VSSX son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. El formato de archivo VSSX puede abrirse con Visio 2013 y versiones posteriores. Los archivos de Visio son conocidos por la representación de una variedad de elementos de dibujo, como colecciones de formas, conectores, diagramas de flujo, diseños de red, diagramas UML,
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Los archivos con extensiones VSTX son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. Estos archivos VSTX proporcionan un punto de partida para crear dibujos de Visio, guardados como archivos .VSDX, con diseño y configuraciones predeterminados.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Los archivos con extensión VSDM son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. Los archivos VSDM son dibujos OPC/XML similares a VSDX, pero también ofrecen la capacidad de ejecutar macros cuando se abre el archivo.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Los archivos con extensión .VSSM son archivos de plantilla de Microsoft Visio que proporcionan soporte para macros. Un archivo VSSM, al abrirse, permite ejecutar las macros para lograr el formato y la ubicación deseados de las formas en un diagrama.
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Los archivos con extensión VSTM son archivos de plantilla creados con Microsoft Visio que admiten macros. A diferencia de los archivos VSDX, los archivos creados a partir de plantillas VSTM pueden ejecutar macros desarrolladas en código Visual Basic for Applications (VBA).
Obtén más información sobre este formato de archivo [aquí](../https://wiki.fileformat.com/image/vstm).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
