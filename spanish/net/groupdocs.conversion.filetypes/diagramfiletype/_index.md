---
title: "DiagramFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos Diagram. Incluye los siguientes tipos Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /es/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Define documentos Diagram. Incluye los siguientes tipos: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Constructor de serialización |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | Un archivo con extensión DRAWIO es un diagrama creado con diagrams.net (anteriormente draw.io). Se almacena en formato de archivo XML con el elemento raíz mxfile y contiene el contenido y formato de los elementos del diagrama como texto, imágenes, diseño, formas y posicionamiento. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | Un archivo con extensión MMD es un diagrama escrito en el lenguaje de marcado Mermaid. Se almacena como un documento de texto plano que comienza con la declaración del diagrama, como flowchart o sequenceDiagram, seguido de la definición de los nodos y las conexiones entre ellos. Obtén más información sobre este formato de archivo [aquí](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW es el formato de archivo Visio Graphics Service que especifica los flujos y almacenes requeridos para renderizar un dibujo web. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Cualquier dibujo o gráfico creado en Microsoft Visio, pero guardado en formato XML tiene la extensión .VDX. Un archivo XML de dibujo Visio se crea en el software Visio, que es desarrollado por Microsoft. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | Los archivos VSD son dibujos creados con la aplicación Microsoft Visio para representar una variedad de objetos gráficos y la interconexión entre ellos. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | Los archivos con extensión VSDM son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. Los archivos VSDM son dibujos OPC/XML similares a VSDX, pero también ofrecen la capacidad de ejecutar macros cuando se abre el archivo. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | Los archivos con extensión .VSDX representan el formato de archivo de Microsoft Visio introducido a partir de Microsoft Office 2013. Fue desarrollado para reemplazar el formato de archivo binario, .VSD, que es compatible con versiones anteriores de Microsoft Visio. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS son archivos de plantilla creados con Microsoft Visio 2007 y versiones anteriores. Los archivos de plantilla proporcionan objetos de dibujo que pueden incluirse en un dibujo .VSD de Visio. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | Los archivos con extensión .VSSM son archivos de plantilla de Microsoft Visio que admiten macros. Un archivo VSSM, al abrirse, permite ejecutar las macros para lograr el formato y la ubicación deseada de las formas en un diagrama. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | Los archivos con extensión .VSSX son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. El formato de archivo VSSX puede abrirse con Visio 2013 y versiones posteriores. Los archivos de Visio son conocidos por representar una variedad de elementos de dibujo, como colecciones de formas, conectores, diagramas de flujo, diseños de red, diagramas UML. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | Los archivos con extensión VST son archivos de imagen vectorial creados con Microsoft Visio y actúan como plantillas para crear más archivos. Estos archivos de plantilla están en formato binario y contienen el diseño y la configuración predeterminados que se utilizan para crear nuevos dibujos de Visio. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | Los archivos con extensión VSTM son archivos de plantilla creados con Microsoft Visio que admiten macros. A diferencia de los archivos VSDX, los archivos creados a partir de plantillas VSTM pueden ejecutar macros desarrolladas en código Visual Basic for Applications (VBA). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | Los archivos con extensión VSTX son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. Estos archivos VSTX proporcionan un punto de partida para crear dibujos de Visio, guardados como archivos .VSDX, con diseño y configuración predeterminados. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | Los archivos con extensión .VSX se refieren a plantillas que consisten en dibujos y formas que se utilizan para crear diagramas en Microsoft Visio. Los archivos VSX se guardan en formato XML y fueron compatibles hasta Visio 2013. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | Un archivo con extensión VTX es una plantilla de dibujo de Microsoft Visio que se guarda en disco en formato XML. La plantilla está diseñada para proporcionar un archivo con configuraciones básicas que pueden usarse para crear múltiples archivos de Visio con los mismos ajustes. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/image/vtx). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
