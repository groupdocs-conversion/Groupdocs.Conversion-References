---
title: OnConversionCompleted
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Ricevi lo stream della pagina convertita. Verrà attivato solo se ConvertToconvertedStreamProvider è impostato.
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Ricevi lo stream della pagina convertita. Verrà attivato solo se "ConvertTo(convertedStreamProvider)" è impostato.

```csharp
public IConversionConvertOrCompress OnConversionCompleted(
    Action<int, Stream, string> convertedPageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| convertedPageStream | Action`3 | Provider del flusso di pagine convertito Il nome del file |

### Valore di ritorno

Interfaccia per continuare la costruzione della conversione

### Guarda anche

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* spazio dei nomi [GroupDocs.Conversion.Fluent](../../iconversionbypagecompleted)
* assemblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
