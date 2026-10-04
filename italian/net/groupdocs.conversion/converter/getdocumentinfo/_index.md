---
title: "GetDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Ottiene le informazioni del documento sorgente, il conteggio delle pagine e altre proprietà del documento specifiche per il tipo di file."
type: docs
weight: 40
url: /it/net/groupdocs.conversion/converter/getdocumentinfo/
---
## GetDocumentInfo() {#getdocumentinfo}

Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Valore restituito

Informazioni sul documento come [`IDocumentInfo`](../../../groupdocs.conversion.contracts/idocumentinfo).

### Osservazioni

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### IConversionConvertOptions

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetDocumentInfo&lt;T&gt;() {#getdocumentinfo_1}

Ottiene le informazioni del documento sorgente - conteggio delle pagine e altre proprietà del documento specifiche del tipo di file.

```csharp
public T GetDocumentInfo<T>()
    where T : IDocumentInfo
```

| Parameter | Descrizione |
| --- | --- |
| T | Il tipo specifico di informazioni sul documento. |

### Valore restituito

Informazioni sul documento come il tipo specificato T.

### Osservazioni

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### IConversionConvertOptions

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
