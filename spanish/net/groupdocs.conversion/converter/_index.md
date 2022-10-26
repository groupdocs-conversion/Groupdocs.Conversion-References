---
title: Converter
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Representa la clase principal que controla el proceso de conversión de documentos.
type: docs
weight: 670
url: /es/net/groupdocs.conversion/converter/
---
## Converter class

Representa la clase principal que controla el proceso de conversión de documentos.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Converter](converter#constructor)() | Inicializa una nueva instancia de[`Converter`](../converter) clase para configuración de conversión fluida. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_7)(string) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Inicializa una nueva instancia de[`Converter`](../converter) clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(SaveDocumentStream, ConvertOptions) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(SaveDocumentStream, ConvertOptionsProvider) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(SaveDocumentStreamForFileType, ConvertOptions) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(SaveDocumentStreamForFileType, ConvertOptionsProvider) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(SavePageStream, ConvertOptions) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(SavePageStream, ConvertOptionsProvider) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(SavePageStreamForFileType, ConvertOptions) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(SavePageStreamForFileType, ConvertOptionsProvider) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) | Convierte el documento de origen. Guarda todo el documento convertido. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(SavePageStream, ConvertedPageStream, ConvertOptions) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) | Convierte el documento de origen. Guarda el documento convertido página por página. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Libera recursos. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Obtiene información del documento de origen: recuento de páginas y otras propiedades del documento específicas del tipo de archivo. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Obtiene posibles conversiones para el documento fuente. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Configurar secuencia de documentos de origen |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Configurar conjunto de flujos de documentos de origen |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Configurar documento fuente para conversión |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Configurar conjunto de documentos de origen |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Configurar ajustes de conversión |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Obtiene todas las conversiones admitidas |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Obtiene conversiones admitidas para la extensión de documento proporcionada |

### Ver también

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* espacio de nombres [GroupDocs.Conversion](../../groupdocs.conversion)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
