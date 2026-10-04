---
title: "FileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Basisbestandstypeklasse"
type: docs
weight: 1130
url: /nl/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Basisbestandstypeklasse

```csharp
public class FileType : Enumeration
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FileType](filetype)() | Serialisatie‑constructor |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Haalt FileType op voor de opgegeven fileExtension |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Retourneert FileType voor de opgegeven fileName |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Retourneert FileType voor de opgegeven document stream |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Retourneert alle enumeratiewaarden. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Impliciete conversie naar string |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Onbekend bestandstype |

### Zie ook

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
