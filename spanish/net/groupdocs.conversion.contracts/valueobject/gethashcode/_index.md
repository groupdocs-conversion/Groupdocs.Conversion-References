---
title: "GetHashCode"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Sirve como la función hash predeterminada."
type: docs
weight: 20
url: /es/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

Sirve como la función hash predeterminada.

```csharp
public override int GetHashCode()
```

### Valor de retorno

Un código hash para el objeto actual.

### Observaciones

Los componentes de matriz, lista y diccionario se hashizan por su contenido, coincidiendo con la forma en que la igualdad los compara, de modo que dos objetos que son iguales también generan el mismo hash y pueden usarse como claves de diccionario o miembros de conjunto. Esto NO se extiende a un componente que sea otro IEnumerable: dicho componente se hashiza por referencia, y uno expuesto como un iterador perezoso produce un valor diferente en cada acceso, por lo que un objeto que lo contiene no es utilizable como clave en absoluto. Las colecciones anidadas se comparan y hashizan de manera similar por referencia en lugar de recursivamente. La otra consecuencia es que mutar una colección que expone un objeto de valor —agregar a una lista de páginas o escribir en una matriz de nombres de diseño— cambia el hash de ese objeto, de modo que una instancia ya almacenada en un contenedor de hash se vuelve inaccesible. Trate un objeto de valor como congelado una vez que se haya usado como clave.

### Ver también

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
