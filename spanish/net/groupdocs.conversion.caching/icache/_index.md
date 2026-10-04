---
title: "ICache"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define los métodos requeridos para almacenar el documento renderizado y los recursos del documento en caché."
type: docs
weight: 20
url: /es/net/groupdocs.conversion.caching/icache/
---
## ICache interface

Define los métodos requeridos para almacenar el documento renderizado y los recursos del documento en caché.

```csharp
public interface ICache
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/icache/getkeys)(string) | Devuelve todas las claves que coinciden con el filtro. |
| [Set](../../groupdocs.conversion.caching/icache/set)(string, object) | Inserta una entrada en la caché. |
| [TryGetValue](../../groupdocs.conversion.caching/icache/trygetvalue)(string, out object) | Obtiene la entrada asociada a esta clave si está presente. |

### Ver también

* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
