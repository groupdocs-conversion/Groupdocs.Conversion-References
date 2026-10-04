---
title: "ConvertTo"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Guardar documento convertido como archivo"
type: docs
weight: 20
url: /es/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Guardar documento convertido como archivo

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Documento convertido |

### Valor de retorno

Opciones o interfaz de configuración de manejador para continuar construyendo la conversión

### Ver también

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Guardar documento convertido como flujo

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Proveedor de flujo de documento convertido El contexto de guardado |

### Valor de retorno

Opciones o interfaz de configuración de manejador para continuar construyendo la conversión

### Ver también

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
