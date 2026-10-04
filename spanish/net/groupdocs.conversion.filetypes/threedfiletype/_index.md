---
title: "TipoDeArchivo3D"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos 3D Incluye los siguientes tipos Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Obtenga más información sobre los formatos 3D aquíhttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /es/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Define documentos 3D Incluye los siguientes tipos: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Obtenga más información sobre los formatos 3D [aquí](https://wiki.fileformat.com/3d).

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Un archivo AMF consiste en directrices para la descripción de objetos con el fin de ser utilizado por procesos de fabricación aditiva. Contiene una etiqueta XML de apertura y termina con un elemento. Esto va precedido por una línea de declaración XML que especifica la versión XML y la codificación del archivo. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Un archivo con extensión .ase es un formato de archivo Autodesk ASCII Scene Export que es una representación ASCII de una escena, que contiene información 2D o 3D al exportar datos de escena usando Autodesk. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Un archivo DAE es un formato de archivo Digital Asset Exchange que se utiliza para intercambiar datos entre aplicaciones 3D interactivas. Este formato de archivo se basa en el esquema XML COLLADA (COLLAborative Design Activity) que es un estándar abierto XML para el intercambio de activos digitales entre aplicaciones de software gráfico. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Un archivo con extensión .drc es un formato de archivo 3D comprimido creado con la biblioteca Google Draco. Google ofrece Draco como una biblioteca de código abierto para comprimir y descomprimir mallas geométricas 3D y nubes de puntos, y mejora el almacenamiento y la transmisión de gráficos 3D. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, es un formato de archivo 3D popular que fue desarrollado originalmente por Kaydara para MotionBuilder. Fue adquirido por Autodesk Inc en 2006 y ahora es uno de los principales formatos de intercambio 3D utilizados por muchas herramientas 3D. FBX está disponible tanto en formato binario como ASCII. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB es la representación en formato de archivo binario de modelos 3D guardados en el GL Transmission Format (glTF). Este formato binario almacena el activo glTF (JSON, .bin e imágenes) en un blob binario. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) es un formato de archivo 3D que almacena la información de modelos 3D en formato JSON. El uso de JSON minimiza tanto el tamaño de los activos 3D como el procesamiento en tiempo de ejecución necesario para desempaquetar y usar esos activos. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) es un formato de datos 3D eficiente, centrado en la industria y flexible, estandarizado por ISO, desarrollado por Siemens PLM Software. Los dominios de CAD mecánico de la industria aeroespacial, automotriz y de equipos pesados utilizan JT como su principal formato de visualización 3D. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | Un archivo con extensión .ma es un archivo de proyecto 3D creado con la aplicación Autodesk Maya. Contiene una gran lista de comandos textuales para especificar información sobre el archivo. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | Un archivo con extensión .mb es un archivo de proyecto binario creado con la aplicación Autodesk Maya. A diferencia del formato de archivo MA, que está en formato ASCII, los archivos MB se almacenan en formato binario. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | Los archivos OBJ son utilizados por la aplicación Advanced Visualizer de Wavefront para definir y almacenar los objetos geométricos. La transmisión hacia atrás y hacia adelante de datos geométricos es posible mediante archivos OBJ. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, representa un formato de archivo 3D que almacena objetos gráficos descritos como una colección de polígonos. El propósito de este formato de archivo era establecer un tipo de archivo simple y fácil que fuera lo suficientemente general como para ser útil en una amplia gama de modelos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | Los archivos de datos RVM están relacionados con AVEVA PDMS. El archivo RVM es un archivo de proyecto del modelo del Sistema de Gestión de Diseño de Plantas AVEVA. El Sistema de Gestión de Diseño de Plantas (PDMS) de AVEVA es el sistema de diseño 3D más popular que utiliza tecnología centrada en datos para gestionar proyectos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Un archivo con extensión .3ds representa el formato de archivo de malla 3D Studio (DOS) utilizado por Autodesk 3D Studio. Autodesk 3D Studio ha estado en el mercado de formatos de archivo 3D desde la década de 1990 y ahora ha evolucionado a 3D Studio MAX para trabajar con modelado, animación y renderizado 3D. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, es utilizado por aplicaciones para renderizar modelos de objetos 3D a una variedad de otras aplicaciones, plataformas, servicios e impresoras. Fue creado para evitar las limitaciones y problemas de otros formatos de archivo 3D, como STL, al trabajar con las versiones más recientes de impresoras 3D. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) es un formato de archivo comprimido y una estructura de datos para gráficos por computadora 3D. Contiene información de modelos 3D como mallas de triángulos, iluminación, sombreado, datos de movimiento, líneas y puntos con color y estructura. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Un archivo con extensión .usd es un formato de archivo Universal Scene Description que codifica datos con el propósito de intercambiar y ampliar datos entre aplicaciones de creación de contenido digital. Desarrollado por Pixar, USD brinda la capacidad de intercambiar activos elementales (como modelos) o animaciones. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Un archivo con extensión .usdz es un archivo ZIP sin comprimir y sin cifrar para el formato de archivo USD (Universal Scene Description) que contiene y actúa como proxy de archivos de otros formatos (como texturas y animaciones) incrustados dentro del archivo y los ejecuta directamente con el tiempo de ejecución de USD sin necesidad de descomprimir. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | El Lenguaje de Modelado de Realidad Virtual (VRML) es un formato de archivo para la representación de objetos 3D interactivos en la World Wide Web (www). Se utiliza para crear representaciones tridimensionales de escenas complejas, como ilustraciones, definiciones y presentaciones de realidad virtual. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Un archivo con extensión .x se refiere al formato de archivo heredado DirectX 3D Graphics que se introdujo con Microsoft DirectX 2.0. Se utilizó para el renderizado de gráficos 3D en juegos y especifica las estructuras para mallas, texturas, animaciones y objetos definidos por el usuario. Ha quedado obsoleto desde 2014, ya que el formato de archivo Autodesk FBX sirve mejor como un formato más moderno. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/3d/x). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
