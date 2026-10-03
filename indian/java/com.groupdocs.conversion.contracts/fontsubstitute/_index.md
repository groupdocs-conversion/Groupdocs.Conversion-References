---
title: "FontSubstitute"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "गायब फ़ॉन्ट के लिए प्रतिस्थापन का वर्णन करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

गायब फ़ॉन्ट के लिए प्रतिस्थापन का वर्णन करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | नया फ़ॉन्ट प्रतिस्थापन जोड़ी बनाएं। |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | मूल फ़ॉन्ट नाम। |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | प्रतिस्थापन फ़ॉन्ट नाम। |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


नया फ़ॉन्ट प्रतिस्थापन जोड़ी बनाएं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | originalFont | java.lang.String | स्रोत दस्तावेज़ से फ़ॉन्ट। |
|
|  | substituteWith | java.lang.String | फ़ॉन्ट जो originalFont को बदलने के लिए उपयोग किया जाएगा। |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


मूल फ़ॉन्ट नाम।


**Returns:**
java.lang.String - मूल फ़ॉन्ट नाम।

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


प्रतिस्थापन फ़ॉन्ट नाम।


**Returns:**
java.lang.String - प्रतिस्थापन फ़ॉन्ट नाम।

