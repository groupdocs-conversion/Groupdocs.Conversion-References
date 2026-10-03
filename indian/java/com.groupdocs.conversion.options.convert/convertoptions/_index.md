---
title: "ConvertOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "सामान्य रूपांतरण विकल्प वर्ग।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

सामान्य रूपांतरण विकल्प वर्ग।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए। |
|
|  | [deepClone()](#deepClone--) | वर्तमान विकल्प इंस्टेंस की प्रतिलिपि बनाता है। |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए। |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए। |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


इनपुट दस्तावेज़ को जिस वांछित फ़ाइल प्रकार में परिवर्तित किया जाना चाहिए, उसे प्राप्त करता है।


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


वर्तमान विकल्प इंस्टेंस की प्रतिलिपि बनाता है।


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए।


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


वांछित फ़ाइल प्रकार जिसमें इनपुट दस्तावेज़ को परिवर्तित किया जाना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | TFileType |  |

