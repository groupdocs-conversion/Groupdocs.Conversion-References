---
title: "Cargar"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Configura el documento fuente para la conversión"
type: docs
weight: 10
url: /es/net/groupdocs.conversion/fluentconverter/load/
---
## Load(string) {#load_2}

Configura el documento fuente para la conversión

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Documento de origen |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Configura el conjunto de documentos fuente

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String[] | Matriz de archivos de origen |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Configura la secuencia del documento fuente

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Proveedor de flujo de documento de origen |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Configura el conjunto de secuencias de documentos fuente

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(
    Func<Stream[]> documentStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Proveedor de flujos de documentos de origen |

### Ver también

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
