---
title: "التثبيت"
linkTitle: "Installation"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "قم بتثبيت GroupDocs.Conversion للبايثون عبر .NET على Windows أو Linux أو macOS — من PyPI أو من عجلة مُحمّلة مسبقًا، بما في ذلك إصدارات Intel و Apple Silicon."
type: docs
url: /ar/python-net/guides/installation/
is_root: false
weight: 10
---


يتم توزيع GroupDocs.Conversion للبايثون عبر .NET كعجلة مُعدة مسبقًا على [PyPI](https://pypi.org/project/groupdocs-conversion-net/). يُضيف فهرس PyPI عجلة منفصلة لكل منصة مدعومة، ويختار `pip` العجلة الصحيحة تلقائيًا.

قبل التثبيت، تأكد من أن بيئتك تتطابق مع المنصات المدعومة وإصدارات بايثون المذكورة في موضوع [System Requirements]().

## Install Package from PyPI

افتح طرفية (Terminal) وشغّل أمر التثبيت الخاص بمنصتك:

{{< tabs "install-pypi">}}
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

بعد تشغيل الأمر، يجب أن ترى مخرجات مشابهة لـ:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

سيتضمن اسم ملف العجلة لاحقة منصة تتطابق مع نظام التشغيل الخاص بك — على سبيل المثال `manylinux1_x86_64` على Ubuntu/Debian، `macosx_11_0_arm64` على Apple Silicon، أو `win_amd64` على Windows 64 بت.

## Add the Package to `requirements.txt`

لضمان بيئات قابلة لإعادة الإنتاج، ثبّت إصدار الحزمة في ملف `requirements.txt` الخاص بك:

```txt
groupdocs-conversion-net==26.9.0
```

ثم قم بتثبيت جميع التبعيات في خطوة واحدة:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

إذا لم يتمكن بيئة البناء الخاصة بك من الوصول إلى PyPI، قم بتنزيل العجلة المناسبة من [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) وقم بتثبيتها محليًا. العجلات التالية منشورة لكل إصدار:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

ضع العجلة التي تم تنزيلها في مجلد مشروعك، ثم قم بتثبيتها:

{{< tabs "install-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-manylinux1_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-macosx_11_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install groupdocs_conversion_net-26.9.0-py3-none-macosx_10_14_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

المخرجات المتوقعة:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
