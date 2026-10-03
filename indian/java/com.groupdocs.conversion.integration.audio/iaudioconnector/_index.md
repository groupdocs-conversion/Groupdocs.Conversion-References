---
title: "IAudioConnector"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ऑडियो को ऑडियो दस्तावेज़ों में बदलने के लिए आवश्यक विधियों को परिभाषित करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.integration.audio/iaudioconnector/
---```
public interface IAudioConnector
```

Defines methods that are required to convert audio to audio documents.

## Methods

| Method | Description |
| --- | --- |
| [convertAudio(InputStream sourceStream, AudioConvertOptions convertOptions)](#convertAudio-java.io.InputStream-com.groupdocs.conversion.options.convert.AudioConvertOptions-) | Does the Audio conversion provided as a stream.
 |
### convertAudio(InputStream sourceStream, AudioConvertOptions convertOptions) {#convertAudio-java.io.InputStream-com.groupdocs.conversion.options.convert.AudioConvertOptions-}
```
public abstract InputStream convertAudio(InputStream sourceStream, AudioConvertOptions convertOptions)
```


Does the Audio conversion provided as a stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | java.io.InputStream | Stream, containing an audio to process
 |
| convertOptions | [AudioConvertOptions](../../com.groupdocs.conversion.options.convert/audioconvertoptions) | Audio convert options
 |

**Returns:**
java.io.InputStream - Converted audio

