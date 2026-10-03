---
title: "RecognizedImage"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mewakili teks yang diekstrak dari gambar sebagai hasil proses pengenalan."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Mewakili teks, yang diekstrak dari gambar sebagai hasil proses pengenalan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Menginisialisasi instance baru dari kelas, menggunakan sekumpulan baris yang dikenali. |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [EMPTY](#EMPTY) | Gambar yang dikenali kosong |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLines()](#getLines--) | Mendapatkan baris teks, beserta fragmennya, yang dikenali dalam dokumen. |
|
|  | [getText()](#getText--) | Mendapatkan ekuivalen teks dari teks terstruktur |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Menginisialisasi instance baru dari kelas, menggunakan sekumpulan baris yang dikenali.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | baris | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | sebuah IEnumerable (misalnya daftar atau array) dari baris yang dikenali |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Gambar yang dikenali kosong


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Mendapatkan baris teks, beserta fragmennya, yang dikenali dalam dokumen.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Mendapatkan ekuivalen teks dari teks terstruktur


**Returns:**
java.lang.String
