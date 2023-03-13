---
title: ThreeDFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define documentos 3D Incluye los siguientes tipos Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/x Más información sobre formatos 3Daquíhttps//wiki.fileformat.com/3d .
type: docs
weight: 1060
url: /es/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Define documentos 3D Incluye los siguientes tipos: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x) Más información sobre formatos 3D[aquí](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Constructor de serialización |

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
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Un archivo AMF consta de pautas para la descripción de objetos para ser utilizados por los procesos de Fabricación Aditiva. Contiene una etiqueta XML de apertura y termina con un elemento. Está precedido por una línea de declaración XML que especifica la versión XML y la codificación del archivo. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Un archivo con una extensión .ase es un formato de archivo de exportación de escena ASCII de Autodesk que es una representación ASCII de una escena, que contiene información 2D o 3D mientras se exportan datos de escena usando Autodesk. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Un archivo DAE es un formato de archivo de intercambio de activos digitales que se utiliza para intercambiar datos entre aplicaciones 3D interactivas. Este formato de archivo se basa en el esquema XML COLLADA (COLLAborative Design Activity), que es un esquema XML estándar abierto para el intercambio de activos digitales entre aplicaciones de software de gráficos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Un archivo con extensión .drc es un formato de archivo 3D comprimido creado con la biblioteca Google Draco. Google ofrece Draco como biblioteca de código abierto para comprimir y descomprimir mallas geométricas 3D y nubes de puntos, y mejora el almacenamiento y la transmisión de gráficos 3D. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, es un popular formato de archivo 3D desarrollado originalmente por Kaydara para MotionBuilder. Fue adquirido por Autodesk Inc en 2006 y ahora es uno de los principales formatos de intercambio 3D que utilizan muchas herramientas 3D. FBX está disponible en formato de archivo binario y ASCII. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (formato de transmisión GL) es un formato de archivo 3D que almacena información del modelo 3D en formato JSON. El uso de JSON minimiza tanto el tamaño de los activos 3D como el procesamiento en tiempo de ejecución necesario para desempaquetar y usar esos activos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) es un formato de datos 3D estandarizado ISO eficiente, flexible y centrado en la industria desarrollado por Siemens PLM Software. Los dominios de CAD mecánico de la industria aeroespacial, automotriz y de equipos pesados utilizan JT como su formato de visualización 3D más importante. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Los archivos OBJ son utilizados por la aplicación Advanced Visualizer de Wavefront para definir y almacenar los objetos geométricos. La transmisión hacia adelante y hacia atrás de datos geométricos es posible a través de archivos OBJ. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, representa un formato de archivo 3D que almacena objetos gráficos descritos como una colección de polígonos. El propósito de este formato de archivo fue establecer un tipo de archivo simple y fácil que sea lo suficientemente general como para ser útil para una amplia gama de modelos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | Los archivos de datos RVM están relacionados con AVEVA PDMS. El archivo RVM es un archivo de proyecto del modelo del sistema de gestión de diseño de plantas de AVEVA. El sistema de gestión de diseño de plantas (PDMS) de AVEVA es el sistema de diseño 3D más popular que utiliza tecnología centrada en datos para gestionar proyectos. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Un archivo con extensión .3ds representa el formato de archivo de malla 3D Sudio (DOS) utilizado por Autodesk 3D Studio. Autodesk 3D Studio ha estado en el mercado de formatos de archivo 3D desde la década de 1990 y ahora ha evolucionado a 3D Studio MAX para trabajar con modelado, animación y renderizado 3D. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, formato de fabricación 3D, lo utilizan las aplicaciones para representar modelos de objetos 3D en una variedad de otras aplicaciones, plataformas, servicios e impresoras. Se creó para evitar las limitaciones y los problemas de otros formatos de archivo 3D, como STL, para trabajar con las últimas versiones de impresoras 3D. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) es un formato de archivo comprimido y una estructura de datos para gráficos 3D por computadora. Contiene información del modelo 3D, como mallas triangulares, iluminación, sombreado, datos de movimiento, líneas y puntos con color y estructura. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Un archivo con extensión .usd es un formato de archivo de descripción de escena universal que codifica datos con el fin de intercambiar y aumentar datos entre aplicaciones de creación de contenido digital. Desarrollado por Pixar, USD brinda la capacidad de intercambiar activos elementales (como modelos) o animaciones. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Un archivo con .usdz es un archivo ZIP sin comprimir y sin cifrar para el formato de archivo USD (Universal Scene Description) que contiene y representa archivos de otros formatos (como texturas y animaciones) incrustados dentro del archivo y los ejecuta directamente con el Tiempo de ejecución USD sin necesidad de desempaquetar. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | El lenguaje de modelado de realidad virtual (VRML) es un formato de archivo para la representación de objetos del mundo 3D interactivos en la World Wide Web (www). Encuentra su uso en la creación de representaciones tridimensionales de escenas complejas, como ilustraciones, definición y presentaciones de realidad virtual. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Un archivo con la extensión .x hace referencia al formato de archivo heredado de DirectX 3D Graphics que se introdujo con Microsoft DirectX 2.0. Se utilizó para la representación de gráficos 3D en juegos y especifica las estructuras para mallas, texturas, animaciones y objetos definidos por el usuario. Ha quedado obsoleto desde 2014 porque el formato de archivo Autodesk FBX funciona mejor como un formato más moderno. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/3d/x) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
