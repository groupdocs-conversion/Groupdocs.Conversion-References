---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen zum Laden von Pdf-Dokumenten."
type: docs
weight: 2740
url: /de/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Optionen zum Laden von Pdf-Dokumenten.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Initialisiert eine neue Instanz der Klasse [`PdfLoadOptions`](../pdfloadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Entfernt integrierte Metadaten‑Eigenschaften aus dem Dokument. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Entfernt benutzerdefinierte Metadaten‑Eigenschaften aus dem Dokument. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Implementiert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard ist false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Implementiert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard ist true. |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Standard-Schriftart für Pdf-Dokument. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Implementiert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | Alle Felder des PDF-Formulars flachlegen. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Bestimmte Schriftarten beim Konvertieren des Pdf-Dokuments ersetzen. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Transformiert vorhandene Schriften, nachdem das Laden des Dokuments und die Schriftart‑Ersetzung abgeschlossen sind. Schriftart‑Transformationen können alle Schriften im Dokument ändern, einschließlich der erfolgreich geladenen Schriften. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Dateityp des Eingabedokuments. Ist `null`, bis ein Format festgelegt wurde, daher prüfen Sie auf `null` anstatt gegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) zu vergleichen, was niemals zutrifft. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Anmerkungen in Pdf-Dokumenten ausblenden. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Aktivieren oder deaktivieren Sie die Erzeugung von Seitenzahlen im konvertierten Dokument. Standard: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Passwort festlegen, um geschütztes Dokument zu entsperren. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Eingebettete Dateien entfernen. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | JavaScript entfernen. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Setzt die Schriftarten‑Ordner zurück, bevor das Dokument geladen wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |

### Siehe auch

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
