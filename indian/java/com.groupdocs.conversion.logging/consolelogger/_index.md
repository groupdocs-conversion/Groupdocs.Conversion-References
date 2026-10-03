---
title: "ConsoleLogger"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "कंसोल लॉगर कार्यान्वयन।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.conversion.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.logging.ILogger](../../com.groupdocs.conversion.logging/ilogger)
```
public final class ConsoleLogger implements ILogger
```

कंसोल लॉगर कार्यान्वयन।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [trace(String message)](#trace-java.lang.String-) | ट्रेस लॉग संदेश लिखता है; |
ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।
|
|  | [warning(String message)](#warning-java.lang.String-) | चेतावनी लॉग संदेश लिखता है; |
चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।
|
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | त्रुटि लॉग संदेश लिखता है; |
त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public void trace(String message)
```


ट्रेस लॉग संदेश लिखता है;
ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | ट्रेस संदेश। |
|

### warning(String message) {#warning-java.lang.String-}
```
public void warning(String message)
```


चेतावनी लॉग संदेश लिखता है;
चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | चेतावनी संदेश। |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public void error(String message, Exception exception)
```


त्रुटि लॉग संदेश लिखता है;
त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | त्रुटि संदेश। |
|
|  | अपवाद | java.lang.Exception | अपवाद। |
|

