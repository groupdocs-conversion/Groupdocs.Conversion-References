---
title: "FileCache"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Comportamiento de caché de archivos. Significa que la caché se almacena en el sistema de archivos"
type: docs
weight: 10
url: /es/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

Comportamiento de caché de archivos. Significa que la caché se almacena en el sistema de archivos

```csharp
public sealed class FileCache : ICache
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FileCache](filecache)(string) | Crea una nueva instancia de la clase FileCache |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | Devuelve todas las claves que coinciden con el filtro. |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | Inserta una entrada en la caché. |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | Obtiene la entrada asociada a esta clave si está presente. |

### Observaciones

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### Ver también

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
