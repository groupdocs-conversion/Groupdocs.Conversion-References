---
title: "ImageLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Image."
type: docs
weight: 21
url: /it/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Opzioni per il caricamento dei documenti Image.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | Inizializza una nuova istanza della classe [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Carattere predefinito per i tipi di documento Psd, Emf, Wmf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Carattere predefinito per i tipi di documento Psd, Emf, Wmf. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Imposta il connettore OCR dell'immagine |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Reimposta le cartelle dei caratteri prima di caricare il documento |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Inizializza una nuova istanza della classe [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions).


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Tipo di file del documento di input


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Carattere predefinito per i tipi di documento Psd, Emf, Wmf. Il carattere seguente verrà utilizzato se ne manca uno.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Carattere predefinito per i tipi di documento Psd, Emf, Wmf. Il carattere seguente verrà utilizzato se ne manca uno.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### isRecognitionEnabled() {#isRecognitionEnabled--}
```
public boolean isRecognitionEnabled()
```




**Returns:**
booleano
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


Imposta il connettore OCR dell'immagine


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | Istanza del connettore OCR |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reimposta le cartelle dei caratteri prima di caricare il documento


**Returns:**
booleano
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resetFontFolders | booleano |  |

