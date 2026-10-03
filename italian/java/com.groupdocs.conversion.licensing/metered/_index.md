---
title: "A consumo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Fornisce metodi per applicare la licenza a consumo."
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per applicare
[Metered](../https://purchase.groupdocs.com/faqs/licensing/metered)
licenza.
**Learn more** More about Metered licensing: [Metered Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing/metered) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Attiva il prodotto con chiavi a consumo. |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la quantità di MB elaborati. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Recupera il conteggio dei crediti consumati. |
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


Attiva il prodotto con chiavi a consumo.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | publicKey | java.lang.String | La chiave pubblica. |
|
|  | privateKey | java.lang.String | La chiave privata. |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Recupera la quantità di MB elaborati.

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


Recupera il conteggio dei crediti consumati.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytesCount | long |  |

