---
title: "Счётный"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Предоставляет методы для применения счётной лицензии."
type: docs
weight: 11
url: /ru/java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Предоставляет методы для применения
[Metered](../https://purchase.groupdocs.com/faqs/licensing/metered)
лицензии.
**Learn more** More about Metered licensing: [Metered Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing/metered) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metered()](#Metered--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Активирует продукт с счётными ключами. |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Получает количество обработанных мегабайт. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Получает количество использованных кредитов. |
|
| [increaseBytesCount(long bytesCount)](#increaseBytesCount-long-) |  |
| [consumeCreditsBySize(long bytesCount)](#consumeCreditsBySize-long-) |  |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Активирует продукт с счётными ключами.

<br />

*** ** * ** ***

> ```
>  Following example demonstrates how to activate product with Metered keys.
>   string publicKey = "Public Key";
>  string privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.SetMeteredKey(publicKey, privateKey);
>  
>  
> ```

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | publicKey | java.lang.String | Публичный ключ. |
|
|  | privateKey | java.lang.String | Приватный ключ. |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Получает количество обработанных мегабайт.

<br />

*** ** * ** ***

> ```
>   Following example demonstrates how to retrieve amount of MBs processed.
>     string publicKey = "Public Key";
>   string privateKey = "Private Key";
>
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal mbProcessed = Metered.GetConsumptionQuantity();
>   
>   
> ```

<br />



**Returns:**
java.math.BigDecimal
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Получает количество использованных кредитов.

<br />

*** ** * ** ***

> ```
>   Following example demonstrates how to retrieve count of credits consumed.
>     string publicKey = "Public Key";
>   string privateKey = "Private Key";
>
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal creditsConsumed = Metered.GetConsumptionCredit();
>   
>   
> ```

<br />



**Returns:**
java.math.BigDecimal
### increaseBytesCount(long bytesCount) {#increaseBytesCount-long-}
```
public static void increaseBytesCount(long bytesCount)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bytesCount | long |  |

