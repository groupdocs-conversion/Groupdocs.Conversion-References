---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen zum Laden von XML-Dokumenten."
type: docs
weight: 2960
url: /de/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Optionen zum Laden von XML-Dokumenten.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Initialisiert eine neue Instanz der Klasse [`XmlLoadOptions`](../xmlloadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Der Basis-Pfad/URL für das HTML |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Aktion zur Konfiguration der Anforderungsheader. Der erste Parameter der Aktion ist die Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Anbieter von Anmeldeinformationen für die Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Implementiert [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Liest oder setzt die zu verwendende Kodierung beim Laden des Webdokuments. Wenn die Eigenschaft null ist, wird die Kodierung aus dem Zeichensatzattribut des Dokuments ermittelt. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Steuert, wie HTML-Inhalt gerendert wird. Standard: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Seitenrand-Einstellungen |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Einstellungen für die Seitenausrichtung |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Gibt die Optionen für das Seitenlayout beim Laden von Webdokumenten an. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Aktivieren oder deaktivieren Sie die Erzeugung von Seitenzahlen im konvertierten Dokument. Standard: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Zeitlimit für das Laden externer Ressourcen |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Seitengröße-Einstellungen |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Implementiert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Verwende ein XML-Dokument als Datenquelle |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Verwende PDF für die Konvertierung. Standard: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Implementiert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | XSL-FO-Dokumentenstream zum Konvertieren von XML mithilfe einer XSL-FO-Markup-Datei. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | XSLT-Dokumentenstream zum Konvertieren von XML, wobei eine XSL-Transformation zu HTML durchgeführt wird. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Gibt den Zoom‑Level als Prozentsatz an. Der Zoom‑Level wird vor der Konvertierung auf das &lt;body&gt;-Tag des Dokuments angewendet und skaliert das visuelle Erscheinungsbild des Dokuments. Ein Wert von 100 % entspricht der Originalgröße. Der Standardwert ist 100. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |

### Siehe auch

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
