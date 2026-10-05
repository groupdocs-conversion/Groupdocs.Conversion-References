---
title: "Instalasi"
linkTitle: "Installation"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Instal GroupDocs.Conversion untuk Python via .NET di Windows, Linux, atau macOS — dari PyPI atau dari wheel yang sudah diunduh sebelumnya, termasuk build Intel dan Apple Silicon."
type: docs
url: /id/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion untuk Python via .NET didistribusikan sebagai wheel pra-bangun di [PyPI](https://pypi.org/project/groupdocs-conversion-net/). Indeks PyPI menyimpan wheel terpisah untuk setiap platform yang didukung, dan `pip` memilih yang tepat secara otomatis.

Sebelum menginstal, pastikan lingkungan Anda cocok dengan platform yang didukung dan versi Python yang tercantum dalam topik [System Requirements]().

## Install Package from PyPI

Buka terminal dan jalankan perintah instalasi untuk platform Anda:

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

Setelah menjalankan perintah, Anda akan melihat output serupa dengan:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Nama file wheel akan menyertakan akhiran platform yang sesuai dengan sistem operasi Anda — misalnya `manylinux1_x86_64` pada Ubuntu/Debian, `macosx_11_0_arm64` pada Apple Silicon, atau `win_amd64` pada Windows 64-bit.

## Add the Package to `requirements.txt`

Untuk lingkungan yang dapat direproduksi, tetapkan versi paket dalam `requirements.txt` Anda:

```txt
groupdocs-conversion-net==26.9.0
```

Kemudian instal semua dependensi dalam satu langkah:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Jika lingkungan build Anda tidak dapat mengakses PyPI, unduh wheel yang sesuai dari [situs GroupDocs Releases](https://releases.groupdocs.com/conversion/python-net/) dan instal secara lokal. Wheel berikut dipublikasikan untuk setiap rilis:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Letakkan wheel yang diunduh ke dalam folder proyek Anda, lalu instal:

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

Output yang diharapkan:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
