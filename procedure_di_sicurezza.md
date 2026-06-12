# PROCEDURE

## Gestione degli accessi

### LOGICI

* Utilizzo di Microsoft Authenticator come password manager e MFA 
* revisione periodica degli accessi tramite monitoraggio dei log
* gestione dei criteri di gruppo e dei permessi tramite AD 

### FISICI

* chiusura delle porte di accesso dei pc 
* chiusura delle porte di accesso alla rete
* utilizzo di server room con l'uso di strumenti di sicurezza per controllare gli accessi (videosorveglianza)
* smaltimento sicuro degli asset a fine utilizzo 
* settare dei timer per l'ibernazione del pc   

### PERSONALI

* creazione delle password seguendo la normativa nis2
* sensibilizzazione su l'uso privato degli account aziendali

## Gestione degli incidenti di sicurezza

### LOGICI

* creazione periodica di punti di backup con verifica settimanale dei dati (con ridondanza in più aree)
* implementazione di sistemi di monitoraggio per verifica e mitigazione
* aggiornamento degli asset mitigando le vulnerabilità riscontrate
* Suddivisione delle fasi di procedimenti in test, pre-produzione e produzione
*  isolamento dell'incidente in una determinata area logica in modo da non propagarlo

### FISICI

* isoliamo l'incidente in un'area fisica per fare in modo che non si propaghi
* applico la politica di backup per incidenti ambientali

## PERSONALI

* cifratura dei dischi in caso di smarrimento dei dispositivi
* l'uso di cloud storage per avere una maggiore trasportabilità dei dati

## Procedura di backup e ripristino

* regola 3-2-1, 3 backup 2 su formati in sedi diverse (gruppi di continuità per i backup fisici) e uno in cloud
* synthetic backup: backup incrementali giornalieri e un full backup settimanale
* backup settimanale per il gestionale
* RTO: 36 ore, business continuity garantita da AWS
* RPO: codice sorgente quasi pari a zero (cloud), dati quasi pari a zero (cloud)

### [avanti](SOC.md) 
### [indietro](policy.md)