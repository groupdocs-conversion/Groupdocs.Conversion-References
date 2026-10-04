---
title: "PresentationFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar presentationsfilformat som lagrar en samling poster för att rymma presentationsdata såsom bildspel, former, text, animationer, video, ljud och inbäddade objekt. Inkluderar följande filtyper Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Läs mer om presentationsformat härhttps//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /sv/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definierar presentationsfilformat som lagrar en samling poster för att rymma presentationsdata såsom bildspel, former, text, animationer, video, ljud och inbäddade objekt. Inkluderar följande filtyper: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Läs mer om presentationsformat [här](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Filer med FODP‑ändelse representerar OpenDocument Flat XML Presentation. Presentationsfil sparad i OpenDocument‑formatet, men sparad med ett platt XML‑format istället för .ZIP‑behållaren som används av standard‑.ODP‑filer. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Filer med ODP‑ändelse representerar presentationsfilformat som används av OpenOffice.org i OASIS‑standard. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Filer med .OTP‑ändelse representerar presentationsmallfiler som skapats av program i OASIS OpenDocument‑standardformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Filer med .POT‑ändelse representerar Microsoft PowerPoint‑mallfiler som skapats av PowerPoint‑versionerna 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Filer med POTM‑tillägg är Microsoft PowerPoint‑mallfiler med stöd för makron. POTM‑filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Filer med .POTX‑tillägg representerar Microsoft PowerPoint‑mallpresentationer som skapas med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint‑bildspel, filer skapas med Microsoft PowerPoint för bildspelsändamål. Läsning och skapande av PPS‑filer stöds av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Filer med PPSM‑tillägg representerar makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, PowerPoint‑bildspel, filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | En fil med PPT‑tillägg representerar en PowerPoint‑fil som består av en samling bilder för visning som bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Filer med PPTM‑tillägg är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Filer med PPTX‑tillägg är presentationsfiler skapade med det populära Microsoft PowerPoint‑programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT, som var binärt, är PPTX‑formatet baserat på Microsoft PowerPoints öppna XML‑presentationsfilformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptx). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
