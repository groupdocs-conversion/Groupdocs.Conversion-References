---
title: "EmailLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ईमेल दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

ईमेल दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | नया उदाहरण प्रारंभ करता है [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | ईमेल हेडर को दिखाने या छिपाने का विकल्प। |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | ईमेल हेडर को दिखाने या छिपाने का विकल्प। |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | "from" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | "from" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | "to" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | "to" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | "Cc" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | "Cc" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | "Bcc" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | "Bcc" ईमेल पता को दिखाने या छिपाने का विकल्प। |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | संदेश तिथियों के लिए समन्वित सार्वभौमिक समय (UTC) ऑफ़सेट को प्राप्त करता है या सेट करता है। |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | बाहरी संसाधनों को लोड करने के लिए टाइमआउट |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | बाहरी संसाधनों को लोड करने के लिए टाइमआउट (सेटर) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | संदेश तिथियों के लिए समन्वित सार्वभौमिक समय (UTC) ऑफ़सेट को प्राप्त करता है या सेट करता है। |
|
|  | [deepClone()](#deepClone--) | वर्तमान उदाहरण की प्रतिलिपि बनाता है। |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | ईमेल संदेश और फ़ील्ड टेक्स्ट प्रतिनिधित्व के बीच मैपिंग प्राप्त करता है |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | ईमेल संदेश और फ़ील्ड टेक्स्ट प्रतिनिधित्व के बीच मैपिंग सेट करता है |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | सेव करते समय मेल संदेश में मूल तिथि हेडर स्ट्रिंग को रखने की आवश्यकता है या नहीं को परिभाषित करता है (डिफ़ॉल्ट मान true है) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | सेव करते समय मेल संदेश में मूल तिथि हेडर स्ट्रिंग को रखने की आवश्यकता है या नहीं को परिभाषित करता है |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | हेडर में अटैचमेंट को दिखाने या छिपाने का विकल्प प्राप्त करता है। |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | हेडर में अटैचमेंट को दिखाने या छिपाने का विकल्प सेट करता है। |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | हेडर में विषय को दिखाने या छिपाने का विकल्प प्राप्त करता है। |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | हेडर में विषय को दिखाने या छिपाने का विकल्प सेट करता है |
|
|  | [isDisplaySent()](#isDisplaySent--) | हेडर में भेजी गई तिथि/समय को दिखाने या छिपाने का विकल्प प्राप्त करता है। |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | हेडर में भेजी गई तिथि/समय को दिखाने या छिपाने का विकल्प सेट करता है। |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | यदि सत्य हो तो http संसाधन लोडिंग को छोड़ देता है |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


नया उदाहरण प्रारंभ करता है [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) क्लास।


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


ईमेल हेडर को दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: सत्य।


**Returns:**
बूलियन
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


ईमेल हेडर को दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: सत्य।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


\"from\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: सत्य।


**Returns:**
बूलियन
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


\"from\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: सत्य।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


\"to\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: सत्य।


**Returns:**
बूलियन
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


\"to\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: सत्य।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


\"Cc\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: असत्य।


**Returns:**
बूलियन
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


\"Cc\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: असत्य।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


\"Bcc\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: असत्य।


**Returns:**
बूलियन
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


\"Bcc\" ईमेल पता दिखाने या छिपाने का विकल्प। डिफ़ॉल्ट: असत्य।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


संदेश तिथियों के लिए समन्वित सार्वभौमिक समय (UTC) ऑफ़सेट को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी स्थानीय समय और UTC के बीच समय क्षेत्र अंतर को परिभाषित करती है।


**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


बाहरी संसाधनों को लोड करने के लिए टाइमआउट


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


बाहरी संसाधनों को लोड करने के लिए टाइमआउट (सेटर)


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


संदेश तिथियों के लिए समन्वित सार्वभौमिक समय (UTC) ऑफ़सेट को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी स्थानीय समय और UTC के बीच समय क्षेत्र अंतर को परिभाषित करती है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


वर्तमान उदाहरण की प्रतिलिपि बनाता है।


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


ईमेल संदेश और फ़ील्ड टेक्स्ट प्रतिनिधित्व के बीच मैपिंग प्राप्त करता है


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - मैपिंग

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


ईमेल संदेश और फ़ील्ड टेक्स्ट प्रतिनिधित्व के बीच मैपिंग सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | मैपिंग |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


सेव करते समय मेल संदेश में मूल तिथि हेडर स्ट्रिंग को रखने की आवश्यकता है या नहीं को परिभाषित करता है (डिफ़ॉल्ट मान true है)


**Returns:**
बूलियन - यदि सत्य हो तो मूल तिथि को संरक्षित रखें

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


सेव करते समय मेल संदेश में मूल तिथि हेडर स्ट्रिंग को रखने की आवश्यकता है या नहीं को परिभाषित करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | preserveOriginalDate | बूलियन | मूल तिथि को संरक्षित रखें |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


विकल्प प्राप्त करता है जिससे नियंत्रित किया जा सके कि क्या दस्तावेज़ कंटेनर स्वयं को परिवर्तित किया जाना चाहिए


**Returns:**
बूलियन
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOwner | बूलियन |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


दस्तावेज़ कंटेनर में स्वामित्व वाले दस्तावेज़ों को परिवर्तित किया जाना चाहिए या नहीं, इसे नियंत्रित करने का विकल्प


**Returns:**
बूलियन
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOwned | बूलियन |  |

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

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


हेडर में अटैचमेंट्स को दिखाने या छिपाने का विकल्प प्राप्त करता है। डिफ़ॉल्ट: सत्य।


**Returns:**
बूलियन
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


हेडर में अटैचमेंट को दिखाने या छिपाने का विकल्प सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| displayAttachments | बूलियन |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


हेडर में विषय को दिखाने या छिपाने का विकल्प प्राप्त करता है। डिफ़ॉल्ट: सत्य।


**Returns:**
बूलियन
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


हेडर में विषय को दिखाने या छिपाने का विकल्प सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| displaySubject | बूलियन |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


हेडर में भेजी गई तिथि/समय को दिखाने या छिपाने का विकल्प प्राप्त करता है। डिफ़ॉल्ट: सत्य।


**Returns:**
बूलियन
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


हेडर में भेजी गई तिथि/समय को दिखाने या छिपाने का विकल्प सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| displaySent | बूलियन |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


यदि सत्य हो तो http संसाधन लोडिंग को छोड़ देता है


**Returns:**
बूलियन
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| skipExternalResources | बूलियन |  |

