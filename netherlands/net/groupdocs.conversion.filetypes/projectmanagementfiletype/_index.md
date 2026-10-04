---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert projectbestandsformaten die worden gemaakt door projectmanagementsoftware zoals Microsoft Project, Primavera P6, enz. Een projectbestand is een verzameling van taken, resources en hun planning om een meetbaar resultaat te verkrijgen in de vorm van een product of een dienst. Projectmanagementdocumenten. Bevat de volgende bestandstypen Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. Meer informatie over projectmanagementformaten hierhttps//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /nl/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Definieert projectbestandsformaten die worden gemaakt door projectmanagementsoftware zoals Microsoft Project, Primavera P6, enz. Een projectbestand is een verzameling van taken, resources en hun planning om een meetbaar resultaat te verkrijgen in de vorm van een product of een dienst. Projectmanagementdocumenten. Bevat de volgende bestandstypen: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). Meer informatie over projectmanagementformaten [hier](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Serialisatie‑constructor |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP is een Microsoft Project-gegevensbestand dat informatie met betrekking tot projectmanagement op een geïntegreerde manier opslaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Microsoft Project-sjabloonbestanden bevatten basisinformatie en -structuur samen met documentinstellingen voor het maken van .MPP-bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format is een ASCII-bestandsformaat voor het overdragen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX-bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Het XER-bestandsformaat is een propriëtair projectbestandsformaat dat wordt gebruikt door de Primavera P6 projectplanning- en -managementtoepassing. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/project-management/xer). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
