---
title: "MboxLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "एमबॉक्स दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 23
url: /hi/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

एमबॉक्स दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | मालिक को परिवर्तित नहीं किया जाएगा |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} डिफ़ॉल्ट: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


मालिक को परिवर्तित नहीं किया जाएगा


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


परिवर्तन करने के लिए गहराई में कितने स्तरों को नियंत्रित करने का विकल्प। डिफ़ॉल्ट: 3


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

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
