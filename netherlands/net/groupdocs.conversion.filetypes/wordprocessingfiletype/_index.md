---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of rich‑text‑formaat. Een platte‑tekst‑bestandsformaat bevat onopgemaakte tekst en geen lettertype‑ of pagina‑instellingen enz. kunnen worden toegepast. Daarentegen biedt een rich‑text‑bestandsformaat opmaakopties zoals het instellen van lettertypen, type, stijlen, vet, cursief, onderstrepen enz., paginamarges, koppen, opsommingstekens en cijfers en verschillende andere opmaakfuncties. Bevat de volgende bestandstypen Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt Md./wordprocessingfiletype/md. Leer meer over tekstverwerkingsformaten hierhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /nl/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of opgemaakte tekstindeling. Een platte-tekst bestandsindeling bevat onopgemaakte tekst en geen lettertype‑ of pagina‑instellingen enzovoort. In tegenstelling hiermee staat een opgemaakte‑tekst bestandsindeling opmaakopties toe, zoals het instellen van lettertype‑type, stijlen (vet, cursief, onderstrepen, enz.), paginamarges, koppen, opsommingstekens en nummers, en verschillende andere opmaakfuncties. Bevat de volgende bestandstypen: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Meer informatie over tekstverwerkingsindelingen [hier](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serialisatie‑constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Bestanden met de .doc‑extensie vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsprogramma’s in binair bestandsformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM‑bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid macro’s uit te voeren. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX is een bekend formaat voor Microsoft Word‑documenten. Introductie vanaf 2007 met de release van Microsoft Office 2007, de structuur van dit nieuwe documentformaat werd gewijzigd van platte binair naar een combinatie van XML‑ en binaire bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Bestanden met de .DOT‑extensie zijn sjabloonbestanden die door Microsoft Word zijn aangemaakt om vooraf opgemaakte instellingen te hebben voor het genereren van verdere DOC‑ of DOCX‑bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Een bestand met de DOTM‑extensie vertegenwoordigt een sjabloonbestand dat is aangemaakt met Microsoft Word 2007 of hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Bestanden met de DOTX‑extensie zijn sjabloonbestanden die door Microsoft Word zijn aangemaakt om vooraf opgemaakte instellingen te hebben voor het genereren van verdere DOCX‑bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word is Office Open XML WordprocessingML opgeslagen in een plat XML‑bestand in plaats van een ZIP‑pakket. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Tekstbestanden die zijn gemaakt met Markdown‑taaldialecten worden opgeslagen met de .MD‑ of .MARKDOWN‑bestandsextensie. MD‑bestanden worden opgeslagen in platte‑tekstformaat dat Markdown‑taal gebruikt, die ook inline‑tekens bevat, waarmee wordt gedefinieerd hoe tekst kan worden opgemaakt, zoals inspringingen, tabelopmaak, lettertypen en koppen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT‑bestanden zijn een type documenten die zijn aangemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument‑tekstbestandformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Bestanden met de OTT‑extensie vertegenwoordigen sjabloondocumenten die door applicaties zijn gegenereerd in overeenstemming met de OpenDocument‑standaard van OASIS. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introductie en documentatie door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en grafische elementen te coderen voor gebruik binnen applicaties. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Een bestand met de .TXT‑extensie vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/txt). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
