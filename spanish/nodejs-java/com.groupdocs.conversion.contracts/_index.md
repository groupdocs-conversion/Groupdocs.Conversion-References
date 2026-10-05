---
title: "com.groupdocs.conversion.contracts"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "El espacio de nombres GroupDocs.Conversion.Contracts proporciona miembros para instanciar y liberar documentos de salida, gestionar sustituciones de fuentes, etc."
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.conversion.contracts/
---

El espacio de nombres GroupDocs.Conversion.Contracts proporciona miembros para instanciar y liberar el documento de salida, gestionar sustituciones de fuentes, etc.


## Clases

| Clase | Descripción |
| --- | --- |
| [ConversionPair](../com.groupdocs.conversion.contracts/conversionpair) | Representa un par de conversión |
| [Enumeration](../com.groupdocs.conversion.contracts/enumeration) | Clase de enumeración genérica. |
| [FontSubstitute](../com.groupdocs.conversion.contracts/fontsubstitute) | Describe la sustitución para fuentes faltantes. |
| [PossibleConversions](../com.groupdocs.conversion.contracts/possibleconversions) | Representa un mapeo de los pares de conversión compatibles con un formato de archivo fuente específico |
| [TargetConversion](../com.groupdocs.conversion.contracts/targetconversion) | Representa la conversión de destino posible y una bandera que indica si es primaria o secundaria |
| [ValueObject](../com.groupdocs.conversion.contracts/valueobject) | Clase abstracta de objeto de valor. |

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [ConvertOptionsProvider](../com.groupdocs.conversion.contracts/convertoptionsprovider) | Describe el delegado que proporciona opciones de conversión para un documento fuente específico. |
| [ConvertedDocumentStream](../com.groupdocs.conversion.contracts/converteddocumentstream) | Describe el delegado que recibe el flujo del documento convertido. |
| [ConvertedPageStream](../com.groupdocs.conversion.contracts/convertedpagestream) | Describe el delegado que recibe el flujo de la página convertida. |
| [ConverterSettingsProvider](../com.groupdocs.conversion.contracts/convertersettingsprovider) | Proveedor de ConverterSettings |
| [DocumentStreamProvider](../com.groupdocs.conversion.contracts/documentstreamprovider) | Proveedor para InputStream |
| [DocumentStreamsProvider](../com.groupdocs.conversion.contracts/documentstreamsprovider) | Proveedor para matriz de InputStream |
| [SaveDocumentStream](../com.groupdocs.conversion.contracts/savedocumentstream) | Describe el delegado para guardar el documento convertido en un flujo de salida. |
| [SaveDocumentStreamForFileType](../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Describe el delegado para guardar el documento convertido en un flujo. |
| [SavePageStream](../com.groupdocs.conversion.contracts/savepagestream) | Describe el delegado para guardar la página del documento convertido en un flujo. |
| [SavePageStreamForFileType](../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Describe el delegado para guardar la página del documento convertido en un flujo. |
