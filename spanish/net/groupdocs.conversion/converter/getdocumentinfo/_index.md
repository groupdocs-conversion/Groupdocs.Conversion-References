---
title: "GetDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Obtiene la información del documento fuente, el recuento de páginas y otras propiedades del documento específicas del tipo de archivo."
type: docs
weight: 40
url: /es/net/groupdocs.conversion/converter/getdocumentinfo/
---
## GetDocumentInfo() {#getdocumentinfo}

Obtiene información del documento fuente: recuento de páginas y otras propiedades del documento específicas del tipo de archivo.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Valor de retorno

Información del documento como [`IDocumentInfo`](../../../groupdocs.conversion.contracts/idocumentinfo).

### Observaciones

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### Ver también

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetDocumentInfo&lt;T&gt;() {#getdocumentinfo_1}

Obtiene información del documento fuente: recuento de páginas y otras propiedades del documento específicas del tipo de archivo.

```csharp
public T GetDocumentInfo<T>()
    where T : IDocumentInfo
```

| Parámetro | Descripción |
| --- | --- |
| T | El tipo específico de información del documento. |

### Valor de retorno

Información del documento como el tipo especificado T.

### Observaciones

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### Ver también

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
