---
title: Convert
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Convierte el documento de origen. Guarda todo el documento convertido.
type: docs
weight: 20
url: /es/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStream | El delegado que guarda el documento convertido en una secuencia. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStream | El delegado que guarda el documento convertido en una secuencia. |
| documentCompleted | ConvertedDocumentStream | El delegado que recibe el flujo de documentos convertidos. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStream | El delegado que guarda el documento convertido en una secuencia. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStream | El delegado que guarda el documento convertido en una secuencia. |
| documentCompleted | ConvertedDocumentStream | El delegado que recibe el flujo de documentos convertidos. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | El delegado que guarda el documento convertido en una secuencia. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | El delegado que guarda el documento convertido en una secuencia. |
| documentCompleted | ConvertedDocumentStream | El delegado que recibe el flujo de documentos convertidos. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | El delegado que guarda el documento convertido en una secuencia. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

Convierte el documento de origen. Guarda todo el documento convertido.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | El delegado que guarda el documento convertido en una secuencia. |
| documentCompleted | ConvertedDocumentStream | El delegado que recibe el flujo de documentos convertidos. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
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

## Convert(SavePageStream, ConvertOptions) {#convert_11}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStream | El delegado que guarda el documento convertido en una secuencia. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStream | El delegado que guarda la página del documento convertido en una secuencia. |
| documentCompleted | ConvertedPageStream | El delegado que recibe el flujo de página del documento convertido. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStream | El delegado que guarda el documento convertido en una secuencia. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStream | El delegado que guarda la página del documento convertido en una secuencia. |
| documentCompleted | ConvertedPageStream | El delegado que recibe el flujo de página del documento convertido. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStreamForFileType | El delegado que guarda el documento convertido en una secuencia. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStreamForFileType | El delegado que guarda la página del documento convertido en una secuencia. |
| documentCompleted | ConvertedPageStream | El delegado que recibe el flujo de página del documento convertido. |
| convertOptions | ConvertOptions | Las opciones de conversión específicas para el tipo de archivo de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStreamForFileType | El delegado que guarda el documento convertido en una secuencia. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

Convierte el documento de origen. Guarda el documento convertido página por página.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | SavePageStreamForFileType | El delegado que guarda la página del documento convertido en una secuencia. |
| documentCompleted | ConvertedPageStream | El delegado que recibe el flujo de página del documento convertido. |
| convertOptionsProvider | ConvertOptionsProvider | Proveedor de opciones de conversión. Se llamará para cada conversión para proporcionar opciones de conversión específicas al tipo de documento de destino deseado. |

### Observaciones

**Aprende más**

* Más sobre escenarios básicos de conversión de documentos: [Cómo convertir documentos en 3 pasos](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casos de uso de conversión, configuraciones avanzadas y personalizaciones: [Convertir documento con configuración avanzada](https://docs.groupdocs.com/display/conversionnet/Converting)

### Ver también

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* espacio de nombres [GroupDocs.Conversion](../../converter)
* asamblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
