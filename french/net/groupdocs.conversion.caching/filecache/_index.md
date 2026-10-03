---
title: "FileCache"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Comportement du cache de fichiers. Signifie que le cache est stocké sur le système de fichiers"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

Comportement du cache de fichiers. Signifie que le cache est stocké sur le système de fichiers

```csharp
public sealed class FileCache : ICache
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileCache](filecache)(string) | Crée une nouvelle instance de la classe FileCache |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | Renvoie toutes les clés correspondant au filtre. |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | Insère une entrée dans le cache. |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | Obtient l'entrée associée à cette clé si elle est présente. |

### Remarques

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### Voir aussi

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
