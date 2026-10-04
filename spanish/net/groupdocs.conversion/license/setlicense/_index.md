---
title: "SetLicense"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Licencia el componente."
type: docs
weight: 30
url: /es/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseStream | Stream | El flujo de licencia. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando el Stream del archivo de licencia.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string licensePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licensePath | String | La ruta de la licencia. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando una ruta al archivo de licencia.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
