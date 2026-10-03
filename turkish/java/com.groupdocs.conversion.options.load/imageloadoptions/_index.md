---
title: "ImageLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Görüntü belgelerini yükleme seçenekleri."
type: docs
weight: 21
url: /tr/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Görüntü belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | Yeni bir [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) sınıfının örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Psd, Emf, Wmf belge türleri için varsayılan yazı tipi. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Psd, Emf, Wmf belge türleri için varsayılan yazı tipi. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Görüntü OCR bağlayıcısını ayarla |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Yeni bir [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions) sınıfının örneğini başlatır.


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Girdi belge dosya türü


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Psd, Emf, Wmf belge türleri için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Psd, Emf, Wmf belge türleri için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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


Görüntü OCR bağlayıcısını ayarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | OCR bağlayıcı örneği |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resetFontFolders | boolean |  |

