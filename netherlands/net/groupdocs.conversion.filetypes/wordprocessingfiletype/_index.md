---
title: WordProcessingFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of RTFindeling. Een plattetekstbestandsindeling bevat nietopgemaakte tekst en er kunnen geen lettertype of paginainstellingen etc. worden toegepast. Een rich textbestandsindeling biedt daarentegen opmaakopties zoals het instellen van lettertypen stijlen vet cursief onderstrepen enz. paginamarges koppen opsommingstekens en cijfers en verschillende andere opmaakfuncties. Bevat de volgende bestandstypen Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . Meer informatie over indelingen voor tekstverwerkinghierhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /nl/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definieert tekstverwerkingsbestanden die gebruikersinformatie bevatten in platte tekst of RTF-indeling. Een platte-tekstbestandsindeling bevat niet-opgemaakte tekst en er kunnen geen lettertype- of pagina-instellingen etc. worden toegepast. Een rich text-bestandsindeling biedt daarentegen opmaakopties zoals het instellen van lettertypen, stijlen (vet, cursief, onderstrepen, enz.), paginamarges, koppen, opsommingstekens en cijfers, en verschillende andere opmaakfuncties. Bevat de volgende bestandstypen: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . Meer informatie over indelingen voor tekstverwerking[hier](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serialisatie-constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstype omschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt huidige object met andere. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Tekenreeksweergave |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Bestanden met de extensie .doc vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binaire bestandsindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM-bestanden zijn Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van gewoon binair naar een combinatie van XML en binaire bestanden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Bestanden met de extensie .DOT zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | Een bestand met de DOTM-extensie vertegenwoordigt een sjabloonbestand dat is gemaakt met Microsoft Word 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Bestanden met de DOTX-extensie zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Tekstbestanden gemaakt met Markdown-taaldialecten worden opgeslagen met de bestandsextensie .MD of .MARKDOWN. MD-bestanden worden opgeslagen in platte tekstindeling die Markdown-taal gebruikt, die ook inline tekstsymbolen bevat, die bepalen hoe een tekst kan worden opgemaakt, zoals inspringingen, tabelopmaak, lettertypen en kopteksten. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT-bestanden zijn type documenten die zijn gemaakt met tekstverwerkingsprogramma's die zijn gebaseerd op het OpenDocument-tekstbestandsformaat. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Bestanden met de OTT-extensie vertegenwoordigen sjabloondocumenten die zijn gegenereerd door toepassingen in overeenstemming met het OpenDocument-standaardformaat van OASIS. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Geïntroduceerd en gedocumenteerd door Microsoft, de Rich Text Format (RTF) vertegenwoordigt een methode voor het coderen van opgemaakte tekst en afbeeldingen voor gebruik binnen toepassingen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | Een bestand met de extensie .TXT vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/txt) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
