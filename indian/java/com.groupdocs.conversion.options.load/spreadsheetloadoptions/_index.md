---
title: "SpreadsheetLoadOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "स्प्रेडशीट दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 31
url: /hi/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

स्प्रेडशीट दस्तावेज़ लोड करने के विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | नया उदाहरण प्रारंभ करता है [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) वर्ग का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSheets()](#getSheets--) | परिवर्तित करने के लिए शीट का नाम प्राप्त करें |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | परिवर्तित करने के लिए शीट का नाम सेट करें |
|
|  | [getCultureInfo()](#getCultureInfo--) | फ़ाइल लोड होने के समय सिस्टम संस्कृति जानकारी प्राप्त करें |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | फ़ाइल लोड होने के समय सिस्टम संस्कृति जानकारी सेट करें |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | स्प्रेडशीट दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | स्प्रेडशीट दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | स्प्रेडशीट दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें। |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | स्प्रेडशीट दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें। |
|
|  | [getShowGridLines()](#getShowGridLines--) | Excel फ़ाइलों को परिवर्तित करते समय ग्रिड लाइनों को दिखाएँ। |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Excel फ़ाइलों को परिवर्तित करते समय ग्रिड लाइनों को दिखाएँ। |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | Excel फ़ाइलों को परिवर्तित करते समय छिपी शीट्स दिखाएँ। |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Excel फ़ाइलों को परिवर्तित करते समय छिपी शीट्स दिखाएँ। |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | यदि OnePagePerSheet सत्य है तो शीट की सामग्री PDF दस्तावेज़ में एक पृष्ठ में परिवर्तित होगी। |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | यदि OnePagePerSheet सत्य है तो शीट की सामग्री PDF दस्तावेज़ में एक पृष्ठ में परिवर्तित होगी। |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | AllColumnsInOnePagePerSheet प्रॉपर्टी प्राप्त करता है |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | AllColumnsInOnePagePerSheet प्रॉपर्टी सेट करता है |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | यदि सत्य है और PDF में परिवर्तित किया जा रहा है तो रूपांतरण बेहतर फ़ाइल आकार के लिए अनुकूलित किया जाता है, प्रिंट गुणवत्ता की तुलना में। |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | यदि सत्य है और PDF में परिवर्तित किया जा रहा है तो रूपांतरण बेहतर फ़ाइल आकार के लिए अनुकूलित किया जाता है, प्रिंट गुणवत्ता की तुलना में। |
|
|  | [getConvertRange()](#getConvertRange--) | स्प्रेडशीट स्वरूप के अलावा अन्य स्वरूप में परिवर्तित करते समय विशिष्ट रेंज को परिवर्तित करें। |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | स्प्रेडशीट स्वरूप के अलावा अन्य स्वरूप में परिवर्तित करते समय विशिष्ट रेंज को परिवर्तित करें। |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | परिवर्तित करते समय खाली पंक्तियों और स्तंभों को छोड़ें। |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | परिवर्तित करते समय खाली पंक्तियों और स्तंभों को छोड़ें। |
|
|  | [getPassword()](#getPassword--) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
|
|  | [getHideComments()](#getHideComments--) | टिप्पणियों को छुपाएँ। |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | टिप्पणियों को छुपाएँ। |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | जब उपयोगकर्ता सेल संबंधित वस्तुओं को संशोधित करता है तो Excel फ़ाइल की प्रतिबंध जांचें या नहीं। |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | परिवर्तित करने के लिए शीट इंडेक्स की सूची प्राप्त करता है। |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | परिवर्तित करने के लिए शीट इंडेक्स की सूची सेट करता है। |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | परिवर्तित करते समय सभी पंक्तियों को स्वचालित रूप से फिट करें |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | वर्तमान उदाहरण की प्रतिलिपि बनाता है। |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | वर्कशीट को पंक्तियों के आधार पर पृष्ठों में विभाजित करें। |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | वर्कशीट को पंक्तियों के आधार पर पृष्ठों में विभाजित करें। |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | वर्कशीट को स्तंभों के आधार पर पृष्ठों में विभाजित करें। |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | वर्कशीट को स्तंभों के आधार पर पृष्ठों में विभाजित करें। |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


नया उदाहरण प्रारंभ करता है [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) वर्ग का।


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


परिवर्तित करने के लिए शीट का नाम प्राप्त करें


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


परिवर्तित करने के लिए शीट का नाम सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| शीट्स | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


फ़ाइल लोड होने के समय सिस्टम संस्कृति जानकारी प्राप्त करें


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


फ़ाइल लोड होने के समय सिस्टम संस्कृति जानकारी सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


इनपुट दस्तावेज़ फ़ाइल प्रकार


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


स्प्रेडशीट दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट का उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


स्प्रेडशीट दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट का उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


स्प्रेडशीट दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें।


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


स्प्रेडशीट दस्तावेज़ को परिवर्तित करते समय विशिष्ट फ़ॉन्ट बदलें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Excel फ़ाइलों को परिवर्तित करते समय ग्रिड लाइनों को दिखाएँ।


**Returns:**
बूलियन
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Excel फ़ाइलों को परिवर्तित करते समय ग्रिड लाइनों को दिखाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Excel फ़ाइलों को परिवर्तित करते समय छिपी शीट्स दिखाएँ।


**Returns:**
बूलियन
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Excel फ़ाइलों को परिवर्तित करते समय छिपी शीट्स दिखाएँ।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


यदि OnePagePerSheet सत्य है तो शीट की सामग्री को PDF दस्तावेज़ में एक पृष्ठ में परिवर्तित किया जाएगा। डिफ़ॉल्ट मान गलत (false) है।


**Returns:**
बूलियन
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


यदि OnePagePerSheet सत्य है तो शीट की सामग्री को PDF दस्तावेज़ में एक पृष्ठ में परिवर्तित किया जाएगा। डिफ़ॉल्ट मान गलत (false) है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


AllColumnsInOnePagePerSheet प्रॉपर्टी प्राप्त करता है


**Returns:**
boolean - यदि सभी कॉलम एक पृष्ठ में फिट होते हैं तो सत्य

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


AllColumnsInOnePagePerSheet प्रॉपर्टी सेट करता है


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | बूलियन | AllColumnsInOnePagePerSheet प्रॉपर्टी |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


यदि सत्य है और PDF में परिवर्तित किया जा रहा है तो रूपांतरण बेहतर फ़ाइल आकार के लिए अनुकूलित किया जाता है, प्रिंट गुणवत्ता की तुलना में।


**Returns:**
बूलियन
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


यदि सत्य है और PDF में परिवर्तित किया जा रहा है तो रूपांतरण बेहतर फ़ाइल आकार के लिए अनुकूलित किया जाता है, प्रिंट गुणवत्ता की तुलना में।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


स्प्रेडशीट फ़ॉर्मेट के अलावा अन्य फ़ॉर्मेट में परिवर्तित करते समय विशिष्ट रेंज को बदलें। उदाहरण: "D1:F8"।


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


स्प्रेडशीट फ़ॉर्मेट के अलावा अन्य फ़ॉर्मेट में परिवर्तित करते समय विशिष्ट रेंज को बदलें। उदाहरण: "D1:F8"।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


परिवर्तन के दौरान खाली पंक्तियों और कॉलमों को छोड़ देता है। डिफ़ॉल्ट सत्य (True) है।


**Returns:**
बूलियन
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


परिवर्तन के दौरान खाली पंक्तियों और कॉलमों को छोड़ देता है। डिफ़ॉल्ट सत्य (True) है।


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

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


जब उपयोगकर्ता कोशिकाओं से संबंधित वस्तुओं को संशोधित करता है तो एक्सेल फ़ाइल की प्रतिबंधों की जाँच करनी चाहिए या नहीं। उदाहरण के लिए, एक्सेल 32K से अधिक लंबी स्ट्रिंग मान को इनपुट करने की अनुमति नहीं देता। यदि आप 32K से अधिक मान इनपुट करते हैं और यह प्रॉपर्टी सत्य है, तो आपको एक Exception मिलेगा। यदि यह प्रॉपर्टी गलत (false) है, तो हम आपके इनपुट स्ट्रिंग मान को सेल के मान के रूप में स्वीकार करेंगे ताकि बाद में आप CSV जैसे अन्य फ़ाइल फ़ॉर्मेट के लिए पूर्ण स्ट्रिंग मान आउटपुट कर सकें। हालांकि, यदि आप ऐसा मान सेट करते हैं जो एक्सेल फ़ाइल फ़ॉर्मेट के लिए अमान्य है, तो आपको बाद में वर्कबुक को एक्सेल फ़ाइल फ़ॉर्मेट में सहेजना नहीं चाहिए। अन्यथा उत्पन्न एक्सेल फ़ाइल में अप्रत्याशित त्रुटि हो सकती है।


**Returns:**
boolean - प्रतिबंध जाँच फ़्लैग

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| checkExcelRestriction | बूलियन |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


परिवर्तित करने के लिए शीट इंडेक्स की सूची प्राप्त करता है।


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


परिवर्तित करने के लिए शीट इंडेक्स की सूची सेट करता है। इंडेक्स शून्य-आधारित होने चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


परिवर्तित करते समय सभी पंक्तियों को स्वचालित रूप से फिट करें


**Returns:**
बूलियन
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| autoFitRows | बूलियन |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें


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

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


वर्तमान उदाहरण की प्रतिलिपि बनाता है।


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


वर्कशीट को पंक्तियों द्वारा पृष्ठों में विभाजित करें। डिफ़ॉल्ट 0 है, कोई पेजिनेशन नहीं।


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


वर्कशीट को पंक्तियों द्वारा पृष्ठों में विभाजित करें। डिफ़ॉल्ट 0 है, कोई पेजिनेशन नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


वर्कशीट को कॉलमों द्वारा पृष्ठों में विभाजित करें। डिफ़ॉल्ट 0 है, कोई पेजिनेशन नहीं।


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


वर्कशीट को कॉलमों द्वारा पृष्ठों में विभाजित करें। डिफ़ॉल्ट 0 है, कोई पेजिनेशन नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnsPerPage | int |  |

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

