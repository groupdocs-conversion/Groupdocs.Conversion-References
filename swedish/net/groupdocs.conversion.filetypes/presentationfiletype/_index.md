---
title: PresentationFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar presentationsfilformat som lagrar samling av poster för att ta emot presentationsdata som bilder former text animationer video ljud och inbäddade objekt. Innehåller följande filtyper Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Läs mer om presentationsformathärhttps//wiki.fileformat.com/presentation .
type: docs
weight: 910
url: /sv/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Definierar presentationsfilformat som lagrar samling av poster för att ta emot presentationsdata som bilder, former, text, animationer, video, ljud och inbäddade objekt. Innehåller följande filtyper: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Läs mer om presentationsformat[här](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypsbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filtillägget |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | Filer med FODP-tillägg representerar OpenDocument Flat XML Presentation. Presentationsfilen sparad i OpenDocument-formatet, men sparad med ett platt XML-format istället för .ZIP-behållaren som används av vanliga .ODP-filer |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | Filer med ODP-tillägg representerar presentationsfilformat som används av OpenOffice.org i OASISOpen-standarden. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | Filer med filtillägget .OTP representerar presentationsmallfiler skapade av applikationer i OASIS OpenDocument standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | Filer med tillägget .POT representerar Microsoft PowerPoint-mallfiler skapade av PowerPoint 97-2003-versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | Filer med POTM-tillägg är Microsoft PowerPoint-mallfiler med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller högre och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | Filer med tillägget .POTX representerar Microsoft PowerPoint-mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slide Show, filer skapas med Microsoft PowerPoint för Slide Show-ändamål. PPS-filläsning och skapande stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | Filer med PPSM-tillägg representerar makroaktiverat bildspelsfilformat som skapats med Microsoft PowerPoint 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slide Show, filer skapas med Microsoft PowerPoint 2007 och senare för Slide Show-ändamål. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | En fil med PPT-tillägg representerar en PowerPoint-fil som består av en samling bilder för visning som SlideShow. Den anger det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | Filer med PPTM-tillägg är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | Filer med PPTX-tillägg är presentationsfiler skapade med populära Microsoft PowerPoint-applikation. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML-presentationsfilformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptx) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
