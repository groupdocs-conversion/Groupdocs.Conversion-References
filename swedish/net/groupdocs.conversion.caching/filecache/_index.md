---
title: "FileCache"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Filcachebeteende. Betyder att cachen lagras på filsystemet."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

Filcachebeteende. Betyder att cachen lagras på filsystemet.

```csharp
public sealed class FileCache : ICache
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileCache](filecache)(string) | Skapar en ny instans av klassen FileCache. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | Returnerar alla nycklar som matchar filtret. |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | Infogar ett cache‑objekt i cachen. |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | Hämtar objektet som är associerat med denna nyckel om det finns. |

### Anmärkningar

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### Se även

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
