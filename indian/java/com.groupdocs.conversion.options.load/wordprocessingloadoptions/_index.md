---
title: "WordProcessingLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "WordProcessing दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 40
url: /hi/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

WordProcessing दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | नया उदाहरण प्रारंभ करता है [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) क्लास। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Words दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Words दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | यदि AutoFontSubstitution अक्षम है, तो GroupDocs.Conversion गायब फ़ॉन्ट्स के प्रतिस्थापन के लिए DefaultFont का उपयोग करता है। |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | यदि AutoFontSubstitution अक्षम है, तो GroupDocs.Conversion गायब फ़ॉन्ट्स के प्रतिस्थापन के लिए DefaultFont का उपयोग करता है। |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Words दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट्स को प्रतिस्थापित करें। |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | यदि EmbedTrueTypeFonts सत्य है, तो GroupDocs.Conversion आउटपुट दस्तावेज़ में true type फ़ॉन्ट्स को एम्बेड करता है। |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | लोड करने के बाद पृष्ठ लेआउट को अपडेट करें। |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | लोड करने के बाद फ़ील्ड्स को अपडेट करें। |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | तारीख फ़ील्ड का मूल मान रखें। |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | तारीख फ़ील्ड का मूल मान रखने को सेट करता है। |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Words दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट्स को प्रतिस्थापित करें। |
|
|  | [getPassword()](#getPassword--) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Word दस्तावेज़ों के लिए मार्कअप और परिवर्तन ट्रैक को छुपाएँ। |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Word दस्तावेज़ों के लिए मार्कअप और परिवर्तन ट्रैक को छुपाएँ। |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | टिप्पणियों को छुपाएँ। |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | बुकमार्क विकल्प |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | बुकमार्क विकल्प |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | निर्दिष्ट करता है कि Microsoft Word फ़ॉर्म फ़ील्ड्स को PDF में फ़ॉर्म फ़ील्ड्स के रूप में संरक्षित रखना है या उन्हें टेक्स्ट में बदलना है। |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | preserveFontFields फ़्लैग को सेट करता है |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | बेहतर करनिंग डिस्प्ले के लिए टेक्स्ट शेपर का उपयोग करना है या नहीं, यह निर्दिष्ट करता है। |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | बेहतर करनिंग डिस्प्ले के लिए टेक्स्ट शेपर का उपयोग करना है या नहीं, यह निर्दिष्ट करता है। |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | निर्धारित करता है कि PDF में परिवर्तित करते समय दस्तावेज़ संरचना को संरक्षित रखना चाहिए या नहीं (डिफ़ॉल्ट रूप से गलत)। |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | निर्दिष्ट करता है कि आउटपुट दस्तावेज़ में टिप्पणियों को कैसे प्रदर्शित किया जाना चाहिए। |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | टिप्पणियों में टिप्पणीकर्ता का पूरा नाम दिखाएँ। |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | परिवर्तित दस्तावेज़ में पृष्ठ क्रमांक जनरेशन को सक्षम या अक्षम करें। |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | WordProcessing दस्तावेज़ों के लिए हाइफ़नेशन विकल्प प्राप्त करता है। |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | WordProcessing दस्तावेज़ों के लिए हाइफ़नेशन विकल्प सेट करता है। |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | InterruptThreadIfImageExceptionThrown फ़्लैग प्राप्त करता है डिफ़ॉल्ट: false यदि true हो तो मुख्य रूपांतरण थ्रेड को बाधित करें यदि इमेज प्रोसेसिंग थ्रेड में अपवाद हुआ हो। |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | InterruptThreadIfImageExceptionThrown फ़्लैग सेट करता है। |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | जब सक्षम हो (डिफ़ॉल्ट), पैराग्राफ़ और रन जिनका टेक्स्ट मुख्यतः दाएँ‑से‑बाएँ (RTL) है, रूपांतरण से पहले उनके bidi फ़्लैग ठीक किए जाएंगे। |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | autoDetectRtlDirection सेट करता है। |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


नया उदाहरण प्रारंभ करता है [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) क्लास।


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Words दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध हो तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Words दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध हो तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


यदि AutoFontSubstitution अक्षम है, तो GroupDocs.Conversion अनुपलब्ध फ़ॉन्टों के प्रतिस्थापन के लिए DefaultFont का उपयोग करता है। यदि AutoFontSubstitution सक्षम है,
GroupDocs.Conversion अनुपलब्ध फ़ॉन्ट के लिए FontInfo (Panose, Sig आदि) में सभी संबंधित फ़ील्डों का मूल्यांकन करता है और उपलब्ध फ़ॉन्ट स्रोतों में सबसे निकटतम मिलान खोजता है।
ध्यान दें कि फ़ॉन्ट प्रतिस्थापन तंत्र उन मामलों में DefaultFont को ओवरराइड करेगा जब दस्तावेज़ में अनुपलब्ध फ़ॉन्ट के लिए FontInfo उपलब्ध हो। डिफ़ॉल्ट मान True है।


**Returns:**
बूलियन
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


यदि AutoFontSubstitution अक्षम है, तो GroupDocs.Conversion अनुपलब्ध फ़ॉन्टों के प्रतिस्थापन के लिए DefaultFont का उपयोग करता है। यदि AutoFontSubstitution सक्षम है,
GroupDocs.Conversion अनुपलब्ध फ़ॉन्ट के लिए FontInfo (Panose, Sig आदि) में सभी संबंधित फ़ील्डों का मूल्यांकन करता है और उपलब्ध फ़ॉन्ट स्रोतों में सबसे निकटतम मिलान खोजता है।
ध्यान दें कि फ़ॉन्ट प्रतिस्थापन तंत्र उन मामलों में DefaultFont को ओवरराइड करेगा जब दस्तावेज़ में अनुपलब्ध फ़ॉन्ट के लिए FontInfo उपलब्ध हो। डिफ़ॉल्ट मान True है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Words दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट्स को प्रतिस्थापित करें।


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


यदि EmbedTrueTypeFonts true है, तो GroupDocs.Conversion आउटपुट दस्तावेज़ में TrueType फ़ॉन्ट एम्बेड करता है। डिफ़ॉल्ट: false


**Returns:**
बूलियन
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| embedTrueTypeFonts | बूलियन |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


लोड करने के बाद पेज लेआउट अपडेट करें। डिफ़ॉल्ट: false


**Returns:**
बूलियन
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| updatePageLayout | बूलियन |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


लोड करने के बाद फ़ील्ड अपडेट करें। डिफ़ॉल्ट: false


**Returns:**
बूलियन
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| updateFields | बूलियन |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


डेट फ़ील्ड का मूल मान रखें। डिफ़ॉल्ट: false


**Returns:**
बूलियन
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


तारीख फ़ील्ड का मूल मान रखने को सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keepDateFieldOriginalValue | बूलियन |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Words दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट्स को प्रतिस्थापित करें।


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

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Word दस्तावेज़ों के लिए मार्कअप और परिवर्तन ट्रैक को छुपाएँ।


**Returns:**
बूलियन
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Word दस्तावेज़ों के लिए मार्कअप और परिवर्तन ट्रैक को छुपाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


टिप्पणियों को छुपाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


बुकमार्क विकल्प


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


बुकमार्क विकल्प


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


निर्दिष्ट करता है कि Microsoft Word फ़ॉर्म फ़ील्ड को PDF में फ़ॉर्म फ़ील्ड के रूप में संरक्षित किया जाए या उन्हें टेक्स्ट में परिवर्तित किया जाए। डिफ़ॉल्ट false है।


**Returns:**
boolean - preserveFontFields फ़्लैग

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


preserveFontFields फ़्लैग को सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | preserveFontFields | बूलियन | Microsoft Word फ़ॉर्म फ़ील्ड को PDF में फ़ॉर्म फ़ील्ड के रूप में संरक्षित करें या उन्हें टेक्स्ट में परिवर्तित करें |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


बेहतर करनिंग डिस्प्ले के लिए टेक्स्ट शेपर का उपयोग करना है या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट false है।


**Returns:**
बूलियन
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


बेहतर करनिंग डिस्प्ले के लिए टेक्स्ट शेपर का उपयोग करना है या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट false है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | isUseTextShaper | बूलियन | isUseTextShaper फ़्लैग |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


निर्धारित करता है कि PDF में परिवर्तित करते समय दस्तावेज़ संरचना को संरक्षित किया जाना चाहिए या नहीं (डिफ़ॉल्ट false है)। ध्यान दें कि दस्तावेज़ संरचना को निर्यात करने से मेमोरी उपयोग में काफी वृद्धि होती है, विशेष रूप से बड़े दस्तावेज़ों के लिए।


**Returns:**
बूलियन
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| preserveDocumentStructure | बूलियन |  |

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

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


निर्दिष्ट करता है कि आउटपुट दस्तावेज़ में टिप्पणियाँ कैसे प्रदर्शित की जानी चाहिए। डिफ़ॉल्ट ShowInBalloons है।


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


टिप्पणियों में टिप्पणीकर्ता का पूरा नाम दिखाएँ। डिफ़ॉल्ट false है।


**Returns:**
बूलियन
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| showFullCommenterName | बूलियन |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


परिवर्तित दस्तावेज़ में पृष्ठ क्रमांक जनरेशन को सक्षम या अक्षम करें। डिफ़ॉल्ट: false


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

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


WordProcessing दस्तावेज़ों के लिए हाइफ़नेशन विकल्प प्राप्त करता है।


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


WordProcessing दस्तावेज़ों के लिए हाइफ़नेशन विकल्प सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


InterruptThreadIfImageExceptionThrown फ़्लैग प्राप्त करता है डिफ़ॉल्ट: false यदि true हो तो मुख्य रूपांतरण थ्रेड को बाधित करें यदि इमेज प्रोसेसिंग थ्रेड में अपवाद हुआ हो।


**Returns:**
बूलियन
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


InterruptThreadIfImageExceptionThrown फ़्लैग सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | बूलियन |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


जब सक्षम हो (डिफ़ॉल्ट), पैराग्राफ़ और रन जिनका टेक्स्ट मुख्यतः दाएँ‑से‑बाएँ (RTL) है, रूपांतरण से पहले उनके bidi फ़्लैग ठीक किए जाएंगे।


यह Microsoft Word और LibreOffice द्वारा लागू की गई हीयुरिस्टिक से मेल खाता है और
जनरेटर द्वारा निर्मित अरबी/हिब्रू दस्तावेज़ों की रेंडरिंग को ठीक करता है
(विशेष रूप से Google Docs) जो OOXML को बिना


और साथ में

केवल RTL स्क्रिप्ट वाले रन पर।


सेट करें
false
सख्त OOXML व्याख्या को संरक्षित करने के लिए
स्रोत मार्कअप।


**Returns:**
बूलियन
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


autoDetectRtlDirection सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | autoDetectRtlDirection | बूलियन | autoDetectRtlDirection |
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

