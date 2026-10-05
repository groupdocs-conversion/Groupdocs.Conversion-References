---
title: "EmailFileType क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "ईमेल एप्लिकेशन द्वारा संदेश, अटैचमेंट, फ़ोल्डर, एड्रेस बुक और अन्य डेटा को संग्रहीत करने के लिए उपयोग किए जाने वाले ईमेल फ़ाइल फ़ॉर्मेट्स को परिभाषित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

ईमेल एप्लिकेशन द्वारा संदेश, अटैचमेंट, फ़ोल्डर, एड्रेस बुक और अन्य डेटा को संग्रहीत करने के लिए उपयोग किए जाने वाले ईमेल फ़ाइल फ़ॉर्मेट्स को परिभाषित करता है।

निम्नलिखित फ़ाइल प्रकार शामिल हैं:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

ईमेल फ़ॉर्मेट के बारे में अधिक जानने के लिए https://wiki.fileformat.com/email पर जाएँ।

EmailFileType प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | सीरियलाइज़ेशन के लिए नया EmailFileType प्रारंभ करता है। |

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | वर्तमान ऑब्जेक्ट की तुलना अन्य से करता है। ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) से विरासत में मिला) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) से विरासत में मिला) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) द्वारा परिभाषित समानता तुलना को लागू करता है। ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) से विरासत में मिला) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) से विरासत में मिला) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) से विरासत में मिला) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | प्रदान किए गए फ़ाइल एक्सटेंशन के लिए FileType प्राप्त करता है। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | निर्दिष्ट file_name के लिए FileType लौटाता है। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | प्रदान किए गए दस्तावेज़ स्ट्रीम के लिए FileType लौटाता है। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) से विरासत में मिला) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | डिफ़ॉल्ट हैश फ़ंक्शन प्रदान करता है। ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) से विरासत में मिला) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | फ़ाइल प्रकार का स्ट्रिंग प्रतिनिधित्व। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### गुणधर्म
| गुण | विवरण |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | फ़ाइल प्रकार का विवरण। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | फ़ाइल एक्सटेंशन। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | फ़ाइल परिवार। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | फ़ाइल फ़ॉर्मेट। (विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG एक फ़ाइल फ़ॉर्मेट है जिसे Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, अपॉइंटमेंट या अन्य कार्यों को संग्रहीत करने के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | EML फ़ाइल फ़ॉर्मेट Outlook और अन्य संबंधित अनुप्रयोगों द्वारा सहेजे गए ईमेल संदेशों को दर्शाता है। लगभग सभी ईमेल क्लाइंट इस फ़ॉर्मेट का समर्थन करते हैं क्योंकि यह RFC-822 इंटरनेट संदेश फ़ॉर्मेट मानक के अनुरूप है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | EMLX फ़ाइल फ़ॉर्मेट Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल फ़ॉर्मेट का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (वर्चुअल कार्ड फ़ॉर्मेट) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल फ़ॉर्मेट है। यह फ़ॉर्मेट लोकप्रिय सूचना विनिमय अनुप्रयोगों के बीच डेटा आदान-प्रदान के लिए व्यापक रूप से उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | MBox फ़ाइल फ़ॉर्मेट एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए कंटेनर को दर्शाता है। संदेशों को उनके अटैचमेंट्स के साथ कंटेनर के भीतर संग्रहीत किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | .PST एक्सटेंशन वाली फ़ाइलें Outlook पर्सनल स्टोरेज फ़ाइलें (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) दर्शाती हैं, जो विभिन्न उपयोगकर्ता जानकारी को संग्रहीत करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST या ऑफ़लाइन स्टोरेज फ़ाइलें Microsoft Outlook का उपयोग करके Exchange Server के साथ पंजीकरण के बाद स्थानीय मशीन पर ऑफ़लाइन मोड में उपयोगकर्ता के मेलबॉक्स डेटा को दर्शाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | .olm एक्सटेंशन वाली फ़ाइल Microsoft Outlook की Mac ऑपरेटिंग सिस्टम के लिए फ़ाइल है। OLM फ़ाइल ईमेल संदेश, जर्नल, कैलेंडर डेटा और अन्य प्रकार के एप्लिकेशन डेटा को संग्रहीत करती है। ये Windows ऑपरेटिंग सिस्टम पर Outlook द्वारा उपयोग की जाने वाली PST फ़ाइलों के समान हैं। हालांकि, Mac के लिए Outlook द्वारा बनाई गई OLM फ़ाइलें Windows के लिए Outlook में नहीं खोली जा सकतीं। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | ICS (iCalendar) फ़ाइल फ़ॉर्मेट इवेंट्स, टु-डू, और फ्री/बिजी डेटा जैसी कैलेंडरिंग और शेड्यूलिंग जानकारी को दर्शाने और आदान-प्रदान करने के लिए उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में यहाँ अधिक जानें। |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | अज्ञात फ़ाइल प्रकार (से विरासत में मिला [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### साथ ही देखें
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
