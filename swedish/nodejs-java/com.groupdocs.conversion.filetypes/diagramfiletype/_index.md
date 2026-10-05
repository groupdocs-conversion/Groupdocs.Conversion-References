---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar diagramdokument."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Definierar Diagram‑dokument. Inkluderar följande typer: [Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdw), [Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vdx), [Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsd), [Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdm), [Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsdx), [Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vss), [Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssm), [Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vssx), [Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vst), [Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstm), [Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vstx), [Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vsx), [Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype\#Vtx).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DiagramFileType()](#DiagramFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Vsd](#Vsd) | VSD‑filer är ritningar skapade med Microsoft Visio‑applikationen för att representera en mängd grafiska objekt och deras sammankoppling. |
| [Vsdx](#Vsdx) | Filer med .VSDX‑extension representerar Microsoft Visio‑filformatet som introducerades från Microsoft Office 2013 och framåt. |
| [Vss](#Vss) | VSS är stencil‑filer skapade med Microsoft Visio 2007 och tidigare. |
| [Vst](#Vst) | Filer med VST‑extension är vektor‑bildfiler skapade med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. |
| [Vsx](#Vsx) | Filer med .VSX‑tillägg avser mallar som består av ritningar och former som används för att skapa diagram i Microsoft Visio. |
| [Vtx](#Vtx) | En fil med VTX‑tillägg är en Microsoft Visio‑ritmall som sparas på disk i XML‑filformat. |
| [Vdw](#Vdw) | VDW är Visio Graphics Service‑filformatet som specificerar de strömmar och lagringar som krävs för att rendera en webb‑ritning. |
| [Vdx](#Vdx) | Alla ritningar eller diagram som skapas i Microsoft Visio, men sparas i XML‑format, har .VDX‑tillägg. |
| [Vssx](#Vssx) | Filer med .VSSX‑tillägg är ritningsmallar som skapats med Microsoft Visio 2013 och senare. |
| [Vstx](#Vstx) | Filer med VSTX‑tillägg är ritningsmallfiler som skapats med Microsoft Visio 2013 och senare. |
| [Vsdm](#Vsdm) | Filer med VSDM‑tillägg är ritningsfiler som skapats med Microsoft Visio‑programmet som stöder makron. |
| [Vssm](#Vssm) | Filer med .VSSM‑tillägg är Microsoft Visio‑mallfiler som ger stöd för makron. |
| [Vstm](#Vstm) | Filer med VSTM‑tillägg är mallfiler som skapats med Microsoft Visio och som stöder makron. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Serialiseringskonstruktor

### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


VSD‑filer är ritningar som skapats med Microsoft Visio‑programmet för att representera en mängd grafiska objekt och deras sammankoppling. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vsd

### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


Filer med .VSDX‑tillägg representerar Microsoft Visio‑filformatet som introducerades från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöds av tidigare versioner av Microsoft Visio. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS är mallfiler som skapats med Microsoft Visio 2007 och tidigare. Mallfilerna tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio‑ritning. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vss

### Vst {#Vst}
```
public static final DiagramFileType Vst
```


Filer med VST‑tillägg är vektorbildfiler som skapats med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Dessa mallfiler är i binärt filformat och innehåller standardlayouten och inställningarna som används för att skapa nya Visio‑ritningar. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vst

### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


Filer med .VSX‑tillägg avser mallar som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX‑filer sparas i XML‑filformat och stöddes fram till Visio 2013. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vsx

### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


En fil med VTX‑tillägg är en Microsoft Visio‑ritmall som sparas på disk i XML‑filformat. Mallen är avsedd att tillhandahålla en fil med grundinställningar som kan användas för att skapa flera Visio‑filer med samma inställningar. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vtx

### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW är Visio Graphics Service‑filformatet som specificerar de strömmar och lagringar som krävs för att rendera en webb‑ritning. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/web/vdw

### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Alla ritningar eller diagram som skapas i Microsoft Visio, men sparas i XML‑format, har .VDX‑tillägg. En Visio‑ritnings‑XML‑fil skapas i Visio‑programvaran, som utvecklats av Microsoft. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vdx

### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


Filer med .VSSX‑tillägg är ritningsmallar som skapats med Microsoft Visio 2013 och senare. VSSX‑filformatet kan öppnas med Visio 2013 och senare. Visio‑filer är kända för att representera en mängd ritningselement såsom samlingar av former, anslutningar, flödesscheman, nätverkslayouter, UML‑diagram. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vssx

### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


Filer med VSTX‑tillägg är ritmallfiler som skapats med Microsoft Visio 2013 och senare. Dessa VSTX‑filer ger en utgångspunkt för att skapa Visio‑ritningar, sparade som .VSDX‑filer, med standardlayout och -inställningar. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vstx

### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


Filer med VSDM‑tillägg är ritningsfiler som skapats med Microsoft Visio‑applikationen som stödjer makron. VSDM‑filer är OPC/XML‑ritningar som liknar VSDX, men ger också möjlighet att köra makron när filen öppnas. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


Filer med .VSSM‑tillägg är Microsoft Visio‑stencil‑filer som stödjer makron. En VSSM‑fil som öppnas tillåter att köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vssm

### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


Filer med VSTM‑tillägg är mallfiler som skapats med Microsoft Visio och som stödjer makron. Till skillnad från VSDX‑filer kan filer som skapats från VSTM‑mallar köra makron som utvecklats i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat [here][].


[here]: https://wiki.fileformat.com/image/vstm

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
