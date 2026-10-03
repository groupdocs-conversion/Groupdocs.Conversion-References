---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Lorsque true les paragraphes par défaut et les runs dont le texte est majoritairement righttoleft verront leurs indicateurs bidi réparés avant la conversion. Cela correspond à l'heuristique appliquée par Microsoft Word et LibreOffice et corrige le rendu des documents arabe/hébreu produits par des générateurs, notamment Google Docs, qui émettent du OOXML sans ltwbidi/gt et avec ltwrtl wval0/gt sur les runs qui ne contiennent que du script RTL. Réglez sur false pour préserver une interprétation stricte du OOXML du balisage source."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

Lorsque vrai (par défaut), les paragraphes et les runs dont le texte est majoritairement de droite à gauche verront leurs indicateurs bidi réparés avant la conversion. Cela correspond à l'heuristique appliquée par Microsoft Word et LibreOffice et corrige le rendu des documents arabes/hébreux générés par des générateurs (notamment Google Docs) qui produisent du OOXML sans &lt;w:bidi/&gt; et avec &lt;w:rtl w:val=\"0\"/&gt; sur les runs contenant uniquement du script RTL. Réglez sur false pour préserver une interprétation stricte du OOXML du balisage source.

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### Voir aussi

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
