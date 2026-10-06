---
title: "Kurulum"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "GroupDocs.Conversion for Python via .NET'i Windows, Linux veya macOS üzerinde — PyPI'dan ya da önceden indirilmiş bir tekerlekte, Intel ve Apple Silicon derlemeleri dahil, kurun."
type: docs
url: /tr/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion for Python via .NET, [PyPI](https://pypi.org/project/groupdocs-conversion-net/) üzerinde önceden derlenmiş bir tekerlek olarak dağıtılır. PyPI indeksi, desteklenen her platform için ayrı bir tekerlek barındırır ve `pip` otomatik olarak doğru olanı seçer.

Kurulumdan önce, ortamınızın [System Requirements]() konusundaki desteklenen platformlar ve Python sürümleriyle eşleştiğini doğrulayın.

## Install Package from PyPI

Bir terminal açın ve platformunuz için kurulum komutunu çalıştırın:

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

Komutu çalıştırdıktan sonra aşağıdaki gibi bir çıktı görmelisiniz:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Tekerlek dosya adı, işletim sisteminizle eşleşen bir platform soneki içerecektir — örneğin Ubuntu/Debian'da `manylinux1_x86_64`, Apple Silicon'da `macosx_11_0_arm64` veya 64-bit Windows'ta `win_amd64`.

## Add the Package to `requirements.txt`

Tekrarlanabilir ortamlar için, paket sürümünü `requirements.txt` dosyanıza sabitleyin:

```txt
groupdocs-conversion-net==26.9.0
```

Ardından tüm bağımlılıkları tek adımda kurun:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Derleme ortamınız PyPI'ye erişemiyorsa, uygun tekerleği [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) adresinden indirin ve yerel olarak kurun. Her sürüm için aşağıdaki tekerlekler yayınlanmıştır:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

İndirilen tekerleği proje klasörünüze koyun, ardından kurun:

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

Beklenen çıktı:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
