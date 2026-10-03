---
title: "PdfOptimizationOptions"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "Pdf ऑप्टिमाइज़ेशन विकल्पों को परिभाषित करता है।"
type: docs
weight: 29
url: /hi/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Pdf ऑप्टिमाइज़ेशन विकल्पों को परिभाषित करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | नया उदाहरण प्रारंभ करता है [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | डुप्लिकेट स्ट्रीम्स को लिंक करें |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | डुप्लिकेट स्ट्रीम्स को लिंक करें |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | अप्रयुक्त ऑब्जेक्ट्स हटाएँ |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | अप्रयुक्त ऑब्जेक्ट्स हटाएँ |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | अप्रयुक्त स्ट्रीम्स हटाएँ |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | अप्रयुक्त स्ट्रीम्स हटाएँ |
|
|  | [getCompressImages()](#getCompressImages--) | यदि CompressImages सेट किया गया है |
true
, दस्तावेज़ में सभी छवियों को पुनः संपीड़ित किया जाता है।
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | यदि CompressImages सेट किया गया है |
true
, दस्तावेज़ में सभी छवियों को पुनः संपीड़ित किया जाता है।
|
|  | [getImageQuality()](#getImageQuality--) | प्रतिशत में मान जहाँ 100% अपरिवर्तित गुणवत्ता और छवि आकार है। |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | प्रतिशत में मान जहाँ 100% अपरिवर्तित गुणवत्ता और छवि आकार है। |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | यदि true सेट किया गया है तो फ़ॉन्ट्स को एम्बेड न करें |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | यदि true सेट किया गया है तो फ़ॉन्ट्स को एम्बेड न करें |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | फ़ॉन्ट उपसमुच्चय रणनीति सेट करें |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


नया उदाहरण प्रारंभ करता है [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) क्लास का।


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


डुप्लिकेट स्ट्रीम्स को लिंक करें


**Returns:**
बूलियन
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


डुप्लिकेट स्ट्रीम्स को लिंक करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


अप्रयुक्त ऑब्जेक्ट्स हटाएँ


**Returns:**
बूलियन
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


अप्रयुक्त ऑब्जेक्ट्स हटाएँ


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


अप्रयुक्त स्ट्रीम्स हटाएँ


**Returns:**
बूलियन
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


अप्रयुक्त स्ट्रीम्स हटाएँ


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


यदि CompressImages सेट किया गया है
true
, दस्तावेज़ में सभी छवियों को पुनः संपीड़ित किया जाता है। संपीड़न ImageQuality प्रॉपर्टी द्वारा परिभाषित है।


**Returns:**
बूलियन
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


यदि CompressImages सेट किया गया है
true
, दस्तावेज़ में सभी छवियों को पुनः संपीड़ित किया जाता है। संपीड़न ImageQuality प्रॉपर्टी द्वारा परिभाषित है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


प्रतिशत में मान जहाँ 100% अपरिवर्तित गुणवत्ता और छवि आकार है। छवि आकार को कम करने के लिए इस प्रॉपर्टी को 100 से कम सेट करें।


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


प्रतिशत में मान जहाँ 100% अपरिवर्तित गुणवत्ता और छवि आकार है। छवि आकार को कम करने के लिए इस प्रॉपर्टी को 100 से कम सेट करें।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


यदि true सेट किया गया है तो फ़ॉन्ट्स को एम्बेड न करें


**Returns:**
बूलियन
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


यदि true सेट किया गया है तो फ़ॉन्ट्स को एम्बेड न करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


फ़ॉन्ट उपसमुच्चय रणनीति सेट करें


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

