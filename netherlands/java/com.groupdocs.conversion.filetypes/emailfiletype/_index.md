---
title: "EmailFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert e‑mailbestandsformaten die door e‑mailtoepassingen worden gebruikt om hun verschillende gegevens op te slaan, inclusief e‑mailberichten, bijlagen, mappen, adresboeken enz."
type: docs
weight: 15
url: /nl/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Definieert e-mailbestandsformaten die door e-mailtoepassingen worden gebruikt om hun verschillende gegevens op te slaan, inclusief e-mailberichten, bijlagen, mappen, adresboeken, enz.
Bevat de volgende bestandstypen:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Meer informatie over e‑mailformaten [hier](../https://wiki.fileformat.com/email).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Msg](#Msg) | MSG is een bestandsformaat dat wordt gebruikt door Microsoft Outlook en Exchange om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. |
|
|  | [Eml](#Eml) | EML‑bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. |
|
|  | [Emlx](#Emlx) | Het EMLX‑bestandsformaat is geïmplementeerd en ontwikkeld door Apple. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie. |
|
|  | [Mbox](#Mbox) | MBox‑bestandsformaat is een algemene term die een container voor een verzameling elektronische e‑mailberichten aanduidt. |
|
|  | [Pst](#Pst) | Bestanden met de .PST‑extensie vertegenwoordigen Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die een verscheidenheid aan gebruikersinformatie opslaan. |
|
|  | [Ost](#Ost) | OST of Offline Storage Files vertegenwoordigen de mailboxgegevens van de gebruiker in offline modus op de lokale machine bij registratie bij Exchange Server met Microsoft Outlook. |
|
|  | [Olm](#Olm) | Een bestand met de extensie .olm is een Microsoft Outlook‑bestand voor het Mac‑besturingssysteem. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Serialisatieconstructor


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG is een bestandsformaat dat wordt gebruikt door Microsoft Outlook en Exchange om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan.
Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Het EML‑bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. Bijna alle e‑mailclients ondersteunen dit bestandsformaat vanwege de naleving van de RFC‑822 Internet Message Format‑standaard.
Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Het EMLX‑bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail‑applicatie gebruikt het EMLX‑bestandsformaat voor het exporteren van de e‑mails.
Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie. Het formaat wordt veel gebruikt voor gegevensuitwisseling tussen populaire informatie‑uitwisselingsapplicaties.
Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox‑bestandsformaat is een algemene term die een container voor een verzameling elektronische e‑mailberichten vertegenwoordigt. De berichten worden opgeslagen in de container samen met hun bijlagen.
Leer meer over dit bestandsformaat [hier](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


Bestanden met de extensie .PST vertegenwoordigen Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die een verscheidenheid aan gebruikersinformatie opslaan. Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST of Offline Storage Files vertegenwoordigen de mailboxgegevens van de gebruiker in offline modus op de lokale machine bij registratie bij Exchange Server met Microsoft Outlook. Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


Een bestand met de extensie .olm is een Microsoft Outlook‑bestand voor het Mac‑besturingssysteem. Een OLM‑bestand slaat e‑mailberichten, journaals, agenda‑gegevens en andere soorten toepassingsgegevens op. Deze lijken op PST‑bestanden die door Outlook op Windows‑besturingssysteem worden gebruikt. Echter, OLM‑bestanden die door Outlook voor Mac zijn gemaakt, kunnen\\u2019t worden geopend in Outlook voor Windows. Leer meer over dit bestandsformaat [hier](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
