---
title: "ConvertByPageTo"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Guardar página convertida como flujo"
type: docs
weight: 10
url: /es/net/groupdocs.conversion.fluent/iconversionto/convertbypageto/
---
## IConversionTo.ConvertByPageTo method

Guardar página convertida como flujo

```csharp
public IConversionByPageOptionsOrHandlerSetup ConvertByPageTo(
    Func<SavePageContext, Stream> convertedStreamProvider)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Proveedor de flujo de página de documento convertido El contexto de guardado |

### Valor de retorno

Opciones de página o interfaz de configuración de manejador para continuar construyendo la conversión

### Ver también

* interface [IConversionByPageOptionsOrHandlerSetup](../../iconversionbypageoptionsorhandlersetup)
* class [SavePageContext](../../../groupdocs.conversion/savepagecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
