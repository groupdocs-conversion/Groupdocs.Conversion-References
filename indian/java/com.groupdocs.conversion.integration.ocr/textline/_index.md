---
title: "TextLine"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "इमेज से निकाले गए टेक्स्ट को उसके रिकग्निशन प्रोसेस के परिणामस्वरूप दर्शाता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

छवि से निकाले गए पाठ को, उसकी पहचान प्रक्रिया के परिणामस्वरूप, दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | OCR इंजन द्वारा इमेज से निकाली गई टेक्स्ट लाइन का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFragments()](#getFragments--) | लाइन में पहचाने गए टेक्स्ट फ्रैगमेंट्स, जैसे कि सिम्बॉल और शब्दों की एरे प्राप्त करता है। |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


OCR इंजन द्वारा इमेज से निकाली गई टेक्स्ट लाइन का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | फ्रैगमेंट्स | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | टेक्स्ट फ्रैगमेंट्स का प्रारंभिक सेट |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


लाइन में पहचाने गए टेक्स्ट फ्रैगमेंट्स, जैसे कि सिम्बॉल और शब्दों की एरे प्राप्त करता है।


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
