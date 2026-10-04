---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получает возможные варианты конвертации для исходного документа."
type: docs
weight: 50
url: /ru/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Получает возможные варианты конвертации для исходного документа.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Возвращаемое значение

Возможные конвертации как [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Примечания

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### См. также

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Получает поддерживаемые преобразования для указанного расширения документа

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение документа |

### Возвращаемое значение

Возможные конвертации для указанного расширения как [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Примечания

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Примеры

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### См. также

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
