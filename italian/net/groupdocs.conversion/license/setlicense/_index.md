---
title: "SetLicense"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Licenzia il componente."
type: docs
weight: 30
url: /it/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licenzia il componente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| licenseStream | Stream | Il flusso di licenza. |

### Esempi

Il seguente esempio dimostra come impostare una licenza passando lo Stream del file di licenza.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### IConversionConvertOptions

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licenzia il componente.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| licensePath | String | Il percorso della licenza. |

### Esempi

Il seguente esempio dimostra come impostare una licenza passando un percorso al file di licenza.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### IConversionConvertOptions

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
