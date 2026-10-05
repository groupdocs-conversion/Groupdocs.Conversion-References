---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar presentationsfilformat som lagrar en samling poster för att hantera presentationsdata såsom bilder, former, text, animationer, video, ljud och inbäddade objekt."
type: docs
weight: 22
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Definierar presentationsfilformat som lagrar en samling poster för att hantera presentationsdata såsom bilder, former, text, animationer, video, ljud och inbäddade objekt. Inkluderar följande filtyper: [Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Odp), [Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Otp), [Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pot), [Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potm), [Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Potx), [Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pps), [Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsm), [Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppsx), [Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Ppt), [Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptm), [Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype\#Pptx). Läs mer om presentationsformat [here][].


[here]: https://wiki.fileformat.com/presentation
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationFileType()](#PresentationFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Ppt](#Ppt) | En fil med PPT‑extension representerar en PowerPoint‑fil som består av en samling bilder för att visas som bildspel. |
| [Pps](#Pps) | PPS, PowerPoint Slide Show, filer skapas med Microsoft PowerPoint för bildspelsändamål. |
| [Pptx](#Pptx) | Filer med PPTX‑extension är presentationsfiler skapade med det populära Microsoft PowerPoint‑programmet. |
| [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. |
| [Odp](#Odp) | Filer med ODP‑extension representerar presentationsfilformat som används av OpenOffice.org i OASISOpen‑standarden. |
| [Otp](#Otp) | Filer med .OTP‑extension representerar presentationsmallfiler som skapats av program i OASIS OpenDocument‑standardformat. |
| [Potx](#Potx) | Filer med .POTX‑extension representerar Microsoft PowerPoint‑mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. |
| [Pot](#Pot) | Filer med .POT‑extension representerar Microsoft PowerPoint‑mallfiler skapade av PowerPoint‑versionerna 97‑2003. |
| [Potm](#Potm) | Filer med POTM‑extension är Microsoft PowerPoint‑mallfiler med stöd för makron. |
| [Pptm](#Pptm) | Filer med PPTM‑extension är makroaktiverade presentationsfiler som skapats med Microsoft PowerPoint 2007 eller senare versioner. |
| [Ppsm](#Ppsm) | Filer med PPSM‑extension representerar makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. |
| [Fodp](#Fodp) | Filer med FODP‑extension representerar OpenDocument Flat XML‑presentation. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Serialiseringskonstruktor

### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


En fil med PPT‑extension representerar en PowerPoint‑fil som består av en samling bilder för att visas som bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint‑bildspel, filer skapas med Microsoft PowerPoint för bildspelsändamål. PPS‑filens läsning och skapande stöds av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


Filer med filändelsen PPTX är presentationsfiler som skapats med det populära Microsoft PowerPoint‑programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT, som var binärt, är PPTX‑formatet baserat på Microsoft PowerPoints öppna XML‑presentationsfilformat. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, PowerPoint‑bildspel, filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### Odp {#Odp}
```
public static final PresentationFileType Odp
```


Filer med ODP‑ändelse representerar presentationsfilformatet som används av OpenOffice.org i OASIS‑standard. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### Otp {#Otp}
```
public static final PresentationFileType Otp
```


Filer med .OTP‑ändelse representerar presentationsmallar som skapats av program i OASIS OpenDocument‑standardformatet. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### Potx {#Potx}
```
public static final PresentationFileType Potx
```


Filer med .POTX‑ändelse representerar Microsoft PowerPoint‑mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### Pot {#Pot}
```
public static final PresentationFileType Pot
```


Filer med .POT‑ändelse representerar Microsoft PowerPoint‑mallfiler som skapats av PowerPoint‑versionerna 97‑2003. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### Potm {#Potm}
```
public static final PresentationFileType Potm
```


Filer med POTM‑ändelse är Microsoft PowerPoint‑mallfiler med stöd för makron. POTM‑filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


Filer med PPTM‑ändelse är makroaktiverade presentationsfiler som skapats med Microsoft PowerPoint 2007 eller högre versioner. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


Filer med PPSM‑ändelse representerar ett makroaktiverat bildspelsfilformat som skapats med Microsoft PowerPoint 2007 eller senare. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


Filer med FODP‑ändelse representerar OpenDocument Flat XML‑presentation. Presentationsfil sparas i OpenDocument‑formatet, men sparas med ett platt XML‑format istället för .ZIP‑behållaren som används av standard‑.ODP‑filer.

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
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
