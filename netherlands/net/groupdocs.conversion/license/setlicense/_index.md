---
title: "SetLicense"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Licentieert het component."
type: docs
weight: 30
url: /nl/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licentieert het component.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseStream | Stream | De licentiestroom. |

### Voorbeelden

Het volgende voorbeeld toont hoe een licentie in te stellen door een Stream van het licentiebestand door te geven.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Zie ook

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licentieert het component.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licensePath | String | Het licentiepad. |

### Voorbeelden

Het volgende voorbeeld toont hoe een licentie in te stellen door een pad naar het licentiebestand door te geven.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Zie ook

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
