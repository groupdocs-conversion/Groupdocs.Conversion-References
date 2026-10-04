---
title: "MissingDependencyException"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Excepción de GroupDocs lanzada cuando una conversión no puede ejecutarse porque un ensamblado del que depende no está presente en la salida de la aplicación. El documento no es responsable."
type: docs
weight: 1030
url: /es/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

Excepción de GroupDocs lanzada cuando una conversión no puede ejecutarse porque una ensambladura de la que depende no está presente en la salida de la aplicación. El documento no es el culpable.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Constructor predeterminado |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Crea una instancia de excepción con un mensaje |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Crea una instancia de excepción con un mensaje y propaga la excepción interna |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Crea una instancia de excepción nombrando el ensamblado que no se pudo cargar |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | El nombre simple del ensamblado que no se pudo cargar, o null cuando no se pudo determinar. |

### Ver también

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
