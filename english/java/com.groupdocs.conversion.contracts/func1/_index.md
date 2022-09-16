---
title: Func1
second_title: GroupDocs.Conversion for Java API Reference
description: Encapsulates a method that has one parameter and returns a value of the type specified by the  parameter.
type: docs
weight: 13
url: /java/com.groupdocs.conversion.contracts/func1/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class Func1<T,TResult> extends System.MulticastDelegate
```

Encapsulates a method that has one parameter and returns a value of the type specified by the  parameter.
## Constructors

| Constructor | Description |
| --- | --- |
| [Func1()](#Func1--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(T arg)](#invoke-T-) | Method |
| [beginInvoke(T arg, System.AsyncCallback callback, Object state)](#beginInvoke-T-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### Func1() {#Func1--}
```
public Func1()
```


### invoke(T arg) {#invoke-T-}
```
public abstract TResult invoke(T arg)
```


Method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg | T | argument |

**Returns:**
TResult - result
### beginInvoke(T arg, System.AsyncCallback callback, Object state) {#beginInvoke-T-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(T arg, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg | T |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final System.IO.Stream endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
com.aspose.ms.System.IO.Stream
