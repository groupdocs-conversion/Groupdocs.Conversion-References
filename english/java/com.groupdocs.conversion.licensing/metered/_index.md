---
title: Metered
second_title: GroupDocs.Conversion for Java API Reference
description: Provides methods for applying Metered license.
type: docs
weight: 11
url: /java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods for applying  [Metered][]  license. **Learn more**More about Metered licensing: [Metered Licensing FAQ][Metered]More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activates product with Metered keys. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Retrieves amount of MBs processed. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves count of credits consumed. |
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


Activates product with Metered keys.

--------------------

> ```
> Following example demonstrates how to activate product with Metered keys.
>  
>  string publicKey = "Public Key";
>  string privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.SetMeteredKey(publicKey, privateKey);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | The public key. |
| privateKey | java.lang.String | The private key. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Retrieves amount of MBs processed.

--------------------

> ```
> Following example demonstrates how to retrieve amount of MBs processed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal mbProcessed = Metered.GetConsumptionQuantity();
> ```

**Returns:**
java.math.BigDecimal
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Retrieves count of credits consumed.

--------------------

> ```
> Following example demonstrates how to retrieve count of credits consumed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal creditsConsumed = Metered.GetConsumptionCredit();
> ```

**Returns:**
java.math.BigDecimal
### increaseBytesCount(long bytesCount) {#increaseBytesCount-long-}
```
public static void increaseBytesCount(long bytesCount)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytesCount | long |  |

