---
title: "CompressionFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce i formati di compressione. Include i seguenti tipi di file Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Maggiori informazioni sui formati di compressione qui https//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /it/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Definisce i formati di compressione. Include i seguenti tipi di file: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Maggiori informazioni sui formati di compressione [qui](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia del file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Definisce se il formato supporta più file/cartelle in un unico archivio. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione stringa |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | Un file con estensione .aar è un Apple Archive, il contenitore che Apple fornisce con macOS per raggruppare file e cartelle. Ogni voce è compressa singolarmente, spesso con LZFSE. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | Un file con estensione .alz è un archivio ALZip, un formato di ESTsoft ampiamente utilizzato in Corea del Sud. Le voci possono essere crittografate individualmente con una password. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/compression/alz/). |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 sono file compressi generati utilizzando il metodo di compressione open source BZIP2, principalmente su sistemi UNIX o Linux. Viene utilizzato per la compressione di un singolo file e non è destinato all'archiviazione di più file. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | Un file con estensione .cab appartiene a un file cabinet di Windows che rientra nella categoria dei file di sistema. È un file salvato nel formato di archivio nelle versioni di Microsoft Windows che supportano algoritmi di compressione dei dati, come LZX, Quantum e ZIP. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/system/cab/). |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio è un'utilità di archiviazione di file generica e il relativo formato di file. È principalmente installato su sistemi operativi simili a Unix. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Un file GZ è un archivio compresso creato utilizzando l'algoritmo di compressione standard gzip (GNU zip). Può contenere più file compressi, directory e stub di file. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/compression/gz/). |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Un file Gzip è un archivio compresso creato utilizzando l'algoritmo di compressione standard gzip (GNU zip). Può contenere più file compressi, directory e stub di file. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/compression/gz/). |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | Un file con estensione .iso è un file immagine disco di archivio non compresso che rappresenta il contenuto di tutti i dati su un disco ottico come CD o DVD. Basato sullo standard ISO-9660, il formato file immagine ISO contiene i dati del disco insieme alle informazioni del file system memorizzate al suo interno. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | Un file con estensione .lzh e .lha di solito è relativo a un formato di compressione di archivio. Questo formato è lo stesso di altri formati di compressione come ZIP, RAR, ecc. Lo scopo principale di questi formati è ridurre le dimensioni per facilitarne l'invio e mantenerli insieme in forma compressa. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | Un file con estensione .lz è un archivio compresso creato con Lzip, uno strumento da riga di comando gratuito per la compressione. Supporta la concatenazione per comprimere file di supporto. I file LZ hanno tipo MIME application/lzip e offrono un rapporto di compressione più elevato rispetto a BZ2. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | Un file con estensione .lz4 è un archivio compresso creato con applicazioni/utilità che supportano la compressione LZ4. L'algoritmo LZ4 si concentra sul compromesso tra velocità e rapporto di compressione. Gli archivi LZ4 compressi possono essere creati usando l'utilità da riga di comando LZ4 e possono essere decompressi con la stessa. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | Un file con estensione .lzma è un archivio compresso creato utilizzando il metodo di compressione LZMA (Lempel-Ziv-Markov chain Algorithm). Questi sono principalmente presenti/utilizzati sui sistemi operativi Unix e sono simili ad altri algoritmi di compressione come ZIP per ridurre le dimensioni dei file. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | I file con estensione .rar sono file di archivio creati per memorizzare informazioni in forma compressa o normale. RAR, che sta per Roshal ARchive file format. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z è un formato di archiviazione per comprimere file e cartelle con un alto rapporto di compressione. È basato su un'architettura Open Source che consente di utilizzare qualsiasi algoritmo di compressione e crittografia. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | I file con estensione .tar sono archivi creati con un'utilità basata su Unix per raccogliere uno o più file. I file multipli sono memorizzati in un formato non compresso con il supporto per aggiungere file e cartelle all'archivio. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Un archivio uuencoded è un file o una raccolta di file che sono stati codificati usando lo schema di codifica Unix-to-Unix (uuencode). Questo metodo di codifica converte i dati binari in un formato di testo, facilitando l'invio dei file su canali che supportano solo testo, come la posta elettronica. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | Un file con estensione .wim è un archivio Windows Imaging Format, un'immagine disco basata su file che Microsoft utilizza per distribuire Windows. Un singolo archivio contiene una o più immagini e memorizza ogni file una sola volta, indipendentemente da quante immagini lo facciano riferimento. Scopri di più su questo formato file [qui](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | Un file con estensione .xar è un eXtensible ARchive, un formato costruito attorno a una tabella dei contenuti memorizzata come XML compresso. Viene utilizzato per distribuire i pacchetti di installazione macOS e mantiene ogni voce compressa singolarmente. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ è un formato di file compresso che utilizza l'algoritmo di compressione LZMA2. È stato progettato come sostituto dei popolari formati gzip e bzip2, e offre diversi vantaggi rispetto a questi standard più vecchi. Scopri di più su questo formato file [qui](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Un file Z è una categoria di file appartenenti ai file di dati compressi UNIX. I file Unix compressi sono il tipo di estensione più popolare e ampiamente usato del file Z. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | Un file con estensione .zip è un archivio che può contenere uno o più file o directory. All'archivio può essere applicata la compressione ai file inclusi per ridurre le dimensioni del file ZIP. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | Un file ZST è un file compresso generato con l'algoritmo di compressione Zstandard (zstd). È un file compresso creato con compressione senza perdita dall'algoritmo. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/compression/zst/). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
