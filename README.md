 # Percorso GIS: un viaggio attraverso la costruzione, l’ambiente e il territorio per studenti

* Necessità aula informatica.
* Connessione internet.
* [Software QGIS installato](https://qgis.org/downloads/QGIS-OSGeo4W-3.36.0-1.msi)
* [Link alle slides](https://docs.google.com/presentation/d/1rVDbSUtQ4r-1ev7_xsUm5pY7KFVrygD76g24w607Bow/edit?usp=sharing)

Tutti i dati e i materiali, salvo dove è specificatamente indicato, sono destinati all'uso didattico e sono rilasciati con licenza CC-BY 4.0

 ## Modulo 1 (2h)
[Link dati](https://drive.google.com/drive/folders/1PvS6UI1ruR1K0JNXw617S0RKR7QzI1TY?usp=sharing)

Dalla storia delle analisi geografiche a QGIS. In questo modulo capiremo le logiche che stanno dietro ai Sistemi Informativi Geografici partendo dalla storia di John Snow fino al Geomarketing. Si introdurrà il software QGIS e si familiarizzerà con l'interfaccia e i vari modelli di dati spaziali (raster e vettoriali). Si utilizzeranno i plugin di QGIS per contestualizzare i dati e caricare le basemap.

 ### Modulo 1 - introduzione al GIS

* Introduzione ai Sistemi Informativi Geografici
* cosa significa GIS e come viene impiegato 
* dalla mappa di John Snow ai satelliti
* QGIS: introduzione e intefaccia  
  Primi dati in QGIS:
* come sono strutturati i dati (lo shapefile, ecc.)
* caricamento vettore (shapefile comuni Veneto)
* tabella attributi
* selezione da mappa e da tabella
* stili: simbologia ed etichette
* Basemaps:
 QuickMapServices
 WMS


 ## Modulo 2 (2h)
[Link dati](https://drive.google.com/drive/folders/17CAUkm3rC8NUpLni3vixayLukJwBlxep?usp=sharing)

Punti linee poligoni: in questo secondo modulo si affronterà la tematica dei Sistemi di Riferimento (SR) e di come ci si posiziona sulla Terra. Si lavorerà con dataset vettoriali (importazione, interrogazione, stilizzazione) e si faranno delle prime query spaziali utilizzando dati vettoriali e semplici interrogazioni SQL. Si lavorerà sulla tabella attributi dei dati spaziali, per capire l’importanza delle informazioni collegate alle geometrie e come si selezionano e filtrano i dati, sulla base del contenuto informativo o delle relazioni spaziali.

### Modulo 2 - dati vettoriali

* Sistemi di Riferimento:
* Sistemi di riferimento e proiezioni
* Esempi di SR
* Data mining: provenienza dei dati: geoportali, OSM, rilievi
* Query sui dati vettoriali (selezione con espressioni SQL o spaziali)
* Join:  esercizio calcolo densità abitativa per comuni della Prov. di Padova: shapefile comuni Veneto - filtro per provincia, join con csv popolazione padova, calcolatore campi (somma popolazione, area comune, densità), stilizzazione per densità.


 ## Modulo 3 (2h)
[Link dati](https://drive.google.com/drive/folders/12fUyL91Tp3qWiwHYs1R4ZrGqveIhrlyz?usp=sharing)

Dal punto al pixel: il terzo modulo è dedicato ai raster, per la rappresentazione di grandezze continue come le quote del terreno. Si lavorerà sulla stilizzazione di questi dati, sull’estrazione di informazioni vettoriali (punti quotati, isolinee, profili) e sull’interpolazione di un dataset di dati rilevati. Si affronterà il processo di georeferenziazione della cartografia. Esercitazione sull’analisi del cambiamento climatico nelle zone urbane con dati dell'ARPAV.

### Modulo 3 - dati raster

* Raster: introduzione
* Data mining: download DTM Este da Geoportale Veneto
* Importazione raster: ortofoto, dem, classificazione suolo
* Interrogazione e stilizzazione
* Processing geomorfologico: hillshade, slope, aspect
* Viewshed: esercizio visibilità tramite DTM Este (ed eventualmente DTM Monselice) Interpolazione: esercizio cambiamento climatico dai dati delle stazioni ARPAV: join tra punti stazioni Arpav e tabella valori temperatura, calcolatore campi (temperatura media stagionale), interpolazione IDW e creazione raster temperature stagionali, statistiche zonali per aree di censo.

 ## Modulo 4 (2h)
[Link dati](https://drive.google.com/drive/folders/1z8zbW7cGhlQIKWIivs-s2d2IuBikCRLt?usp=sharing)

Dai satelliti al GIS: il quarto modulo è dedicato alla digitalizzazione e vettorializzazione della cartografia a partire da dataset ottenuti tramite remote sensing, e ai primi tool di geoprocessing. Si considereranno quindi gli strumenti disegno CAD in GIS e le prime analisi spaziali come il “buffer”

### Modulo 4 - digitalizzazione

* Georeferenziazione: PDF piano interventi Este
* Fotogrammetria per creazione ortofoto e DEM
* Tools di digitalizzazione:
* importare ortofoto (ortofoto drone)
* disegno planimetria con strumenti CAD
* importare DEM (DSM drone)
* estrazione linee di quota
* estrazione profili con Profile Tool
* Export vettoriali in DXF (anche con etichette)


 ## Modulo 5 (2h)
[Link dati]( https://drive.google.com/drive/folders/1F9fn1PG1C8gbWsfo8V5h7ac6HEbCIwtS?usp=sharing)

Cosa si vede da...: lezione dedicata a strumenti di geoprocessing più avanzati, come la viewshed analysis. Esercitazione dedicata all’analisi della visibilità urbana. Si concluderà il corso affrontando il layout di stampa di QGIS per l’esportazione di apposite tavole geografiche.

### Modulo 5 - geoprocessing e stampa

* Layout di stampa:
creazione tavola con rilievo da drone
* Esercizi geoprocessing:
calcolo popolazione interessata da rumore oltre norma: vettore strada, buffer di 100 m, intersezione edifici entro buffer,  join spaziale con punti esposizione acustica, selezione edifici sopra soglia, calcolo popolazione totale esposta

