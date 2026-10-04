---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Описывает одну замену шрифта, произошедшую при загрузке или рендеринге исходного документа. Экземпляры передаются в OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /ru/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Описывает одну замену шрифта, произошедшую при загрузке или рендеринге исходного документа. Экземпляры передаются в [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Создаёт новый [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Свойства

| Имя | Описание |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Имя шрифта, на который ссылается исходный документ, но недоступного для конвейера конвертации. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Сообщение о замене точно так, как оно сообщается конвейером преобразования, дословно и без разбора. Для документов, которые структурно раскрывают имена шрифтов, это может быть `null` (используйте [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); для остальных оно содержит полное человекочитаемое описание, в котором указаны как отсутствующий, так и заменяющий шрифт. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Имя файла исходного документа, который конвертируется. Когда источник предоставлен как поток, который не является FileStream, здесь содержится сгенерированный идентификатор вместо реального имени файла. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Имя шрифта, используемого в качестве замены. Может быть `null` для документов, движок которых сообщает о замене только в виде описательного текста — в этом случае читайте [`Reason`](./reason). |

### См. также

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
