---
title: "TextFragment"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili bagian dari teks yang dikenali, kata, simbol, dll yang diekstrak oleh mesin OCR."
type: docs
weight: 11
url: /id/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Mewakili bagian dari teks yang dikenali (kata, simbol, dll), yang diekstrak oleh mesin OCR.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Menginisialisasi instance baru dari fragmen teks yang dikenali. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getText()](#getText--) | Mendapatkan konten teks dari fragmen teks yang dikenali. |
|
|  | [getRectangle()](#getRectangle--) | Mendapatkan persegi panjang pembatas dari fragmen teks yang dikenali. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Menginisialisasi instance baru dari fragmen teks yang dikenali.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | teks | java.lang.String | konten teks dari fragmen teks yang dikenali |
|
|  | persegi panjang | java.awt.Rectangle | persegi panjang pembatas dari fragmen teks yang dikenali |
|

### getText() {#getText--}
```
public String getText()
```


Mendapatkan konten teks dari fragmen teks yang dikenali.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Mendapatkan persegi panjang pembatas dari fragmen teks yang dikenali.


**Returns:**
[Rectangle](../../java.awt/rectangle)
