---
title: "PdfFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Pdf."
type: docs
weight: 21
url: /id/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Mendefinisikan dokumen Pdf. Menyertakan jenis file berikut:
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Konstruktor serialisasi


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/view/pdf).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
