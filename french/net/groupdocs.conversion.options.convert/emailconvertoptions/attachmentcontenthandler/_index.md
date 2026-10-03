---
title: "AttachmentContentHandler"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Un délégué pour gérer le traitement personnalisé des pièces jointes d'e‑mail. Le délégué reçoit le nom de la pièce jointe, le type de contenu et le flux de la pièce jointe originale en paramètres, et renvoie le flux de la pièce jointe modifié."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler/
---
## EmailConvertOptions.AttachmentContentHandler property

Un délégué pour gérer le traitement personnalisé des pièces jointes d'e‑mail. Le délégué prend le nom de la pièce jointe, le type de contenu et le flux de la pièce jointe originale comme paramètres et renvoie le flux de la pièce jointe modifié.

```csharp
public Func<string, string, Stream, Stream> AttachmentContentHandler { get; set; }
```

### Voir aussi

* class [EmailConvertOptions](../../emailconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
