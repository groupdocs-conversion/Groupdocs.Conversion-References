---
title: "Metered"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Metered lisansını uygulamak için yöntemler sağlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Metered lisansını uygulamak için yöntemler sağlar. **Daha fazla bilgi**Metered lisanslama hakkında daha fazla bilgi: [Metered Licensing FAQ][Metered]GroupDocs.Conversion lisanslaması hakkında daha fazla bilgi: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered anahtarlarıyla ürünü etkinleştirir. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | İşlenen MB miktarını alır. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Harcanan kredi sayısını alır. |
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


Metered anahtarlarıyla ürünü etkinleştirir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | Genel anahtar. |
| privateKey | java.lang.String | Özel anahtar. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


İşlenen MB miktarını alır.

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


Harcanan kredi sayısını alır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytesCount | long |  |

