
## FUNZIONALITA' SOC

* Monitoraggio continuo della sicurezza
* Rilevamento e analisi degli incidenti
* Gestione delle vulnerabilità
* Threat Intelligence
* Pianificazione della risposta agli incidenti
* inventario degli asset
* Testing regolare e assessment vulnerabilità
* aggiornamento regolare del sw e del OS degli endpoint 
* log managment
* Ripristino e correzione post incidente
* Gestione delle conformità (GDPR, ISO 27001, AI act)

## ARCHITETTURA SOC 

* SIEM (Security information and Event managment): raccoglie, aggrega e analizza i volumi di dati delle applicazioni, dei dispositivi, dei server e degli utenti per rilevare e bloccare gli attacchi. Semplifica anche la gestione dei log, la gestione degli eventi e degli incidenti e la creazione di report di conformità. Microsoft sentinel
* Piattaforme di threat intelligence: automatizza il processo di raccolta, analisi e diffusione dei dati threat intelligence. 
* EDR (endpoint detection and response): monitoraggio degli endpoint, rapresentazione grafica degli alert
* XDR (extended detection and response): raccoglie gli avvisi di basso livello e li correla, Dal monitoraggio del comportamento di minaccia e dall'invio di avvisi all'indagine e alla correzione, usa l'intelligenza artificiale per rilevare, rispondere e mitigare automaticamente i possibili attacchi informatici, crea profili di comportamento sospetto, isola i dispositivi e account utente compromessi per interrompere gli utenti malintenzionati.
* sandbox: ambiente di test per penetration test

### INTERAZIONE TRA GLI STRUMENTI SOC

**ON PREMISE**: Combinando SIEM con la piattaforma di threat intelligence per raccolta dei dati che poi verranno sfruttati da EDR e XDR per la gestione della messa in sicurazza dell'infrastruttura. 
**CLOUD**: scegliamo uno strumento di gestione centralizzata per le SecOps Microsoft Security, un sistema che integra tutti gli strumenti per la sicurezza in un unica console: Microsoft defender XDR, Microsoft Sentinel (SIEM), Microsoft Defender per il cloud, Microsoft security copilot (quando avviene un incidente copilot ridige un testo con analisi della minacccia: IP di orgine, link cliccato etc) 

## RUOLI SOC

* soc manager: gestione comprensiva del soc, definisce strategie di sicurezza e si assicura che vengano applicate in maniera efficace
* incident responder: si occupa della risposta agli incidente, si occupa di eradicare gli incidenti e di implentare le dovute contromisure affinchè non avvengano di nuovo
* threat hunter: analizza la rete per trovare le minacce sfruttando la piattaforma di gestione centralizzara Microsoft Security e gli strumenti per la raccolta dati on premise 
* compliance analyst: si occupa di controllare la conformità alle norme vigenti
* security engineer: si occupa di progettare e migliorare le infrastrutture di sicurezza per il SOC

### [indietro](SOC.md)
