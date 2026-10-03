---
title: "Enumerazione"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Classe di enumerazione generica."
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Classe di enumerazione generica.


TKey
:

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Restituisce tutti i valori dell'enumerazione. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se due istanze di oggetto sono uguali. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Determina se due istanze di oggetto sono uguali. |
|
|  | [hashCode()](#hashCode--) | Funziona come funzione hash predefinita. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Restituisce l'oggetto per chiave. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Restituisce l'oggetto per nome visualizzato. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Confronta l'oggetto corrente con un altro. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Operatore di uguaglianza. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Operatore di disuguaglianza. |
|
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.


**Returns:**
java.lang.String - Rappresentazione della stringa

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Restituisce tutti i valori dell'enumerazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Enumerabile del tipo fornito


T
: Tipo di oggetto enumerato.

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

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Determina se due istanze di oggetto sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | L'oggetto da confrontare con l'oggetto corrente. |
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

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Restituisce l'oggetto per chiave.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | valore | java.lang.String | Il valore |
|

**Returns:**
T - L'oggetto

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Restituisce l'oggetto per nome visualizzato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | Il nome visualizzato |
|

**Returns:**
T - L'oggetto

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Confronta l'oggetto corrente con un altro.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | L'altro oggetto |
|

**Returns:**
int - zero se uguale

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Operatore di uguaglianza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Il primo oggetto |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Il secondo oggetto |
|

**Returns:**
boolean -  true  se gli oggetti sono uguali

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Operatore di disuguaglianza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Il primo oggetto |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Il secondo oggetto |
|

**Returns:**
boolean -  true  se gli oggetti non sono uguali

