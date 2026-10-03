---
title: "PdfFileType"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "PDF दस्तावेज़ों को परिभाषित करता है।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Pdf दस्तावेज़ों को परिभाषित करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | सीरियलाइज़ेशन कंस्ट्रक्टर |
|
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) 1990 के दशक में Adobe द्वारा बनाई गई दस्तावेज़ प्रकार है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


सीरियलाइज़ेशन कंस्ट्रक्टर


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) 1990 के दशक में Adobe द्वारा बनाई गई दस्तावेज़ प्रकार है। इस फ़ाइल फ़ॉर्मेट का उद्देश्य एक मानक प्रस्तुत करना था जिससे दस्तावेज़ और अन्य संदर्भ सामग्री को ऐसे फ़ॉर्मेट में दर्शाया जा सके जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://wiki.fileformat.com/view/pdf).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


स्रोत फ़ाइल प्रकार के लिए डिफ़ॉल्ट लोड विकल्प तैयार किए गए


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


फ़ाइल प्रकार के लिए डिफ़ॉल्ट रूपांतरण विकल्प तैयार किए गए


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
