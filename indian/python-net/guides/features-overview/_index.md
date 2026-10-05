---
title: "फ़ीचर अवलोकन"
linkTitle: "Features overview"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Conversion for Python via .NET की प्रमुख विशेषताएँ — 10,000+ फ़ॉर्मेट जोड़े, पृष्ठ चयन, लोड/कनवर्ट विकल्प, वॉटरमार्क, दस्तावेज़ निरीक्षण, और AI‑पाइपलाइन इंटीग्रेशन।"
type: docs
url: /hi/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Overview

GroupDocs.Conversion for Python via .NET दस्तावेज़ों को **10,000+ format pairs** के बीच परिवर्तित करता है — Microsoft Office, PDF, OpenDocument, images, CAD, email, archives, eBooks, HTML, TeX, और पेज‑डिस्क्रिप्शन भाषाएँ। यह पूरी तरह ऑन‑प्रेमिस चलता है, कोई Microsoft Office या Adobe Acrobat इंस्टॉलेशन आवश्यक नहीं है, और Windows, Linux, और macOS पर प्री‑बिल्ट व्हील के रूप में उपलब्ध है।

पूरी सूची देखें [supported formats]() या प्रत्येक API सतह के चलाने योग्य उदाहरणों के लिए [Developer Guide]() ब्राउज़ करें।

## File Conversion

मुख्य क्षमता किसी भी समर्थित स्रोत दस्तावेज़ को किसी भी समर्थित लक्ष्य फ़ॉर्मेट में परिवर्तित करना है। सभी रूपांतरण Microsoft Office, LibreOffice, या Adobe Acrobat स्थापित किए बिना संभव हैं। GroupDocs.Conversion पाइपलाइन को अनुकूलित करने के लिए विकल्पों का एक लचीला सेट प्रदान करता है।

### Convert specific document pages

पूरा दस्तावेज़, व्यक्तिगत पृष्ठ, या पृष्ठ रेंज को कनवर्ट करें। या तो स्पष्ट `pages` सूची का उपयोग करें या `page_number` + `pages_count` रेंज को [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) क्लास पर उपयोग करें। चलाने योग्य उदाहरणों के लिए देखें [Convert a Document to Another Format]().

### Per-page file output

प्रति पृष्ठ एक आउटपुट फ़ाइल उत्पन्न करें — प्रस्तुतियों, मल्टी‑पेज PDFs, और दस्तावेज़ों को छवियों में रेंडर करने के लिए उपयोगी। `pages_count = 1` रखते हुए `page_number` एट्रिब्यूट को लूप करें। देखें [Convert a Document to Multiple Page Files]().

### Auto-detect source document format

जब स्रोत फ़ाइल बाइट स्ट्रीम के रूप में आती है और उसका कोई फ़ाइल नाम नहीं होता, तो GroupDocs.Conversion स्ट्रीम हेडर की जाँच करके फ़ॉर्मेट को स्वचालित रूप से पहचान लेता है। देखें [Load File From Stream](#example-2-load-file-from-stream-and-detect-file-type-automatically).

### Load source document with extended options

प्रत्येक लोड विकल्प क्लास फ़ॉर्मेट‑विशिष्ट सेटिंग्स को उजागर करता है:

- **Passwords** — open [password-protected documents]() by setting `WordProcessingLoadOptions.password`, `PdfLoadOptions.password`, `SpreadsheetLoadOptions.password`, etc.
- **PDF load options** — hide annotations, flatten form fields, remove embedded files via [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/).
- **Spreadsheet load options** — pick specific sheet indexes, show grid lines, convert a cell range (`convert_range`), skip empty rows and columns via [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/).
- **Word Processing load options** — hide comments, hide tracked changes, substitute fonts via [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/).
- **Email load options** — alter header visibility, change field labels via [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/).
- **Text load options** — set encoding, control leading/trailing spaces via [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/) / [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/).

### Discover possible conversions

पाइपलाइन चलाने से पहले इंजन से समर्थित लक्ष्य फ़ॉर्मेट पूछें — पूरे लाइब्रेरी स्तर पर, एक्सटेंशन द्वारा, या किसी विशिष्ट लोडेड दस्तावेज़ के लिए। तीन ओवरलोड के लिए देखें [Get Possible Conversions]().

### Watermark the converted document

कनवर्ट करते समय टेक्स्ट वॉटरमार्क जोड़ें — रंग, आकार, घुमाव, पारदर्शिता, और पृष्ठभूमि/फ़ोरग्राउंड प्लेसमेंट को नियंत्रित करें। देखें [Add a Watermark to Converted Document]().

### Convert files inside a container

ZIP, RAR, 7Z, OST, या PST कंटेनर खोलें, सामग्री को कनवर्ट करें, और एक ही कॉल में एकीकृत आउटपुट दस्तावेज़ लिखें। देखें [Convert Files Within Document Containers]().

## Document Information Extraction

GroupDocs.Conversion स्रोत दस्तावेज़ से मेटाडाटा पढ़ सकता है बिना वास्तव में इसे कनवर्ट किए — फ़ॉर्मेट, पृष्ठ या स्लाइड गिनती, लेखक, निर्माण तिथि, आयाम, सामग्री तालिका, और फ़ॉर्मेट‑विशिष्ट विवरण। सभी नौ वैरिएंट्स के लिए देखें [Getting Document Information]().

- **PDF** — author, title, TOC, version, page dimensions, encryption flag.
- **Word Processing** — author, title, TOC, word count, line count.
- **Spreadsheet** — author, title, worksheet count.
- **Presentation** — author, title, slide count.
- **Image** — width, height, bits per pixel.
- **CAD** — layouts and layers list, drawing dimensions.
- **Project Management** — task count, start / end dates.
- **Email** — encryption flag, attachment list, HTML-body flag.

## Load Documents From Different Sources

Python [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) कंस्ट्रक्टर फ़ाइल पाथ और बाइनरी फ़ाइल‑जैसे ऑब्जेक्ट दोनों को स्वीकार करता है, इसलिए आप दस्तावेज़ लोड कर सकते हैं:

- Local disk — see [Load File From Local Disk]().
- Any stream — `open("file.docx", "rb")`, `io.BytesIO(data)`, or a file handle returned from `boto3`, `azure-storage-blob`, `requests`, etc. See [Load File From Stream]().

क्लाउड स्टोरेज (Amazon S3, Azure Blob Storage, Google Cloud Storage) बाइट्स को `BytesIO` बफ़र में लाकर और उसे [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) कंस्ट्रक्टर को पास करके काम करता है।

## Logging and Diagnostics

एक [`ConsoleLogger`](/conversion/python-net/groupdocs.conversion.logging/consolelogger/) को [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) के माध्यम से जोड़ें ताकि रूपांतरण पाइपलाइन — लोडर चयन, रूपांतरण शुरू और समाप्ति, तथा इंजन द्वारा उत्पन्न किसी भी चेतावनी — को ट्रेस किया जा सके। देखें [Logging and Diagnostics]().

## AI and LLM Integration

GroupDocs.Conversion को AI दस्तावेज़ पाइपलाइन के लिए प्रथम-श्रेणी का बिल्डिंग ब्लॉक बनने के लिए डिज़ाइन किया गया है। `groupdocs-conversion-net` pip पैकेज व्हील के अंदर एक `AGENTS.md` फ़ाइल शामिल करता है ताकि AI कोडिंग सहायक स्वचालित रूप से API सतह की खोज कर सकें, और GroupDocs ऑन-डिमांड दस्तावेज़ खोज के लिए एक सार्वजनिक [MCP server](https://docs.groupdocs.com/mcp) चलाता है। पूर्ण कहानी के लिए देखें [Agents and LLM Integration](), जिसमें यह बताया गया है कि GroupDocs.Conversion को GroupDocs.Markdown के साथ कैसे जोड़कर साफ़ RAG इनपुट प्राप्त किया जाए।

## On-Premise Deployment

कोई क्लाउड कॉल नहीं, कोई आउटबाउंड नेटवर्क ट्रैफ़िक नहीं, कोई थर्ड‑पार्टी सॉफ़्टवेयर निर्भरताएँ नहीं जो OS द्वारा पहले से प्रदान की गई चीज़ों से अधिक हों। व्हील Windows पर स्व-निहित है और Linux तथा macOS पर अपनी स्वयं की नेटिव रनटाइम लाइब्रेरीज़ के साथ आता है। वैकल्पिक नेटिव पैकेजों (ICU, fontconfig, Microsoft core fonts) की संक्षिप्त सूची के लिए देखें [System Requirements]().
