---
title: CadFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define documentos CAD diseño asistido por computadora que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Obtenga más información sobre los formatos CADaquíhttps//wiki.fileformat.com/cad .
type: docs
weight: 800
url: /es/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Define documentos CAD (diseño asistido por computadora) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos: [`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Obtenga más información sobre los formatos CAD[aquí](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CadFileType](cadfiletype)() | Constructor de serialización |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Archivo de formato de archivo común. Archivo CAD que contiene diseños de paquetes 3D u otros datos de modelo; se puede procesar y cortar con una máquina CAD/CAM, como un dispositivo de troquelado. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design, los archivos son dibujos creados y admitidos por aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) representa dibujos 2D/3D en formato comprimido para ver, revisar o imprimir archivos de diseño. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo debido a su formato comprimido. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | El archivo DWFX es un dibujo 2D o 3D creado con el software CAD de Autodesk. Se guarda en formato DWFx, que es similar a un archivo . DWF, pero está formateado con la especificación de papel XML (XPS) de Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Los archivos con extensión DWG representan archivos binarios propietarios que se utilizan para contener datos de diseño 2D y 3D. Al igual que DXF, que son archivos ASCII, DWG representa el formato de archivo binario para dibujos CAD (diseño asistido por computadora). Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Un archivo DWT es un archivo de plantilla de dibujo de AutoCAD que se utiliza como iniciador para crear dibujos que se pueden guardar como archivos DWG. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, formato de intercambio de dibujos o formato de intercambio de dibujos, es una representación de datos etiquetados del archivo de dibujo de AutoCAD. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Los archivos con extensión IFC se refieren al formato de archivo Industry Foundation Classes (IFC) que establece estándares internacionales para importar y exportar objetos de construcción y sus propiedades. Este formato de archivo proporciona interoperabilidad entre diferentes aplicaciones de software. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | formato documento Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | El formato de archivo PLT es un archivo de trazador basado en vectores introducido por Autodesk, Inc. y contiene información para un determinado archivo CAD. Los detalles de trazado requieren exactitud y precisión en la producción, y el uso del archivo PLT lo garantiza, ya que todas las imágenes se imprimen utilizando líneas en lugar de puntos. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abreviatura de estereolitrografía, es un formato de archivo intercambiable que representa geometría de superficie tridimensional. El formato de archivo encuentra su uso en varios campos, como la creación rápida de prototipos, la impresión 3D y la fabricación asistida por computadora. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/cad/stl) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
