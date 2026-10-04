---
title: "FinanceFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert financiële documenten. Bevat de volgende typen Xbrl./financefiletype/xbrl IXbrl./financefiletype/ixbrl Ofx./financefiletype/ofx Meer informatie over financiële formaten hier https//docs.fileformat.com/finance/."
type: docs
weight: 1140
url: /nl/net/groupdocs.conversion.filetypes/financefiletype/
---
## FinanceFileType class

Definieert financiële documenten. Bevat de volgende typen: [`Xbrl`](./xbrl)[`IXbrl`](./ixbrl)[`Ofx`](./ofx) Meer informatie over financiële formaten [hier](https://docs.fileformat.com/finance/).

```csharp
public sealed class FinanceFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FinanceFileType](financefiletype)() | Serialisatie‑constructor |

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
| static readonly [IXbrl](../../groupdocs.conversion.filetypes/financefiletype/ixbrl) | Binnen iXBRL worden de inhoud van XBRL verpakt in het xHTML‑bestandsformaat dat XML‑tags gebruikt. Net als XBRL is dit het root‑element van iXBRL‑bestanden. Het XHTML‑formaat vertegenwoordigt de inhoud als een verzameling verschillende documenttypen en modules. Alle bestanden in XHTML zijn gebaseerd op het XML‑bestandsformaat en voldoen aan de XML‑documentstandaarden. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/finance/ixbrl/). |
| static readonly [Ofx](../../groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) is een datastroomformaat voor het uitwisselen van financiële informatie dat is voortgekomen uit Microsoft's Open Financial Connectivity (OFC) en Intuit's Open Exchange‑bestandsformaten. Meer informatie over dit bestandsformaat [hier](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |
| static readonly [Xbrl](../../groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL is een open internationale standaard voor digitale bedrijfsrapportage die wereldwijd veel wordt gebruikt. Het is een op XML gebaseerde taal die XBRL‑elementen, bekend als tags, gebruikt om elk item van bedrijfsgegevens te beschrijven om gegevens te formuleren voor rapportsortering en analyse. Leer meer over dit bestandsformaat [hier](https://docs.fileformat.com/finance/xbrl/). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
