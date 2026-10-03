---
title: "ValueObject"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ऐब्स्ट्रैक्ट वैल्यू ऑब्जेक्ट क्लास।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

ऐब्स्ट्रैक्ट वैल्यू ऑब्जेक्ट क्लास।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
|
|  | [hashCode()](#hashCode--) | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | समानता ऑपरेटर। |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | असमानता ऑपरेटर। |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |
|

**Returns:**
boolean -  true  यदि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है; अन्यथा,  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |
|

**Returns:**
boolean -  true  यदि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है; अन्यथा,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है।


**Returns:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


समानता ऑपरेटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | पहला ऑब्जेक्ट |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | दूसरा ऑब्जेक्ट |
|

**Returns:**
boolean -  true  यदि ऑब्जेक्ट समान हैं

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


असमानता ऑपरेटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | पहला ऑब्जेक्ट |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | दूसरा ऑब्जेक्ट |
|

**Returns:**
boolean -  true  यदि ऑब्जेक्ट समान नहीं हैं

