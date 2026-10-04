---
title: "MissingDependencyException"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Исключение GroupDocs, выбрасываемое, когда конвертация не может выполниться, потому что зависимая сборка отсутствует в выводе приложения. Документ не является причиной."
type: docs
weight: 1030
url: /ru/net/groupdocs.conversion.exceptions/missingdependencyexception/
---
## MissingDependencyException class

Исключение GroupDocs, выброшенное, когда конвертация не может выполниться, потому что зависимая сборка отсутствует в выводе приложения. Документ не является причиной.

```csharp
public sealed class MissingDependencyException : GroupDocsConversionException
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Конструктор по умолчанию |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Создаёт экземпляр исключения с сообщением |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Создаёт экземпляр исключения с сообщением и передаёт внутреннее исключение |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Создаёт экземпляр исключения, указывая сборку, которую не удалось загрузить |

## Свойства

| Имя | Описание |
| --- | --- |
| [AssemblyName](../../groupdocs.conversion.exceptions/missingdependencyexception/assemblyname) { get; } | Простое имя сборки, которую не удалось загрузить, или null, если оно не может быть определено. |

### См. также

* class [GroupDocsConversionException](../groupdocsconversionexception)
* namespace [GroupDocs.Conversion.Exceptions](../../groupdocs.conversion.exceptions)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
