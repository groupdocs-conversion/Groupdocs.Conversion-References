---
title: "Converter"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Inicializa una nueva instancia de la clase Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /es/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Inicializa una nueva instancia de la clase [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | El método que devuelve un flujo legible. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzada cuando *sourceStreamProvider* es nulo. |

### Observaciones

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Inicializa una nueva instancia de la clase [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | El método que devuelve un flujo legible. |
| settings | Func`1 | La configuración del Converter. |

### Observaciones

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Inicializa una nueva instancia de la clase [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | Func`2 | Delegado que proporciona opciones de carga para el documento. Firma: `Func<LoadContext, LoadOptions>`. El parámetro [`LoadContext`](../../loadcontext) contiene información sobre el documento que se está cargando. |
| settings | Func`1 | La configuración del Converter. |

### Observaciones

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Inicializa una nueva instancia de la clase [`Converter`](../../converter) con eventos de conversión explícitos.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | Func`2 | Delegado que proporciona opciones de carga para el documento. |
| settings | Func`1 | La configuración del Converter. |
| events | Func`1 | Delegado que proporciona [`ConversionEvents`](../../conversionevents) agregados registrados durante la vida útil del conversor. |

### Ver también

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Inicializa una nueva instancia de la clase [`Converter`](../../converter) con eventos de conversión explícitos.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | El método que devuelve un flujo legible. |
| settings | Func`1 | La configuración del Converter. |
| events | Func`1 | Delegado que proporciona [`ConversionEvents`](../../conversionevents) agregados registrados durante la vida útil del conversor. |

### Ver también

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Inicializa una nueva instancia de la clase [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento fuente. |

### Observaciones

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Inicializa una nueva instancia de la clase [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento fuente. |
| settings | Func`1 | La configuración del Converter. |

### Observaciones

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Inicializa una nueva instancia de la clase [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento fuente. |
| loadOptions | Func`2 | Delegado que proporciona opciones de carga para el documento. Firma: `Func<LoadContext, LoadOptions>`. El parámetro [`LoadContext`](../../loadcontext) contiene información sobre el documento que se está cargando. |
| settings | Func`1 | La configuración del Converter. |

### Observaciones

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Inicializa una nueva instancia de la clase [`Converter`](../../converter) con eventos de conversión explícitos.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento fuente. |
| loadOptions | Func`2 | Delegado que proporciona opciones de carga para el documento. |
| settings | Func`1 | La configuración del Converter. |
| events | Func`1 | Delegado que proporciona [`ConversionEvents`](../../conversionevents) agregados registrados durante la vida útil del conversor. |

### Ver también

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Inicializa una nueva instancia de la clase [`Converter`](../../converter) con eventos de conversión explícitos.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento fuente. |
| settings | Func`1 | La configuración del Converter. |
| events | Func`1 | Delegado que proporciona [`ConversionEvents`](../../conversionevents) agregados registrados durante la vida útil del conversor. |

### Ver también

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
