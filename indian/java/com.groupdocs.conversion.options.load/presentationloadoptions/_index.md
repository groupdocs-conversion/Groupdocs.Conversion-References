---
title: "PresentationLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "प्रेज़ेंटेशन दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 29
url: /hi/java/com.groupdocs.conversion.options.load/presentationloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PresentationLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IDocumentsContainerLoadOptions
```

प्रेज़ेंटेशन दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PresentationLoadOptions()](#PresentationLoadOptions--) | नया उदाहरण प्रारंभ करता है [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | प्रेजेंटेशन रेंडरिंग के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | प्रेजेंटेशन रेंडरिंग के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | प्रेजेंटेशन दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को बदलें। |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | प्रेजेंटेशन दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को बदलें। |
|
|  | [getPassword()](#getPassword--) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [getHideComments()](#getHideComments--) | टिप्पणियों को छुपाएँ। |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | टिप्पणियों को छुपाएँ। |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | छिपी हुई स्लाइड्स दिखाएँ। |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | छिपी हुई स्लाइड्स दिखाएँ। |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
| [getDocumentFontSources()](#getDocumentFontSources--) |  |
| [setDocumentFontSources(List<String> documentFontSources)](#setDocumentFontSources-java.util.List-java.lang.String--) |  |
|  | [getNotesPosition()](#getNotesPosition--) | स्लाइड के साथ टिप्पणियों के प्रिंट होने के तरीके को दर्शाता है। |
|
|  | [setNotesPosition(PresentationNotesPosition notesPosition)](#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-) | स्लाइड के साथ नोट्स प्रिंट होने का तरीका दर्शाता है। |
|
| [getCommentsPosition()](#getCommentsPosition--) |  |
| [setCommentsPosition(PresentationCommentsPosition commentsPosition)](#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-) |  |
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


नया उदाहरण प्रारंभ करता है [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions) क्लास।


### getFormat() {#getFormat--}
```
public final PresentationFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[PresentationFileType](../../com.groupdocs.conversion.filetypes/presentationfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


प्रेजेंटेशन रेंडर करने के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि प्रेजेंटेशन फ़ॉन्ट अनुपलब्ध हो तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


प्रेजेंटेशन रेंडर करने के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि प्रेजेंटेशन फ़ॉन्ट अनुपलब्ध हो तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


प्रेजेंटेशन दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को बदलें।


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


प्रेजेंटेशन दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट को बदलें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


टिप्पणियों को छुपाएँ।


**Returns:**
बूलियन
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


टिप्पणियों को छुपाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


छिपी हुई स्लाइड्स दिखाएँ।


**Returns:**
बूलियन
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


छिपी हुई स्लाइड्स दिखाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


यदि true है तो सभी बाहरी संसाधन लोड नहीं होंगे, सिवाय उन संसाधनों के जो


**Returns:**
बूलियन
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| छोड़ें | बूलियन |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


बाहरी संसाधन जो हमेशा लोड किए जाएंगे


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getDocumentFontSources() {#getDocumentFontSources--}
```
public List<String> getDocumentFontSources()
```




**Returns:**
java.util.List<java.lang.String>
### setDocumentFontSources(List<String> documentFontSources) {#setDocumentFontSources-java.util.List-java.lang.String--}
```
public void setDocumentFontSources(List<String> documentFontSources)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentFontSources | java.util.List<java.lang.String> |  |

### getNotesPosition() {#getNotesPosition--}
```
public PresentationNotesPosition getNotesPosition()
```


स्लाइड के साथ टिप्पणियों के प्रिंट होने का तरीका दर्शाता है। डिफ़ॉल्ट कोई नहीं है।


**Returns:**
[PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition)
### setNotesPosition(PresentationNotesPosition notesPosition) {#setNotesPosition-com.groupdocs.conversion.contracts.PresentationNotesPosition-}
```
public void setNotesPosition(PresentationNotesPosition notesPosition)
```


स्लाइड के साथ नोट्स के प्रिंट होने का तरीका दर्शाता है। डिफ़ॉल्ट कोई नहीं है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| notesPosition | [PresentationNotesPosition](../../com.groupdocs.conversion.contracts/presentationnotesposition) |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public PresentationCommentsPosition getCommentsPosition()
```




**Returns:**
[PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) - 
### setCommentsPosition(PresentationCommentsPosition commentsPosition) {#setCommentsPosition-com.groupdocs.conversion.contracts.PresentationCommentsPosition-}
```
public void setCommentsPosition(PresentationCommentsPosition commentsPosition)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| commentsPosition | [PresentationCommentsPosition](../../com.groupdocs.conversion.contracts/presentationcommentsposition) |  |

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

