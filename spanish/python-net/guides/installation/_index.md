---
title: "Instalación"
linkTitle: "Installation"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Instala GroupDocs.Conversion para Python a través de .NET en Windows, Linux o macOS — desde PyPI o desde un wheel predescargado, incluyendo versiones para Intel y Apple Silicon."
type: docs
url: /es/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion para Python a través de .NET se distribuye como un wheel preconstruido en [PyPI](https://pypi.org/project/groupdocs-conversion-net/). El índice de PyPI aloja un wheel separado para cada plataforma compatible, y `pip` selecciona el correcto automáticamente.

Antes de instalar, confirma que tu entorno coincide con las plataformas compatibles y versiones de Python enumeradas en el tema [Requisitos del sistema]().

## Install Package from PyPI

Abre una terminal y ejecuta el comando de instalación para tu plataforma:

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

Después de ejecutar el comando deberías ver una salida similar a:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

El nombre del archivo wheel incluirá un sufijo de plataforma que coincida con tu sistema operativo — por ejemplo `manylinux1_x86_64` en Ubuntu/Debian, `macosx_11_0_arm64` en Apple Silicon, o `win_amd64` en Windows de 64 bits.

## Add the Package to `requirements.txt`

Para entornos reproducibles, fija la versión del paquete en tu `requirements.txt`:

```txt
groupdocs-conversion-net==26.9.0
```

Luego instala todas las dependencias en un solo paso:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Si tu entorno de compilación no puede acceder a PyPI, descarga el wheel apropiado desde el [sitio de lanzamientos de GroupDocs](https://releases.groupdocs.com/conversion/python-net/) e instálalo localmente. Los siguientes wheels se publican para cada versión:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Coloca el wheel descargado en la carpeta de tu proyecto, luego instálalo:

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

Salida esperada:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
