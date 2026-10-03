---
title: "ImageLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van afbeelding‑documenten."
type: docs
weight: 21
url: /nl/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Opties voor het laden van afbeelding‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standaardlettertype voor Psd-, Emf- en Wmf-documenttypen. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standaardlettertype voor Psd-, Emf- en Wmf-documenttypen. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Stel afbeeldings-OCR-connector in |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Reset lettertype-mappen vóór het laden van het document |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions).


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Invoerdocumentbestandstype


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standaardlettertype voor Psd-, Emf- en Wmf-documenttypen. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standaardlettertype voor Psd-, Emf- en Wmf-documenttypen. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
boolean
### getOcrConnector() {#getOcrConnector--}
```
public IOcrConnector getOcrConnector()
```




**Returns:**
[IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector)
### setOcrConnector(IOcrConnector ocrConnector) {#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-}
```
public void setOcrConnector(IOcrConnector ocrConnector)
```


Stel afbeeldings-OCR-connector in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR-connectorinstantie |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset lettertype-mappen vóór het laden van het document


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resetFontFolders | boolean |  |

