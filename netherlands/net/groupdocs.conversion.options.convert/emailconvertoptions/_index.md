---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor conversie naar Email‑bestandtype."
type: docs
weight: 1800
url: /nl/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Opties voor conversie naar Email‑bestandtype.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Initialiseert een nieuwe instantie van de [`EmailConvertOptions`](../emailconvertoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Een delegate om aangepaste verwerking van e‑mailbijlagen af te handelen. De delegate neemt de bestandsnaam van de bijlage, het content‑type en de oorspronkelijke bijlage‑stream als parameters en retourneert de gewijzigde bijlage‑stream. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementeert [`Format`](../iconvertoptions/format) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige opties-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
