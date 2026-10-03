---
title: "FileCache"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Comportamento della cache su file."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Comportamento della cache su file. Significa che la cache è memorizzata sul file system **Learn more** Ulteriori informazioni su caching e ottimizzazione delle prestazioni del processo di conversione: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Crea una nuova istanza della classe FileCache |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserisce una voce nella cache. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Ottiene la voce associata a questa chiave, se presente. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Restituisce tutte le chiavi che corrispondono al filtro. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Crea una nuova istanza della classe FileCache


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cachePath | java.lang.String | Percorso relativo o assoluto dove verrà memorizzata la cache dei documenti |
|

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Inserisce una voce nella cache.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | chiave | java.lang.String | Un identificatore univoco per la voce della cache. |
|
|  | valore | java.lang.Object | L'oggetto da inserire. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Ottiene la voce associata a questa chiave, se presente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | chiave | java.lang.String | Una chiave che identifica la voce richiesta. |
|

**Returns:**
java.lang.Object - Oggetto se la chiave è stata trovata, altrimenti null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Restituisce tutte le chiavi che corrispondono al filtro.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filtro | java.lang.String | Il filtro da utilizzare. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Chiavi corrispondenti al filtro.

