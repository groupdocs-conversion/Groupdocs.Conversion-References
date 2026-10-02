---
title: "Metered"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يوفر طرقًا لتطبيق ترخيص Metered."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا لتطبيق
[Metered](../https://purchase.groupdocs.com/faqs/licensing/metered)
الترخيص.
**Learn more** More about Metered licensing: [Metered Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing/metered) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يفعل المنتج بمفاتيح Metered. |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | يسترجع مقدار الميجابايتات المعالجة. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | يسترجع عدد الاعتمادات المستهلكة. |
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


يفعل المنتج بمفاتيح Metered.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | publicKey | java.lang.String | المفتاح العام. |
|
|  | privateKey | java.lang.String | المفتاح الخاص. |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


يسترجع مقدار الميجابايتات المعالجة.

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


يسترجع عدد الاعتمادات المستهلكة.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bytesCount | long |  |

