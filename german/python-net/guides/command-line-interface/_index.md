---
title: "Befehlszeilenschnittstelle"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Konvertieren Sie Dokumente direkt im Terminal mit dem groupdocs-conversion Befehlszeilentool — kein Python‑Skript erforderlich. Untersuchen Sie Dokumente, listen Sie unterstützte Formate auf und wenden Sie eine Lizenz an, alles aus der Shell."
type: docs
url: /de/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


Die Installation des `groupdocs-conversion-net`‑Pakets legt außerdem ein `groupdocs-conversion`‑Konsolenskript in Ihrem `PATH` ab. Es ist ein dünner Wrapper über die Python‑API, entwickelt für Fälle, in denen das Aufsetzen eines Python‑Skripts übertrieben ist — Shell‑Pipelines, Make‑Regeln, CI‑Schritte und einmalige Konvertierungen.

## Prerequisites

Die CLI wird mit dem Paket ausgeliefert, sodass keine zusätzliche Installation erforderlich ist. Stellen Sie sicher, dass `groupdocs-conversion-net` installiert ist (siehe den [Quick Start Guide]()), und prüfen Sie dann, ob das Konsolenskript verfügbar ist:

```bash
groupdocs-conversion --version
```

Sie sollten die Paketversion angezeigt bekommen, zum Beispiel `groupdocs-conversion 26.9.0`.

Falls der Befehl `groupdocs-conversion` nicht gefunden wird, befindet sich das Skriptverzeichnis des Pakets möglicherweise nicht in Ihrem `PATH`. Sie können die CLI stattdessen immer über die Python‑Modulform aufrufen: `python -m groupdocs.conversion`. Beide sind äquivalent.

## Commands

Die CLI stellt vier Unterbefehle bereit. Führen Sie `groupdocs-conversion --help` aus, um die vollständige Auflistung der Optionen zu erhalten, oder `groupdocs-conversion <command> --help` für einen bestimmten Unterbefehl.

### convert

Konvertieren Sie ein Dokument in ein anderes Format. Das Zielformat wird aus der Dateierweiterung der Ausgabedatei abgeleitet; übergeben Sie `--format`, um es zu überschreiben.

```bash
# Die Erweiterung wählt das Zielformat
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Überschreiben Sie das Format, wenn der Ausgabename keine brauchbare Erweiterung enthält
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Konvertieren Sie eine einzelne Seite (1‑basiert) — nützlich für Rasterziele
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Öffnen Sie eine passwortgeschützte Quelle
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Option | Beschreibung |
| :- | :- |
| `--format` | Zielformat-Token (überschreibt die Ausgabenerweiterung). |
| `--password` | Passwort für ein geschütztes Quelldokument. |
| `--page` | Erste Seite zum Konvertieren, 1‑basiert. |
| `--count` | Anzahl der zu konvertierenden Seiten. |

Bei Erfolg gibt der Befehl den Ausgabepfad aus und beendet sich mit dem Code `0`.

### info

Gibt grundlegende Informationen über ein Dokument aus — Format, Größe, Seitenzahl und Erstellungsdatum, falls verfügbar.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Verwende `--password` für geschützte Quellen.

### list-formats

Liste jedes Zielformat auf, das die Engine für ein gegebenes Eingabedokument erzeugen kann, aufgeteilt in primäre und sekundäre Ziele.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Verwende `--password` für geschützte Quellen.

### list-all-formats

Gibt die vollständige Quell‑zu‑Ziel-Konvertierungsmatrix aus, die der Engine bekannt ist — jedes Eingabeformat und die Ziele, in die es konvertiert werden kann.

```bash
groupdocs-conversion list-all-formats
```

Dieser Befehl benötigt keine Eingabedatei.

## Global options

Diese Optionen gelten für jeden Befehl:

| Option | Beschreibung |
| :- | :- |
| `--license PATH` | Wende eine Lizenzdatei an, bevor der Befehl ausgeführt wird. |
| `--version` | Gibt die CLI-Version aus und beendet das Programm. |
| `--help` | Zeige die Hilfe zur Benutzung und beende das Programm. |

Wende eine Lizenz im Voraus an, indem du `--license` vor dem Unterbefehl platzierst:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

Die CLI berücksichtigt außerdem die Umgebungsvariable `GROUPDOCS_LIC_PATH` — ist sie gesetzt, wird die Lizenz automatisch angewendet und du kannst `--license` weglassen. Siehe das Thema [Licensing]() für Details.

## Format tokens

`convert` ordnet die Ausgabenerweiterung — oder den `--format`‑Wert, kleingeschrieben — den passenden Konvertierungsoptionen und dem Dateityp zu. Die unterstützten Tokens sind:

| Kategorie | Tokens |
| :- | :- |
| PDF | `pdf` |
| Textverarbeitung | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Tabellenkalkulation | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Präsentation | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Bild | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eBook | `epub`, `mobi`, `azw3` |

Ein unbekanntes Token verursacht, dass der Befehl mit dem Code `2` beendet wird und die Liste der akzeptierten Tokens ausgibt.

## Exit codes

| Code | Bedeutung |
| :- | :- |
| `0` | Erfolg. |
| `2` | Benutzerfehler — unbekanntes Format-Token oder fehlende Eingabedatei. |
| `1` | Laufzeitfehler — die zugrunde liegende .NET-Ausnahmemeldung wird an den Standardfehler ausgegeben. |

Diese Codes erleichtern das Verzweigen der CLI in Shell‑Skripten und CI‑Pipelines.

## When to use the Python API instead

Die CLI deckt die gängigen Einzeldokument‑Konvertierungsfälle ab. Für alles darüber hinaus — pro‑Seiten‑Callbacks, In‑Memory‑Streams, Wasserzeichen, Schriftart oder Zellbereichs‑Optionen sowie mehrdokumentige Container‑Hierarchien — verwenden Sie die Python‑API direkt. Sie bietet eine umfangreichere Oberfläche als die CLI‑Optionen. Siehe den [Developer Guide]() für das vollständige Funktionsset.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
