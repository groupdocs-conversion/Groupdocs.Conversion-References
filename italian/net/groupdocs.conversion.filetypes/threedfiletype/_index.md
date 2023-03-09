---
title: ThreeDFileType
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Definisce i documenti 3D Include i seguenti tipi Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/x Ulteriori informazioni sui formati 3DQuihttps//wiki.fileformat.com/3d .
type: docs
weight: 1060
url: /it/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

Definisce i documenti 3D Include i seguenti tipi: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x) Ulteriori informazioni sui formati 3D[Qui](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Costruttore di serializzazione |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia di file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina se due istanze di oggetto sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetto sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funge da funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione di stringa |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Un file AMF è costituito da linee guida per la descrizione degli oggetti da utilizzare nei processi di Additive Manufacturing. Contiene un tag XML di apertura e termina con un elemento. Questo è preceduto da una riga di dichiarazione XML che specifica la versione XML e la codifica del file. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | Un file con estensione .ase è un formato di file di esportazione della scena ASCII di Autodesk che è una rappresentazione ASCII di una scena, contenente informazioni 2D o 3D durante l'esportazione dei dati della scena utilizzando Autodesk. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Un file DAE è un formato di file Digital Asset Exchange utilizzato per lo scambio di dati tra applicazioni 3D interattive. Questo formato di file si basa sullo schema XML COLLADA (COLLAborative Design Activity), che è uno schema XML standard aperto per lo scambio di risorse digitali tra applicazioni software di grafica. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | Un file con estensione .drc è un formato di file 3D compresso creato con la libreria Google Draco. Google offre Draco come libreria open source per la compressione e la decompressione di mesh geometriche 3D e nuvole di punti e migliora l'archiviazione e la trasmissione della grafica 3D. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, è un popolare formato di file 3D originariamente sviluppato da Kaydara per MotionBuilder. È stato acquisito da Autodesk Inc nel 2006 ed è ora uno dei principali formati di scambio 3D utilizzato da molti strumenti 3D. FBX è disponibile sia in formato file binario che ASCII. Ulteriori informazioni su questo formato file[Qui](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format) è un formato di file 3D che memorizza le informazioni del modello 3D in formato JSON. L'uso di JSON riduce al minimo sia la dimensione delle risorse 3D sia l'elaborazione in fase di esecuzione necessaria per decomprimere e utilizzare tali risorse. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation) è un formato di dati 3D standardizzato ISO efficiente, orientato al settore e flessibile sviluppato da Siemens PLM Software. I domini CAD meccanici di aerospaziale, industria automobilistica e attrezzature pesanti utilizzano JT come formato di visualizzazione 3D più importante. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | I file OBJ vengono utilizzati dall'applicazione Advanced Visualizer di Wavefront per definire e memorizzare gli oggetti geometrici. La trasmissione avanti e indietro dei dati geometrici è resa possibile tramite i file OBJ. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, rappresenta il formato di file 3D che memorizza oggetti grafici descritti come una raccolta di poligoni. Lo scopo di questo formato di file era quello di stabilire un tipo di file semplice e facile che fosse abbastanza generale da essere utile per un'ampia gamma di modelli. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | I file di dati RVM sono correlati a AVEVA PDMS. Il file RVM è un file di progetto del modello di sistema di gestione della progettazione dell'impianto AVEVA. Il Plant Design Management System (PDMS) di AVEVA è il sistema di progettazione 3D più popolare che utilizza una tecnologia incentrata sui dati per la gestione dei progetti. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | Un file con estensione .3ds rappresenta il formato di file mesh 3D Sudio (DOS) utilizzato da Autodesk 3D Studio. Autodesk 3D Studio è presente sul mercato dei formati di file 3D dagli anni '90 e ora si è evoluto in 3D Studio MAX per lavorare con la modellazione, l'animazione e il rendering 3D. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, viene utilizzato dalle applicazioni per eseguire il rendering di modelli di oggetti 3D su una varietà di altre applicazioni, piattaforme, servizi e stampanti. È stato creato per evitare le limitazioni e i problemi di altri formati di file 3D, come STL, per lavorare con le versioni più recenti delle stampanti 3D. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D) è un formato di file compresso e una struttura di dati per la computer grafica 3D. Contiene informazioni sul modello 3D come mesh triangolari, illuminazione, ombreggiatura, dati di movimento, linee e punti con colore e struttura. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | Un file con estensione .usd è un formato di file Universal Scene Description che codifica i dati allo scopo di scambiare e aumentare i dati tra le applicazioni di creazione di contenuti digitali. Sviluppato da Pixar, USD offre la possibilità di scambiare risorse elementari (come modelli) o animazioni. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | Un file con .usdz è un archivio ZIP non compresso e non crittografato per il formato di file USD (Universal Scene Description) che contiene e proxy per file di altri formati (come trame e animazioni) incorporati nell'archivio e li esegue direttamente con il Tempo di esecuzione USD senza necessità di decompressione. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Il Virtual Reality Modeling Language (VRML) è un formato di file per la rappresentazione di oggetti del mondo 3D interattivi sul World Wide Web (www). Trova il suo utilizzo nella creazione di rappresentazioni tridimensionali di scene complesse come illustrazioni, definizione e presentazioni di realtà virtuale. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | Un file con estensione .x si riferisce al formato di file legacy DirectX 3D Graphics introdotto con Microsoft DirectX 2.0. È stato utilizzato per il rendering di grafica 3D nei giochi e specifica le strutture per mesh, trame, animazioni e oggetti definiti dall'utente. È stato deprecato dal 2014 poiché il formato di file Autodesk FBX funziona meglio come formato più moderno. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/3d/x) . |

### Guarda anche

* class [FileType](../filetype)
* spazio dei nomi [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assemblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
