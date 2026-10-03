---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Reference"
description: "CSV दस्तावेज़ लोड करने के विकल्प।"
type: docs
weight: 2450
url: /hi/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

CSV दस्तावेज़ लोड करने के विकल्प।

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | नया उदाहरण प्रारंभ करता है [`CsvLoadOptions`](../csvloadoptions) क्लास का। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | यदि AllColumnsInOnePagePerSheet सत्य है, तो एक शीट की सभी कॉलम सामग्री परिणाम में केवल एक पृष्ठ पर आउटपुट होगी। pagesetup के कागज़ आकार की चौड़ाई अमान्य हो जाएगी, और pagesetup की अन्य सेटिंग्स अभी भी प्रभावी रहेंगी। |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | परिवर्तन के दौरान सभी पंक्तियों को स्वचालित रूप से फिट करता है |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | जब उपयोगकर्ता कोशिकाओं से संबंधित वस्तुओं को संशोधित करता है तो एक्सेल फ़ाइल की प्रतिबंधों की जाँच करें या नहीं। उदाहरण के लिए, एक्सेल 32K से अधिक लंबा स्ट्रिंग मान इनपुट करने की अनुमति नहीं देता। यदि आप 32K से अधिक मान इनपुट करते हैं और यह प्रॉपर्टी true है, तो आपको एक Exception मिलेगा। यदि यह प्रॉपर्टी false है, तो हम आपके इनपुट स्ट्रिंग मान को सेल के मान के रूप में स्वीकार करेंगे ताकि बाद में आप CSV जैसे अन्य फ़ाइल फ़ॉर्मेट के लिए पूर्ण स्ट्रिंग मान आउटपुट कर सकें। हालांकि, यदि आपने ऐसा मान सेट किया है जो एक्सेल फ़ाइल फ़ॉर्मेट के लिए अमान्य है, तो आपको बाद में वर्कबुक को एक्सेल फ़ाइल फ़ॉर्मेट में सहेजना नहीं चाहिए। अन्यथा उत्पन्न एक्सेल फ़ाइल में अप्रत्याशित त्रुटि हो सकती है। |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | दस्तावेज़ से अंतर्निहित मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | दस्तावेज़ से कस्टम मेटाडेटा प्रॉपर्टीज़ को हटाता है। |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | वर्कशीट को कॉलम के आधार पर पृष्ठों में विभाजित करें। डिफ़ॉल्ट 0 है, कोई पेजिनेशन नहीं। |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | यह दर्शाता है कि फ़ाइल में स्ट्रिंग को तिथि में परिवर्तित किया गया है या नहीं। डिफ़ॉल्ट True है। |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | यह दर्शाता है कि फ़ाइल में स्ट्रिंग को संख्यात्मक में परिवर्तित किया गया है या नहीं। डिफ़ॉल्ट True है। |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | लागू करता है [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) डिफ़ॉल्ट false है |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | लागू करता है [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) डिफ़ॉल्ट true है |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | स्प्रेडशीट फ़ॉर्मेट के अलावा अन्य फ़ॉर्मेट में बदलते समय विशिष्ट रेंज को बदलें। उदाहरण: "D1:F8"। |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | फ़ाइल लोड होने के समय सिस्टम कल्चर जानकारी प्राप्त करें या सेट करें |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | स्प्रेडशीट दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट। यदि कोई फ़ॉन्ट अनुपलब्ध है तो निम्नलिखित फ़ॉन्ट उपयोग किया जाएगा। |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | लागू करता है [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) डिफ़ॉल्ट: 1 |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | एन्कोडिंग। डिफ़ॉल्ट Encoding.Default है। |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | स्प्रेडशीट दस्तावेज़ को बदलते समय विशिष्ट फ़ॉन्टों को प्रतिस्थापित करें। |
| [Format](../../groupdocs.conversion.options.load/csvloadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | इनपुट दस्तावेज़ फ़ाइल प्रकार। |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | यदि पाठ "=" से शुरू होता है तो यह दर्शाता है कि वह फ़ॉर्मूला है। |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | सूचित करता है कि फ़ॉर्मूला गणना त्रुटियों को अनदेखा किया जाए या नहीं। त्रुटि असमर्थित फ़ंक्शन, बाहरी लिंक आदि हो सकती है। डिफ़ॉल्ट false है। |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True का अर्थ है कि फ़ाइल में कई एन्कोडिंग्स हैं। |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | पृष्ठ मार्जिन सेटिंग्स |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | यदि OnePagePerSheet true है तो शीट की सामग्री PDF दस्तावेज़ में एक पृष्ठ में बदल जाएगी। डिफ़ॉल्ट मान true है। |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | यदि True है और PDF में बदल रहे हैं तो रूपांतरण को बेहतर फ़ाइल आकार के लिए अनुकूलित किया जाता है, प्रिंट गुणवत्ता की तुलना में। |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | सुरक्षित दस्तावेज़ को अनप्रोटेक्ट करने के लिए पासवर्ड सेट करें। |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | निर्धारित करता है कि PDF में परिवर्तित करते समय दस्तावेज़ संरचना को संरक्षित किया जाना चाहिए या नहीं (डिफ़ॉल्ट false है)। |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | शीट के साथ टिप्पणियों के प्रिंट होने के तरीके को दर्शाता है। डिफ़ॉल्ट PrintNoComments है। |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | दस्तावेज़ लोड करने से पहले फ़ॉन्ट फ़ोल्डर रीसेट करें |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | वर्कशीट को पंक्तियों के आधार पर पृष्ठों में विभाजित करें। डिफ़ॉल्ट 0 है, कोई पेजिनेशन नहीं। |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Csv फ़ाइल का डिलिमिटर। |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | बदलने के लिए शीट इंडेक्स की सूची। इंडेक्स शून्य-आधारित होने चाहिए |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | बदलने के लिए शीट नाम |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Excel फ़ाइलों को बदलते समय ग्रिड लाइनों को दिखाएँ |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Excel फ़ाइलों को बदलते समय छिपी हुई शीट्स दिखाएँ |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | पृष्ठ आकार सेटिंग्स |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | बदलते समय खाली पंक्तियों और कॉलमों को छोड़ें। डिफ़ॉल्ट True है। |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | लागू करता है [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | स्प्रेडशीट दस्तावेज़ों को बदलते समय फुटर को छोड़ें। डिफ़ॉल्ट: false। |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | स्प्रेडशीट दस्तावेज़ों को बदलते समय हेडर को छोड़ें। डिफ़ॉल्ट: false। |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | लागू करता है [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | वर्तमान इंस्टेंस को क्लोन करता है। |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | निर्धारित करता है कि दो ऑब्जेक्ट इंस्टेंस समान हैं या नहीं। |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | डिफ़ॉल्ट हैश फ़ंक्शन के रूप में कार्य करता है। |

### देखें भी

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
