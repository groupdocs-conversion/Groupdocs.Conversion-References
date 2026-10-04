---
title: "FontTransformation"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Описывает конфигурацию преобразования шрифтов, включая атрибуты шрифта. Преобразования шрифтов применяются после загрузки документа и замены шрифта."
type: docs
weight: 260
url: /ru/net/groupdocs.conversion.contracts/fonttransformation/
---
## FontTransformation class

Описывает конфигурацию преобразования шрифтов, включая атрибуты шрифта. Преобразования шрифтов применяются после загрузки документа и замены шрифта.

```csharp
public class FontTransformation : ValueObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [MatchAnySize](../../groupdocs.conversion.contracts/fonttransformation/matchanysize) { get; } | Если true, сопоставляет любой размер шрифта для оригинального имени шрифта. Если false, сопоставляет точный размер шрифта, указанный в OriginalFont. |
| [MatchAnyStyle](../../groupdocs.conversion.contracts/fonttransformation/matchanystyle) { get; } | Если true, сопоставляет любой стиль шрифта (жирный, курсив, подчеркивание) для оригинального шрифта. Если false, сопоставляет точный стиль шрифта, указанный в OriginalFont. |
| [OriginalFont](../../groupdocs.conversion.contracts/fonttransformation/originalfont) { get; } | Исходная спецификация шрифта для сопоставления и замены. |
| [ReplacementFont](../../groupdocs.conversion.contracts/fonttransformation/replacementfont) { get; } | Спецификация заменяющего шрифта. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/fonttransformation/create)(Font, Font) | Создаёт преобразование шрифта с точным сопоставлением шрифта (размер и стиль должны совпадать). |
| static [CreateByName](../../groupdocs.conversion.contracts/fonttransformation/createbyname)(string, string) | Создаёт преобразование шрифта только по имени, сопоставляя любой размер и стиль. Заменяющий шрифт сохранит размер и стиль оригинального шрифта. |
| static [CreateFlexible](../../groupdocs.conversion.contracts/fonttransformation/createflexible)(Font, Font, bool, bool) | Создаёт преобразование шрифта с гибкими параметрами сопоставления. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Определяет, равны ли два экземпляра объекта. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Определяет, равны ли два экземпляра объекта. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Служит функцией хеширования по умолчанию. |

### См. также

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
