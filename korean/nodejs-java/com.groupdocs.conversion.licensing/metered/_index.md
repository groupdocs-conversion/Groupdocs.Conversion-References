---
title: "계량식"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Metered 라이선스를 적용하기 위한 메서드를 제공합니다."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion.licensing/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Metered 라이선스를 적용하기 위한 메서드를 제공합니다. **자세히 알아보기**Metered 라이선스에 대한 자세한 내용: [Metered Licensing FAQ][Metered]GroupDocs.Conversion 라이선스에 대한 자세한 내용: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered 키로 제품을 활성화합니다. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 처리된 MB 양을 가져옵니다. |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소모된 크레딧 수를 가져옵니다. |
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


Metered 키로 제품을 활성화합니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키. |
| privateKey | java.lang.String | 개인 키. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


처리된 MB 양을 가져옵니다.

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


소모된 크레딧 수를 가져옵니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytesCount | long |  |

### consumeCreditsBySize(long bytesCount) {#consumeCreditsBySize-long-}
```
public static void consumeCreditsBySize(long bytesCount)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytesCount | long |  |

