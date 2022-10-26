---
title: Converter
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Inicializa una nueva instancia deConvertergroupdocs.conversion/converter clase.
type: docs
weight: 10
url: /es/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(Func<Stream> document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El método que devuelve un flujo legible. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*document* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El método que devuelve un flujo legible. |
| settings | Func`1 | La configuración del convertidor. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | Func`1 | Los métodos que devuelven las opciones de carga de documentos. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | Func`1 | Los métodos que devuelven las opciones de carga de documentos. |
| settings | Func`1 | La configuración del convertidor. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | Func`2 | Los métodos que devuelven las opciones de carga de documentos. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | Func`2 | Los métodos que devuelven las opciones de carga de documentos. |
| settings | Func`1 | La configuración del convertidor. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |
| settings | Func`1 | La configuración del convertidor. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |
| loadOptions | Func`1 | Los métodos que devuelven las opciones de carga de documentos. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |
| loadOptions | Func`1 | Los métodos que devuelven las opciones de carga de documentos. |
| settings | Func`1 | La configuración del convertidor. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |
| loadOptions | Func`2 | Los métodos que devuelven las opciones de carga de documentos. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Inicializa una nueva instancia de[`Converter`](../../converter) clase.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |
| loadOptions | Func`2 | Los métodos que devuelven las opciones de carga de documentos. |
| settings | Func`1 | La configuración del convertidor. |

### Observaciones

**Aprende más**

* Más información sobre cómo cargar y convertir documentos almacenados en FTP, Amazon S3 Storage, Windows Azure o cualquier otro almacenamiento de terceros: [Cargando documento de diferentes fuentes](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Más información sobre las opciones de carga de documentos según el tipo de archivo: [Opciones de carga para diferentes tipos de documentos](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Inicializa una nueva instancia de[`Converter`](../../converter) clase para configuración de conversión fluida.

```csharp
public Converter()
```

### Observaciones

Ejemplo de uso de conversión fluida:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### Ver también

* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
