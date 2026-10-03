---
title: "MemoryCache"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "मेमोरी कैशिंग व्यवहार।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Memory caching व्यवहार। अर्थात् कैश मेमोरी में संग्रहीत किया जाता है **और अधिक जानें** कैशिंग और रूपांतरण प्रक्रिया के प्रदर्शन को अनुकूलित करने के बारे में अधिक जानकारी: [कैशिंग रूपांतरण परिणाम](../https://docs.groupdocs.com/display/conversionnet/Caching)

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | MemoryCache क्लास का नया उदाहरण बनाता है |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | कैश में एक कैश एंट्री डालता है। |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | यदि मौजूद हो तो इस कुंजी से संबंधित एंट्री प्राप्त करता है। |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | फ़िल्टर से मेल खाने वाली सभी कुंजियों को लौटाता है। |
|
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


MemoryCache क्लास का नया उदाहरण बनाता है


### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


कैश में एक कैश एंट्री डालता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | कुंजी | java.lang.String | कैश एंट्री के लिए एक अद्वितीय पहचानकर्ता। |
|
|  | मान | java.lang.Object | डालने के लिए ऑब्जेक्ट। |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


यदि मौजूद हो तो इस कुंजी से संबंधित एंट्री प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | कुंजी | java.lang.String | अनुरोधित एंट्री की पहचान करने वाली कुंजी। |
|

**Returns:**
java.lang.Object - प्राप्त मान या null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


फ़िल्टर से मेल खाने वाली सभी कुंजियों को लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | फ़िल्टर | java.lang.String | उपयोग करने के लिए फ़िल्टर। |
|

**Returns:**
java.lang.Iterable<java.lang.String> - फ़िल्टर से मेल खाने वाली कुंजियाँ।

