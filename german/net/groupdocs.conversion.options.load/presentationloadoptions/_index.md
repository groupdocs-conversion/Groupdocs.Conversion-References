---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen zum Laden von Presentation-Dokumenten."
type: docs
weight: 2770
url: /de/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Optionen zum Laden von Presentation-Dokumenten.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | Initialisiert eine neue Instanz der Klasse [`PresentationLoadOptions`](../presentationloadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | Entfernt integrierte Metadaten‑Eigenschaften aus dem Dokument. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | Entfernt benutzerdefinierte Metadaten‑Eigenschaften aus dem Dokument. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | Stellt dar, wie Kommentare mit der Folie gedruckt werden. Standard ist None. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | Implementiert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard ist false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | Implementiert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard ist true. |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | Standard‑Schriftart für die Darstellung der Präsentation. Die folgende Schriftart wird verwendet, wenn eine Präsentationsschriftart fehlt. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | Implementiert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | Ersetzt bestimmte Schriftarten beim Konvertieren eines Präsentationsdokuments. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | Dateityp des Eingabedokuments. Ist `null`, bis ein Format festgelegt wurde, daher prüfen Sie auf `null` anstatt gegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) zu vergleichen, was niemals zutrifft. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | Stellt dar, wie Notizen mit der Folie gedruckt werden. Standard ist None. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | Passwort festlegen, um geschütztes Dokument zu entsperren. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | Bestimmt, ob die Dokumentstruktur beim Konvertieren zu PDF erhalten bleiben soll (Standard ist false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | Versteckte Folien anzeigen. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | Implementiert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | Implementiert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | Video‑Dokument‑Connector festlegen |

### Siehe auch

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
