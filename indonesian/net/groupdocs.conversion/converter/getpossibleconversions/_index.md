---
title: "GetPossibleConversions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendapatkan konversi yang memungkinkan untuk dokumen sumber."
type: docs
weight: 50
url: /id/net/groupdocs.conversion/converter/getpossibleconversions/
---
## GetPossibleConversions()

Mendapatkan konversi yang memungkinkan untuk dokumen sumber.

```csharp
public PossibleConversions GetPossibleConversions()
```

### Nilai Kembali

Konversi yang mungkin sebagai [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Catatan

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Lihat Juga

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetPossibleConversions(string)

Mendapatkan konversi yang didukung untuk ekstensi dokumen yang diberikan

```csharp
public static PossibleConversions GetPossibleConversions(string extension)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | String | Ekstensi dokumen |

### Nilai Kembali

Konversi yang mungkin untuk ekstensi yang ditentukan sebagai [`PossibleConversions`](../../../groupdocs.conversion.contracts/possibleconversions).

### Catatan

**Learn more**

* Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
* Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

### Contoh

Converter.GetPossibleConversions(".docx")

Converter.GetPossibleConversions("docx")

### Lihat Juga

* class [PossibleConversions](../../../groupdocs.conversion.contracts/possibleconversions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
