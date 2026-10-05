---
title: "Enumeratie"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Generieke enumeratieklasse."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Generieke enumeratieklasse.

TKey :
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
| [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Geeft alle enumeratiewaarden terug. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of twee objectinstanties gelijk zijn. |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Bepaalt of twee objectinstanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als de standaard hash-functie. |
| [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Retourneert object op sleutel. |
| [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Retourneert object op weergavenaam. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Vergelijkt het huidige object met een ander. |
| [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Gelijkheidsoperator. |
| [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Ongelijkheidsoperator. |
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.

**Returns:**
java.lang.String - Stringrepresentatie
### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Geeft alle enumeratiewaarden terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Enumeratie van het opgegeven type

T : Genummerd objecttype.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of twee objectinstanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met het huidige object. |

**Returns:**
boolean -  true  als het opgegeven object gelijk is aan het huidige object; anders,  false .
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Bepaalt of twee objectinstanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Het object om te vergelijken met het huidige object. |

**Returns:**
boolean -  true  als het opgegeven object gelijk is aan het huidige object; anders,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als de standaard hash-functie.

**Returns:**
int - Een hashcode voor het huidige object.
### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Retourneert object op sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| value | java.lang.String | De waarde |

**Returns:**
T - Het object
### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Retourneert object op weergavenaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| displayName | java.lang.String | De weergavenaam |

**Returns:**
T - Het object
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Vergelijkt het huidige object met een ander.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het andere object |

**Returns:**
int - nul als gelijk
### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Gelijkheidsoperator.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Het eerste object |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Het tweede object |

**Returns:**
boolean -  true  als objecten gelijk zijn
### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Ongelijkheidsoperator.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Het eerste object |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Het tweede object |

**Returns:**
boolean -  true  als objecten niet gelijk zijn
