# Università degli Studi di Messina

**Studente**: Claudio Anchesi</br>
**Titolo della tesi**: Progettazione e implementazione di un sistema di orchestrazione di microservizi su sistemi Edge basato sull'algoritmo di consenso Raft</br>
**Relatore**: Maria Fazio</br>

## Introduzione

Questa repository contiene il codice sorgente di un basilare sistema di orchestrazione di microservizi basato su Raft, tale da implementare un log distribuito. 

### Abstract

Lo scopo di questo lavoro di tesi è quello di progettare un sistema di orchestrazione di microservizi distribuito in una rete di nodi edge. La gestione del carico di lavoro di ogni nodo, necessaria alla massimizzazione dell’efficienza di questo
sistema, sarà gestita in maniera altresì distribuita, imponendo che la decisione su quale nodo debba prendere in carico un certo servizio sia presa dai nodi stessi tramite l’utilizzo di un algoritmo di consenso. Infine, è previsto che ogni attività concordata della rete sia mantenuta su un sistema di log distribuito e accessibile da ogni nodo.
Una priorità è che questo sistema sfrutti le funzionalità di piattaforme di orchestrazione note, come Docker, solo come strumento ad un livello logicamente sottostante per l’effettiva esecuzione dei servizi, permettendo che sia integrabile con un certo spettro di tecnologie verosimilmente scelte dall’amministratore dell’infrastruttura.
