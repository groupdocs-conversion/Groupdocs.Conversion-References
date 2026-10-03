---
title: "ICache"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les méthodes requises pour stocker le document rendu et le cache des ressources du document."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion.caching/icache/
---
## ICache interface

Définit les méthodes requises pour stocker le document rendu et le cache des ressources du document.

```csharp
public interface ICache
```

## Méthodes

| Nom | Description |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/icache/getkeys)(string) | Renvoie toutes les clés correspondant au filtre. |
| [Set](../../groupdocs.conversion.caching/icache/set)(string, object) | Insère une entrée dans le cache. |
| [TryGetValue](../../groupdocs.conversion.caching/icache/trygetvalue)(string, out object) | Obtient l'entrée associée à cette clé si elle est présente. |

### Voir aussi

* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
