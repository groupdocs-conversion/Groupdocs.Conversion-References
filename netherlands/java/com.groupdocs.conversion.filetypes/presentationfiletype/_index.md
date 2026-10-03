---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Definieert presentatiebestandsformaten die een verzameling records opslaan om presentatiedata te bevatten, zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten."
type: docs
weight: 22
url: /nl/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Definieert presentatiedocumentformaten die een verzameling records opslaan om presentatiedata zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten te bevatten.
Bevat de volgende bestandstypen:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
Meer informatie over presentatieformaten [hier](../https://wiki.fileformat.com/presentation).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Serialisatieconstructor |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Ppt](#Ppt) | Een bestand met de extensie PPT vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. |
|
|  | [Pps](#Pps) | PPS, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. |
|
|  | [Pptx](#Pptx) | Bestanden met de extensie PPTX zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint‑applicatie. |
|
|  | [Ppsx](#Ppsx) | PPSX, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden. |
|
|  | [Odp](#Odp) | Bestanden met de extensie ODP vertegenwoordigen een presentatie‑bestandformaat dat wordt gebruikt door OpenOffice.org volgens de OASIS‑open standaard. |
|
|  | [Otp](#Otp) | Bestanden met de extensie .OTP vertegenwoordigen presentatiesjabloonbestanden die zijn gemaakt door applicaties volgens het OASIS OpenDocument‑formaat. |
|
|  | [Potx](#Potx) | Bestanden met de extensie .POTX vertegenwoordigen Microsoft PowerPoint‑sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. |
|
|  | [Pot](#Pot) | Bestanden met de extensie .POT vertegenwoordigen Microsoft PowerPoint‑sjabloonbestanden die zijn gemaakt met PowerPoint‑versies 97‑2003. |
|
|  | [Potm](#Potm) | Bestanden met de extensie POTM zijn Microsoft PowerPoint‑sjabloonbestanden met ondersteuning voor macro's. |
|
|  | [Pptm](#Pptm) | Bestanden met de extensie PPTM zijn macro‑ingeschakelde presentatiebestanden die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. |
|
|  | [Ppsm](#Ppsm) | Bestanden met de extensie PPSM vertegenwoordigen een macro‑ingeschakeld diavoorstellingsbestandformaat dat is gemaakt met Microsoft PowerPoint 2007 of hoger. |
|
|  | [Fodp](#Fodp) | Bestanden met de extensie FODP vertegenwoordigen een OpenDocument Flat XML‑presentatie. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Serialisatieconstructor


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


Een bestand met de extensie PPT vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97‑2003.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. Het lezen en maken van PPS‑bestanden wordt ondersteund door Microsoft PowerPoint 97‑2003.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Bestanden met de extensie PPTX zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint‑applicatie. In tegenstelling tot de vorige versie van het presentatiebestandformaat PPT, dat binair was, is het PPTX‑formaat gebaseerd op het Microsoft PowerPoint Open XML‑presentatieformaat.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Bestanden met de extensie ODP vertegenwoordigen een presentatie‑bestandformaat dat wordt gebruikt door OpenOffice.org volgens de OASIS‑open standaard.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Bestanden met de extensie .OTP vertegenwoordigen presentatiesjabloonbestanden die zijn gemaakt door applicaties volgens het OASIS OpenDocument‑formaat.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Bestanden met de extensie .POTX vertegenwoordigen Microsoft PowerPoint‑sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Bestanden met de extensie .POT vertegenwoordigen Microsoft PowerPoint‑sjabloonbestanden die zijn gemaakt met PowerPoint‑versies 97‑2003.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Bestanden met de extensie POTM zijn Microsoft PowerPoint-sjabloonbestanden met ondersteuning voor macro's. POTM-bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om verdere presentatiesbestanden te maken.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Bestanden met de extensie PPTM zijn macro‑ingeschakelde presentatiebestanden die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Bestanden met de extensie PPSM vertegenwoordigen een macro‑ingeschakeld diavoorstellingsbestandformaat dat is gemaakt met Microsoft PowerPoint 2007 of hoger.
Meer informatie over dit bestandsformaat [hier](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Bestanden met de extensie FODP vertegenwoordigen OpenDocument Flat XML-presentatie. Presentatiebestand opgeslagen in het OpenDocument-formaat, maar opgeslagen met een plat XML-formaat in plaats van de .ZIP-container die wordt gebruikt door standaard .ODP-bestanden.


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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
