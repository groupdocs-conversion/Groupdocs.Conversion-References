---
title: "FileCache"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Datei‑Cache‑Verhalten."
type: docs
weight: 10
url: /de/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Verhalten des Dateicachings. Bedeutet, dass der Cache im Dateisystem gespeichert wird **Learn more** Mehr über Caching und die Optimierung der Leistung des Konvertierungsprozesses: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Erstellt eine neue Instanz der Klasse FileCache |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Fügt einen Cache-Eintrag in den Cache ein. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Liefert den Eintrag, der mit diesem Schlüssel verknüpft ist, falls vorhanden. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Gibt alle Schlüssel zurück, die dem Filter entsprechen. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Erstellt eine neue Instanz der Klasse FileCache


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | cachePath | java.lang.String | Relativer oder absoluter Pfad, an dem der Dokument-Cache gespeichert wird |
|

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Fügt einen Cache-Eintrag in den Cache ein.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Schlüssel | java.lang.String | Ein eindeutiger Bezeichner für den Cache-Eintrag. |
|
|  | Wert | java.lang.Object | Das einzufügende Objekt. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Liefert den Eintrag, der mit diesem Schlüssel verknüpft ist, falls vorhanden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Schlüssel | java.lang.String | Ein Schlüssel, der den angeforderten Eintrag identifiziert. |
|

**Returns:**
java.lang.Object – Objekt, wenn der Schlüssel gefunden wurde, sonst null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Gibt alle Schlüssel zurück, die dem Filter entsprechen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Filter | java.lang.String | Der zu verwendende Filter. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Schlüssel, die dem Filter entsprechen.

