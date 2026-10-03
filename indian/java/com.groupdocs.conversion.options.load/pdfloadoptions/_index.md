---
title: "PdfLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "पीडीएफ दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 27
url: /hi/java/com.groupdocs.conversion.options.load/pdfloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public final class PdfLoadOptions extends LoadOptions implements Serializable, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

पीडीएफ दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfLoadOptions()](#PdfLoadOptions--) | नया उदाहरण इनिशियलाइज़ करता है [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getRemoveEmbeddedFiles()](#getRemoveEmbeddedFiles--) | एम्बेडेड फ़ाइलें हटाएँ। |
|
|  | [setRemoveEmbeddedFiles(boolean value)](#setRemoveEmbeddedFiles-boolean-) | एम्बेडेड फ़ाइलें हटाएँ। |
|
|  | [getPassword()](#getPassword--) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [getDefaultFont()](#getDefaultFont--) | Pdf दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pdf दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Pdf दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें। |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Pdf दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें। |
|
|  | [getHidePdfAnnotations()](#getHidePdfAnnotations--) | Pdf दस्तावेज़ों में एनोटेशन छिपाएँ। |
|
|  | [setHidePdfAnnotations(boolean value)](#setHidePdfAnnotations-boolean-) | Pdf दस्तावेज़ों में एनोटेशन छिपाएँ। |
|
|  | [getFlattenAllFields()](#getFlattenAllFields--) | PDF फ़ॉर्म के सभी फ़ील्ड को फ्लैटन करें। |
|
|  | [setFlattenAllFields(boolean value)](#setFlattenAllFields-boolean-) | PDF फ़ॉर्म के सभी फ़ील्ड को फ्लैटन करें। |
|
|  | [getResetFontFolders()](#getResetFontFolders--) | दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें। |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | परिवर्तित दस्तावेज़ में पृष्ठ क्रमांक जनरेशन को सक्षम या अक्षम करें। |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [isRemoveJavascript()](#isRemoveJavascript--) | Remove JavaScript फ़्लैग प्राप्त करता है। |
|
|  | [setRemoveJavascript(boolean removeJavascript)](#setRemoveJavascript-boolean-) | Remove JavaScript फ़्लैग सेट करता है। |
|
|  | [isConvertOwner()](#isConvertOwner--) | निर्दिष्ट करता है कि मालिक दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं। |
|
|  | [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) | निर्दिष्ट करता है कि मालिक दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं। |
|
|  | [isConvertOwned()](#isConvertOwned--) | निर्दिष्ट करता है कि स्वामित्व वाले दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं। |
|
|  | [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) | निर्दिष्ट करता है कि स्वामित्व वाले दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं। |
|
|  | [getDepth()](#getDepth--) | स्वामित्व वाले दस्तावेज़ों को प्रोसेस करने की अधिकतम गहराई। |
|
|  | [setDepth(int depth)](#setDepth-int-) | स्वामित्व वाले दस्तावेज़ों को प्रोसेस करने की अधिकतम गहराई। |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


नया उदाहरण इनिशियलाइज़ करता है [PdfLoadOptions](../../com.groupdocs.conversion.options.load/pdfloadoptions) क्लास का।


### getFormat() {#getFormat--}
```
public final PdfFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[PdfFileType](../../com.groupdocs.conversion.filetypes/pdffiletype)
### getRemoveEmbeddedFiles() {#getRemoveEmbeddedFiles--}
```
public final boolean getRemoveEmbeddedFiles()
```


एम्बेडेड फ़ाइलें हटाएँ।


**Returns:**
बूलियन
### setRemoveEmbeddedFiles(boolean value) {#setRemoveEmbeddedFiles-boolean-}
```
public final void setRemoveEmbeddedFiles(boolean value)
```


एम्बेडेड फ़ाइलें हटाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

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

### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Pdf दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट।
यदि फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Pdf दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट।
यदि फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Pdf दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें।


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Pdf दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getHidePdfAnnotations() {#getHidePdfAnnotations--}
```
public final boolean getHidePdfAnnotations()
```


Pdf दस्तावेज़ों में एनोटेशन छिपाएँ।


**Returns:**
बूलियन
### setHidePdfAnnotations(boolean value) {#setHidePdfAnnotations-boolean-}
```
public final void setHidePdfAnnotations(boolean value)
```


Pdf दस्तावेज़ों में एनोटेशन छिपाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getFlattenAllFields() {#getFlattenAllFields--}
```
public final boolean getFlattenAllFields()
```


PDF फ़ॉर्म के सभी फ़ील्ड को फ्लैटन करें।


**Returns:**
बूलियन
### setFlattenAllFields(boolean value) {#setFlattenAllFields-boolean-}
```
public final void setFlattenAllFields(boolean value)
```


PDF फ़ॉर्म के सभी फ़ील्ड को फ्लैटन करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें।


**Returns:**
बूलियन
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resetFontFolders | बूलियन |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


परिवर्तित दस्तावेज़ में पेज नंबरिंग जनरेशन को सक्षम या अक्षम करें। डिफ़ॉल्ट: false.


**Returns:**
बूलियन
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isPageNumbering | बूलियन |  |

### isRemoveJavascript() {#isRemoveJavascript--}
```
public boolean isRemoveJavascript()
```


Remove JavaScript फ़्लैग प्राप्त करता है।


**Returns:**
बूलियन
### setRemoveJavascript(boolean removeJavascript) {#setRemoveJavascript-boolean-}
```
public void setRemoveJavascript(boolean removeJavascript)
```


Remove JavaScript फ़्लैग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| removeJavascript | बूलियन |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


निर्दिष्ट करता है कि मालिक दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं।

डिफ़ॉल्ट है
true
.


**Returns:**
बूलियन
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```


निर्दिष्ट करता है कि मालिक दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं।

डिफ़ॉल्ट है
true
.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOwner | बूलियन |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


निर्दिष्ट करता है कि स्वामित्व वाले दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं।

डिफ़ॉल्ट है
false
.


**Returns:**
बूलियन
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```


निर्दिष्ट करता है कि स्वामित्व वाले दस्तावेज़ को परिवर्तित किया जाना चाहिए या नहीं।

डिफ़ॉल्ट है
false
.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertOwned | बूलियन |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


स्वामित्व वाले दस्तावेज़ों को प्रोसेस करने की अधिकतम गहराई।

डिफ़ॉल्ट है
2
.


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```


स्वामित्व वाले दस्तावेज़ों को प्रोसेस करने की अधिकतम गहराई।

डिफ़ॉल्ट है
2
.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| depth | int |  |

