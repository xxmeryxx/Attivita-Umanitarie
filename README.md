# Sistema Informativo per la Gestione delle Attività Umanitarie

## Descrizione del Progetto
Questo progetto consiste nella creazione di un sistema informativo per la gestione delle attività umanitarie, della distribuzione delle risorse e del personale nel territorio palestinese. L'obiettivo è fornire supporto alla popolazione, garantendo una corretta gestione delle risorse, il coordinamento delle operazioni e il monitoraggio tramite report periodici.

## Funzionalità Principali
* **Gestione Personale:** Coordinamento di volontari (addetti all'aggiornamento del registro risorse) e operatori retribuiti (incaricati della creazione dei report periodici).
* **Tracciamento Risorse e Donazioni:** Registrazione delle donazioni (monetarie o materiali) e coordinamento delle risorse disponibili attraverso un registro specifico.
* **Organizzazione Attività Umanitarie:** Classificazione delle attività (distribuzione di cibo, assistenza sanitaria, alloggio e riparo) con assegnazione di livelli di priorità e requisiti di personale.
* **Gestione Beneficiari:** Mappatura tra i bisogni primari dei beneficiari e le specifiche tipologie di attività umanitarie erogate.
* **Monitoraggio:** Generazione di report periodici sottoposti alla supervisione di un ente di controllo.

## Fasi di Progettazione
Il database è stato sviluppato seguendo i requisiti standard di progettazione:
1. **Progettazione Concettuale:** Analisi dei requisiti, definizione dei dizionari dei dati (entità e relazioni) e stesura dello schema E-R.
2. **Progettazione Logica:** Eliminazione di gerarchie e attributi composti/multivalore, analisi delle ridondanze (calcolo degli accessi) e normalizzazione in Terza Forma Normale (3NF).
3. **Progettazione Fisica:** Implementazione dello schema relazionale e creazione delle tabelle con relativi vincoli di integrità referenziale.

## Tecnologie Utilizzate
* Progettazione Entità-Relazione (Schema EER)
* MySQL (Script DDL per la creazione del database fisico)
