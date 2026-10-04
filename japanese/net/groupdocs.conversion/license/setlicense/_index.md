---
title: "SetLicense"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "コンポーネントにライセンスを付与します。"
type: docs
weight: 30
url: /ja/net/groupdocs.conversion/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream licenseStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licenseStream | Stream | ライセンスストリームです。 |

### 例

次の例は、ライセンスファイルの Stream を渡してライセンスを設定する方法を示しています。

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
    lic.SetLicense(licenseStream);
}
```

### 関連項目

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licensePath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| licensePath | String | ライセンスパスです。 |

### 例

次の例は、ライセンスファイルへのパスを渡してライセンスを設定する方法を示しています。

```csharp
string licensePath = "GroupDocs.Conversion.lic";
GroupDocs.Conversion.License lic = new GroupDocs.Conversion.License();
lic.SetLicense(licensePath);
```

### 関連項目

* class [License](../../license)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
