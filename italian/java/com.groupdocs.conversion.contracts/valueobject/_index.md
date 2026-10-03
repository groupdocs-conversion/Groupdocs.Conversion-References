---
title: "ValueObject"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Classe astratta di oggetto valore."
type: docs
weight: 15
url: /it/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Classe astratta di oggetto valore.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se due istanze di oggetto sono uguali. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Determina se due istanze di oggetto sono uguali. |
|
|  | [hashCode()](#hashCode--) | Funziona come funzione hash predefinita. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Operatore di uguaglianza. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Operatore di disuguaglianza. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se due istanze di oggetto sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | L'oggetto da confrontare con l'oggetto corrente. |
|

**Returns:**
boolean -  true  se l'oggetto specificato è uguale all'oggetto corrente; altrimenti,  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Determina se due istanze di oggetto sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | L'oggetto da confrontare con l'oggetto corrente. |
|

**Returns:**
boolean -  true  se l'oggetto specificato è uguale all'oggetto corrente; altrimenti,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash predefinita.


**Returns:**
int - Un codice hash per l'oggetto corrente.

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Operatore di uguaglianza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Il primo oggetto |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Il secondo oggetto |
|

**Returns:**
boolean -  true  se gli oggetti sono uguali

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Operatore di disuguaglianza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Il primo oggetto |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Il secondo oggetto |
|

**Returns:**
boolean -  true  se gli oggetti non sono uguali

