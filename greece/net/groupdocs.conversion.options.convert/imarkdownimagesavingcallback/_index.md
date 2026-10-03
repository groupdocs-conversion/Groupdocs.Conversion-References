---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Διαχειρίζεται την προσαρμοσμένη επεξεργασία εικόνων κατά την αποθήκευση σε Markdown. Καλείται μία φορά ανά εικόνα για να μεταβάλλει το MarkdownImageSavingArgs./markdownimagesavingargs ώστε να ελέγξει το URI που ενσωματώνεται στην έξοδο Markdown και/ή να ανακατευθύνει πού γράφονται τα bytes της εικόνας."
type: docs
weight: 1870
url: /el/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Διαχειρίζεται την προσαρμοσμένη επεξεργασία εικόνων κατά την αποθήκευση σε Markdown. Καλείται μία φορά ανά εικόνα· μεταβάλλει το [`MarkdownImageSavingArgs`](../markdownimagesavingargs) ώστε να ελέγξει το URI που ενσωματώνεται στην έξοδο Markdown και/ή να ανακατευθύνει πού γράφονται τα bytes της εικόνας.

```csharp
public interface IMarkdownImageSavingCallback
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Καλείται για κάθε εικόνα που γράφεται στο έγγραφο Markdown. |

### Παραδείγματα

Σενάριο 1 — σύλληψη των bytes της εικόνας στη μνήμη και ενσωμάτωση αναγνωριστικών placeholder (χρήσιμο όταν ο καλών θέλει να αποθηκεύσει τις εικόνες αλλού ή να τις επεξεργαστεί μεταγενέστερα):

```csharp
class CaptureImagesCallback : IMarkdownImageSavingCallback
{
    private int _index;
    private readonly Dictionary<string, MemoryStream> _images;

    public CaptureImagesCallback(Dictionary<string, MemoryStream> images) => _images = images;

    public void ImageSaving(MarkdownImageSavingArgs args)
    {
        var id = $"image{_index++}";
        var buffer = new MemoryStream();
        _images[id] = buffer;
        args.ImageStream = buffer;            // redirect image bytes into our buffer
        args.ImageFileName = id;              // placeholder URI written into the .md
        args.KeepImageStreamOpen = true;      // keep buffer readable after Convert() returns
    }
}

var captured = new Dictionary<string, MemoryStream>();
try
{
    var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
    options.MarkdownOptions.ImageSavingCallback = new CaptureImagesCallback(captured);

    using var converter = new Converter("source.pdf");
    converter.Convert("output.md", options);
    // captured[\"image0\"], captured[\"image1\"], ... τώρα περιέχουν τα bytes της εικόνας
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Σενάριο 2 — διατήρηση των εικόνων στο δίσκο μαζί με το .md και αναφορά σε αυτές με το όνομα αρχείου:

```csharp
class FileImagesCallback : IMarkdownImageSavingCallback
{
    private readonly string _outputFolder;
    private int _index;

    public FileImagesCallback(string outputFolder) => _outputFolder = outputFolder;

    public void ImageSaving(MarkdownImageSavingArgs args)
    {
        var fileName = $"image{_index++}.png";
        args.ImageStream = new FileStream(Path.Combine(_outputFolder, fileName), FileMode.Create);
        args.ImageFileName = fileName;        // written into the .md as ![](image0.png)
        // Το KeepImageStreamOpen παραμένει στην προεπιλογή (false) → ο μετατροπέας εκκαθαρίζει και κλείνει το αρχείο.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... γράφονται και κλείνουν από τον μετατροπέα.
```

### Δείτε επίσης

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
