---
title: "CadFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos CAD (Diseño Asistido por Computadora) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos Cf2./cadfiletype/cf2 Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfx Dwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Obtén más información sobre los formatos CAD aquíhttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /es/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Define documentos CAD (Diseño Asistido por Computadora) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Obtén más información sobre los formatos CAD [aquí](https://wiki.fileformat.com/cad).

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Archivo de Formato Común. Archivo CAD que contiene diseños de paquetes 3D u otros datos de modelo; puede ser procesado y cortado por una máquina CAD/CAM, como un dispositivo de troquelado. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | Los archivos DGN, Design, son dibujos creados y compatibles con aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) representa dibujos 2D/3D en formato comprimido para visualizar, revisar o imprimir archivos de diseño. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo gracias a su formato comprimido. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | El archivo DWFX es un dibujo 2D o 3D creado con el software CAD de Autodesk. Se guarda en el formato DWFx, que es similar a un archivo .DWF, pero está formateado usando la especificación XML Paper Specification (XPS) de Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | Los archivos con extensión DWG representan archivos binarios propietarios utilizados para contener datos de diseño 2D y 3D. Al igual que DXF, que son archivos ASCII, DWG representa el formato de archivo binario para dibujos CAD (Computer Aided Design). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | Un archivo DWT es una plantilla de dibujo de AutoCAD que se utiliza como punto de partida para crear dibujos que pueden guardarse como archivos DWG. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, o Drawing Exchange Format, es una representación de datos etiquetados de un archivo de dibujo AutoCAD. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | Los archivos con extensión IFC se refieren al formato de archivo Industry Foundation Classes (IFC) que establece normas internacionales para importar y exportar objetos de construcción y sus propiedades. Este formato de archivo proporciona interoperabilidad entre diferentes aplicaciones de software. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Formato de documento Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | El formato de archivo PLT es un archivo de trazador basado en vectores introducido por Autodesk, Inc. y contiene información para un determinado archivo CAD. Los detalles de trazado requieren precisión y exactitud en la producción, y el uso del archivo PLT garantiza esto ya que todas las imágenes se imprimen usando líneas en lugar de puntos. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, abreviatura de estereolitografía, es un formato de archivo intercambiable que representa geometría de superficie tridimensional. Este formato de archivo se utiliza en varios campos como el prototipado rápido, la impresión 3D y la fabricación asistida por computadora. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/cad/stl). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
