---
title: "स्थापना"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "Windows, Linux, या macOS पर .NET के माध्यम से Python के लिए GroupDocs.Conversion स्थापित करें — PyPI से या पूर्व‑डाउनलोडेड व्हील से, जिसमें Intel और Apple Silicon बिल्ड शामिल हैं।"
type: docs
url: /hi/python-net/guides/installation/
is_root: false
weight: 10
---


Python के लिए .NET के माध्यम से GroupDocs.Conversion को [PyPI](https://pypi.org/project/groupdocs-conversion-net/) पर एक प्री‑बिल्ट व्हील के रूप में वितरित किया जाता है। PyPI इंडेक्स प्रत्येक समर्थित प्लेटफ़ॉर्म के लिए एक अलग व्हील रखता है, और `pip` स्वचालित रूप से सही वाला चुन लेता है।

स्थापना से पहले, सुनिश्चित करें कि आपका पर्यावरण [System Requirements]() विषय में सूचीबद्ध समर्थित प्लेटफ़ॉर्म और Python संस्करणों से मेल खाता है।

## Install Package from PyPI

एक टर्मिनल खोलें और अपने प्लेटफ़ॉर्म के लिए इंस्टॉल कमांड चलाएँ:

{{< tabs \"install-pypi\">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

कमांड चलाने के बाद आपको इस प्रकार का आउटपुट दिखना चाहिए:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

व्हील फ़ाइल नाम में एक प्लेटफ़ॉर्म सफ़िक्स शामिल होगा जो आपके ऑपरेटिंग सिस्टम से मेल खाता है — उदाहरण के लिए Ubuntu/Debian पर `manylinux1_x86_64`, Apple Silicon पर `macosx_11_0_arm64`, या 64‑bit Windows पर `win_amd64`।

## Add the Package to `requirements.txt`

पुनरुत्पादनीय पर्यावरणों के लिए, अपने `requirements.txt` में पैकेज संस्करण को पिन करें:

```txt
groupdocs-conversion-net==26.9.0
```

फिर सभी निर्भरताओं को एक ही चरण में स्थापित करें:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

यदि आपका बिल्ड पर्यावरण PyPI तक नहीं पहुँच सकता, तो उपयुक्त व्हील को [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) से डाउनलोड करें और स्थानीय रूप से स्थापित करें। प्रत्येक रिलीज़ के लिए निम्नलिखित व्हील प्रकाशित किए गए हैं:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

डाउनलोड किया गया व्हील अपने प्रोजेक्ट फ़ोल्डर में रखें, फिर इसे स्थापित करें:

{{< tabs \"install-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-manylinux1_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-macosx_11_0_arm64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-macosx_10_14_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

अपेक्षित आउटपुट:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
