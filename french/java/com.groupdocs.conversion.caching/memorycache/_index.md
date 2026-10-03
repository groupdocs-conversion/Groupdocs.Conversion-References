---
title: "MemoryCache"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Comportement de mise en cache en mémoire."
type: docs
weight: 11
url: /fr/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Comportement de mise en cache en mémoire. Signifie que le cache est stocké en mémoire **Learn more** Plus d'informations sur la mise en cache et l'optimisation des performances du processus de conversion : [Mise en cache des résultats de conversion](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | Crée une nouvelle instance de la classe MemoryCache |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Insère une entrée de cache dans le cache. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Obtient l'entrée associée à cette clé si elle est présente. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Renvoie toutes les clés correspondant au filtre. |
|
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Crée une nouvelle instance de la classe MemoryCache


### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Insère une entrée de cache dans le cache.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | clé | java.lang.String | Un identifiant unique pour l'entrée du cache. |
|
|  | valeur | java.lang.Object | L'objet à insérer. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Obtient l'entrée associée à cette clé si elle est présente.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | clé | java.lang.String | Une clé identifiant l'entrée demandée. |
|

**Returns:**
java.lang.Object - La valeur trouvée ou null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Renvoie toutes les clés correspondant au filtre.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filtre | java.lang.String | Le filtre à utiliser. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Clés correspondant au filtre.

