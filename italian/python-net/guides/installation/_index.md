---
title: "Installazione"
linkTitle: "Installation"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Installa GroupDocs.Conversion per Python via .NET su Windows, Linux o macOS — da PyPI o da un wheel pre‑scaricato, includendo build per Intel e Apple Silicon."
type: docs
url: /it/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion per Python via .NET è distribuito come wheel pre‑costruito su [PyPI](https://pypi.org/project/groupdocs-conversion-net/). L'indice PyPI ospita un wheel separato per ogni piattaforma supportata, e `pip` seleziona automaticamente quello corretto.

Prima dell'installazione, verifica che il tuo ambiente corrisponda alle piattaforme supportate e alle versioni di Python elencate nella sezione [Requisiti di sistema]().

## Install Package from PyPI

Apri un terminale ed esegui il comando di installazione per la tua piattaforma:

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

Dopo aver eseguito il comando dovresti vedere un output simile a:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Il nome del file wheel includerà un suffisso di piattaforma che corrisponde al tuo sistema operativo — ad esempio `manylinux1_x86_64` su Ubuntu/Debian, `macosx_11_0_arm64` su Apple Silicon, o `win_amd64` su Windows a 64 bit.

## Add the Package to `requirements.txt`

Per ambienti riproducibili, fissa la versione del pacchetto nel tuo `requirements.txt`:

```txt
groupdocs-conversion-net==26.9.0
```

Quindi installa tutte le dipendenze in un unico passaggio:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Se il tuo ambiente di build non può raggiungere PyPI, scarica il wheel appropriato dal [sito di rilascio GroupDocs](https://releases.groupdocs.com/conversion/python-net/) e installalo localmente. I seguenti wheel sono pubblicati per ogni rilascio:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Posiziona il wheel scaricato nella cartella del tuo progetto, quindi installalo:

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

Output previsto:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
