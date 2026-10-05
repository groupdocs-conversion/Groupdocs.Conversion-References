---
title: "FileCache"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Поведение кэширования файлов."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Поведение кэширования в файлах. Означает, что кэш хранится в файловой системе **Learn more**Подробнее о кэшировании и оптимизации производительности процесса конвертации: [Caching conversion results][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Создаёт новый экземпляр класса FileCache. |
## Методы

| Метод | Описание |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Вставляет запись в кэш. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Получает запись, связанную с этим ключом, если она присутствует. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Возвращает все ключи, соответствующие фильтру. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Создаёт новый экземпляр класса FileCache.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cachePath | java.lang.String | Относительный или абсолютный путь, где будет храниться кэш документов. |

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Вставляет запись в кэш.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Уникальный идентификатор записи кэша. |
| значение | java.lang.Object | Объект для вставки. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Получает запись, связанную с этим ключом, если она присутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ, идентифицирующий запрашиваемую запись. |

**Returns:**
java.lang.Object - Объект, если ключ найден, иначе null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Возвращает все ключи, соответствующие фильтру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| фильтр | java.lang.String | Фильтр для использования. |

**Returns:**
java.lang.Iterable<java.lang.String> - Ключи, соответствующие фильтру.
