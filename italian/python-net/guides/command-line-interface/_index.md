---
title: "Interfaccia a riga di comando"
linkTitle: "Command Line Interface"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Converti i documenti direttamente dal terminale con lo strumento da riga di comando groupdocs-conversion — non è necessario alcuno script Python. Ispeziona i documenti, elenca i formati supportati e applica una licenza, tutto dalla shell."
type: docs
url: /it/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


L'installazione del pacchetto `groupdocs-conversion-net` aggiunge anche uno script console `groupdocs-conversion` al tuo `PATH`. È un leggero wrapper sull'API Python, creato per i casi in cui avviare uno script Python è eccessivo — pipeline di shell, regole Make, passaggi CI e conversioni occasionali.

## Prerequisites

La CLI è inclusa nel pacchetto, quindi non è necessaria alcuna installazione aggiuntiva. Assicurati che `groupdocs-conversion-net` sia installato (vedi la [Guida rapida]()), quindi verifica che lo script console sia disponibile:

```bash
groupdocs-conversion --version
```

Dovresti vedere stampata la versione del pacchetto, ad esempio `groupdocs-conversion 26.9.0`.

Se il comando `groupdocs-conversion` non viene trovato, la directory degli script del pacchetto potrebbe non essere nel tuo `PATH`. Puoi sempre invocare la CLI tramite il modulo Python invece: `python -m groupdocs.conversion`. I due sono equivalenti.

## Commands

La CLI espone quattro sotto‑comandi. Esegui `groupdocs-conversion --help` per l'elenco completo delle opzioni, o `groupdocs-conversion <command> --help` per un sotto‑comando specifico.

### convert

Converti un documento in un altro formato. Il formato di destinazione è dedotto dall'estensione del file di output; passa `--format` per sovrascriverlo.

```bash
# L'estensione determina il formato di destinazione
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Sovrascrivi il formato quando il nome di output non contiene un'estensione utilizzabile
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Converti una singola pagina (indice a partire da 1) — utile per destinazioni raster
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Apri una sorgente protetta da password
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Opzione | Descrizione |
| :- | :- |
| `--format` | Token del formato di destinazione (sovrascrive l'estensione di output). |
| `--password` | Password per un documento sorgente protetto. |
| `--page` | Prima pagina da convertire, indicizzata a partire da 1. |
| `--count` | Numero di pagine da convertire. |

In caso di successo il comando stampa il percorso di output ed esce con il codice `0`.

### info

Stampa informazioni di base su un documento — formato, dimensione, numero di pagine e data di creazione quando disponibili.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Usa `--password` per sorgenti protette.

### list-formats

Elenca tutti i formati di destinazione che il motore può produrre per un dato documento di input, suddivisi in destinazioni primarie e secondarie.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Usa `--password` per sorgenti protette.

### list-all-formats

Stampa la matrice completa di conversione da sorgente a destinazione conosciuta dal motore — ogni formato di input e le destinazioni in cui può essere convertito.

```bash
groupdocs-conversion list-all-formats
```

Questo comando non richiede alcun file di input.

## Global options

Queste opzioni si applicano a tutti i comandi:

| Opzione | Descrizione |
| :- | :- |
| `--license PATH` | Applica un file di licenza prima di eseguire il comando. |
| `--version` | Stampa la versione della CLI ed esci. |
| `--help` | Mostra la guida all'uso ed esci. |

Applica una licenza in anticipo posizionando `--license` prima del sottocomando:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

La CLI rispetta anche la variabile d'ambiente `GROUPDOCS_LIC_PATH` — se è impostata, la licenza viene applicata automaticamente e puoi omettere `--license`. Vedi l'argomento [Licensing]() per i dettagli.

## Format tokens

`convert` associa l'estensione di output — o il valore `--format`, in minuscolo — alle opzioni di conversione corrispondenti e al tipo di file. I token supportati sono:

| Categoria | Token |
| :- | :- |
| PDF | `pdf` |
| Elaborazione testi | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Foglio di calcolo | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Presentazione | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Immagine | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eBook | `epub`, `mobi`, `azw3` |

Un token sconosciuto fa sì che il comando termini con il codice `2` e stampi l'elenco dei token accettati.

## Exit codes

| Codice | Significato |
| :- | :- |
| `0` | Successo. |
| `2` | Errore dell'utente — token di formato sconosciuto o file di input mancante. |
| `1` | Errore di runtime — il messaggio dell'eccezione .NET sottostante viene stampato su standard error. |

Questi codici rendono la CLI facile da gestire negli script shell e nelle pipeline CI.

## When to use the Python API instead

La CLI copre i casi comuni di conversione di un singolo documento. Per tutto ciò che va oltre — callback per pagina, stream in memoria, filigrana, carattere o opzioni di intervallo di celle, e gerarchie di contenitori multi-documento — utilizza direttamente l'API Python. Offre un'interfaccia più ricca rispetto alle opzioni della CLI. Consulta la [Guida per sviluppatori]() per l'insieme completo di funzionalità.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
