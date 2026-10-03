---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Indique s'il faut vérifier les restrictions du fichier Excel lorsque l'utilisateur modifie des objets liés aux cellules. Par exemple, Excel n'autorise pas la saisie d'une chaîne de caractères supérieure à 32 K. Si vous saisissez une valeur supérieure à 32 K et que cette propriété est vraie, une exception sera levée. Si cette propriété est fausse, nous accepterons votre chaîne saisie comme valeur de cellule, ce qui vous permettra ensuite d'exporter la chaîne complète vers d'autres formats de fichier tels que CSV. Cependant, si vous avez défini une valeur de ce type qui est invalide pour le format de fichier Excel, vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, des erreurs inattendues peuvent survenir dans le fichier Excel généré."
type: docs
weight: 40
url: /fr/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

Détermine si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules. Par exemple, Excel n'autorise pas la saisie d'une chaîne de caractères supérieure à 32 K. Lorsque vous saisissez une valeur supérieure à 32 K, si cette propriété est vraie, vous obtiendrez une exception. Si cette propriété est fausse, nous accepterons votre chaîne saisie comme valeur de la cellule afin que vous puissiez ensuite exporter la chaîne complète vers d'autres formats de fichier tels que CSV. Cependant, si vous avez défini une valeur de ce type qui n'est pas valide pour le format de fichier Excel, vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, il peut y avoir une erreur inattendue dans le fichier Excel généré.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Voir aussi

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
