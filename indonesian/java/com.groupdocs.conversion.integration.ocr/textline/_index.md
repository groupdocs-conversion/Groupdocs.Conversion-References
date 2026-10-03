---
title: "TextLine"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili teks yang diekstrak dari gambar sebagai hasil proses pengenalan."
type: docs
weight: 12
url: /id/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Mewakili teks, yang diekstrak dari gambar sebagai hasil proses pengenalan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Menginisialisasi instance baru dari baris teks, diekstrak oleh mesin OCR dari sebuah gambar. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFragments()](#getFragments--) | Mendapatkan array fragmen teks, seperti simbol dan kata, yang dikenali dalam baris. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Menginisialisasi instance baru dari baris teks, diekstrak oleh mesin OCR dari sebuah gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fragmen | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | set awal fragmen teks |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Mendapatkan array fragmen teks, seperti simbol dan kata, yang dikenali dalam baris.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
