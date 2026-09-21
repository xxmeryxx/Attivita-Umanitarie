# Sistema Informativo per la Gestione delle Attività Umanitarie

## Descrizione del Progetto
Questo progetto consiste nella creazione di un sistema informativo per la gestione delle attività umanitarie, della distribuzione delle risorse e del personale nel territorio palestinese. L'obiettivo è fornire supporto alla popolazione, garantendo una corretta gestione delle risorse, il coordinamento delle operazioni e il monitoraggio tramite report periodici.

## Funzionalità Principali
* **Gestione Personale:** Coordinamento di volontari (addetti all'aggiornamento del registro risorse) e operatori retribuiti (incaricati della creazione dei report periodici)[cite: 3].
* **Tracciamento Risorse e Donazioni:** Registrazione delle donazioni (monetarie o materiali) e coordinamento delle risorse disponibili attraverso un registro specifico[cite: 3].
* **Organizzazione Attività Umanitarie:** Classificazione delle attività (distribuzione di cibo, assistenza sanitaria, alloggio e riparo) con assegnazione di livelli di priorità e requisiti di personale[cite: 3].
* **Gestione Beneficiari:** Mappatura tra i bisogni primari dei beneficiari e le specifiche tipologie di attività umanitarie erogate[cite: 3].
* **Monitoraggio:** Generazione di report periodici sottoposti alla supervisione di un ente di controllo[cite: 3].

## Fasi di Progettazione
Il database è stato sviluppato seguendo i requisiti standard di progettazione:
1. **Progettazione Concettuale:** Analisi dei requisiti, definizione dei dizionari dei dati (entità e relazioni) e stesura dello schema E-R[cite: 3].
2. **Progettazione Logica:** Eliminazione di gerarchie e attributi composti/multivalore, analisi delle ridondanze (calcolo degli accessi) e normalizzazione in Terza Forma Normale (3NF)[cite: 3].
3. **Progettazione Fisica:** Implementazione dello schema relazionale e creazione delle tabelle con relativi vincoli di integrità referenziale[cite: 3].

## Tecnologie Utilizzate
* Progettazione Entità-Relazione (Schema EER)[cite: 3]
* MySQL (Script DDL per la creazione del database fisico)[cite: 3]
