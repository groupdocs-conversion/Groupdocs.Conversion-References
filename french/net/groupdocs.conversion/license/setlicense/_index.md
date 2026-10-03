---
title: "SetLicense"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Licence le composant."
type: docs
weight: 30
url: /fr/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream licenseStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseStream | Stream | Le flux de licence. |

### Exemples

L'exemple suivant montre comment définir une licence en passant le Stream du fichier de licence.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licensePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licensePath | String | Le chemin de la licence. |

### Exemples

L'exemple suivant montre comment définir une licence en passant un chemin vers le fichier de licence.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
