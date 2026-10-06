---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Installera GroupDocs.Conversion för Python via .NET på Windows, Linux eller macOS — från PyPI eller från ett förhandsnedladdat hjul, inklusive Intel‑ och Apple‑Silicon‑byggnader."
type: docs
url: /sv/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion för Python via .NET distribueras som ett förbyggt hjul på [PyPI](https://pypi.org/project/groupdocs-conversion-net/). PyPI‑indexet har ett separat hjul för varje stödd plattform, och `pip` väljer automatiskt rätt.

Innan du installerar, bekräfta att din miljö matchar de stödda plattformarna och Python‑versionerna som listas i ämnet [System Requirements]().

## Install Package from PyPI

Öppna en terminal och kör installationskommandot för din plattform:

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

Efter att ha kört kommandot bör du se en utdata liknande:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Hjulfilens namn kommer att innehålla ett platformsuffix som matchar ditt operativsystem — till exempel `manylinux1_x86_64` på Ubuntu/Debian, `macosx_11_0_arm64` på Apple Silicon, eller `win_amd64` på 64‑bit Windows.

## Add the Package to `requirements.txt`

För reproducerbara miljöer, lås paketversionen i din `requirements.txt`:

```txt
groupdocs-conversion-net==26.9.0
```

Installera sedan alla beroenden i ett steg:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Om din byggmiljö inte kan nå PyPI, ladda ner rätt hjul från [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) och installera det lokalt. Följande hjul publiceras för varje release:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Placera det nedladdade hjulet i din projektmapp och installera det:

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

Förväntad utdata:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
