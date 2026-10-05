---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Installieren Sie GroupDocs.Conversion für Python über .NET unter Windows, Linux oder macOS — von PyPI oder von einem vorab heruntergeladenen Wheel, einschließlich Intel‑ und Apple‑Silicon‑Builds."
type: docs
url: /de/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion für Python über .NET wird als vorgefertigtes Wheel auf [PyPI](https://pypi.org/project/groupdocs-conversion-net/) bereitgestellt. Der PyPI‑Index beherbergt ein separates Wheel für jede unterstützte Plattform, und `pip` wählt das richtige automatisch aus.

Stellen Sie vor der Installation sicher, dass Ihre Umgebung den in dem Thema [System Requirements]() aufgeführten unterstützten Plattformen und Python‑Versionen entspricht.

## Install Package from PyPI

Öffnen Sie ein Terminal und führen Sie den Installationsbefehl für Ihre Plattform aus:

{{< tabs "install-pypi">}}
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

Nachdem Sie den Befehl ausgeführt haben, sollten Sie eine Ausgabe ähnlich der folgenden sehen:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Der Wheel-Dateiname enthält ein Plattform‑Suffix, das Ihrem Betriebssystem entspricht — zum Beispiel `manylinux1_x86_64` unter Ubuntu/Debian, `macosx_11_0_arm64` auf Apple Silicon oder `win_amd64` unter 64‑Bit‑Windows.

## Add the Package to `requirements.txt`

Für reproduzierbare Umgebungen fixieren Sie die Paketversion in Ihrer `requirements.txt`:

```txt
groupdocs-conversion-net==26.9.0
```

Installieren Sie dann alle Abhängigkeiten in einem Schritt:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Falls Ihre Build‑Umgebung PyPI nicht erreichen kann, laden Sie das passende Wheel von der [GroupDocs Releases-Website](https://releases.groupdocs.com/conversion/python-net/) herunter und installieren Sie es lokal. Die folgenden Wheels werden für jede Version veröffentlicht:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Legen Sie das heruntergeladene Wheel in Ihren Projektordner und installieren Sie es anschließend:

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

Erwartete Ausgabe:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
