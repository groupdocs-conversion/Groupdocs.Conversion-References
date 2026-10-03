---
title: "EBookFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti CAD (Computer Aided Design) che sono usati per formati di file grafici 3D e possono contenere progetti 2D o 3D."
type: docs
weight: 14
url: /it/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Definisce documenti CAD (Computer Aided Design) che sono utilizzati per formati di file grafici 3D e possono contenere progetti 2D o 3D.
Include i seguenti tipi:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Scopri di più sui formati CAD [qui](../https://wiki.fileformat.com/cad).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Epub](#Epub) | L'estensione EPUB è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. |
|
|  | [Mobi](#Mobi) | Il formato file MOBI è uno dei formati e-book più ampiamente utilizzati. |
|
|  | [Azw3](#Azw3) | AZW3, noto anche come Kindle Format 8 (KF8), è la versione modificata del formato di file digitale e-book AZW sviluppato per i dispositivi Amazon Kindle. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Costruttore di serializzazione


### Epub {#Epub}
```
public static final EBookFileType Epub
```


L'estensione EPUB è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è ormai così comune che è supportato da molti e-reader e applicazioni software. Scopri di più su questo formato [qui](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Il formato file MOBI è uno dei formati e-book più ampiamente utilizzati. Il formato è un miglioramento del vecchio formato OEB (Open Ebook Format) ed è stato usato come formato proprietario per Mobipocket Reader. Scopri di più su questo formato [qui](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, noto anche come Kindle Format 8 (KF8), è la versione modificata del formato di file digitale e-book AZW sviluppato per i dispositivi Amazon Kindle. Il formato è un miglioramento dei vecchi file AZW ed è utilizzato solo sui dispositivi Kindle Fire con compatibilità retroattiva per i formati di file precedenti, cioè MOBI e AZW. Scopri di più su questo formato [qui](../https://docs.fileformat.com/ebook/azw3/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opzioni di conversione predefinite preparate per il tipo di file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
