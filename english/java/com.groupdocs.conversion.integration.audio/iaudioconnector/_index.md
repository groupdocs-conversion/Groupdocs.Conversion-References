---
title: IAudioConnector
second_title: GroupDocs.Conversion for Java API Reference
description: Defines methods that are required to convert audio to audio documents.
type: docs
weight: 10
url: /java/com.groupdocs.conversion.integration.audio/iaudioconnector/
---```
public interface IAudioConnector
```

Defines methods that are required to convert audio to audio documents.
## Methods

| Method | Description |
| --- | --- |
| [convertAudio(InputStream sourceStream, AudioConvertOptions convertOptions)](#convertAudio-java.io.InputStream-com.groupdocs.conversion.options.convert.AudioConvertOptions-) | Does the Audio conversion provided as a stream. |
### convertAudio(InputStream sourceStream, AudioConvertOptions convertOptions) {#convertAudio-java.io.InputStream-com.groupdocs.conversion.options.convert.AudioConvertOptions-}
```
public abstract InputStream convertAudio(InputStream sourceStream, AudioConvertOptions convertOptions)
```


Does the Audio conversion provided as a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | java.io.InputStream | Stream, containing an audio to process |
| convertOptions | [AudioConvertOptions](../../com.groupdocs.conversion.options.convert/audioconvertoptions) | Audio convert options |

**Returns:**
java.io.InputStream - Converted audio
