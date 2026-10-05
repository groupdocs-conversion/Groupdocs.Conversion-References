---
title: "CadFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define documentos CAD (Computer Aided Design) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos: [Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dgn), [Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwf), [Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwg), [Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwt), [Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dxf), [Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Ifc), [Igs](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Igs), [Plt](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Plt), [Stl](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Stl). [Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Cf2). [Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwfx). Obtenga más información sobre los formatos CAD [here][]."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

DXF, Drawing Interchange Format, o Drawing Exchange Format, es una representación de datos etiquetada de un archivo de dibujo de AutoCAD.


[here]: https://wiki.fileformat.com/cad
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CadFileType()](#CadFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Dxf](#Dxf) | Los archivos con extensión DWG representan archivos binarios propietarios utilizados para contener datos de diseño 2D y 3D. |
| [Dwg](#Dwg) | DGN, Design, los archivos son dibujos creados y compatibles con aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. |
| [Dgn](#Dgn) | Design Web Format (DWF) representa dibujos 2D/3D en formato comprimido para visualizar, revisar o imprimir archivos de diseño. |
| [Dwf](#Dwf) | STL, abreviatura de estereolitografía, es un formato de archivo intercambiable que representa geometría de superficie tridimensional. |
| [Stl](#Stl) | Los archivos con extensión IFC se refieren al formato de archivo Industry Foundation Classes (IFC) que establece normas internacionales para importar y exportar objetos de construcción y sus propiedades. |
| [Ifc](#Ifc) | El formato de archivo PLT es un archivo de plotter basado en vectores introducido por Autodesk, Inc. |
| [Plt](#Plt) | Formato de documento Igs |
| [Igs](#Igs) | Un archivo DWT es una plantilla de dibujo de AutoCAD que se utiliza como punto de partida para crear dibujos que pueden guardarse como archivos DWG. |
| [Dwt](#Dwt) | El archivo DWFX es un dibujo 2D o 3D creado con el software CAD de Autodesk. |
| [Dwfx](#Dwfx) | Archivo de Formato de Archivo Común. |
| [Cf2](#Cf2) | DXF, Drawing Interchange Format, o Drawing Exchange Format, es una representación de datos etiquetada de un archivo de dibujo de AutoCAD. Obtenga más información sobre este formato de archivo [here][]. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Constructor de serialización

### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


Los archivos con extensión DWG representan archivos binarios propietarios utilizados para contener datos de diseño 2D y 3D. Al igual que DXF, que son archivos ASCII, DWG representa el formato de archivo binario para dibujos CAD (Computer Aided Design). Obtenga más información sobre este formato de archivo [here][]


[here]: https://wiki.fileformat.com/cad/dxf

### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


DGN, Design, los archivos son dibujos creados y compatibles con aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, Design, files son dibujos creados y compatibles con aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/cad/dgn

### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) representa dibujos 2D/3D en formato comprimido para ver, revisar o imprimir archivos de diseño. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo gracias a su formato comprimido. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, abreviatura de estereolitografía, es un formato de archivo intercambiable que representa la geometría de superficies tridimensionales. Este formato de archivo se utiliza en varios campos como el prototipado rápido, la impresión 3D y la fabricación asistida por computadora. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/stl

### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


Los archivos con extensión IFC se refieren al formato de archivo Industry Foundation Classes (IFC) que establece normas internacionales para importar y exportar objetos de construcción y sus propiedades. Este formato de archivo proporciona interoperabilidad entre diferentes aplicaciones de software. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### Plt {#Plt}
```
public static final CadFileType Plt
```


El formato de archivo PLT es un archivo de trazador vectorial introducido por Autodesk, Inc. y contiene información para un determinado archivo CAD. Los detalles de trazado requieren precisión y exactitud en la producción, y el uso del archivo PLT garantiza esto ya que todas las imágenes se imprimen con líneas en lugar de puntos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/plt

### Igs {#Igs}
```
public static final CadFileType Igs
```


Un archivo DWT es una plantilla de dibujo de AutoCAD que se utiliza como punto de partida para crear dibujos que pueden guardarse como archivos DWG.

### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


Un archivo DWT es una plantilla de dibujo de AutoCAD que se utiliza como punto de partida para crear dibujos que pueden guardarse como archivos DWG. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


El archivo DWFX es un dibujo 2D o 3D creado con el software CAD de Autodesk. Se guarda en el formato DWFx, que es similar a un archivo .DWF, pero está formateado usando la especificación XML Paper Specification (XPS) de Microsoft.

### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


Archivo de Formato Común. Archivo CAD que contiene diseños de paquetes 3D u otros datos de modelo; puede ser procesado y cortado por una máquina CAD/CAM, como un dispositivo de troquelado.

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
