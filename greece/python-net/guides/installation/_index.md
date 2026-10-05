---
title: "Εγκατάσταση"
linkTitle: "Installation"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εγκαταστήστε το GroupDocs.Conversion για Python μέσω .NET σε Windows, Linux ή macOS — από το PyPI ή από ένα προ-κατεβασμένο wheel, συμπεριλαμβανομένων των εκδόσεων για Intel και Apple Silicon."
type: docs
url: /el/python-net/guides/installation/
is_root: false
weight: 10
---


Το GroupDocs.Conversion για Python μέσω .NET διανέμεται ως προ-κατασκευασμένο wheel στο [PyPI](https://pypi.org/project/groupdocs-conversion-net/). Το ευρετήριο PyPI φιλοξενεί ένα ξεχωριστό wheel για κάθε υποστηριζόμενη πλατφόρμα, και το `pip` επιλέγει αυτόματα το σωστό.

Πριν την εγκατάσταση, βεβαιωθείτε ότι το περιβάλλον σας ταιριάζει με τις υποστηριζόμενες πλατφόρμες και εκδόσεις Python που αναφέρονται στο θέμα [Απαιτήσεις Συστήματος]().

## Install Package from PyPI

Ανοίξτε ένα τερματικό και εκτελέστε την εντολή εγκατάστασης για την πλατφόρμα σας:

{{< tabs \"install-pypi\">}}
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

Μετά την εκτέλεση της εντολής, θα πρέπει να δείτε έξοδο παρόμοια με:

```bash
Collecting groupdocs-conversion-net
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl.metadata (7.0 kB)
  Downloading groupdocs_conversion_net-26.9.0-py3-none-win_amd64.whl (199.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.5/199.5 MB 2.8 MB/s eta 0:00:00
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

Το όνομα του αρχείου wheel θα περιλαμβάνει ένα επίθημα πλατφόρμας που ταιριάζει με το λειτουργικό σας σύστημα — για παράδειγμα `manylinux1_x86_64` σε Ubuntu/Debian, `macosx_11_0_arm64` σε Apple Silicon ή `win_amd64` σε 64-bit Windows.

## Add the Package to `requirements.txt`

Για αναπαραγώγιμα περιβάλλοντα, καθορίστε την έκδοση του πακέτου στο `requirements.txt` σας:

```txt
groupdocs-conversion-net==26.9.0
```

Στη συνέχεια εγκαταστήστε όλες τις εξαρτήσεις σε ένα βήμα:

```bash
pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

Εάν το περιβάλλον κατασκευής σας δεν μπορεί να προσεγγίσει το PyPI, κατεβάστε το κατάλληλο wheel από τον ιστότοπο [Ιστότοπος Κυκλοφοριών GroupDocs](https://releases.groupdocs.com/conversion/python-net/) και εγκαταστήστε το τοπικά. Τα παρακάτω wheels δημοσιεύονται για κάθε έκδοση:

- **Windows 64-bit**: file name ends with `win_amd64.whl`
- **Linux x64 (glibc)**: file name ends with `manylinux1_x86_64.whl`
- **macOS Apple Silicon**: file name ends with `macosx_11_0_arm64.whl`
- **macOS Intel**: file name ends with `macosx_10_14_x86_64.whl`

Τοποθετήστε το κατεβασμένο wheel στον φάκελο του έργου σας, στη συνέχεια εγκαταστήστε το:

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

Αναμενόμενη έξοδος:

```bash
Processing groupdocs_conversion_net-26.9.0-py3-none-*.whl
Installing collected packages: groupdocs-conversion-net
Successfully installed groupdocs-conversion-net-26.9.0
```

## Next Steps

- Follow the [Quick Start Guide]() to run your first conversion.
- Clone the [examples repository](https://github.com/groupdocs-conversion/GroupDocs.Conversion-for-Python-via-.NET) and read [Running Examples]() to try every documented scenario locally.
- If you work with AI agents or LLMs, see [Agents and LLMs]() for MCP and `AGENTS.md` integration details.
