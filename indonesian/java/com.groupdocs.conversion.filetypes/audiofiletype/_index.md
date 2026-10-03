---
title: "AudioFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Audio. Menyertakan tipe berikut Pelajari lebih lanjut tentang format audio di sini."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Mendefinisikan dokumen Audio. Menyertakan tipe berikut: , , , , , , , , , Pelajari lebih lanjut tentang format audio [di sini](../https://docs.fileformat.com/audio/).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [AudioFileType()](#AudioFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Mp3](#Mp3) | File dengan ekstensi .mp3 adalah format file audio yang dienkode secara digital dan secara formal didasarkan pada MPEG-1 Audio Layer III atau MPEG-2 Audio Layer III. |
|
|  | [Aac](#Aac) | AAC (Advanced Audio Coding) mengacu pada standar pengkodean audio digital yang merepresentasikan file audio berdasarkan kompresi audio lossy. |
|
|  | [Aiff](#Aiff) | AIFF (Audio Interchange File Format) adalah format file audio tidak terkompresi yang dikembangkan oleh Apple pada 1998, tetapi berbasis pada EA IFF 85. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/aiff/). |
|
|  | [Flac](#Flac) | FLAC (Free Lossless Audio Codec) adalah format pengkodean audio kompresi lossless yang dikembangkan oleh Xiph.Org Foundation. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/flac/). |
|
|  | [M4a](#M4a) | Format file M4A adalah file audio yang dibuat dengan menggunakan AAC (Advanced Audio Coding) yang dikenal sebagai kompresi lossy. |
|
|  | [Wma](#Wma) | File dengan ekstensi .wma mewakili file audio yang disimpan dalam format Advanced Systems Format (ASF). |
|
|  | [Ac3](#Ac3) | File dengan ekstensi .ac3 adalah file Audio Codec 3, yang diperkenalkan oleh Dolby Laboratories. |
|
|  | [Ogg](#Ogg) | OGG adalah Ogg Vorbis Compressed Audio File yang disimpan dengan ekstensi .ogg. |
|
|  | [Wav](#Wav) | WAV, yang dikenal sebagai WAVE (Waveform Audio File Format), adalah subset dari spesifikasi Microsoft\\u2019s Resource Interchange File Format (RIFF) untuk menyimpan file audio digital. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Konstruktor serialisasi


### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


File dengan ekstensi .mp3 adalah format file yang dikodekan secara digital untuk file audio yang secara resmi berbasis pada MPEG-1 Audio Layer III atau MPEG-2 Audio Layer III. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/mp3/).


### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) mengacu pada standar pengkodean audio digital yang merepresentasikan file audio berdasarkan kompresi audio lossy. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/aac/).


### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


AIFF (Audio Interchange File Format) adalah format file audio tidak terkompresi yang dikembangkan oleh Apple pada 1998, tetapi berbasis pada EA IFF 85. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/aiff/).


### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC (Free Lossless Audio Codec) adalah format pengkodean audio kompresi lossless yang dikembangkan oleh Xiph.Org Foundation. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/flac/).


### M4a {#M4a}
```
public static final AudioFileType M4a
```


Format file M4A adalah file audio yang dibuat dengan menggunakan AAC (Advanced Audio Coding) yang dikenal sebagai kompresi lossy. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/m4a/).


### Wma {#Wma}
```
public static final AudioFileType Wma
```


File dengan ekstensi .wma mewakili file audio yang disimpan dalam format Advanced Systems Format (ASF). Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/wma/).


### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


File dengan ekstensi .ac3 adalah file Audio Codec 3, yang diperkenalkan oleh Dolby Laboratories. Ini adalah format audio yang dapat menampung hingga enam saluran output audio. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/ac3/).


### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG adalah Ogg Vorbis Compressed Audio File yang disimpan dengan ekstensi .ogg. File OGG digunakan untuk menyimpan data audio dan dapat menyertakan informasi artis, trek, serta metadata. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/ogg/).


### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, yang dikenal sebagai WAVE (Waveform Audio File Format), adalah subset dari spesifikasi Microsoft\\u2019s Resource Interchange File Format (RIFF) untuk menyimpan file audio digital. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/audio/ogg/).


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
