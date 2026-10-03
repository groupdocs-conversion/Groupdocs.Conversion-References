---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Lorsqu'il est activé, limite la résolution de rendu PDF par page à la résolution raster native de la page afin qu'aucune page ne soit rendue à un DPI supérieur à celui de l'image intégrée qu'elle contient réellement, et émet cette page avec ses dimensions de pixel natives plus petites et son DPI natif dans le résultat final au lieu de la ré‑inflater au DPI demandé. Seules les pages numérisées dominées par l'image sont affectées ; les pages contenant du texte ou du contenu vectoriel ne sont jamais adoucies et sont émises au DPI demandé. Ignoré lorsqu'une sortie explicite Widthgroupdocs.conversion.options.convert/imageconvertoptions/width ou Heightgroupdocs.conversion.options.convert/imageconvertoptions/height est définie. La valeur par défaut est false, aucune limitation ; chaque page est rendue et émise au DPI demandé."
type: docs
weight: 40
url: /fr/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

Lorsqu'il est activé, limite la résolution de rendu PDF par page à la résolution raster native de la page afin qu'aucune page ne soit rendue à un DPI supérieur à celui de l'image intégrée qu'elle contient, et émet cette page avec ses dimensions de pixel natives (plus petites) et son DPI natif dans le résultat final au lieu de la ré‑inflater au DPI demandé. Seules les pages dominées par l'image (numérisation) sont affectées ; les pages contenant du texte ou du contenu vectoriel ne sont jamais adoucies et sont émises au DPI demandé. Ignoré lorsqu'une sortie explicite [`Width`](../width) ou [`Height`](../height) est définie. La valeur par défaut est `false` (pas de limitation ; chaque page est rendue et émise au DPI demandé).

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### Voir aussi

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
