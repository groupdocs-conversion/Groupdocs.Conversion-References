---
title: "FileCache"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Comportement de mise en cache des fichiers."
type: docs
weight: 10
url: /fr/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Comportement de mise en cache sur le système de fichiers. Signifie que le cache est stocké sur le système de fichiers **Learn more** Plus d'informations sur la mise en cache et l'optimisation des performances du processus de conversion : [Mise en cache des résultats de conversion](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Crée une nouvelle instance de la classe FileCache |
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
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Crée une nouvelle instance de la classe FileCache


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cachePath | java.lang.String | Chemin relatif ou absolu où le cache du document sera stocké |
|

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
java.lang.Object - Objet si la clé a été trouvée sinon null.

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

