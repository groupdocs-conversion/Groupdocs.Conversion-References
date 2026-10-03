---
title: "EmailFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert E-Mail-Dateiformate, die von E-Mail-Anwendungen verwendet werden, um deren verschiedene Daten einschließlich E-Mail-Nachrichten, Anhänge, Ordner, Adressbücher usw. zu speichern."
type: docs
weight: 15
url: /de/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Definiert E‑Mail-Dateiformate, die von E‑Mail‑Anwendungen verwendet werden, um verschiedene Daten wie E‑Mail‑Nachrichten, Anhänge, Ordner, Adressbücher usw. zu speichern.
Enthält die folgenden Dateitypen:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Erfahren Sie mehr über E-Mail-Formate [hier](../https://wiki.fileformat.com/email).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Msg](#Msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E-Mail-Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern. |
|
|  | [Eml](#Eml) | Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. |
|
|  | [Emlx](#Emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zur Speicherung von Kontaktinformationen. |
|
|  | [Mbox](#Mbox) | MBox-Dateiformat ist ein generischer Begriff, der einen Container für eine Sammlung von elektronischen Mailnachrichten bezeichnet. |
|
|  | [Pst](#Pst) | Dateien mit der .PST-Erweiterung stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die eine Vielzahl von Benutzerinformationen speichern. |
|
|  | [Ost](#Ost) | OST- oder Offline Storage Files repräsentieren die Postfachdaten des Benutzers im Offline-Modus auf dem lokalen Rechner nach der Registrierung beim Exchange Server mit Microsoft Outlook. |
|
|  | [Olm](#Olm) | Eine Datei mit der .olm-Erweiterung ist eine Microsoft Outlook-Datei für das Mac-Betriebssystem. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Serialisierungskonstruktor


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E-Mail-Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Fast alle E-Mail-Clients unterstützen dieses Dateiformat, da es dem RFC-822 Internet Message Format Standard entspricht.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple Mail-Anwendung verwendet das EMLX-Dateiformat zum Exportieren von E-Mails.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zur Speicherung von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen beliebten Informationsaustausch-Anwendungen verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox-Dateiformat ist ein generischer Begriff, der einen Container für eine Sammlung von elektronischen Mailnachrichten bezeichnet. Die Nachrichten werden zusammen mit ihren Anhängen im Container gespeichert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


Dateien mit der .PST-Erweiterung stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die eine Vielzahl von Benutzerinformationen speichern. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST‑ oder Offline‑Speicherdateien stellen die Postfachdaten des Benutzers im Offline‑Modus auf dem lokalen Rechner dar, wenn er sich mit dem Exchange‑Server über Microsoft Outlook registriert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


Eine Datei mit der Erweiterung .olm ist eine Microsoft Outlook‑Datei für das Mac‑Betriebssystem. Eine OLM‑Datei speichert E‑Mail‑Nachrichten, Journale, Kalenderdaten und andere Arten von Anwendungsdaten. Diese ähneln den PST‑Dateien, die von Outlook unter Windows verwendet werden. Allerdings können OLM‑Dateien, die von Outlook für Mac erstellt wurden, nicht in Outlook für Windows geöffnet werden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Standard‑Konvertierungsoptionen für den Dateityp vorbereitet


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
