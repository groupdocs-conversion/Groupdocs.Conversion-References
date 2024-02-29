---
title: AudioFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Audio documents Includes the following types          Learn more about audio formats here.
type: docs
weight: 10
url: /java/com.groupdocs.conversion.filetypes/audiofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class AudioFileType extends FileType
```

Defines Audio documents Includes the following types: , , , , , , , , , Learn more about audio formats [here][].


[here]: https://docs.fileformat.com/audio/
## Constructors

| Constructor | Description |
| --- | --- |
| [AudioFileType()](#AudioFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Mp3](#Mp3) | Files with .mp3 extension are digitally encoded file formats for audio files that are formally based on the MPEG-1 Audio Layer III or MPEG-2 Audio Layer III. |
| [Aac](#Aac) | AAC (Advanced Audio Coding) refers to digital audio coding standard that represent audio files based on lossy audio compression. |
| [Aiff](#Aiff) | The AIFF (Audio Interchange File Format) is an uncompressed audio file format developed by Apple in 1998, but is based on EA IFF 85 Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/aiff/ |
| [Flac](#Flac) | FLAC(Free Lossless Audio Codec) is a lossless compression audio coding format developed by Xiph.Org Foundation Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/flac/ |
| [M4a](#M4a) | The M4A file format is an audio file created by using the AAC (Advanced Audio Coding) which is known as a lossy compression. |
| [Wma](#Wma) | A file with .wma extension represents an audio file that is saved in the Advanced Systems Format (ASF) format. |
| [Ac3](#Ac3) | A file with a .ac3 extension is an Audio Codec 3 file, introduced by Dolby Laboratories. |
| [Ogg](#Ogg) | OGG is an Ogg Vorbis Compressed Audio File that is saved with the .ogg extension. |
| [Wav](#Wav) | WAV, known for WAVE (Waveform Audio File Format), is a subset of Microsoft\\u2019s Resource Interchange File Format (RIFF) specification for storing digital audio files. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### AudioFileType() {#AudioFileType--}
```
public AudioFileType()
```


Serialization constructor

### Mp3 {#Mp3}
```
public static final AudioFileType Mp3
```


Files with .mp3 extension are digitally encoded file formats for audio files that are formally based on the MPEG-1 Audio Layer III or MPEG-2 Audio Layer III. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/mp3/

### Aac {#Aac}
```
public static final AudioFileType Aac
```


AAC (Advanced Audio Coding) refers to digital audio coding standard that represent audio files based on lossy audio compression. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/aac/

### Aiff {#Aiff}
```
public static final AudioFileType Aiff
```


The AIFF (Audio Interchange File Format) is an uncompressed audio file format developed by Apple in 1998, but is based on EA IFF 85 Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/aiff/

### Flac {#Flac}
```
public static final AudioFileType Flac
```


FLAC(Free Lossless Audio Codec) is a lossless compression audio coding format developed by Xiph.Org Foundation Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/flac/

### M4a {#M4a}
```
public static final AudioFileType M4a
```


The M4A file format is an audio file created by using the AAC (Advanced Audio Coding) which is known as a lossy compression. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/m4a/

### Wma {#Wma}
```
public static final AudioFileType Wma
```


A file with .wma extension represents an audio file that is saved in the Advanced Systems Format (ASF) format. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/wma/

### Ac3 {#Ac3}
```
public static final AudioFileType Ac3
```


A file with a .ac3 extension is an Audio Codec 3 file, introduced by Dolby Laboratories. It is an audio format that can contain up to six channels of audio output. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/ac3/

### Ogg {#Ogg}
```
public static final AudioFileType Ogg
```


OGG is an Ogg Vorbis Compressed Audio File that is saved with the .ogg extension. OGG files are used for storing audio data and can include artist and track information and metadata as well. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/ogg/

### Wav {#Wav}
```
public static final AudioFileType Wav
```


WAV, known for WAVE (Waveform Audio File Format), is a subset of Microsoft\\u2019s Resource Interchange File Format (RIFF) specification for storing digital audio files. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/audio/ogg/

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Prepared default load options for the source file type

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Prepared default convert options for the file type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
