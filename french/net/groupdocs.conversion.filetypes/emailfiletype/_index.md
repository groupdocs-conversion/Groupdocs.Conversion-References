---
title: "EmailFileType"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définit les formats de fichiers Email qui sont utilisés par les applications de messagerie pour stocker leurs diverses données, y compris les messages électroniques, les pièces jointes, les dossiers, les carnets d'adresses, etc. Inclut les types de fichiers suivants : Eml./emailfiletype/eml Emlx./emailfiletype/emlx Msg./emailfiletype/msg Vcf./emailfiletype/vcf. Mbox./emailfiletype/mbox. Pst./emailfiletype/pst. Ost./emailfiletype/ost. Olm./emailfiletype/olm. En savoir plus sur les formats Email icihttps//wiki.fileformat.com/email."
type: docs
weight: 1120
url: /fr/net/groupdocs.conversion.filetypes/emailfiletype/
---
## EmailFileType class

Définit les formats de fichiers Email qui sont utilisés par les applications de messagerie pour stocker leurs diverses données, y compris les messages électroniques, les pièces jointes, les dossiers, les carnets d'adresses, etc. Inclut les types de fichiers suivants : [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Vcf`](./vcf). [`Mbox`](./mbox). [`Pst`](./pst). [`Ost`](./ost). [`Olm`](./olm). En savoir plus sur les formats Email [ici](https://wiki.fileformat.com/email).

```csharp
public sealed class EmailFileType : FileType
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmailFileType](emailfiletype)() | Constructeur de sérialisation |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Description du type de fichier |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'extension du fichier |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famille de fichiers |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Le format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compare l'objet actuel à un autre. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implémente [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Détermine si deux instances d'objet sont égales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Servir de fonction de hachage par défaut. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Représentation sous forme de chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Eml](../../groupdocs.conversion.filetypes/emailfiletype/eml) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. La plupart des clients de messagerie prennent en charge ce format de fichier en raison de sa conformité à la norme RFC-822 Internet Message Format. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/eml). |
| static readonly [Emlx](../../groupdocs.conversion.filetypes/emailfiletype/emlx) | Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les courriels. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/emlx). |
| static readonly [Ics](../../groupdocs.conversion.filetypes/emailfiletype/ics) | Le format de fichier ICS (iCalendar) est utilisé pour représenter et échanger des informations de calendrier et de planification telles que les événements, les tâches et les données de disponibilité (free/busy). En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/ics). |
| static readonly [Mbox](../../groupdocs.conversion.filetypes/emailfiletype/mbox) | Le format de fichier MBox est un terme générique qui représente un conteneur pour une collection de messages électroniques. Les messages sont stockés à l'intérieur du conteneur avec leurs pièces jointes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/mbox/). |
| static readonly [Msg](../../groupdocs.conversion.filetypes/emailfiletype/msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/msg). |
| static readonly [Olm](../../groupdocs.conversion.filetypes/emailfiletype/olm) | Un fichier avec l'extension .olm est un fichier Microsoft Outlook pour le système d'exploitation Mac. Un fichier OLM stocke des messages électroniques, des journaux, des données de calendrier et d'autres types de données d'application. Ceux‑ci sont similaires aux fichiers PST utilisés par Outlook sur le système d'exploitation Windows. Cependant, les fichiers OLM créés par Outlook pour Mac ne peuvent pas être ouverts dans Outlook pour Windows. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/olm). |
| static readonly [Ost](../../groupdocs.conversion.filetypes/emailfiletype/ost) | Les fichiers OST ou Offline Storage représentent les données de la boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après l'enregistrement auprès du serveur Exchange via Microsoft Outlook. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/ost). |
| static readonly [Pst](../../groupdocs.conversion.filetypes/emailfiletype/pst) | Les fichiers avec l'extension .PST représentent les fichiers Outlook Personal Storage (également appelés Personal Storage Table) qui stockent une variété d'informations utilisateur. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/pst). |
| static readonly [Vcf](../../groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker des informations de contact. Ce format est largement utilisé pour l'échange de données entre les applications d'échange d'informations populaires. En savoir plus sur ce format de fichier [ici](https://wiki.fileformat.com/email/vcf). |

### Voir aussi

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
