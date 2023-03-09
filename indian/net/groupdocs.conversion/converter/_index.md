---
title: Converter
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: दस्तवेज़ रूपंतरण प्रक्रय क नयंत्रत करने वले मुख्य वर्ग क प्रतनधत्व करत है
type: docs
weight: 730
url: /hi/net/groupdocs.conversion/converter/
---
## Converter class

दस्तावेज़ रूपांतरण प्रक्रिया को नियंत्रित करने वाले मुख्य वर्ग का प्रतिनिधित्व करता है।

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Converter](converter#constructor)() | का नया उदाहरण शुरू करता है[`Converter`](../converter) धाराप्रवाह रूपांतरण सेटअप के लिए वर्ग। |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_7)(string) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | का नया उदाहरण शुरू करता है[`Converter`](../converter) वर्ग. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। परिवर्तित दस्तावेज़ पृष्ठ पृष्ठ द्वारा सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | स्रोत दस्तावेज़ को रूपांतरित करता है। पूरे रूपांतरित दस्तावेज़ को सहेजता है। |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | संसाधन जारी करता है। |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | स्रोत दस्तावेज़ जानकारी प्राप्त करता है - पृष्ठों की संख्या और फ़ाइल प्रकार के लिए विशिष्ट अन्य दस्तावेज़ गुण। |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | स्रोत दस्तावेज़ के लिए संभावित रूपांतरण प्राप्त करता है. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | स्रोत दस्तावेज़ स्ट्रीम कॉन्फ़िगर करें |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | स्रोत दस्तावेज़ स्ट्रीम का सेट कॉन्फ़िगर करें |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | रूपांतरण के लिए स्रोत दस्तावेज़ कॉन्फ़िगर करें |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | स्रोत दस्तावेज़ों का सेट कॉन्फ़िगर करें |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | कन्वर्ज़न सेटिंग कॉन्फ़िगर करें |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | सभी समर्थित रूपांतरण प्राप्त करता है |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | प्रदान किए गए दस्तावेज़ एक्सटेंशन के लिए समर्थित रूपांतरण प्राप्त करता है |

### यह सभी देखें

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* नाम स्थान [GroupDocs.Conversion](../../groupdocs.conversion)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
