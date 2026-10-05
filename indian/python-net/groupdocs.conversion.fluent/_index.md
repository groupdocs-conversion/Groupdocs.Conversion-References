---
title: "groupdocs.conversion.fluent"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "प्रकार groupdocs.conversion.fluent के अंतर्गत।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/
is_root: false
weight: 50
---


प्रकार `groupdocs.conversion.fluent` के अंतर्गत।

### क्लासेस
| क्लास | विवरण |
| :- | :- |
| [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/) | कन्वर्ज़न पेज पूर्ण होने को संभालता है। |
| [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/) | कन्वर्ज़न पूर्णता को संभालता है या कन्वर्ज़न निष्पादित करता है। |
| [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/) | पृष्ठ रूपांतरण के लिए `OnConversionFailed` सेट होने के बाद एक सहज इंटरफ़ेस प्रदान करता है। `OnConversionCompleted` सेट करने या `Convert`/`Compress` पर आगे बढ़ने की अनुमति देता है। |
| [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/) | `OnConversionCompleted` सेट होने के बाद पृष्ठ रूपांतरण के लिए सहज इंटरफ़ेस को दर्शाता है, जिससे `OnConversionFailed` को कॉन्फ़िगर करने या `Convert`/`Compress` पर आगे बढ़ने की अनुमति मिलती है। |
| [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/) | केवल पृष्ठ-वार रूपांतरण हैंडलर्स सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है। |
| [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/) | पृष्ठ रूपांतरण हैंडलर्स सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है। |
| [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) | पृष्ठ-वार रूपांतरण हैंडलर्स चरण को सपाट रूप में दर्शाता है। |
| [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/) | पृष्ठ-वार रूपांतरण विकल्प या हैंडलर सेटअप सेट करने के लिए सहज इंटरफ़ेस। |
| [`IConversionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompleted/) | रूपांतरण पूर्ण होने को संभालता है। |
| [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/) | रूपांतरण पूर्ण होने को संभालें या रूपांतरण निष्पादित करें। |
| [`IConversionCompressResult`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresult/) | सभी रूपांतरण परिणामों को एक एकल संग्रह में संकुचित करता है। |
| [`IConversionCompressResultCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/) | संकुचन पूर्ण होने को संभालता है। |
| [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/) | `Compress(...)` के बाद निरंतरता। सीधे `Convert` के साथ आगे बढ़ें; विरासत में मिला [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) अब अप्रचलित है — इसके बजाय प्रवेश चरण में [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) के माध्यम से हैंडलर पंजीकृत करें। |
| [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/) | रूपांतरण निष्पादित करें। |
| [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/) | रूपांतरण विकल्पों को दर्शाता है। |
| [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/) | रूपांतरण विकल्प, पूर्णता संभालना, या रूपांतरण के लिए निष्पादन को दर्शाता है। |
| [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/) | रूपांतरण विकल्प, पूर्णता संभालना, या निष्पादन को दर्शाता है। |
| [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/) | रूपांतरण विकल्पों को दर्शाता है। |
| [`IConversionConvertOrCompress`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertorcompress/) | संकुचित करें या रूपांतरित करें। |
| [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/) | रूपांतरण के लिए स्रोत सेट करता है। |
| [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/) | स्रोत दस्तावेज़ की जानकारी प्राप्त करता है, जिसमें पृष्ठ गिनती और फ़ाइल प्रकार के विशिष्ट अन्य गुण शामिल हैं। |
| [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/) | स्रोत दस्तावेज़ के संभावित रूपांतरण प्राप्त करता है। |
| [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/) | `OnConversionFailed` सेट होने के बाद सहज इंटरफ़ेस को दर्शाता है, जिससे `OnConversionCompleted` सेट करने या `Convert`/`Compress` पर आगे बढ़ने की अनुमति मिलती है। |
| [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/) | `OnConversionCompleted` सेट होने के बाद एक सहज इंटरफ़ेस प्रदान करता है, जिससे `OnConversionFailed` को कॉन्फ़िगर करने या `Convert`/`Compress` पर आगे बढ़ने की अनुमति मिलती है। |
| [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/) | केवल रूपांतरण हैंडलर्स सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है। |
| [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/) | रूपांतरण हैंडलर्स सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है। किसी भी क्रम में `OnConversionCompleted` और/या `OnConversionFailed` को अधिकतम एक बार सेट करने, या दोनों को छोड़ने की अनुमति देता है। |
| [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/) | रूपांतरण हैंडलर्स चरण को सपाट रूप में दर्शाता है। |
| [`IConversionIsPasswordProtected`](/conversion/python-net/groupdocs.conversion.fluent/iconversionispasswordprotected/) | जाँचता है कि स्रोत दस्तावेज़ पासवर्ड से सुरक्षित है या नहीं। |
| [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/) | परिवर्तन लोड विकल्पों का प्रतिनिधित्व करता है। |
| [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/) | लोड किए गए दस्तावेज़ के साथ परिवर्तन लोड विकल्पों या क्रियाओं का प्रतिनिधित्व करता है। |
| [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/) | केवल परिवर्तन विकल्प सेट करने के लिए एक सहज इंटरफ़ेस प्रदान करता है। |
| [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/) | परिवर्तन विकल्पों या परिवर्तन हैंडलर सेटअप का प्रतिनिधित्व करता है। |
| [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/) | प्रवेश चरण ( `Load` से पहले) पर परिवर्तन सेटिंग्स या इवेंट्स सेट करें। |
| [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/) | परिवर्तन सेटिंग्स या परिवर्तन स्रोत का प्रतिनिधित्व करता है। |
| [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/) | लोड किए गए दस्तावेज़ के साथ संभावित क्रियाएँ प्रदान करता है। |
| [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/) | परिवर्तित दस्तावेज़ कैसे संग्रहीत किया जाता है, यह निर्धारित करता है। |
