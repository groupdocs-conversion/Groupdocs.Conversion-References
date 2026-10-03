---
title: "एन्यूमरेशन"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "सामान्य enumeration वर्ग।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

सामान्य enumeration वर्ग।


TKey
:

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [toString()](#toString--) | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | सभी enumeration मान लौटाता है। |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
|
|  | [hashCode()](#hashCode--) | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | कुंजी द्वारा ऑब्जेक्ट लौटाता है। |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | प्रदर्शित नाम द्वारा ऑब्जेक्ट लौटाता है। |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | वर्तमान ऑब्जेक्ट की अन्य से तुलना करता है। |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | समानता ऑपरेटर। |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | असमानता ऑपरेटर। |
|
### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है।


**Returns:**
java.lang.String - स्ट्रिंग प्रतिनिधित्व

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


सभी enumeration मान लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - प्रदान किए गए प्रकार का एन्यूमेरेबल


T
: सूचीबद्ध वस्तु प्रकार।

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

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |
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

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


कुंजी द्वारा ऑब्जेक्ट लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | मान | java.lang.String | मान |
|

**Returns:**
T - ऑब्जेक्ट

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


प्रदर्शित नाम द्वारा ऑब्जेक्ट लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | प्रदर्शित नाम |
|

**Returns:**
T - ऑब्जेक्ट

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


वर्तमान ऑब्जेक्ट की अन्य से तुलना करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य ऑब्जेक्ट |
|

**Returns:**
int - यदि बराबर हो तो शून्य

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


समानता ऑपरेटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | पहला ऑब्जेक्ट |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | दूसरा ऑब्जेक्ट |
|

**Returns:**
boolean -  true  यदि ऑब्जेक्ट समान हैं

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


असमानता ऑपरेटर।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | पहला ऑब्जेक्ट |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | दूसरा ऑब्जेक्ट |
|

**Returns:**
boolean -  true  यदि ऑब्जेक्ट समान नहीं हैं

