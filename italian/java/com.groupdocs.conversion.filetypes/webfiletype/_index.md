---
title: "WebFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti Web."
type: docs
weight: 27
url: /it/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Definisce i documenti Web.
Include i seguenti tipi:
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
Scopri di più sui formati web [qui](../https://wiki.fileformat.com/web).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Xml](#Xml) | XML sta per Extensible Markup Language, un linguaggio simile a HTML ma diverso nell'uso dei tag per definire gli oggetti. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione dei dati che utilizza testo leggibile dall'uomo per memorizzare e trasmettere i dati. |
|
|  | [Html](#Html) | HTML (Hyper Text Markup Language) è l'estensione per le pagine web create per la visualizzazione nei browser. |
|
|  | [Htm](#Htm) | HTM (Hyper Text Markup Language) è l'estensione per le pagine web create per la visualizzazione nei browser. |
|
|  | [Mht](#Mht) | I file con estensione MHTML rappresentano un formato di archivio di pagine web che può essere creato da diverse applicazioni. |
|
|  | [Mhtml](#Mhtml) | I file con estensione MHTML rappresentano un formato di archivio di pagine web che può essere creato da diverse applicazioni. |
|
|  | [Chm](#Chm) | Il formato file CHM rappresenta un file di aiuto HTML di Microsoft che consiste in una raccolta di pagine HTML. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Costruttore di serializzazione


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML sta per Extensible Markup Language, un linguaggio simile a HTML ma diverso nell'uso dei tag per definire gli oggetti. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/web/xml).


### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione dei dati che utilizza testo leggibile dall'uomo per memorizzare e trasmettere i dati. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/web/json).


### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) è l'estensione per le pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/web/html).


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) è l'estensione per le pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/web/html).


### Mht {#Mht}
```
public static final WebFileType Mht
```


I file con estensione MHTML rappresentano un formato di archivio di pagine web che può essere creato da diverse applicazioni. Il formato è noto come archivio perché salva il codice HTML web e le risorse associate in un unico file. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/web/mhtml).


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


I file con estensione MHTML rappresentano un formato di archivio di pagine web che può essere creato da diverse applicazioni. Il formato è noto come archivio perché salva il codice HTML web e le risorse associate in un unico file. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/web/mhtml).


### Chm {#Chm}
```
public static final WebFileType Chm
```


Il formato file CHM rappresenta un file di aiuto HTML di Microsoft che consiste in una raccolta di pagine HTML. Fornisce un indice per accedere rapidamente agli argomenti e una navigazione verso le diverse parti del documento di aiuto. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/web/chm).


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
