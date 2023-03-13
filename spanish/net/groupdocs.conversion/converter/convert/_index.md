---
title: Convert
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Convierte el documento de origen. Guarda todo el documento convertido.
type: docs
weight: 20
url: /es/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El delegado que guarda el documento convertido en una secuencia. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El delegado que guarda el documento convertido en una secuencia. |
| documentCompleted | Action`2 | El delegado que recibe el flujo de documentos convertido. El flujo de contenido del archivoEl nombre del archivo |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El delegado que guarda el documento convertido en una secuencia. |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`1 | El delegado que guarda el documento convertido en una secuencia. |
| documentCompleted | Action`2 | El delegado que recibe el flujo de documentos convertido. El flujo de contenido del archivoEl nombre del archivo |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda el documento convertido en una secuencia. El tipo del archivo fuente |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda el documento convertido en una secuencia. El tipo del archivo fuente |
| documentCompleted | Action`2 | El delegado que recibe el flujo de documentos convertido. El flujo de contenido del archivoEl nombre del archivo |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda el documento convertido en una secuencia. El tipo del archivo fuente |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda el documento convertido en una secuencia. El tipo del archivo fuente |
| documentCompleted | Action`2 | El delegado que recibe el flujo de documentos convertido. El flujo de contenido del archivoEl nombre del archivo |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo al documento de origen. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda el documento convertido en una secuencia. Número de página |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda la página del documento convertido en una secuencia. Número de página |
| documentCompleted | Action`3 | El delegado que recibe el flujo de página del documento convertido. Número de páginaEl flujo de contenido del archivoEl nombre del archivo |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda el documento convertido en una secuencia. Número de página |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`2 | El delegado que guarda la página del documento convertido en una secuencia. Número de página |
| documentCompleted | Action`3 | El delegado que recibe el flujo de página del documento convertido. Número de páginaEl flujo de contenido del archivoEl nombre del archivo |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`3 | El delegado que guarda el documento convertido en una secuencia. Número de página |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`3 | El delegado que guarda la página del documento convertido en una secuencia. Número de páginaTipo de archivo |
| documentCompleted | Action`3 | El delegado que recibe el flujo de página del documento convertido. Número de páginaEl flujo de contenido del archivoEl nombre del archivo |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`3 | El delegado que guarda el documento convertido en una secuencia. Número de páginaTipo de archivo |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Func`3 | El delegado que guarda la página del documento convertido en una secuencia. Número de páginaTipo de archivo |
| documentCompleted | Action`3 | El delegado que recibe el flujo de página del documento convertido. Número de páginaEl flujo de contenido del archivoEl nombre del archivo |
| convertOptionsProvider | Func`3 | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. El nombre del archivoEl tipo de archivo |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
