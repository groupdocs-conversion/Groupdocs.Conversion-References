---
title: "TextFragment"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "OCR इंजन द्वारा निकाले गए पहचाने गए पाठ, शब्द, प्रतीक आदि का एक भाग दर्शाता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

पहचाने गए पाठ (शब्द, प्रतीक, आदि) का भाग, जिसे OCR इंजन द्वारा निकाला गया है, दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | पहचाने गए टेक्स्ट फ्रैगमेंट का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getText()](#getText--) | पहचाने गए टेक्स्ट फ्रैगमेंट की टेक्स्ट सामग्री प्राप्त करता है। |
|
|  | [getRectangle()](#getRectangle--) | पहचाने गए टेक्स्ट फ्रैगमेंट का बाउंडिंग रेक्टेंगल प्राप्त करता है। |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


पहचाने गए टेक्स्ट फ्रैगमेंट का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | पहचाने गए टेक्स्ट फ्रैगमेंट की टेक्स्ट सामग्री |
|
|  | रेक्टेंगल | java.awt.Rectangle | पहचाने गए टेक्स्ट फ्रैगमेंट का बाउंडिंग रेक्टेंगल |
|

### getText() {#getText--}
```
public String getText()
```


पहचाने गए टेक्स्ट फ्रैगमेंट की टेक्स्ट सामग्री प्राप्त करता है।


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


पहचाने गए टेक्स्ट फ्रैगमेंट का बाउंडिंग रेक्टेंगल प्राप्त करता है।


**Returns:**
[Rectangle](../../java.awt/rectangle)
