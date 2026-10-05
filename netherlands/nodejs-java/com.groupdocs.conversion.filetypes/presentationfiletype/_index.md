---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert presentatiebestandsformaten die een verzameling records opslaan om presentatiedata zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten te ondersteunen."
type: docs
weight: 22
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Definieert presentatiebestandsformaten die een verzameling records opslaan om presentatiedata zoals dia's, vormen, tekst, animaties, video, audio en ingesloten objecten te ondersteunen. Bevat de volgende bestandstypen: [Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Odp), [Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Otp), [Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pot), [Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potm), [Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potx), [Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pps), [Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsm), [Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsx), [Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppt), [Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptm), [Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptx). Leer meer over presentatieformaten [hier][].


[here]: https://wiki.fileformat.com/presentation
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationFileType()](#PresentationFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Ppt](#Ppt) | Een bestand met PPT-extensie vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. |
| [Pps](#Pps) | PPS, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. |
| [Pptx](#Pptx) | Bestanden met PPTX-extensie zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint‑applicatie. |
| [Ppsx](#Ppsx) | PPSX, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden. |
| [Odp](#Odp) | Bestanden met ODP-extensie vertegenwoordigen een presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org in de OASIS‑Open‑standaard. |
| [Otp](#Otp) | Bestanden met .OTP-extensie vertegenwoordigen presentatiesjabloonbestanden die zijn gemaakt door applicaties in het OASIS OpenDocument‑standaardformaat. |
| [Potx](#Potx) | Bestanden met .POTX-extensie vertegenwoordigen Microsoft PowerPoint‑sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. |
| [Pot](#Pot) | Bestanden met .POT-extensie vertegenwoordigen Microsoft PowerPoint‑sjabloonbestanden die zijn gemaakt door PowerPoint‑versies 97‑2003. |
| [Potm](#Potm) | Bestanden met POTM-extensie zijn Microsoft PowerPoint‑sjabloonbestanden met ondersteuning voor macro's. |
| [Pptm](#Pptm) | Bestanden met PPTM-extensie zijn macro‑ingeschakelde presentatiedocumenten die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. |
| [Ppsm](#Ppsm) | Bestanden met PPSM-extensie vertegenwoordigen een macro‑ingeschakeld diavoorstellingsbestandsformaat dat is gemaakt met Microsoft PowerPoint 2007 of hoger. |
| [Fodp](#Fodp) | Bestanden met FODP-extensie vertegenwoordigen een OpenDocument Flat XML‑presentatie. |
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


Een bestand met PPT-extensie vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97‑2003. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/presentation/ppt

### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint‑diavoorstelling, bestanden worden gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. Het lezen en maken van PPS‑bestanden wordt ondersteund door Microsoft PowerPoint 97‑2003. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/presentation/pps

### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Bestanden met PPTX-extensie zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint‑applicatie. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX‑formaat gebaseerd op het Microsoft PowerPoint open XML‑presentatiebestandsformaat. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/presentation/pptx

### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, Power Point Slide Show, bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor Slide‑Show‑doeleinden. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Bestanden met de ODP‑extensie vertegenwoordigen een presentatiestructuur die wordt gebruikt door OpenOffice.org volgens de OASIS‑Open‑standaard. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Bestanden met de .OTP‑extensie vertegenwoordigen presentatiesjabloonbestanden die door toepassingen zijn aangemaakt volgens de OASIS OpenDocument‑standaard. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Bestanden met de .POTX‑extensie vertegenwoordigen Microsoft PowerPoint‑sjabloonpresentaties die zijn aangemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Bestanden met de .POT‑extensie vertegenwoordigen Microsoft PowerPoint‑sjabloonbestanden die zijn aangemaakt met PowerPoint‑versies 97‑2003. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Bestanden met de POTM‑extensie zijn Microsoft PowerPoint‑sjabloonbestanden met ondersteuning voor macro’s. POTM‑bestanden worden aangemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om verdere presentaties te maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Bestanden met de PPTM‑extensie zijn macro‑ingeschakelde presentaties die zijn aangemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Bestanden met de PPSM‑extensie vertegenwoordigen een macro‑ingeschakelde Slide‑Show‑bestandsindeling die is aangemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Bestanden met de FODP‑extensie vertegenwoordigen een OpenDocument Flat XML‑presentatie. Een presentatiebestand opgeslagen in het OpenDocument‑formaat, maar bewaard met een vlak XML‑formaat in plaats van de .ZIP‑container die bij standaard .ODP‑bestanden wordt gebruikt.

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
