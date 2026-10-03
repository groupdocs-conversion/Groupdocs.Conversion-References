---
title: "NoteFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "नोट‑लेने के फ़ॉर्मेट को परिभाषित करता है।"
type: docs
weight: 19
url: /hi/java/com.groupdocs.conversion.filetypes/notefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class NoteFileType extends FileType
```

नोट-लेने के फ़ॉर्मेट को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[One](../../com.groupdocs.conversion.filetypes/notefiletype#One).
नोट-लेने के फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/note-taking).

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [NoteFileType()](#NoteFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [One](#One) | .ONE एक्सटेंशन वाली फ़ाइल माइक्रोसॉफ्ट OneNote एप्लिकेशन द्वारा बनाई जाती हैं। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### NoteFileType() {#NoteFileType--}
```
public NoteFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### One {#One}
```
public static final NoteFileType One
```


.ONE एक्सटेंशन वाली फ़ाइल माइक्रोसॉफ्ट OneNote एप्लिकेशन द्वारा बनाई जाती हैं। OneNote आपको एप्लिकेशन का उपयोग करके जानकारी एकत्र करने देता है जैसे आप नोट्स लेने के लिए अपने ड्राफ्टपैड का उपयोग कर रहे हों।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/note-taking/one).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
