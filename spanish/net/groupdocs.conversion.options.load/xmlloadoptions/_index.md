---
title: "XmlLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos XML."
type: docs
weight: 2960
url: /es/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Opciones para cargar documentos XML.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Inicializa una nueva instancia de la clase [`XmlLoadOptions`](../xmlloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | La ruta/base URL para el HTML |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Acción para la configuración de los encabezados de la solicitud. El primer parámetro de la acción es el Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Proveedor de credenciales para el Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Implementa [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle). |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Obtiene o establece la codificación que se usará al cargar el documento web. Si la propiedad es nula, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Controla cómo se renderiza el contenido HTML. Predeterminado: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Configuración de márgenes de página |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Configuración de la orientación de la página |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Especifica las opciones de diseño de página al cargar documentos web. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Habilita o deshabilita la generación de numeración de páginas en el documento convertido. Valor predeterminado: falso |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Tiempo de espera para cargar recursos externos |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Configuración de tamaño de página |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Usar documento Xml como fuente de datos |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Usar pdf para la conversión. Predeterminado: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | Secuencia de documento XSL-FO para convertir XML usando un archivo de marcado XSL-FO. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | Secuencia de documento XSLT para convertir XML realizando una transformación XSL a HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Especifica el nivel de zoom como un porcentaje. El nivel de zoom se aplica a la etiqueta &lt;body&gt; del documento antes de la conversión, escalando la apariencia visual del documento. Un valor del 100% representa el tamaño original. El valor predeterminado es 100. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
