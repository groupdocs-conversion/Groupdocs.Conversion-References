---
title: "ImageLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Gambar."
type: docs
weight: 21
url: /id/java/com.groupdocs.conversion.options.load/imageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageLoadOptions extends LoadOptions implements Serializable
```

Opsi untuk memuat dokumen Gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ImageLoadOptions()](#ImageLoadOptions--) | Menginisialisasi instance baru dari kelas [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Font default untuk tipe dokumen Psd, Emf, Wmf. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font default untuk tipe dokumen Psd, Emf, Wmf. |
|
| [isRecognitionEnabled()](#isRecognitionEnabled--) |  |
| [getOcrConnector()](#getOcrConnector--) |  |
|  | [setOcrConnector(IOcrConnector ocrConnector)](#setOcrConnector-com.groupdocs.conversion.integration.ocr.IOcrConnector-) | Atur konektor OCR gambar |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | Reset folder font sebelum memuat dokumen |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
### ImageLoadOptions() {#ImageLoadOptions--}
```
public ImageLoadOptions()
```


Menginisialisasi instance baru dari kelas [ImageLoadOptions](../../com.groupdocs.conversion.options.load/imageloadoptions).


### getFormat() {#getFormat--}
```
public final ImageFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[ImageFileType](../../com.groupdocs.conversion.filetypes/imagefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font default untuk tipe dokumen Psd, Emf, Wmf. Font berikut akan digunakan jika font tidak tersedia.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font default untuk tipe dokumen Psd, Emf, Wmf. Font berikut akan digunakan jika font tidak tersedia.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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


Atur konektor OCR gambar


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ocrConnector | [IOcrConnector](../../com.groupdocs.conversion.integration.ocr/iocrconnector) | Instance konektor OCR |
|

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


Reset folder font sebelum memuat dokumen


**Returns:**
boolean
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resetFontFolders | boolean |  |

