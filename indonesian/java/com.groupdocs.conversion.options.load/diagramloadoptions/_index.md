---
title: "DiagramLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Diagram."
type: docs
weight: 15
url: /id/java/com.groupdocs.conversion.options.load/diagramloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramLoadOptions extends LoadOptions implements Serializable
```

Opsi untuk memuat dokumen Diagram.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DiagramLoadOptions()](#DiagramLoadOptions--) | Menginisialisasi instance baru dari kelas [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Font default untuk dokumen Diagram. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Font default untuk dokumen Diagram. |
|
### DiagramLoadOptions() {#DiagramLoadOptions--}
```
public DiagramLoadOptions()
```


Menginisialisasi instance baru dari kelas [DiagramLoadOptions](../../com.groupdocs.conversion.options.load/diagramloadoptions).


### getFormat() {#getFormat--}
```
public final DiagramFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[DiagramFileType](../../com.groupdocs.conversion.filetypes/diagramfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Font default untuk dokumen Diagram. Font berikut akan digunakan jika sebuah font tidak ditemukan.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Font default untuk dokumen Diagram. Font berikut akan digunakan jika sebuah font tidak ditemukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

