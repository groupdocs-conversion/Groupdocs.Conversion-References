---
title: "NoteLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen One."
type: docs
weight: 24
url: /id/java/com.groupdocs.conversion.options.load/noteloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class NoteLoadOptions extends LoadOptions implements Serializable
```

Opsi untuk memuat dokumen One.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [NoteLoadOptions()](#NoteLoadOptions--) | Menginisialisasi instance baru dari kelas [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Font default untuk dokumen Note. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font default untuk dokumen Note. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Ganti font tertentu saat mengonversi dokumen Note. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Ganti font tertentu saat mengonversi dokumen Note. |
|
|  | [getPassword()](#getPassword--) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |
|
### NoteLoadOptions() {#NoteLoadOptions--}
```
public NoteLoadOptions()
```


Menginisialisasi instance baru dari kelas [NoteLoadOptions](../../com.groupdocs.conversion.options.load/noteloadoptions).


### getFormat() {#getFormat--}
```
public final NoteFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[NoteFileType](../../com.groupdocs.conversion.filetypes/notefiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font default untuk dokumen Note. Font berikut akan digunakan jika sebuah font tidak ditemukan.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font default untuk dokumen Note. Font berikut akan digunakan jika sebuah font tidak ditemukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Ganti font tertentu saat mengonversi dokumen Note.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Ganti font tertentu saat mengonversi dokumen Note.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Atur kata sandi untuk membuka proteksi dokumen yang dilindungi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Atur kata sandi untuk membuka proteksi dokumen yang dilindungi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

