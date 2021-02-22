---
title: Data Browser Release notes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: February 4, 2021
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_50.html
folder: mydoc
---
## Version 1.2.0 (Release date: February 04, 2021)
.NET CORE 3.1.0
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-461	Per migliorare la leggibilità in tabella il TIME_PERIOD non viene mai tagliato su righe diverse  <br>
ISTAT-390	Per i dati con un solo valore distinto sul territorio (es. dato con valori relativi solo all'Italia) è nascosta la mappa  <br>
ISTAT-257	I download disponibili nelle view (dashboard) devono essere quelli configurati a livello di nodo  <br>
ISTAT-439	Aggiornamento jQuery all'ultima versione stabile disponibile (3.5.1)  <br>
ISTAT-315	Predisposizione di 2 servizi schedulabili per il ricalcolo in background di cache di catalogo e view non filtrabili  <br>
ISTAT-223	Gestione delle dimensioni non codificate: in presenza di dimensioni non codificate è proposta all'utente una casella di testo in cui inserire eventuali filtri  <br>
ISTAT-456	Rimozione della logica che selezionava di default la lettura dell'informativa sulla privacy  <br>
ISTAT-459	Per evitare attacchi di tipo "username enumeration" è stata generalizzata la risposta del metodo di recupero password  <br>
ISTAT-458	Per prevenire attacchi di tipo XSS, è stato aggiunto il controllo (ed eventuale rimozione) di script in fase di salvataggio dati  <br> 
ISTAT-455	Allineamento dell'icona seleziona tutti, in criteria  <br>
ISTAT-440	Aggiunta una nuova configurazione, a livello di applicazione e disponibile solo per il superadmin, che permette di selezionare la tipologia di mappa di sfondo tra le seguenti: openstreetmap, regioni di italia  <br>
ISTAT-438	Nell'elenco di download disponibili dovrà essere visualizzato solo il nome e non l'intero path del file  <br>
ISTAT-447	Rimozione di ogni logica di cancellazione delle cache nel caso in cui vengano aggiornate le configurazioni di un nodo  <br>
ISTAT-449	In assenza di configurazione sul Time To Live della cache, i dati scaricati rimarranno sempre validi  <br>
ISTAT-409	Dashboard - il download del CSV della tabella deve essere filtrato come da selezione (tranne che sul time_period)  <br>
ISTAT-181	Tutti i popup di configurazione sono stati resi "full screen"
ISTAT-444	Aggiunta icona nell'intestazione del portale per andare alla home del nodo  <br>
ISTAT-441	Le parole chiave, utilizzate ai soli fini di indicizzazione, sono nascoste dal catalogo  <br>
ISTAT-231	Aggiunta della funzionalità di salvataggio in sessione di specifiche visualizzazioni (nello stile di Fogli Excel)  <br>
ISTAT-487	Separate le configurazioni che permettono di includere/escludere nel catalogo "Dataflow non in produzione", "Linked Dataflow" e "Dataflow non categorizzati"  <br>
ISTAT-475	Aggiunta la possibilità di rimuovere lo swagger tramite apposito parametro di configurazione  <br>
ISTAT-454	L'applicativo è stato reso tollerante ad eventuali errori presenti nei files di configurazione dei servizi di ricalcolo della cache  <br>
ISTAT-425	Nascosto il tooltip in mappa, una volta deselezionato il singolo territorio <br>
ISTAT-345	Grafici: aggiunta della possibilità di personalizzare il titolo dell'export e dei nomi degli assi <br>
ISTAT-331	Mappe: aggiunta la possibilità di personalizzare il titolo dell'export come immagine <br>
ISTAT-158	Aggiunta autocomplete nella fase di ricerca, lasciando comunque la possibilità di cercare "stringhe" arbitrarie <br>
ISTAT-344	Grafico a torta: aggiunta l'etichetta per il valore percentuale
ISTAT-286	Grafici: tooltip separati per serie <br>
ISTAT-143	Aggiunte la configurazione sul “numero degli ultimi periodi” da estrarre a livello di nodo e template <br>
ISTAT-481	BUGFIX: correzione dell'interpretazione degli attributi a livello di osservazione <br>
ISTAT-480	BUGFIX: corretta gestione della visibilità delle dimensioni con annotation “NOT_DISPLAYED” <br> 
ISTAT-473	BUGFIX: corretta interpretazione del flag "isEnable" nel servizio di generazione di cache dei dati <br>
ISTAT-452	BUGFIX: corretta l'interpretazione della configurazione del numero di decimali da template <br>
ISTAT-446	BUGFIX: corretta l'interpretazione annotation per dataflow senza dati associati (solo file) <br>
ISTAT-427	BUGFIX: aggiunta della scrollbar alla legenda di mappa <br>
ISTAT-451	BUGFIX: correzione sul filtraggio dei dati applicando filtri più restrittivi <br>
ISTAT-389	BUGFIX: a prescindere dalla visualizzazione di etichette richiesta (id/descrizione) il TIME_PERIOD dovrà visualizzare sempre l'etichetta <br>


## Version 1.1.1 (Release date: December 03, 2020)
.NET CORE 3.1.0
<br>
<i>The following bugs/improvements have been covered:</i> <br>
- Resolution of the scrollbars not displayed in the table
- Openstreetmap background map removed
- Accessibility improvements

## Version 1.1.0 (Release date: November 25, 2020)
.NET CORE 3.1.0
<br>
<i>The following bugs/improvements have been covered:</i> <br>
ISTAT-230 Accessible version refinement <br>
ISTAT-343 Color selection for items of the graphed dimension <br>
ISTAT-356 Move image files (categories) to node level <br>
ISTAT-383 Added the ability to collapse the legend on the map <br>
ISTAT-387 Move "schedulable" service configurations externally to the appconfig.json file <br>
ISTAT-386 Introduced the use of the count of the record number <br>
ISTAT-378 Loading of maps <br>
ISTAT-414 Application level dashboard duplication and normalization <br>
ISTAT-264 Cursor scrolling problem in dashboards <br>
ISTAT-269 Filter management problems <br>
ISTAT-280 Templates created on maps are not maintained <br>
ISTAT-290 In flat codelists (criteria) added the "deselect all" <br>
ISTAT-365 Disabled internal scrolling of views by scrolling the dashboard <br>
ISTAT-367 Dashboard, Maps -  lack of synchronization with the wait wheel <br>
ISTAT-374 Problems creating map views <br>
ISTAT-380 Query efficiency check <br>
Password change and recovery problem <br>
Problem with saving map configuration in view / template <br>
Check that cache expiration works correctly <br>
In dashboards some objects are not displayed randomly <br>
In registration, the "Organization" field must not be mandatory <br>
The configured default language has to win when you reopen the application  <br>
The combo-box must not be visible at the top left if you start with the default node and the node is the only one present <br>
The "other nodes" button must not be visible on the home-page of the default node if the node is the only one present <br>
The node combo box on the top left must show the node name and not the node ID <br>
