---
title: "IAudioConnector"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i metodi necessari per convertire l'audio in documenti audio."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.integration.audio/iaudioconnector/
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

