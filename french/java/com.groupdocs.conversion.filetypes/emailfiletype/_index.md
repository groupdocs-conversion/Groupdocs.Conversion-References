---
title: "EmailFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les formats de fichiers Email qui sont utilisés par les applications de messagerie pour stocker leurs diverses données, y compris les messages électroniques, les pièces jointes, les dossiers, les carnets d'adresses, etc."
type: docs
weight: 15
url: /fr/java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

Définit les formats de fichiers Email qui sont utilisés par les applications de messagerie pour stocker leurs diverses données, y compris les messages électroniques, les pièces jointes, les dossiers, les carnets d’adresses, etc.
Inclut les types de fichiers suivants :
[Eml](../../com.groupdocs.conversion.filetypes/emailfiletype#Eml),
[Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype#Emlx),
[Msg](../../com.groupdocs.conversion.filetypes/emailfiletype#Msg),
[Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype#Vcf).
[Pst](../../com.groupdocs.conversion.filetypes/emailfiletype#Pst).
[Ost](../../com.groupdocs.conversion.filetypes/emailfiletype#Ost).
[Olm](../../com.groupdocs.conversion.filetypes/emailfiletype#Olm).
En savoir plus sur les formats Email [ici](../https://wiki.fileformat.com/email).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EmailFileType()](#EmailFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Msg](#Msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. |
|
|  | [Eml](#Eml) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. |
|
|  | [Emlx](#Emlx) | Le format de fichier EMLX est implémenté et développé par Apple. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker des informations de contact. |
|
|  | [Mbox](#Mbox) | Le format de fichier MBox est un terme générique qui désigne un conteneur pour une collection de messages électroniques. |
|
|  | [Pst](#Pst) | Les fichiers avec l'extension .PST représentent les Outlook Personal Storage Files (également appelés Personal Storage Table) qui stockent une variété d'informations utilisateur. |
|
|  | [Ost](#Ost) | Les OST ou Offline Storage Files représentent les données de boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après l'enregistrement auprès d'Exchange Server avec Microsoft Outlook. |
|
|  | [Olm](#Olm) | Un fichier avec l'extension .olm est un fichier Microsoft Outlook pour le système d'exploitation Mac. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


Constructeur de sérialisation


### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/msg).


### Eml {#Eml}
```
public static final EmailFileType Eml
```


Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. La quasi‑totalité des clients de messagerie prennent en charge ce format de fichier en raison de sa conformité à la norme RFC‑822 Internet Message Format.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/eml).


### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les courriels.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/emlx).


### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker les informations de contact. Ce format est largement utilisé pour l'échange de données entre les applications d'échange d'informations populaires.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/vcf).


### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


Le format de fichier MBox est un terme générique qui représente un conteneur pour une collection de messages électroniques. Les messages sont stockés à l'intérieur du conteneur avec leurs pièces jointes.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/email/mbox/).


### Pst {#Pst}
```
public static final EmailFileType Pst
```


Les fichiers avec l'extension .PST représentent les Outlook Personal Storage Files (également appelés Personal Storage Table) qui stockent une variété d'informations utilisateur. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/pst).


### Ost {#Ost}
```
public static final EmailFileType Ost
```


Les OST ou Offline Storage Files représentent les données de boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après l'enregistrement auprès d'Exchange Server avec Microsoft Outlook. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/ost).


### Olm {#Olm}
```
public static final EmailFileType Olm
```


Un fichier avec l'extension .olm est un fichier Microsoft Outlook pour le système d'exploitation Mac. Un fichier OLM stocke les messages électroniques, les journaux, les données de calendrier et d'autres types de données d'application. Ceux‑ci sont similaires aux fichiers PST utilisés par Outlook sur le système d'exploitation Windows. Cependant, les fichiers OLM créés par Outlook pour Mac ne peuvent pas être ouverts dans Outlook pour Windows. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/olm).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion par défaut préparées pour le type de fichier


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
