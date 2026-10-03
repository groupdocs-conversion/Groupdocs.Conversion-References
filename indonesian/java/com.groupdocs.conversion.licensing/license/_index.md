---
title: "License"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Menyediakan metode untuk melisensikan komponen."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Menyediakan metode untuk melisensikan komponen. Pelajari lebih lanjut tentang pelisensian
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | Mengembalikan true jika lisensi yang valid telah diterapkan; false jika komponen berjalan dalam mode evaluasi. |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Melisensikan komponen. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Melisensikan komponen. |
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


Mengembalikan true jika lisensi yang valid telah diterapkan; false jika komponen berjalan dalam mode evaluasi.


**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Melisensikan komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | Aliran lisensi. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Melisensikan komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licensePath | java.lang.String | Jalur lisensi. |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




