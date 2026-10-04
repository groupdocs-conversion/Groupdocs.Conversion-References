---
title: "MissingDependencyException"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Eccezione GroupDocs generata quando una conversione non può essere eseguita perché un assembly di cui dipende non è presente nell'output dell'applicazione. Il documento non è responsabile."
type: docs
weight: 1030
url: /it/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

Eccezione GroupDocs generata quando una conversione non può essere eseguita perché un assembly di cui dipende non è presente nell'output dell'applicazione. Il documento non è in colpa.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Costruttore predefinito |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Crea un'istanza di eccezione con un messaggio |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Crea un'istanza di eccezione con un messaggio e propaga l'eccezione interna |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Crea un'istanza di eccezione indicando l'assembly che non è stato caricato |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | Il nome semplice dell'assembly che non è stato caricato, o null quando non può essere determinato. |

### IConversionConvertOptions

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
