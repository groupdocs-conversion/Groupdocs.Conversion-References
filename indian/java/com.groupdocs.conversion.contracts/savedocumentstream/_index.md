---
title: "SaveDocumentStream"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "रूपांतरित दस्तावेज़ को आउटपुट स्ट्रीम में सहेजने वाले डेलीगेट का वर्णन करता है।"
type: docs
weight: 23
url: /hi/java/com.groupdocs.conversion.contracts/savedocumentstream/
---```
public interface SaveDocumentStream
```

Describes delegate for saving converted document into output stream.

## Methods

| Method | Description |
| --- | --- |
| [get()](#get--) | Saves converted document into output stream.
 |
### get() {#get--}
```
public abstract OutputStream get()
```


Saves converted document into output stream.


**Returns:**
java.io.OutputStream - Must return an output stream where the converted document will be saved

