---
title: "License"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 10
url: /it/java/com.groupdocs.conversion.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Fornisce metodi per licenziare il componente. Scopri di più sulla licenza
[here](../https://purchase.groupdocs.com/faqs/licensing)
.
**Learn more** More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing) More about GroupDocs.Conversion licensing: [Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/conversionnet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Conversion)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLicensed()](#isLicensed--) | Restituisce true se è stata applicata una licenza valida; false se il componente è in modalità di valutazione. |
|
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) |  |
|  | [setLicense(System.IO.Stream licenseStream)](#setLicense-com.aspose.ms.System.IO.Stream-) | Licenzia il componente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenzia il componente. |
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


Restituisce true se è stata applicata una licenza valida; false se il componente è in modalità di valutazione.


**Returns:**
booleano
### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseStream | java.io.InputStream |  |

### setLicense(System.IO.Stream licenseStream) {#setLicense-com.aspose.ms.System.IO.Stream-}
```
public final void setLicense(System.IO.Stream licenseStream)
```


Licenzia il componente.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licenseStream | com.aspose.ms.System.IO.Stream | Il flusso della licenza. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public void setLicense(String licensePath)
```


Licenzia il componente.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licensePath | java.lang.String | Il percorso della licenza. |
|

### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




