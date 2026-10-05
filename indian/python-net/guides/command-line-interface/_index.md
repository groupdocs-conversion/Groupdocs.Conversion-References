---
title: "कमांड लाइन इंटरफ़ेस"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "टर्मिनल से सीधे दस्तावेज़ों को groupdocs-conversion कमांड‑लाइन टूल के साथ परिवर्तित करें — कोई Python स्क्रिप्ट आवश्यक नहीं। दस्तावेज़ों का निरीक्षण करें, समर्थित फ़ॉर्मेट सूचीबद्ध करें, और लाइसेंस लागू करें, सभी शेल से।"
type: docs
url: /hi/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


`groupdocs-conversion-net` पैकेज स्थापित करने से आपके `PATH` में `groupdocs-conversion` कंसोल स्क्रिप्ट भी जोड़ दी जाती है। यह Python API के ऊपर एक हल्का रैपर है, जो उन मामलों के लिए बनाया गया है जहाँ Python स्क्रिप्ट चलाना अत्यधिक है — शेल पाइपलाइन, Make नियम, CI चरण, और एक‑बार के रूपांतरण।

## Prerequisites

CLI पैकेज के अंदर ही आता है, इसलिए अतिरिक्त इंस्टॉलेशन की आवश्यकता नहीं है। सुनिश्चित करें कि `groupdocs-conversion-net` स्थापित है (देखें [Quick Start Guide]()), फिर कंसोल स्क्रिप्ट उपलब्ध है या नहीं, इसकी पुष्टि करें:

```bash
groupdocs-conversion --version
```

आपको पैकेज संस्करण प्रिंट होते हुए दिखना चाहिए, उदाहरण के लिए `groupdocs-conversion 26.9.0`।

यदि `groupdocs-conversion` कमांड नहीं मिलता है, तो पैकेज की स्क्रिप्ट डायरेक्टरी आपके `PATH` में नहीं हो सकती। आप हमेशा CLI को Python मॉड्यूल रूप में चलाकर उपयोग कर सकते हैं: `python -m groupdocs.conversion`। दोनों समान हैं।

## Commands

CLI चार सबकमांड्स को उजागर करता है। पूर्ण फ़्लैग सूची के लिए `groupdocs-conversion --help` चलाएँ, या किसी विशिष्ट सबकमांड के लिए `groupdocs-conversion <command> --help` चलाएँ।

### convert

एक दस्तावेज़ को दूसरे फ़ॉर्मेट में परिवर्तित करें। लक्ष्य फ़ॉर्मेट आउटपुट फ़ाइल एक्सटेंशन से अनुमानित होता है; इसे ओवरराइड करने के लिए `--format` पास करें।

```bash
# एक्सटेंशन लक्ष्य फ़ॉर्मेट चुनता है
groupdocs-conversion convert business-plan.docx business-plan.pdf

# जब आउटपुट नाम में उपयोगी एक्सटेंशन नहीं होता है तो फ़ॉर्मेट को ओवरराइड करें
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# एकल पृष्ठ (1‑इंडेक्स्ड) परिवर्तित करें — रास्टर लक्ष्यों के लिए उपयोगी
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# पासवर्ड‑सुरक्षित स्रोत खोलें
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| विकल्प | विवरण |
| :- | :- |
| `--format` | लक्ष्य फ़ॉर्मेट टोकन (आउटपुट एक्सटेंशन को ओवरराइड करता है)। |
| `--password` | संरक्षित स्रोत दस्तावेज़ के लिए पासवर्ड। |
| `--page` | परिवर्तित करने के लिए पहला पृष्ठ, 1-इंडेक्स्ड। |
| `--count` | परिवर्तित करने के लिए पृष्ठों की संख्या। |

सफलता पर कमांड आउटपुट पथ को प्रिंट करता है और कोड `0` के साथ बाहर निकलता है।

### info

दस्तावेज़ के बारे में मूलभूत जानकारी प्रिंट करें — फ़ॉर्मेट, आकार, पृष्ठ गिनती, और उपलब्ध होने पर निर्माण तिथि।

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

संरक्षित स्रोतों के लिए `--password` का उपयोग करें।

### list-formats

दिए गए इनपुट दस्तावेज़ के लिए इंजन द्वारा उत्पन्न किए जा सकने वाले प्रत्येक लक्ष्य फ़ॉर्मेट की सूची दें, जिसे प्राथमिक और द्वितीयक लक्ष्यों में विभाजित किया गया है।

```bash
groupdocs-conversion list-formats business-plan.docx
```

संरक्षित स्रोतों के लिए `--password` का उपयोग करें।

### list-all-formats

इंजन द्वारा ज्ञात पूर्ण स्रोत-से-लक्ष्य रूपांतरण मैट्रिक्स प्रिंट करें — प्रत्येक इनपुट फ़ॉर्मेट और उन लक्ष्यों को जिनमें इसे बदला जा सकता है।

```bash
groupdocs-conversion list-all-formats
```

यह कमांड कोई इनपुट फ़ाइल नहीं लेता है।

## Global options

ये विकल्प प्रत्येक कमांड पर लागू होते हैं:

| विकल्प | विवरण |
| :- | :- |
| `--license PATH` | कमांड चलाने से पहले एक लाइसेंस फ़ाइल लागू करें। |
| `--version` | CLI संस्करण प्रिंट करें और बाहर निकलें। |
| `--help` | उपयोग सहायता दिखाएँ और बाहर निकलें। |

सबकमांड से पहले `--license` रखकर अग्रिम में एक लाइसेंस लागू करें:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI `GROUPDOCS_LIC_PATH` पर्यावरण चर को भी मानता है — यदि यह सेट है, तो लाइसेंस स्वचालित रूप से लागू हो जाता है और आप `--license` को छोड़ सकते हैं। विवरण के लिए [Licensing]() विषय देखें।

## Format tokens

`convert` आउटपुट एक्सटेंशन — या `--format` मान, लोअरकेस — को मिलते-जुलते रूपांतरण विकल्पों और फ़ाइल प्रकार से मैप करता है। समर्थित टोकन हैं:

| श्रेणी | टोकन |
| :- | :- |
| PDF | `pdf` |
| वर्ड प्रोसेसिंग | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| स्प्रेडशीट | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| प्रेज़ेंटेशन | `ppt`, `pptx`, `pptm`, `odp` |
| वेब | `html`, `htm`, `mhtml` |
| छवि | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| ईबुक | `epub`, `mobi`, `azw3` |

एक अज्ञात टोकन कमांड को कोड `2` के साथ बाहर निकलने और स्वीकृत टोकनों की सूची प्रिंट करने का कारण बनता है।

## Exit codes

| कोड | अर्थ |
| :- | :- |
| `0` | सफलता। |
| `2` | उपयोगकर्ता त्रुटि — अज्ञात फ़ॉर्मेट टोकन या इनपुट फ़ाइल गायब है। |
| `1` | रनटाइम त्रुटि — अंतर्निहित .NET अपवाद संदेश मानक त्रुटि पर प्रिंट किया जाता है। |

इन कोडों के कारण शेल स्क्रिप्ट्स और CI पाइपलाइन में CLI को ब्रांच करना आसान हो जाता है।

## When to use the Python API instead

CLI सामान्य एकल-डॉक्यूमेंट रूपांतरण मामलों को कवर करता है। इसके अलावा — प्रति-पृष्ठ कॉलबैक, इन‑मेमोरी स्ट्रीम, वॉटरमार्क, फ़ॉन्ट, या सेल‑रेंज विकल्प, और बहु‑डॉक्यूमेंट कंटेनर पदानुक्रम — सीधे Python API का उपयोग करें। यह CLI फ़्लैग्स की तुलना में अधिक समृद्ध इंटरफ़ेस प्रदान करता है। पूर्ण फीचर सेट के लिए [Developer Guide]() देखें।

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
