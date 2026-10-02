---
title: "License"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 10
url: /ar/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

يوفر طرقًا لترخيص المكوّن. تعرف على المزيد حول الترخيص
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License()](#License--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | يرجع true إذا تم تطبيق ترخيص صالح؛ false إذا كان المكوّن يعمل في وضع التقييم. |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | يرخص المكوّن. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | يرخص المكوّن. |
|
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


يرجع true إذا تم تطبيق ترخيص صالح؛ false إذا كان المكوّن يعمل في وضع التقييم.


**Returns:**
منطقي
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


يرخص المكوّن.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing Stream of the license file.
>   using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
>  {
>      GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>      lic.SetLicense(licenseStream);
>  }
>  
>  
> ```

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | دفق الترخيص. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


يرخص المكوّن.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing a path to the license file.
>   string licensePath = "GroupDocs.Conversion.lic";
>  GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
>  lic.SetLicense(licensePath);
>  
>  
> ```

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licensePath | java.lang.String | مسار الترخيص. |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




