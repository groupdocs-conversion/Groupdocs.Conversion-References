---
title: "EmailFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar e‑postfilformat som används av e‑postprogram för att lagra deras olika data, inklusive e‑postmeddelanden, bilagor, mappar, adressböcker osv."
type: docs
weight: 15
url: /sv/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Definierar e-postfilformat som används av e-postprogram för att lagra deras olika data inklusive e-postmeddelanden, bilagor, mappar, adressböcker etc.
Inkluderar följande filtyper:
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
Läs mer om e‑postformat [här](../https://wiki.fileformat.com/email).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Msg](#Msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter. |
|
|  | [Eml](#Eml) | EML‑filformatet representerar e‑postmeddelanden som sparats med Outlook och andra relevanta program. |
|
|  | [Emlx](#Emlx) | EMLX‑filformatet är implementerat och utvecklat av Apple. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) eller vCard är ett digitalt filformat för lagring av kontaktinformation. |
|
|  | [Mbox](#Mbox) | MBox‑filformatet är en allmän term som representerar en behållare för en samling elektroniska e‑postmeddelanden. |
|
|  | [Pst](#Pst) | Filer med .PST‑ändelse representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar en mängd användarinformation. |
|
|  | [Ost](#Ost) | OST eller Offline Storage Files representerar användarens brevlådedata i offline‑läge på den lokala maskinen efter registrering mot Exchange Server med Microsoft Outlook. |
|
|  | [Olm](#Olm) | En fil med .olm‑ändelse är en Microsoft Outlook‑fil för Mac‑operativsystemet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Serialiseringskonstruktor


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML‑filformatet representerar e‑postmeddelanden som sparats med Outlook och andra relevanta program. Nästan alla e‑postklienter stöder detta filformat på grund av dess överensstämmelse med RFC‑822 Internet Message Format‑standarden.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


EMLX‑filformatet är implementerat och utvecklat av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑postmeddelanden.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) eller vCard är ett digitalt filformat för lagring av kontaktinformation. Formatet används i stor utsträckning för datautbyte mellan populära informationsutbytesprogram.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox-filformatet är en generell term som representerar en behållare för en samling av e‑postmeddelanden. Meddelandena lagras i behållaren tillsammans med deras bilagor.
Läs mer om detta filformat [här](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


Filer med .PST‑extension representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar olika typer av användarinformation. Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST‑ eller Offline Storage Files representerar användarens brevlådedata i offlineläge på den lokala maskinen efter registrering med Exchange Server via Microsoft Outlook. Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


En fil med .olm‑extension är en Microsoft Outlook‑fil för Mac‑operativsystemet. En OLM‑fil lagrar e‑postmeddelanden, journaler, kalenderdata och andra typer av programdata. Dessa liknar PST‑filer som används av Outlook på Windows‑operativsystemet. Dock kan\\u2019t OLM‑filer som skapats av Outlook för Mac öppnas i Outlook för Windows. Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
