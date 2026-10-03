---
title: "PdfFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti PDF."
type: docs
weight: 21
url: /it/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Definisce i documenti Pdf. Include i seguenti tipi di file:
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Costruttore di serializzazione


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era introdurre uno standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/view/pdf).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
