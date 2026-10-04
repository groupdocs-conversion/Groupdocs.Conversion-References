---
title: "ConvertTo"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Salva il documento convertito come file"
type: docs
weight: 20
url: /it/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Salva il documento convertito come file

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| fileName | String | Documento convertito |

### Valore restituito

Interfaccia di impostazione delle opzioni o del gestore per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Salva il documento convertito come stream

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Provider di flusso del documento convertito Il contesto di salvataggio |

### Valore restituito

Interfaccia di impostazione delle opzioni o del gestore per continuare la costruzione della conversione

### IConversionConvertOptions

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
