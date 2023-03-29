## Gestione Albi Ordini Professionali dei Medici Chirurghi e degli Odontoiatri 
E' un sistema Informatico di Gestione degli Albi dei Medici Chirurghi e degli Odontoiatri . Supporta tutte le attività gestionali e amministrative dell’Ordine, automatizzando il ciclo di presenza di un iscritto, a partire dalla richiesta di iscrizione sino alla cancellazione dagli albi.

Questo è il modulo attualmente reso disponibile con la licenza EUPL 

## Descrizione
MeO è stato sviluppato nel 1990 secondo le specifiche richieste dall'Ordine dei Medici Chirurghi ed Odontoiatri della Provincia di Bari.
E' oggi utilizzato da oltre 20 Ordini Professionali dei Medici Chirurghi e degli Odontoiatri, ed è stato evoluto a seconda delle esigenze normative e/o organizzative.
Nel 2017 è stata rilasciata la versione Web del modulo MEO e l'anno successivo è stato reso disponibile in Cloud.
A marzo 2021 il software è stato certificato nel Marketplace AGID (https://catalogocloud.agid.gov.it/service/1607).

Il Sistema è assimilabile ad un vero e proprio Enterprise Resource Planning (ERP) nell'ambito della gestione degli Ordini Professionali dei Medici Chirurghi ed Odontoiatri in quanto supporta tutte le attività gestionali e amministrative dell’Ordine, automatizzando il ciclo di presenza di un iscritto, a partire dalla richiesta di iscrizione sino alla sua cancellazione dagli albi ma è integrabile con altri specifici moduli (protocollo, contabilità...) supportandone i processi e garantendo interoperabilità e uniformità gestionale.

Nella [brochure](https://github.com/latraccia/meo/Documenti/MEO_brochure.pdf) sono evidenziate le principali caratteristiche del Sistema.


## Framework, tecnologie e linguaggi utilizzati
 - Oracle DataBase vers. 11 e superiori
 - Oracle Application Express vers. 4.0 e superiori
 - PL/SQL
 - Java
 - Javascript
 - Jasper Report
 - JQuery

## Requisiti di installazione
|Requisito| Versione |Descrizione|
|-----------|-----------|---------|
|[Oracle Database](https://www.oracle.com/it/database/) | 11> |Base dati (qualsiasi release)
|[Oracle Application Express](https://apex.oracle.com/)|5>|Ambiente di sviluppo
|[Oracle REST Data Services](https://www.oracle.com/it/database/technologies/appdev/rest.html)|18>|PL/SQL Gateway
|[Tomcat](https://tomcat.apache.org) (o altri Apex compliant)|8>|Application server 
|[JasperSoft Studio](https://sourceforge.net/projects/jasperstudio/files/JaspersoftStudio-6.11.0/)|>5|Report builder

## Installazione
Per tutti i dettagli circa le modalità di installazione del MODULO leggere e seguire le istruzioni contenute nel Manuale di Gestione dell'applicazione

## Componenti 
Di seguito i principali Componenti da cui è composto il modulo

 01. **Archivi di Base**
, Informazioni di Carattere generale sull'Ordine 
, tabelle Nazioni/Province/Comuni/CAP
, Atenei
, Branche Specializzazioni
, Elenchi Speciali
, Motivi Cancellazione
, Attività
, Master
, Dottorati
, Annotazioni
, Accessori
, Codice Deontologico
, Tipi Permessi Soggiorno
, Documenti da Rilasciare
, Normativa
, Certificazioni/Documenti
, Tribunali
, Esenzione Certificati
, Gestione Abilitazione Ruoli
, Località Attività
, Gestione Tipi Docenza
, Gestione Regime Impegno Docenza
, Specializzazioni
, Causali Blocco Certificati
, Gestione Attività Professionali
, Gestione Causali Provv. Disciplinare
, Gestione Risposte Non Vaccinati
, Direttori e Strutture Sanitarie

 02. **Delibere**
, Stato delle Richieste
, Iscrizioni/Cancellazioni
, Doppia Iscrizione Albo Odontoiatri
, Doppia Iscrizione Albo Chirurghi
, Iscrizione per Doppia Laurea
, Iscrizioni Transitori
, Stato delle Richieste delle Società
, Iscrizioni/Cancellazioni Società
, Gestione Ratifiche
, Conferma Delibera

 03. **Iscritti**
, Elenco Iscritti
, Scheda Iscritto
, Elenco Società Iscritte
, Scheda Società Iscritta
, Giuramento Iscritti
, Validazione Cambio Indirizzi
, Validazione Inserimento Specializzazione 

 04. **Procedimenti Disciplinari**
, Istruttorie
, Provvedimenti Disciplinari
, Istruttorie Non Iscritti.
, Provvedimenti Non Iscritti. 

 05. **Ruoli**
, Tabella quote annuali
, Elaborazione Annuale Ruoli
, Creazione File CBI per banca
, Importazione file MAV
, Importazione file Bonifici Bancari
, Situazione Riscossione
, Tabulati PagoPA
, Genera PagoPA
, Sollecito Morosi
, Sollecito Morosi Plurianno
, Convocazione Presidente
, Modifica Massiva PagoPA
, Elenco SDD

 06. **Pagamenti e Incassi**
, Configurazione
, IBAN
, Posizioni Debitorie
, Rendicontazioni
, Ricevute di Pagamento
, Tassonomia
, Tipologie di Pagamento

 07. **Stampe**
, Elenco Iscritti con parametri di selezione a scelta
, Rilascio Certificato Iscritti
, Lettere Automatiche
, Stampa Tesserino
, Rilascio Documenti per Esterni
, Esito Invio Email/Pec
, Estrazione Dati 
, Permessi di Soggiorno
, Delibere Confermate
, Statistiche

 08. **Elezioni**
, Gestione Seggio 
, Calcolo Quorum
, Conteggio Voti 

 09. **Utilità**
, Importazione Codici ENPAM
, Importazione Indirizzi PEC
, Ricarica Documenti
, Anagrafe Tributaria
, Casellario Giudiziale
, Creazione File XML Enpam/Fnomceo
, Gestione Lettere Automatiche
, Gestione Testo Privacy
, Conferma validità iscrizione
, Raccolta
, Ripristina Iscrizione
, Cambio Password
, Importazione file NON vaccinazioni

## Documenti 
Di seguito i documenti che accompagnano il codice

 1. Manuale di Gestione dell'Applicazione
 2. Manuale Utente
 3. [Script SQL per la creazione degli oggetti di Data Base](
 4. [File sorgente Apex dell'applicazione]
 5. [Dizionario dati DB]

## Moduli Integrabili a MeO 
I seguenti moduli sono disponibili e integrabili con il modulo MEO con cui condividono la base dati e le utenze applicative.

**EPROT**	
Gestione Protocollo informatico. Scansione automatizzata per salvataggio allegati,  plug-in per MS WORD, possibilità di memorizzazione allegati in ambiente S3 o FTP, Creazione e Conservazione Automatica del Registro di Procollo, Protocollazione Automatica Fatture elettroniche, Web Service per protocollazione.

**EPROT-MAIL**
Protocollazione Automatica di E-mail e PEC, con gestione del workflow di lettura, memorizzazione come allegato della email e relativi allegati, possibilità di memorizzare allegati in ambente S3 o FTP

**SIC** 	
Contabilità finanziaria, gestione dei bilanci, impegni, accertamenti, mandati, reversali. Inventario Beni, Gestione Oil o Siope+ per Banca Tesoriera.

**PAGOPA** 	
Sistema di pagamenti elettronici verso la Pubblica Amministrazione, con stampa bollettini, ricezione notifica pagamenti, Web Service di Colloquio

**FATTEL** 	
Sistema per gestione Fatture Elettroniche, Conservazione a Norma, gestione risposte, client di protocollazione automatica, client di Invio a sistemi Contabili per il registro delle fatture.

**CORSI** 	
Organizzazione dei corsi, iscrizione online, gestione dei crediti, stampa attestati.
Gestisce corsi in aula o web con integrazione con piattaforme di video conferenza (Zoom).

**FEEDBACKTOBUSINESS**
Gestione dei Questionari di valutazione, quiz per esami, analisi e statistiche.

**RILPRES** 	
Rilevazione presenze/assenze con gestione turni, Calcolo orario, gestione MonteOre Causali di Assenza, produzione file per Sistema Paghe. Acquisizione delle timbrature tramite Terminali Orologi Elettronici, acquisizione automatica da INPS dei certificati Medici

**INFOPOINT** 	
Portale Dipendenti per visione cartellino presenze, richieste e validazione timbrature mancanti e permessi, saldo al giorno. Modulo per pubblicazione comunicazioni e documentazione ad uso del singolo dipendente.

