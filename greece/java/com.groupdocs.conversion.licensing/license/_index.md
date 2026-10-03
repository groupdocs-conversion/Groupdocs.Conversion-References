---
title: "Άδεια"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Παρέχει μεθόδους για την αδειοδότηση του στοιχείου."
type: docs
weight: 10
url: /el/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Παρέχει μεθόδους για την άδεια του στοιχείου. Μάθετε περισσότερα για την αδειοδότηση
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | Επιστρέφει true εάν έχει εφαρμοστεί έγκυρη άδεια; false εάν το στοιχείο λειτουργεί σε λειτουργία αξιολόγησης. |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Αδειοδοτεί το στοιχείο. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Αδειοδοτεί το στοιχείο. |
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


Επιστρέφει true εάν έχει εφαρμοστεί έγκυρη άδεια; false εάν το στοιχείο λειτουργεί σε λειτουργία αξιολόγησης.


**Returns:**
boolean
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Αδειοδοτεί το στοιχείο.

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | Η ροή άδειας. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Αδειοδοτεί το στοιχείο.

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | licensePath | java.lang.String | Η διαδρομή άδειας. |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




