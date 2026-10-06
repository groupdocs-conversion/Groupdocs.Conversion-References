---
title: "Установка"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Установите GroupDocs.Conversion для Python через .NET на Windows, Linux или macOS — из PyPI или из предварительно загруженного wheel, включая сборки для Intel и Apple Silicon."
type: docs
url: /ru/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion для Python через .NET распространяется как предварительно собранный wheel на [PyPI](https://pypi.org/project/groupdocs-conversion-net/). Индекс PyPI содержит отдельный wheel для каждой поддерживаемой платформы, и `pip` автоматически выбирает нужный.

Перед установкой убедитесь, что ваша среда соответствует поддерживаемым платформам и версиям Python, перечисленным в теме [Системные требования]().

## Install Package from PyPI

Откройте терминал и выполните команду установки для вашей платформы:

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

После выполнения команды вы должны увидеть вывод, похожий на:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Имя файла wheel будет включать суффикс платформы, соответствующий вашей операционной системе — например `manylinux1_x86_64` на Ubuntu/Debian, `macosx_11_0_arm64` на Apple Silicon или `win_amd64` на 64‑разрядном Windows.

## Add the Package to `requirements.txt`

Для воспроизводимых сред зафиксируйте версию пакета в вашем `requirements.txt`:

```txt
groupdocs-conversion-net==26.9.0
```

Затем установите все зависимости одним шагом:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Если ваша среда сборки не может достичь PyPI, загрузите соответствующий wheel с [веб‑сайт GroupDocs Releases](https://releases.groupdocs.com/conversion/python-net/) и установите его локально. Для каждого выпуска публикуются следующие wheel‑файлы:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Поместите загруженный wheel в папку проекта, затем установите его:

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

Ожидаемый вывод:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
