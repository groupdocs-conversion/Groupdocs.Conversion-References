---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Déclenché lorsqu'une police référencée par le document source n'est pas disponible et est substituée soit par une règle FontSubstitutegroupdocs.conversion.contracts/fontsubstitute fournie par le client, soit par la police par défaut configurée, soit par le fallback interne du pipeline de conversion."
type: docs
weight: 80
url: /fr/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Déclenché lorsqu'une police référencée par le document source n'est pas disponible et est substituée (soit par une règle fournie par le client [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute), soit par la police par défaut configurée, ou par le fallback interne du pipeline de conversion).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Remarques

L'événement est dédupliqué par `(SourceFileName, OriginalFontName)` au sein d'un seul appel `Converter.Convert(...)` — les abonnés reçoivent au maximum une notification par police manquante pour chaque document source. Il se déclenche de manière synchrone sur le thread de conversion. Il n'est pas déclenché pour les conversions d'images.

Pour les documents de présentation, la substitution de police n'est détectée que sous Windows, car le moteur la résout via une correspondance de polices spécifique à la plateforme qui n'est pas disponible sur les autres systèmes d'exploitation.

### Voir aussi

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
