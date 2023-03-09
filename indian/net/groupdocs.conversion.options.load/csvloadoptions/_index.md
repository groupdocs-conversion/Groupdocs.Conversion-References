---
title: CsvLoadOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Conversion
description: सएसव दस्तवेज लड करने के लए वकल्प
type: docs
weight: 2050
url: /hi/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

सीएसवी दस्तावेज लोड करने के लिए विकल्प।

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | का नया उदाहरण शुरू करता है[`CsvLoadOptions`](../csvloadoptions) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | जब उपयोगकर्ता सेल से संबंधित वस्तुओं को संशोधित करता है तो क्या एक्सेल फ़ाइल के प्रतिबंध की जाँच करें। उदाहरण के लिए, एक्सेल 32K से अधिक स्ट्रिंग मान इनपुट करने की अनुमति नहीं देता है। जब आप 32K से अधिक मूल्य इनपुट करते हैं, यदि यह गुण सत्य है, तो आपको एक अपवाद मिलेगा। यदि यह गुण गलत है, तो हम आपके इनपुट स्ट्रिंग मान को सेल के मान के रूप में स्वीकार करेंगे ताकि बाद में आप CSV जैसे अन्य फ़ाइल स्वरूपों के लिए पूर्ण स्ट्रिंग मान आउटपुट कर सकें। हालाँकि, यदि आपने इस तरह का मान निर्धारित किया है जो एक्सेल फ़ाइल स्वरूप के लिए अमान्य है, तो आपको कार्यपुस्तिका को बाद में एक्सेल फ़ाइल स्वरूप के रूप में सहेजना नहीं चाहिए। अन्यथा जेनरेट की गई एक्सेल फाइल के लिए अनपेक्षित त्रुटि हो सकती है। |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | इंगित करता है कि फ़ाइल में स्ट्रिंग दिनांक में परिवर्तित हो गई है या नहीं। डिफ़ॉल्ट True. है |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | इंगित करता है कि फ़ाइल में स्ट्रिंग संख्यात्मक में परिवर्तित हो गई है या नहीं। डिफ़ॉल्ट True. है |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | स्प्रेडशीट प्रारूप के अलावा किसी अन्य प्रारूप में कनवर्ट करते समय विशिष्ट श्रेणी को कनवर्ट करें। उदाहरण: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | फ़ाइल लोड होने के समय सिस्टम कल्चर जानकारी प्राप्त करें या सेट करें |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | स्प्रेडशीट दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्न फ़ॉन्ट का उपयोग किया जाएगा. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | एन्कोडिंग। डिफ़ॉल्ट एन्कोडिंग है। डिफ़ॉल्ट. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | स्प्रेडशीट दस्तावेज़ को कनवर्ट करते समय विशिष्ट फ़ॉन्ट बदलें. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | इनपुट दस्तावेज़ फ़ाइल प्रकार. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | इंगित करता है कि पाठ सूत्र है यदि यह "=". से शुरू होता है |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | टिप्पणियां छुपाएं. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | सही का मतलब है कि फ़ाइल में कई एन्कोडिंग हैं. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | यदि OnePagePerSheet सही है तो शीट की सामग्री को PDF दस्तावेज़ के एक पृष्ठ में बदल दिया जाएगा। डिफ़ॉल्ट मान सत्य है। |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | यदि सही है और पीडीएफ में परिवर्तित हो रहा है तो प्रिंट गुणवत्ता की तुलना में बेहतर फ़ाइल आकार के लिए रूपांतरण को अनुकूलित किया गया है। |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | सुरक्षित दस्तावेज़ को असुरक्षित करने के लिए पासवर्ड सेट करें। |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | एक सीएसवी फ़ाइल का सीमांकक। |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | कनवर्ट करने के लिए शीट इंडेक्स की सूची। इंडेक्स शून्य-आधारित होना चाहिए |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | कन्वर्ट करने के लिए शीट का नाम |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | एक्सेल फ़ाइलों को परिवर्तित करते समय ग्रिड लाइनें दिखाएं। |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | एक्सेल फ़ाइलों को कनवर्ट करते समय छिपी हुई शीट दिखाएं। |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | परिवर्तित करते समय खाली पंक्तियों और स्तंभों को छोड़ देता है। डिफ़ॉल्ट True. है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | क्लोन वर्तमान उदाहरण। |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि क्या दो वस्तु उदाहरण समान हैं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### यह सभी देखें

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* नाम स्थान [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* सभा [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
