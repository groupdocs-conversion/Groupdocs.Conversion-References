---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Exception GroupDocs levée lorsqu'une conversion ne peut pas s'exécuter parce qu'une assembly dont elle dépend n'est pas présente dans la sortie de l'application. Le document n'est pas en faute."
type: docs
weight: 1030
url: /fr/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

Exception GroupDocs levée lorsqu'une conversion ne peut pas s'exécuter parce qu'une assembly dont elle dépend n'est pas présente dans la sortie de l'application. Le document n'est pas en cause.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Constructeur par défaut |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Crée une instance d'exception avec un message |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Crée une instance d'exception avec un message et propage l'exception interne |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Crée une instance d'exception nommant l'assembly qui n'a pas pu être chargé |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | Le nom simple de l'assembly qui n'a pas pu être chargé, ou null lorsqu'il n'a pas pu être déterminé. |

### Voir aussi

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
