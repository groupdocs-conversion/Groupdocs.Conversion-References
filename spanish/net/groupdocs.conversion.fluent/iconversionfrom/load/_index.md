---
title: "Cargar"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Establecer nombre de archivo del documento fuente"
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Establecer nombre de archivo del documento fuente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Documento de origen |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Establecer matriz de documentos fuente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String[] | Conjunto de documentos de origen |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Establecer flujo del documento fuente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Proveedor de flujo de documento de origen |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Si la validación de la configuración del convertidor falla, se lanzará esta excepción |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Establecer matriz de flujos de documentos fuente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Proveedor de flujos de documentos de origen |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Si la validación de la configuración del convertidor falla, se lanzará esta excepción |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
