---
title: "ImageLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von Bilddokumenten."
type: docs
weight: 21
url: /de/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Optionen zum Laden von Bilddokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | Initialisiert eine neue Instanz der Klasse [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Standard-Schriftart für Psd-, Emf- und Wmf-Dokumenttypen. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Standard-Schriftart für Psd-, Emf- und Wmf-Dokumenttypen. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Bild-OCR-Connector festlegen |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Schriftordner vor dem Laden des Dokuments zurücksetzen. |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions).


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Eingabedokument-Dateityp


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Standard-Schriftart für Psd-, Emf- und Wmf-Dokumenttypen. Die folgende Schriftart wird verwendet, wenn eine Schrift fehlt.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Standard-Schriftart für Psd-, Emf- und Wmf-Dokumenttypen. Die folgende Schriftart wird verwendet, wenn eine Schrift fehlt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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


Bild-OCR-Connector festlegen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR-Connector-Instanz |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Schriftordner vor dem Laden des Dokuments zurücksetzen.


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resetFontFolders | boolean |  |

