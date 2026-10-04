---
title: "Convert"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Convierte el documento de origen. Guarda todo el documento convertido."
type: docs
weight: 20
url: /es/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetStreamProvider | Func`2 | El delegado que guarda el documento convertido en un flujo. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptions | ConvertOptions | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| documentCompleted | Action`1 | Delegado que recibe el flujo del documento convertido. Firma: `Action<ConvertedContext>`. El parámetro [`ConvertedContext`](../../convertedcontext) contiene el flujo del documento convertido y los metadatos. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegado que proporciona el flujo para guardar el documento convertido. Firma: `Func<SaveContext, Stream>`. El parámetro [`SaveContext`](../../savecontext) contiene información sobre la operación de guardado. |
| convertOptionsProvider | Func`2 | Delegado que proporciona opciones de conversión. Firma: `Func<ConvertContext, ConvertOptions>`. El parámetro [`ConvertContext`](../../convertcontext) contiene información sobre la operación de conversión. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegado que proporciona opciones de conversión. Firma: `Func<ConvertContext, ConvertOptions>`. El parámetro [`ConvertContext`](../../convertcontext) contiene información sobre la operación de conversión. |
| documentCompleted | Action`1 | Delegado que recibe el flujo del documento convertido. Firma: `Action<ConvertedContext>`. El parámetro [`ConvertedContext`](../../convertedcontext) contiene el flujo del documento convertido y los metadatos. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento fuente. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegado que proporciona un flujo para guardar cada página convertida. Firma: `Func<SavePageContext, Stream>`. El parámetro [`SavePageContext`](../../savepagecontext) contiene el número de página y la información del documento. |
| convertOptionsProvider | Func`2 | Delegado que proporciona opciones de conversión. Firma: `Func<ConvertContext, ConvertOptions>`. El parámetro [`ConvertContext`](../../convertcontext) contiene información sobre la operación de conversión. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegado que proporciona un flujo para guardar cada página convertida. Firma: `Func<SavePageContext, Stream>`. El parámetro [`SavePageContext`](../../savepagecontext) contiene el número de página y la información del documento. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegado que recibe cada página convertida. Firma: `Action<ConvertedPageContext>`. El parámetro [`ConvertedPageContext`](../../convertedpagecontext) contiene el número de página, el flujo, el nombre del archivo fuente y el tipo de archivo de destino. |
| convertOptions | Action`1 | Las opciones de conversión específicas al tipo de archivo de destino deseado. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegado que proporciona opciones de conversión. Firma: `Func<ConvertContext, ConvertOptions>`. El parámetro [`ConvertContext`](../../convertcontext) contiene información sobre la operación de conversión. |
| documentCompleted | Action`1 | Delegado que recibe cada página convertida. Firma: `Action<ConvertedPageContext>`. El parámetro [`ConvertedPageContext`](../../convertedpagecontext) contiene el número de página, el flujo, el nombre del archivo fuente y el tipo de archivo de destino. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Observaciones

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
