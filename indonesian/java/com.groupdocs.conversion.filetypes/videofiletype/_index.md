---
title: "VideoFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Video mencakup tipe-tipe berikut        Pelajari lebih lanjut tentang format video di sini."
type: docs
weight: 26
url: /id/java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Mendefinisikan dokumen Video mencakup tipe-tipe berikut: , , , , , , , Pelajari lebih lanjut tentang format video [di sini](../https://docs.fileformat.com/video/).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [VideoFileType()](#VideoFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Mp4](#Mp4) | MP4 (singkatan dari MPEG-4 Part 14) adalah format file yang berdasarkan ISO/IEC 14496-12:2004 yang didasarkan pada QuickTime File Format tetapi secara resmi menentukan dukungan untuk Initial Object Descriptors (IOD) dan fitur MPEG lainnya. |
|
|  | [Avi](#Avi) | Format file AVI adalah format kontainer multimedia Audio Video yang diperkenalkan oleh Microsoft. |
|
|  | [Flv](#Flv) | FLV (Flash Video) adalah format file kontainer dengan ekstensi .flv. |
|
|  | [Mkv](#Mkv) | MKV (Matroska Video) adalah kontainer multimedia yang mirip dengan format MOV dan AVI tetapi mendukung lebih dari satu trek audio dan subtitle dalam satu file. |
|
|  | [Mov](#Mov) | Format file MOV atau QuickTime adalah kontainer multimedia yang dikembangkan oleh Apple: berisi satu atau lebih trek, masing-masing trek menyimpan jenis data tertentu, misalnya. |
|
|  | [Webm](#Webm) | File dengan ekstensi .webm adalah file video yang berbasis pada format file WebM yang terbuka dan bebas royalti. |
|
|  | [Wmv](#Wmv) | Windows Media Video adalah format video terkompresi yang dikembangkan oleh Microsoft. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Konstruktor serialisasi


### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4 (singkatan dari MPEG-4 Part 14) adalah format file yang berdasarkan ISO/IEC 14496-12:2004 yang didasarkan pada QuickTime File Format tetapi secara resmi menentukan dukungan untuk Initial Object Descriptors (IOD) dan fitur MPEG lainnya. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/mp4/).


### Avi {#Avi}
```
public static final VideoFileType Avi
```


Format file AVI adalah format kontainer multimedia Audio Video yang diperkenalkan oleh Microsoft. Ia menyimpan data audio dan video yang dibuat serta dikompresi menggunakan beberapa codec (Pengode/Pengurai) seperti XVid dan DivX. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/avi/).


### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) adalah format file kontainer dengan ekstensi .flv. FLV digunakan untuk mengirim konten audio/video melalui internet dengan menggunakan Adobe Flash Player atau Adobe Air. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/flv/).


### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) adalah kontainer multimedia yang mirip dengan format MOV dan AVI tetapi mendukung lebih dari satu trek audio dan subtitle dalam satu file. File MKV adalah format kontainer multimedia Matroska yang digunakan untuk video. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/mkv/).


### Mov {#Mov}
```
public static final VideoFileType Mov
```


Format file MOV atau QuickTime adalah kontainer multimedia yang dikembangkan oleh Apple: berisi satu atau lebih trek, setiap trek menyimpan jenis data tertentu seperti Video, Audio, teks, dll. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/mov/).


### Webm {#Webm}
```
public static final VideoFileType Webm
```


File dengan ekstensi .webm adalah file video yang berbasis pada format file WebM yang terbuka dan bebas royalti. File ini dirancang untuk berbagi video di web dan mendefinisikan struktur kontainer file termasuk format video dan audio. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/webm//).


### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video adalah format video terkompresi yang dikembangkan oleh Microsoft. Setelah standarisasi oleh Society of Motion Picture and Television Engineers (SMPTE), WMV kini dianggap sebagai format standar terbuka. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/video/wmv/).


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
