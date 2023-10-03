---
title: VideoFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Video documents Includes the following types        Learn more about video formats here.
type: docs
weight: 26
url: /java/com.groupdocs.conversion.filetypes/videofiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public class VideoFileType extends FileType
```

Defines Video documents Includes the following types: , , , , , , , Learn more about video formats [here][].


[here]: https://docs.fileformat.com/video/
## Constructors

| Constructor | Description |
| --- | --- |
| [VideoFileType()](#VideoFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Mp4](#Mp4) | MP4(short for MPEG-4 Part 14) is a file format based on ISO/IEC 14496-12:2004 that is based on QuickTime File Format but formally specifies support for Initial Object Descriptors (IOD) and other MPEG features. |
| [Avi](#Avi) | The AVI file format is an Audio Video multimedia container file format that was introduced by Microsoft. |
| [Flv](#Flv) | FLV (Flash Video) is a container file format with the .flv extension. |
| [Mkv](#Mkv) | MKV (Matroska Video) is a multimedia container similar to MOV and AVI format but it supports more than one audio and subtitle track in the same file. |
| [Mov](#Mov) | MOV or QuickTime file format is a multimedia container which is developed by Apple: contains one or more tracks, each track holds a particular type of data i.e. |
| [Webm](#Webm) | A file with a .webm extension is a video file based on the open, royalty-free WebM file format. |
| [Wmv](#Wmv) | Windows Media Video is the compressed video format developed by Microsoft. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### VideoFileType() {#VideoFileType--}
```
public VideoFileType()
```


Serialization constructor

### Mp4 {#Mp4}
```
public static final VideoFileType Mp4
```


MP4(short for MPEG-4 Part 14) is a file format based on ISO/IEC 14496-12:2004 that is based on QuickTime File Format but formally specifies support for Initial Object Descriptors (IOD) and other MPEG features. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/mp4/

### Avi {#Avi}
```
public static final VideoFileType Avi
```


The AVI file format is an Audio Video multimedia container file format that was introduced by Microsoft. It holds the audio and video data created and compressed using several codecs (Coders/Decoders) such as XVid and DivX. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/avi/

### Flv {#Flv}
```
public static final VideoFileType Flv
```


FLV (Flash Video) is a container file format with the .flv extension. FLV is used to deliver audio/video content over the internet by using the Adobe Flash Player or Adobe Air. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/flv/

### Mkv {#Mkv}
```
public static final VideoFileType Mkv
```


MKV (Matroska Video) is a multimedia container similar to MOV and AVI format but it supports more than one audio and subtitle track in the same file. An MKV file is the Matroska multimedia container format used for video. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/mkv/

### Mov {#Mov}
```
public static final VideoFileType Mov
```


MOV or QuickTime file format is a multimedia container which is developed by Apple: contains one or more tracks, each track holds a particular type of data i.e. Video, Audio, text, etc. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/mov/

### Webm {#Webm}
```
public static final VideoFileType Webm
```


A file with a .webm extension is a video file based on the open, royalty-free WebM file format. It has been designed for sharing video on the web and defines the file container structure including video and audio formats. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/webm//

### Wmv {#Wmv}
```
public static final VideoFileType Wmv
```


Windows Media Video is the compressed video format developed by Microsoft. After the standardization by the Society of Motion Picture and Television Engineers (SMPTE), WMV is now considered to be an open standard format. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/video/wmv/

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
