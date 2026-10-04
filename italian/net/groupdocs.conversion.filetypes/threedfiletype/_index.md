---
title: "ThreeDFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce documenti 3D Include i seguenti tipi Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb Maggiori informazioni sui formati 3D quihttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /it/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definisce documenti 3D Include i seguenti tipi: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) Maggiori informazioni sui formati 3D [qui](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Costruttore di serializzazione |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia del file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione stringa |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Un file AMF consiste in linee guida per la descrizione degli oggetti al fine di essere utilizzato nei processi di Produzione Additiva. Contiene un tag XML di apertura e termina con un elemento. Questo è preceduto da una riga di dichiarazione XML che specifica la versione XML e la codifica del file. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Un file con estensione .ase è un formato di file Autodesk ASCII Scene Export che è una rappresentazione ASCII di una scena, contenente informazioni 2D o 3D durante l'esportazione dei dati della scena usando Autodesk. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Un file DAE è un formato di file Digital Asset Exchange che viene utilizzato per lo scambio di dati tra applicazioni 3D interattive. Questo formato di file si basa sullo schema XML COLLADA (COLLAborative Design Activity) che è uno schema XML standard aperto per lo scambio di risorse digitali tra applicazioni software grafiche. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Un file con estensione .drc è un formato di file 3D compresso creato con la libreria Google Draco. Google offre Draco come libreria open source per comprimere e decomprimere mesh geometriche 3D e nuvole di punti, migliorando l'archiviazione e la trasmissione della grafica 3D. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, è un popolare formato di file 3D originariamente sviluppato da Kaydara per MotionBuilder. È stato acquisito da Autodesk Inc nel 2006 ed è ora uno dei principali formati di scambio 3D utilizzati da molti strumenti 3D. FBX è disponibile sia in formato binario che ASCII. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB è la rappresentazione in formato file binario dei modelli 3D salvati nel GL Transmission Format (glTF). Questo formato binario memorizza l'asset glTF (JSON, .bin e immagini) in un blob binario. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) è un formato di file 3D che memorizza le informazioni del modello 3D in formato JSON. L'uso di JSON riduce sia la dimensione delle risorse 3D sia l'elaborazione in tempo reale necessaria per decomprimere e utilizzare tali risorse. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) è un formato dati 3D efficiente, orientato all'industria e flessibile, standardizzato ISO, sviluppato da Siemens PLM Software. I domini CAD meccanici dell'aerospazio, dell'industria automobilistica e delle attrezzature pesanti utilizzano JT come loro principale formato di visualizzazione 3D. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | Un file con estensione .ma è un file di progetto 3D creato con l'applicazione Autodesk Maya. Contiene un'ampia lista di comandi testuali per specificare le informazioni sul file. Maggiori informazioni su questo formato di file [qui](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | Un file con estensione .mb è un file di progetto binario creato con l'applicazione Autodesk Maya. A differenza del formato file MA, che è in formato ASCII, i file MB sono memorizzati in formato binario. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | I file OBJ sono usati dall'applicazione Advanced Visualizer di Wavefront per definire e memorizzare gli oggetti geometrici. La trasmissione avanti e indietro dei dati geometrici è resa possibile tramite i file OBJ. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, rappresenta un formato file 3D che memorizza oggetti grafici descritti come una collezione di poligoni. Lo scopo di questo formato file era di stabilire un tipo di file semplice e facile, sufficientemente generico da essere utile per un'ampia gamma di modelli. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | I file dati RVM sono correlati ad AVEVA PDMS. Il file RVM è un file di progetto modello del Plant Design Management System di AVEVA. Il Plant Design Management System (PDMS) di AVEVA è il sistema di progettazione 3D più popolare, che utilizza una tecnologia data‑centric per gestire i progetti. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Un file con estensione .3ds rappresenta il formato file mesh 3D Sudio (DOS) utilizzato da Autodesk 3D Studio. Autodesk 3D Studio è presente nel mercato dei formati file 3D dagli anni ’90 e si è evoluto in 3D Studio MAX per la modellazione, l'animazione e il rendering 3D. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, è usato dalle applicazioni per rendere modelli di oggetti 3D in una varietà di altre applicazioni, piattaforme, servizi e stampanti. È stato creato per evitare le limitazioni e i problemi presenti in altri formati file 3D, come STL, per lavorare con le versioni più recenti delle stampanti 3D. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) è un formato file compresso e una struttura dati per la grafica 3D al computer. Contiene informazioni sul modello 3D come mesh triangolari, illuminazione, ombreggiatura, dati di movimento, linee e punti con colore e struttura. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Un file con estensione .usd è un formato file Universal Scene Description che codifica dati allo scopo di scambiare e arricchire informazioni tra le applicazioni di creazione di contenuti digitali. Sviluppato da Pixar, USD offre la possibilità di scambiare asset elementari (come modelli) o animazioni. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Un file con estensione .usdz è un archivio ZIP non compresso e non crittografato per il formato file USD (Universal Scene Description) che contiene e funge da proxy per file di altri formati (come texture e animazioni) incorporati nell'archivio e li esegue direttamente con il runtime USD senza necessità di estrazione. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Il Virtual Reality Modeling Language (VRML) è un formato file per la rappresentazione di oggetti 3D interattivi sul World Wide Web (www). Viene utilizzato per creare rappresentazioni tridimensionali di scene complesse, come illustrazioni, definizioni e presentazioni di realtà virtuale. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Un file con estensione .x si riferisce al formato file legacy DirectX 3D Graphics introdotto con Microsoft DirectX 2.0. È stato usato per il rendering grafico 3D nei giochi e specifica le strutture per mesh, texture, animazioni e oggetti definiti dall'utente. È stato deprecato dal 2014 poiché il formato file Autodesk FBX è più adatto come formato moderno. Scopri di più su questo formato file [qui](https://docs.fileformat.com/3d/x). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
