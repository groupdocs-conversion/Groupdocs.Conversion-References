---
title: "EmailConvertOptions"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Options de conversion vers le type de fichier Email."
type: docs
weight: 1800
url: /fr/net/groupdocs.conversion.options.convert/emailconvertoptions/
---
## EmailConvertOptions class

Options de conversion vers le type de fichier Email.

```csharp
public class EmailConvertOptions : ConvertOptions<EmailFileType>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmailConvertOptions](emailconvertoptions)() | Initialise une nouvelle instance de la classe [`EmailConvertOptions`](../emailconvertoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AttachmentContentHandler](../../groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler) { get; set; } | Un délégué pour gérer le traitement personnalisé des pièces jointes d'e‑mail. Le délégué prend le nom de la pièce jointe, le type de contenu et le flux de la pièce jointe originale comme paramètres et renvoie le flux de la pièce jointe modifié. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Le type de fichier souhaité vers lequel le document d'entrée doit être converti. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implémente [`Format`](../iconvertoptions/format) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clone l'instance actuelle des options. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Détermine si deux instances d'objet sont égales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Servir de fonction de hachage par défaut. |

### Voir aussi

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [EmailFileType](../../groupdocs.conversion.filetypes/emailfiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
