---
title: "FileCache"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Gedrag van bestandscaching. Betekent dat de cache wordt opgeslagen op het bestandssysteem"
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

Gedrag van bestandscaching. Betekent dat de cache wordt opgeslagen op het bestandssysteem

```csharp
public sealed class FileCache : ICache
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FileCache](filecache)(string) | Maakt een nieuw exemplaar van de FileCache‑klasse |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | Retourneert alle sleutels die overeenkomen met het filter. |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | Voegt een cache‑item toe aan de cache. |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | Haalt het item op dat aan deze sleutel is gekoppeld, indien aanwezig. |

### Opmerkingen

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### Zie ook

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
