---
title: "PersonalStorageLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "पर्सनल स्टोरेज दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 28
url: /hi/java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

पर्सनल स्टोरेज दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFolder()](#getFolder--) | प्रोसेस की जाने वाली फ़ोल्डर। डिफ़ॉल्ट Inbox है। |
|
|  | [setFolder(String folder)](#setFolder-java.lang.String-) | प्रोसेस की जाने वाली फ़ोल्डर सेट करें |
|
|  | [isConvertOwner()](#isConvertOwner--) | {@inheritDoc} मालिक को परिवर्तित नहीं किया जाएगा |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### getFolder() {#getFolder--}
```
public String getFolder()
```


प्रोसेस की जाने वाली फ़ोल्डर। डिफ़ॉल्ट Inbox है।


**Returns:**
java.lang.String - प्रोसेस की जाने वाली फ़ोल्डर

### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


प्रोसेस की जाने वाली फ़ोल्डर सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | फ़ोल्डर | java.lang.String | फ़ोल्डर |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


विकल्प प्राप्त करता है जो नियंत्रित करता है कि क्या दस्तावेज़ कंटेनर स्वयं को परिवर्तित किया जाना चाहिए। मालिक को परिवर्तित नहीं किया जाएगा


**Returns:**
बूलियन
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


दस्तावेज़ कंटेनर में स्वामित्व वाले दस्तावेज़ों को परिवर्तित किया जाना चाहिए या नहीं, इसे नियंत्रित करने का विकल्प


**Returns:**
बूलियन
### getDepth() {#getDepth--}
```
public int getDepth()
```


परिवर्तन करने के लिए गहराई में कितने स्तरों तक करना है, इसे नियंत्रित करने का विकल्प


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| depth | int |  |

