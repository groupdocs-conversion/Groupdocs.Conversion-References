---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Installez GroupDocs.Conversion pour Python via .NET sur Windows, Linux ou macOS — depuis PyPI ou depuis une roue pré‑téléchargée, incluant les versions Intel et Apple Silicon."
type: docs
url: /fr/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Conversion pour Python via .NET est distribué sous forme de roue pré‑construite sur [PyPI](https://pypi.org/project/groupdocs-conversion-net/). L’index PyPI héberge une roue distincte pour chaque plateforme prise en charge, et `pip` sélectionne automatiquement la bonne.

Avant l’installation, assurez‑vous que votre environnement correspond aux plateformes prises en charge et aux versions de Python répertoriées dans le sujet [System Requirements]().

## Install Package from PyPI

Ouvrez un terminal et exécutez la commande d’installation pour votre plateforme :

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

Après avoir exécuté la commande, vous devriez voir une sortie similaire à :

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Le nom du fichier de la roue contiendra un suffixe de plateforme correspondant à votre système d’exploitation — par exemple `manylinux1_x86_64` sur Ubuntu/Debian, `macosx_11_0_arm64` sur Apple Silicon, ou `win_amd64` sur Windows 64 bits.

## Add the Package to `requirements.txt`

Pour des environnements reproductibles, fixez la version du paquet dans votre `requirements.txt` :

```txt
groupdocs-conversion-net==26.9.0
```

Installez ensuite toutes les dépendances en une seule étape :

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Si votre environnement de construction ne peut pas accéder à PyPI, téléchargez la roue appropriée depuis le [site des releases GroupDocs](https://releases.groupdocs.com/conversion/python-net/) et installez‑la localement. Les roues suivantes sont publiées pour chaque version :

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Placez la roue téléchargée dans le dossier de votre projet, puis installez‑la :

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

Sortie attendue :

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
