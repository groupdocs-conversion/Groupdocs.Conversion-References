---
title: "安装"
linkTitle: "Installation"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在 Windows、Linux 或 macOS 上通过 .NET 为 Python 安装 GroupDocs.Conversion——可从 PyPI 或预先下载的 wheel 安装，支持 Intel 和 Apple Silicon 构建。"
type: docs
url: /zh/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion for Python via .NET 以预构建的 wheel 形式分发在 [PyPI](https://pypi.org/project/groupdocs-conversion-net/)。PyPI 索引为每个受支持的平台提供单独的 wheel，`pip` 会自动选择正确的版本。

安装前，请确认您的环境符合 [System Requirements]() 章节中列出的受支持平台和 Python 版本。

## Install Package from PyPI

打开终端并运行适用于您平台的安装命令：

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

运行命令后，您应该会看到类似以下的输出：

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

wheel 文件名将包含与您的操作系统匹配的平台后缀——例如在 Ubuntu/Debian 上为 `manylinux1_x86_64`，在 Apple Silicon 上为 `macosx_11_0_arm64`，或在 64 位 Windows 上为 `win_amd64`。

## Add the Package to `requirements.txt`

为确保可复现的环境，请在 `requirements.txt` 中固定包的版本：

```txt
groupdocs-conversion-net==26.9.0
```

然后一次性安装所有依赖：

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

如果您的构建环境无法访问 PyPI，请从 [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/) 下载相应的 wheel 并在本地安装。每个发行版都会发布以下 wheel：

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

将下载的 wheel 放入项目文件夹，然后安装它：

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

预期输出：

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
