---
title: CompressionFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i formati di compressione. Include i seguenti tipi di file Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Ulteriori informazioni sui formati di compressioneQuihttps//docs.fileformat.com/compression/ .
type: docs
weight: 870
url: /it/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definisce i formati di compressione. Include i seguenti tipi di file: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Ulteriori informazioni sui formati di compressione[Qui](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Costruttore di serializzazione |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia di file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina se due istanze di oggetto sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funge da funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione di stringa |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 sono file compressi generati utilizzando il metodo di compressione open source BZIP2, principalmente su sistemi UNIX o Linux. Viene utilizzato per la compressione di un singolo file e non è pensato per l'archiviazione di più file. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Un file con estensione .cab appartiene a un file CAB di Windows che appartiene alla categoria dei file di sistema. È un file che viene salvato nel formato di file di archivio nelle versioni di Microsoft Windows che supportano algoritmi di dati compressi, come LZX, Quantum e ZIP. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio è un'utilità di archiviazione di file generale e il relativo formato di file associato. È installato principalmente su sistemi operativi per computer simili a Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Un file GZ è un archivio compresso creato utilizzando l'algoritmo di compressione standard gzip (GNU zip). Può contenere più file compressi, directory e stub di file. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Un file Gzip è un archivio compresso creato utilizzando l'algoritmo di compressione standard gzip (GNU zip). Può contenere più file compressi, directory e stub di file. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Un file con estensione .lz è un file di archivio compresso creato con Lzip, uno strumento da riga di comando gratuito per la compressione. Supporta la concatenazione per comprimere i file di supporto. I file LZ hanno il tipo di supporto application/lzip e supportano rapporti di compressione più elevati rispetto a BZ2. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Un file con estensione .lzma è un file di archivio compresso creato utilizzando il metodo di compressione LZMA (Lempel-Ziv-Markov chain Algorithm). Questi si trovano/utilizzano principalmente sul sistema operativo Unix e sono simili ad altri algoritmi di compressione come ZIP per ridurre al minimo le dimensioni del file. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | I file con estensione .rar sono file di archivio creati per memorizzare informazioni in formato compresso o normale. RAR, che sta per Roshal ARchive file format. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z è un formato di archiviazione per la compressione di file e cartelle con un elevato rapporto di compressione. Si basa su un'architettura Open Source che consente di utilizzare qualsiasi algoritmo di compressione e crittografia. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | I file con estensione .tar sono archivi creati con utility basate su Unix per la raccolta di uno o più file. Più file vengono archiviati in un formato non compresso con il supporto dell'aggiunta di file e cartelle all'archivio. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ è un formato di file compresso che utilizza l'algoritmo di compressione LZMA2. È stato progettato per sostituire i popolari formati gzip e bzip2 e offre una serie di vantaggi rispetto a questi standard precedenti. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Il file AZ è una categoria di file appartenenti ai file di dati compressi UNIX. I file Unix compressi sono il tipo di estensione più popolare e ampiamente utilizzato del file Z. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Un file con estensione .zip è un archivio che può contenere uno o più file o directory. L'archivio può avere la compressione applicata ai file inclusi per ridurre le dimensioni del file ZIP. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/compression/zip/) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
