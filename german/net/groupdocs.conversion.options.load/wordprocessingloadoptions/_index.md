---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen zum Laden von WordProcessing-Dokumenten."
type: docs
weight: 2950
url: /de/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Optionen zum Laden von WordProcessing-Dokumenten.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initialisiert eine neue Instanz der Klasse [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Wenn true (Standard), werden Absätze und Läufe, deren Text überwiegend von rechts nach links verläuft, vor der Konvertierung ihre Bidi‑Flags repariert. Dies entspricht der von Microsoft Word und LibreOffice verwendeten Heuristik und behebt die Darstellung von Arabisch‑/Hebräisch‑Dokumenten, die von Generatoren (insbesondere Google Docs) erzeugt werden und OOXML ohne &lt;w:bidi/&gt; und mit &lt;w:rtl w:val=\"0\"/&gt; in Läufen, die nur RTL‑Skript enthalten, ausgeben. Setzen Sie es auf false, um die strikte OOXML‑Interpretation des Quell‑Markups beizubehalten. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Lesezeichen-Optionen |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Entfernt integrierte Metadaten‑Eigenschaften aus dem Dokument. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Entfernt benutzerdefinierte Metadaten‑Eigenschaften aus dem Dokument. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Legt fest, wie Kommentare im Ausgabedokument angezeigt werden sollen. Standard ist ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implementiert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard ist false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implementiert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard ist true. |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Legt die Standardschriftart für ein WordProcessing‑Dokument fest. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implementiert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Wenn EmbedTrueTypeFonts true ist, bettet GroupDocs.Conversion TrueType‑Schriften in das Ausgabedokument ein. Standard: true. |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Ersetzt fehlende Schriften automatisch basierend auf FontConfig im System. Standard: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Ersetzt fehlende Schriften automatisch basierend auf FontInfo im Dokument. Standard: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Ersetzt fehlende Schriften automatisch basierend auf dem Schriftnamen. Standard: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Ersetzt bestimmte Schriften beim Konvertieren eines WordsProcessing‑Dokuments. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Transformiert vorhandene Schriften, nachdem das Laden des Dokuments und die Schriftart‑Ersetzung abgeschlossen sind. Schriftart‑Transformationen können alle Schriften im Dokument ändern, einschließlich der erfolgreich geladenen Schriften. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Dateityp des Eingabedokuments. Ist `null`, bis ein Format festgelegt wurde, daher prüfen Sie auf `null` anstatt gegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) zu vergleichen, was niemals zutrifft. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Versteckt Markup und Änderungsverfolgung für Word‑Dokumente. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Legt Silbentrennungsoptionen für WordProcessing‑Dokumente fest. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Behalte den ursprünglichen Wert des Datumsfelds bei. Standard: false. |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Seitenrand-Einstellungen |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Aktivieren oder deaktivieren Sie die Erzeugung von Seitenzahlen im konvertierten Dokument. Standard: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Passwort festlegen, um geschütztes Dokument zu entsperren. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Bestimmt, ob die Dokumentstruktur beim Konvertieren zu PDF erhalten bleiben soll (Standard ist false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Legt fest, ob Microsoft Word-Formularfelder als Formularfelder im PDF erhalten bleiben oder in Text konvertiert werden sollen. Standard ist false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Vollständigen Namen des Kommentators in Kommentaren anzeigen. Standard ist false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Seitengröße-Einstellungen |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implementiert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Felder nach dem Laden aktualisieren. Standard: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Seitenlayout nach dem Laden aktualisieren. Standard: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Gibt an, ob ein Textformer zur besseren Kerning-Anzeige verwendet werden soll. Standard ist false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implementiert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |

### Hinweise

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Behandelt fehlende/nicht verfügbare Schriftarten mithilfe von FontSubstitutes, DefaultFont und System-Substitution

• Verarbeitungsreihenfolge: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Modifiziert vorhandene Schriftarten im geladenen Dokument mithilfe von FontReplacements

• Wird angewendet, nachdem alle Schriftart-Substitutionen abgeschlossen sind

### Siehe auch

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
