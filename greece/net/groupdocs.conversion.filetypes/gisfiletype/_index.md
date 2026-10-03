---
title: "GisFileType"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ορίζει έγγραφα GIS. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Shp./gisfiletype/shp. GeoJson./gisfiletype/geojson. GeoJsonSeq./gisfiletype/geojsonseq. Gdb./gisfiletype/gdb. Gml./gisfiletype/gml. Kml./gisfiletype/kml. Kmz./gisfiletype/kmz. Gpx./gisfiletype/gpx. TopoJson./gisfiletype/topojson. Osm./gisfiletype/osm."
type: docs
weight: 1160
url: /el/net/groupdocs.conversion.filetypes/gisfiletype/
---
## GisFileType class

Ορίζει έγγραφα GIS. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Shp`](./shp). [`GeoJson`](./geojson). [`GeoJsonSeq`](./geojsonseq). [`Gdb`](./gdb). [`Gml`](./gml). [`Kml`](./kml). [`Kmz`](./kmz). [`Gpx`](./gpx). [`TopoJson`](./topojson). [`Osm`](./osm).

```csharp
public sealed class GisFileType : FileType
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GisFileType](gisfiletype)() | Κατασκευαστής σειριοποίησης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Περιγραφή τύπου αρχείου |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Η επέκταση αρχείου |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Η οικογένεια αρχείου |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Η μορφή αρχείου |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Συγκρίνει το τρέχον αντικείμενο με άλλο. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Υλοποιεί [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Καθορίζει αν δύο παρουσίες αντικειμένου είναι ίσες. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Λειτουργεί ως η προεπιλεγμένη συνάρτηση κατακερματισμού. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Αναπαράσταση συμβολοσειράς |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Gdb](../../groupdocs.conversion.filetypes/gisfiletype/gdb) | Το ESRI file Geodatabase (FileGDB) είναι μια συλλογή αρχείων σε φάκελο στον δίσκο που περιέχει σχεδεμένα γεωχωρικά δεδομένα όπως σύνολα χαρακτηριστικών, κλάσεις χαρακτηριστικών και σχετικούς πίνακες. Απαιτεί ορισμένα άλλα αρχεία να διατηρούνται μαζί με το αρχείο .gdb στον ίδιο κατάλογο για να λειτουργήσει. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/database/gdb/). |
| static readonly [GeoJson](../../groupdocs.conversion.filetypes/gisfiletype/geojson) | GeoJSON είναι μια μορφή βασισμένη σε JSON σχεδιασμένη για την αναπαράσταση γεωγραφικών χαρακτηριστικών με τα μη χωρικά τους χαρακτηριστικά. Αυτή η μορφή ορίζει διαφορετικά αντικείμενα JSON (JavaScript Object Notation) και τον τρόπο σύνδεσής τους. Η μορφή JSON αντιπροσωπεύει συλλογικές πληροφορίες για τα γεωγραφικά χαρακτηριστικά, τις χωρικές εκτάσεις τους και τις ιδιότητές τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/geojson/). |
| static readonly [GeoJsonSeq](../../groupdocs.conversion.filetypes/gisfiletype/geojsonseq) | Η GeoJSON Text Sequence είναι μια ροή ανεξάρτητων εγγραφών GeoJSON αντί για ένα ενιαίο έγγραφο, κάθε εγγραφή διαχωρίζεται με μια νέα γραμμή ή με τον χαρακτήρα ελέγχου RS. Χρησιμοποιείται για ροές που προστίθενται με την πάροδο του χρόνου, όπου το τέλος της συλλογής δεν είναι γνωστό όταν ξεκινά η εγγραφή. |
| static readonly [Gml](../../groupdocs.conversion.filetypes/gisfiletype/gml) | GML σημαίνει Geography Markup Language και βασίζεται σε προδιαγραφές XML που αναπτύχθηκαν από το Open Geospatial Consortium (OGC). Η μορφή χρησιμοποιείται για την αποθήκευση γεωγραφικών δεδομένων χαρακτηριστικών για ανταλλαγή μεταξύ διαφορετικών μορφών αρχείων. Λειτουργεί ως γλώσσα μοντελοποίησης για γεωγραφικά συστήματα καθώς και ως ανοιχτή μορφή ανταλλαγής για γεωγραφικές συναλλαγές στο διαδίκτυο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/gml/). |
| static readonly [Gpx](../../groupdocs.conversion.filetypes/gisfiletype/gpx) | Τα αρχεία με επέκταση GPX αντιπροσωπεύουν τη μορφή GPS Exchange για ανταλλαγή δεδομένων GPS μεταξύ εφαρμογών και διαδικτυακών υπηρεσιών. Είναι μια ελαφριά μορφή XML που περιέχει δεδομένα GPS, δηλαδή σημεία, διαδρομές και ίχνη, που μπορούν να εισαχθούν και να διαβαστούν από πολλαπλά προγράμματα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/gpx/). |
| static readonly [Kml](../../groupdocs.conversion.filetypes/gisfiletype/kml) | Το KML (Keyhole Markup Language) περιέχει γεωχωρικές πληροφορίες σε σημειογραφία XML. Τα αρχεία που αποθηκεύονται ως KML μπορούν να ανοιχτούν σε εφαρμογές Συστήματος Γεωγραφικής Πληροφορίας (GIS), εφόσον τις υποστηρίζουν. Πολλές εφαρμογές έχουν αρχίσει να παρέχουν υποστήριξη για τη μορφή αρχείου KML μετά την υιοθέτησή του ως διεθνή πρότυπο. Το KML χρησιμοποιεί δομή βασισμένη σε ετικέτες με ένθετα στοιχεία και ιδιότητες. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/kml/). |
| static readonly [Kmz](../../groupdocs.conversion.filetypes/gisfiletype/kmz) | Το KMZ είναι ένα αρχείο ZIP που μεταφέρει ένα έγγραφο KML, κατά συμβατότητα ονομάζεται doc.kml στη ρίζα του αρχείου, μαζί με οποιουσδήποτε πόρους αναφέρει το έγγραφο. Η συμπίεση της σημειογραφίας είναι ο σκοπός: μια ροή KML οποιουδήποτε μεγέθους μειώνεται δραματικά, γι' αυτό οι εκδότες διανέμουν KMZ αντί για KML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/kmz/). |
| static readonly [Osm](../../groupdocs.conversion.filetypes/gisfiletype/osm) | Η μορφή αρχείου OSM είναι μια δομημένη μορφή δεδομένων που χρησιμοποιείται για την αποθήκευση γεωγραφικών δεδομένων στο έργο OpenStreetMap. Τα αρχεία OSM είναι συνήθως σε μορφή XML και περιέχουν πληροφορίες όπως η θέση των δρόμων, κτιρίων, σημείων ενδιαφέροντος και άλλων χαρακτηριστικών στο χάρτη. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/osm/). |
| static readonly [Shp](../../groupdocs.conversion.filetypes/gisfiletype/shp) | Το SHP είναι η επέκταση αρχείου για έναν από τους κύριους τύπους αρχείων που χρησιμοποιούνται για την αναπαράσταση του ESRI Shapefile. Αντιπροσωπεύει γεωχωρικές πληροφορίες με τη μορφή διανυσματικών δεδομένων για χρήση από εφαρμογές Συστήματος Γεωγραφικής Πληροφορίας (GIS). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/gis/shp/). |
| static readonly [TopoJson](../../groupdocs.conversion.filetypes/gisfiletype/topojson) | Το TopoJSON είναι μια επέκταση του GeoJSON που κωδικοποιεί την τοπολογία. Αντί να αναπαριστά γεωμετρίες διακριτά, οι γεωμετρίες στα αρχεία TopoJSON συνδέονται από κοινά τμήματα γραμμών που ονομάζονται τόξα. |

### Δείτε επίσης

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
