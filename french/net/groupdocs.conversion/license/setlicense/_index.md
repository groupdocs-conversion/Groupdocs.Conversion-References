---
title: SetLicense
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Licence du composant.
type: docs
weight: 20
url: /fr/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licence du composant.

```csharp
public void SetLicense(Stream licenseStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| licenseStream | Stream | Le flux de licence. |

### Exemples

L'exemple suivant montre comment définir un flux de transmission license du fichier de licence.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### Voir également

* class [License](../../license)
* espace de noms [GroupDocs.Conversion](../../license)
* Assemblée [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

Licence du composant.

```csharp
public void SetLicense(string licensePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| licensePath | String | Le chemin de la licence. |

### Exemples

L'exemple suivant montre comment définir une licence en transmettant un chemin d'accès au fichier de licence.

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### Voir également

* class [License](../../license)
* espace de noms [GroupDocs.Conversion](../../license)
* Assemblée [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->