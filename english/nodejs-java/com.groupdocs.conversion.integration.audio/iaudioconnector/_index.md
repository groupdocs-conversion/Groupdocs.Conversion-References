---
title: IAudioConnector
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Defines methods that are required to convert audio to audio documents.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.conversion.integration.audio/iaudioconnector/
---```
public interface IAudioConnector
```

Defines methods that are required to convert audio to audio documents.
## Methods

| Method | Description |
| --- | --- |
| [convertAudio(System.IO.Stream sourceStream, AudioConvertOptions convertOptions)](#convertAudio-com.aspose.ms.System.IO.Stream-com.groupdocs.conversion.options.convert.AudioConvertOptions-) | Does the Audio conversion provided as a stream. |
### convertAudio(System.IO.Stream sourceStream, AudioConvertOptions convertOptions) {#convertAudio-com.aspose.ms.System.IO.Stream-com.groupdocs.conversion.options.convert.AudioConvertOptions-}
```
public abstract System.IO.Stream convertAudio(System.IO.Stream sourceStream, AudioConvertOptions convertOptions)
```


Does the Audio conversion provided as a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | com.aspose.ms.System.IO.Stream | Stream, containing an audio to process |
| convertOptions | [AudioConvertOptions](../../com.groupdocs.conversion.options.convert/audioconvertoptions) | Audio convert options |

**Returns:**
com.aspose.ms.System.IO.Stream - Converted audio
