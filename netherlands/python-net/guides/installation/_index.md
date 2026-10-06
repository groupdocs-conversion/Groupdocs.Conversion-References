---
title: "Installatie"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Installeer GroupDocs.Conversion voor Python via .NET op Windows, Linux of macOS — vanaf PyPI of vanaf een vooraf gedownloade wheel, inclusief builds voor Intel en Apple Silicon."
type: docs
url: /nl/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion voor Python via .NET wordt gedistribueerd als een vooraf gebouwde wheel op [PyPI](https://pypi.org/project/groupdocs-conversion-net/). De PyPI‑index bevat een aparte wheel voor elk ondersteund platform, en `pip` kiest automatisch de juiste.

Controleer vóór het installeren of je omgeving overeenkomt met de ondersteunde platforms en Python‑versies die in het onderwerp [Systeemvereisten]() staan.

## Install Package from PyPI

Open een terminal en voer het installatie‑commando uit voor je platform:

{{< tabs \"install-pypi\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

Na het uitvoeren van het commando zou je output moeten zien die lijkt op:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

De bestandsnaam van de wheel bevat een platformsuffix die overeenkomt met je besturingssysteem — bijvoorbeeld `manylinux1_x86_64` op Ubuntu/Debian, `macosx_11_0_arm64` op Apple Silicon, of `win_amd64` op 64‑bit Windows.

## Add the Package to `requirements.txt`

Voor reproduceerbare omgevingen, zet de pakketversie vast in je `requirements.txt`:

```txt
groupdocs-conversion-net==26.9.0
```

Installeer vervolgens alle afhankelijkheden in één stap:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Als je build‑omgeving geen toegang heeft tot PyPI, download dan de juiste wheel van de [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) en installeer deze lokaal. De volgende wheels worden gepubliceerd voor elke release:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Plaats de gedownloade wheel in je projectmap en installeer deze vervolgens:

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

Verwachte output:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
