---
title: "método get_hash_code"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Sirve como la función hash predeterminada."
type: docs
url: /es/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Sirve como la función hash predeterminada.

Los componentes de Array, list y dictionary se hashéan por su contenido, coincidiendo con la forma en que la igualdad los compara, de modo que dos objetos que son iguales también generan el mismo hash y pueden usarse como claves de diccionario o miembros de conjunto.

Esto NO se extiende a un componente que sea otro `System.Collections.IEnumerable`: dicho componente se hashéa por referencia, y uno expuesto como un iterador perezoso produce un valor diferente en cada acceso, por lo que un objeto que lo contiene no es utilizable como clave en absoluto. Las colecciones anidadas se comparan y hashéan de manera similar por referencia en lugar de recursivamente.

La otra consecuencia es que mutar una colección que expone un objeto de valor —añadiendo a una lista de páginas, o escribiendo en una matriz de nombres de diseño— cambia el hash de ese objeto, de modo que una instancia ya almacenada en un contenedor de hash se vuelve inaccesible. Trate un objeto de valor como congelado una vez que se haya usado como clave.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Ver también
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
