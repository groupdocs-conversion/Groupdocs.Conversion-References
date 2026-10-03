---
title: "PossibleConversions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Rappresenta una mappatura delle coppie di conversione supportate per un formato di file sorgente specifico"
type: docs
weight: 13
url: /it/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Rappresenta una mappatura delle coppie di conversione supportate per un formato di file sorgente specifico

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Crea l'elenco di conversioni possibili per il formato file sorgente specificato |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [NULL](#NULL) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Opzioni di caricamento predefinite che possono essere usate per convertire dal tipo corrente |
|
|  | [getAll()](#getAll--) | Tutti i tipi di file di destinazione e il flag primario/secondario |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Restituisce la conversione di destinazione per il tipo di file di destinazione specificato |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Tipi di file di destinazione primari |
|
|  | [getSecondary()](#getSecondary--) | Tipi di file di destinazione secondari |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Aggiungi coppia di conversione |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Trova coppia di conversione nella lista corrente per il tipo di file di destinazione |
|
|  | [getSource()](#getSource--) | Formati di file sorgente |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Crea l'elenco di conversioni possibili per il formato file sorgente specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo di file sorgente |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite che possono essere usate per convertire dal tipo corrente


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Tutti i tipi di file di destinazione e il flag primario/secondario


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterabile di [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Restituisce la conversione di destinazione per il tipo di file di destinazione specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo di file di destinazione |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| estensione | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Tipi di file di destinazione primari


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - tipi di file di destinazione primari

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Tipi di file di destinazione secondari


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - tipi di file di destinazione secondari

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Aggiungi coppia di conversione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | coppia di conversione |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Trova coppia di conversione nella lista corrente per il tipo di file di destinazione


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | tipo di file di destinazione |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Formati di file sorgente


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

