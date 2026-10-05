---
title: "라이선스"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "구성 요소에 라이선스를 적용하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

구성 요소에 라이선스를 적용하기 위한 메서드를 제공합니다. 라이선스에 대해 자세히 알아보려면  [here][] .

**Learn more**More about licensing: [GroupDocs Licensing FAQ][here]More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing][]


[here]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isLicensed()](#isLicensed--) | 유효한 라이선스가 적용된 경우 true를 반환하고, 구성 요소가 평가 모드로 실행 중인 경우 false를 반환합니다. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
| [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


유효한 라이선스가 적용된 경우 true를 반환하고, 구성 요소가 평가 모드로 실행 중인 경우 false를 반환합니다.

**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


구성 요소에 라이선스를 적용합니다.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing Stream of the license file.
>  
>  using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
>  {
>      GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>      lic.SetLicense(licenseStream);
>  }
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseStream | com.aspose.ms.System.IO.Stream | 라이선스 스트림입니다. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


구성 요소에 라이선스를 적용합니다.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing a path to the license file.
>  
>  string licensePath = "GroupDocs.Conversion.lic";
>  GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>  lic.SetLicense(licensePath);
> ```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licensePath | java.lang.String | 라이선스 경로입니다. |

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




