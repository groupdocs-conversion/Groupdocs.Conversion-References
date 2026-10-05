---
title: "Lisans"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Bileşeni lisanslamak için yöntemler sağlar. Lisanslama hakkında daha fazla bilgi edinmek için  [here][] .

**Learn more**More about licensing: [GroupDocs Licensing FAQ][here]More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing][]


[here]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isLicensed()](#isLicensed--) | Geçerli bir lisans uygulanmışsa true döndürür; bileşen değerlendirme modunda çalışıyorsa false döndürür. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
| [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Bileşeni lisanslar. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
| [resetLicense()](#resetLicense--) |  |
### License() {#License--}
```
public License()
```


### isLicensed() {#isLicensed--}
```
public boolean isLicensed()
```


Geçerli bir lisans uygulanmışsa true döndürür; bileşen değerlendirme modunda çalışıyorsa false döndürür.

**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Bileşeni lisanslar.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseStream | com.aspose.ms.System.IO.Stream | Lisans akışı. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Bileşeni lisanslar.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licensePath | java.lang.String | Lisans yolu. |

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




