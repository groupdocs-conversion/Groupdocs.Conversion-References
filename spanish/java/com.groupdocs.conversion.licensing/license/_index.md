---
title: "License"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Proporciona métodos para licenciar el componente."
type: docs
weight: 10
url: /es/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Proporciona métodos para licenciar el componente. Obtén más información sobre la licencia
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | Devuelve true si se ha aplicado una licencia válida; false si el componente se está ejecutando en modo de evaluación. |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Licencia el componente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licencia el componente. |
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


Devuelve true si se ha aplicado una licencia válida; false si el componente se está ejecutando en modo de evaluación.


**Returns:**
booleano
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Licencia el componente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | El flujo de licencia. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Licencia el componente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licensePath | java.lang.String | La ruta de la licencia. |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




