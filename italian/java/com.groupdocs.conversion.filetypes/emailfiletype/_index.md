---
title: "EmailFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i formati di file Email utilizzati dalle applicazioni di posta elettronica per memorizzare i vari dati, inclusi messaggi email, allegati, cartelle, rubriche, ecc."
type: docs
weight: 15
url: /it/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Definisce formati di file Email che sono utilizzati dalle applicazioni di posta elettronica per memorizzare i vari dati, inclusi messaggi email, allegati, cartelle, rubriche, ecc.
Include i seguenti tipi di file:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Scopri di più sui formati Email [qui](../https://wiki.fileformat.com/email).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Msg](#Msg) | MSG è un formato di file utilizzato da Microsoft Outlook e Exchange per memorizzare messaggi email, contatti, appuntamenti o altre attività. |
|
|  | [Eml](#Eml) | Il formato di file EML rappresenta i messaggi email salvati con Outlook e altre applicazioni pertinenti. |
|
|  | [Emlx](#Emlx) | Il formato di file EMLX è implementato e sviluppato da Apple. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione delle informazioni di contatto. |
|
|  | [Mbox](#Mbox) | Il formato di file MBox è un termine generico che rappresenta un contenitore per una raccolta di messaggi di posta elettronica. |
|
|  | [Pst](#Pst) | I file con estensione .PST rappresentano Outlook Personal Storage Files (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. |
|
|  | [Ost](#Ost) | OST o Offline Storage Files rappresentano i dati della casella di posta dell'utente in modalità offline sulla macchina locale al momento della registrazione con Exchange Server usando Microsoft Outlook. |
|
|  | [Olm](#Olm) | Un file con estensione .olm è un file Microsoft Outlook per il sistema operativo Mac. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Costruttore di serializzazione


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG è un formato di file utilizzato da Microsoft Outlook e Exchange per memorizzare messaggi email, contatti, appuntamenti o altre attività.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Il formato di file EML rappresenta i messaggi di posta elettronica salvati usando Outlook e altre applicazioni pertinenti. Quasi tutti i client di posta supportano questo formato di file per la sua conformità allo Standard RFC-822 Internet Message Format.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Il formato di file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per l'esportazione delle email.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione delle informazioni di contatto. Il formato è ampiamente usato per lo scambio di dati tra le popolari applicazioni di scambio informazioni.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


Il formato di file MBox è un termine generico che rappresenta un contenitore per una raccolta di messaggi di posta elettronica. I messaggi sono memorizzati all'interno del contenitore insieme ai loro allegati.
Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


I file con estensione .PST rappresentano Outlook Personal Storage Files (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST o Offline Storage Files rappresentano i dati della casella di posta dell'utente in modalità offline sulla macchina locale al momento della registrazione con Exchange Server usando Microsoft Outlook. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


Un file con estensione .olm è un file Microsoft Outlook per il sistema operativo Mac. Un file OLM memorizza messaggi di posta elettronica, diari, dati del calendario e altri tipi di dati dell'applicazione. Questi sono simili ai file PST usati da Outlook su Windows Operating System. Tuttavia, i file OLM creati da Outlook per Mac non possono essere aperti in Outlook per Windows. Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/email/olm).


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
