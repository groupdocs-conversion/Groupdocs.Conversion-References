---
title: "설치"
linkTitle: "Installation"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Windows, Linux 또는 macOS에서 .NET을 통해 Python용 GroupDocs.Conversion을 설치합니다 — PyPI에서 또는 미리 다운로드한 휠에서, Intel 및 Apple Silicon 빌드를 포함합니다."
type: docs
url: /ko/python-net/guides/installation/
is_root: false
weight: 10
---


Python용 GroupDocs.Conversion은 .NET을 통해 [PyPI](https://pypi.org/project/groupdocs-conversion-net/)에서 사전 구축된 휠로 배포됩니다. PyPI 인덱스는 지원되는 각 플랫폼마다 별도의 휠을 호스팅하며, `pip`가 자동으로 올바른 휠을 선택합니다.

설치하기 전에, 환경이 [System Requirements]() 항목에 나열된 지원 플랫폼 및 Python 버전과 일치하는지 확인하십시오.

## Install Package from PyPI

터미널을 열고 해당 플랫폼에 맞는 설치 명령을 실행하십시오:

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

명령을 실행한 후 다음과 유사한 출력이 표시됩니다:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

휠 파일 이름에는 운영 체제와 일치하는 플랫폼 접미사가 포함됩니다 — 예를 들어 Ubuntu/Debian에서는 `manylinux1_x86_64`, Apple Silicon에서는 `macosx_11_0_arm64`, 64비트 Windows에서는 `win_amd64`와 같습니다.

## Add the Package to `requirements.txt`

재현 가능한 환경을 위해, `requirements.txt`에 패키지 버전을 고정하십시오:

```txt
groupdocs-conversion-net==26.9.0
```

그런 다음 한 번에 모든 종속성을 설치하십시오:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

빌드 환경에서 PyPI에 접근할 수 없는 경우, [GroupDocs Releases website](https://releases.groupdocs.com/conversion/python-net/)에서 적절한 휠을 다운로드하여 로컬에 설치하십시오. 각 릴리스마다 다음 휠이 제공됩니다:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

다운로드한 휠을 프로젝트 폴더에 넣은 다음 설치하십시오:

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

예상 출력:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
