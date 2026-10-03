---
title: "RecognizedImage"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "इमेज से निकाले गए टेक्स्ट को उसके रिकग्निशन प्रोसेस के परिणामस्वरूप दर्शाता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

छवि से निकाले गए पाठ को, उसकी पहचान प्रक्रिया के परिणामस्वरूप, दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | पहचानी गई लाइनों के सेट का उपयोग करके क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [EMPTY](#EMPTY) | खाली पहचानी गई इमेज |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getLines()](#getLines--) | डॉक्यूमेंट के भीतर पहचानी गई टेक्स्ट लाइनों को उनके फ्रैगमेंट्स के साथ प्राप्त करता है। |
|
|  | [getText()](#getText--) | संरचित टेक्स्ट का टेक्स्टुअल समकक्ष प्राप्त करता है। |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


पहचानी गई लाइनों के सेट का उपयोग करके क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | लाइन्स | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | पहचानी गई लाइनों का IEnumerable (जैसे कि लिस्ट या एरे) |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


खाली पहचानी गई इमेज


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


डॉक्यूमेंट के भीतर पहचानी गई टेक्स्ट लाइनों को उनके फ्रैगमेंट्स के साथ प्राप्त करता है।


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


संरचित टेक्स्ट का टेक्स्टुअल समकक्ष प्राप्त करता है।


**Returns:**
java.lang.String
