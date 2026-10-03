---
title: "ImageLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för att läsa in bilddokument."
type: docs
weight: 21
url: /sv/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Alternativ för att läsa in bilddokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | Initierar en ny instans av [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) klass. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standardteckensnitt för Psd-, Emf- och Wmf-dokumenttyper. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standardteckensnitt för Psd-, Emf- och Wmf-dokumenttyper. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Ställ in bild-OCR-anslutning |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Återställ teckensnittsmappar innan dokumentet laddas |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Initierar en ny instans av [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) klass.


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Dokumentfiltyp för inmatning


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standardteckensnitt för Psd-, Emf- och Wmf-dokumenttyper. Följande teckensnitt kommer att användas om ett teckensnitt saknas.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standardteckensnitt för Psd-, Emf- och Wmf-dokumenttyper. Följande teckensnitt kommer att användas om ett teckensnitt saknas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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


Ställ in bild-OCR-anslutning


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR-anslutningsinstans |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Återställ teckensnittsmappar innan dokumentet laddas


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resetFontFolders | boolean |  |

