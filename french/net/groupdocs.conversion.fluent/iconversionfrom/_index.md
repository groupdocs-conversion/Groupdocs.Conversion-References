---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Configurer la source pour la conversion"
type: docs
weight: 1440
url: /fr/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Configurer la source pour la conversion

```csharp
public interface IConversionFrom
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Définir le flux du document source |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Définir le tableau des flux des documents source |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Définir le nom de fichier du document source |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Définir le tableau des documents source |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Enregistrer les gestionnaires d'événements du cycle de vie de la conversion sur un sac [`ConversionEvents`](../../groupdocs.conversion/conversionevents) qui vit pendant la durée de vie du convertisseur et se déclenche à chaque exécution de conversion. Peut être appelé avant ou après [`WithSettings`](../iconversionsettings/withsettings). Les appels multiples s'accumulent : le même sac interne est transmis à chaque action *configure*, de sorte que les gestionnaires définis lors des appels précédents survivent sauf s'ils sont remplacés par un appel ultérieur. |

### Voir aussi

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
