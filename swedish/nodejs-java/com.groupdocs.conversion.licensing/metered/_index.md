---
title: "Metered"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Tillhandahåller metoder för att tillämpa Metered‑licens."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller metoder för att tillämpa  [Metered][]  licens. **Läs mer**Mer om Metered‑licensiering: [Metered Licensing FAQ][Metered]Mer om GroupDocs.Conversion‑licensiering: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aktiverar produkten med Metered‑nycklar. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar mängden MB som har bearbetats. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar antalet förbrukade krediter. |
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


Aktiverar produkten med Metered‑nycklar.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | java.lang.String | Den offentliga nyckeln. |
| privateKey | java.lang.String | Den privata nyckeln. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Hämtar mängden MB som har bearbetats.

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


Hämtar antalet förbrukade krediter.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytesCount | long |  |

