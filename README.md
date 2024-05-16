|  Numero documento:   | **C000CMP01SUM01** |
|----------------------|--------------------|
| Revisione documento: | **04.00**          |
| Data:                |  **30/06/2023**    |
| Cage Code:           |  **A0069**         |

|                                                             |
|-------------------------------------------------------------|
| **Digital Security**                                        |
| **CLOUD MANAGEMENT PLATFORM** **Cloud Management Platform** |
|                                                             |

**Firme**

| Autore: Product Owner IPT di Sviluppo Hybrid Cloud Application                             | .......................................................... Daniele Leone        |
|--------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| Verifica: Responsabile U.O. Engineering Technology & Digital Projects                      | .......................................................... Andrea Giorgio Busà  |
| Verifica: PAM IPT Sviluppo Quality Ass. CS Intell. & Dig. Solutions                        | .......................................................... Simonetta De Biase   |
| Approvazione: Technical Authority Public Administration Defence International Agencies LoB | .......................................................... Susanna Fortunato    |
| Approvazione: IPT Leader IPT di Sviluppo Hybrid Cloud Infrastructure                       | .......................................................... Davide Roggero       |
| Autorizzazione:  Product Manager IPT Prodotto Product & Technology Development             | .......................................................... Filippo Montenegro   |

**LISTA DELLE REVISIONI**

| **Rev.** | **Numero Modifiche** | **Data**   | **Descrizione**                  | **Autore/i** |
|----------|----------------------|------------|----------------------------------|--------------|
| 01.00    | -                    | 24/01/2022 | Prima emissione                  | D.Leone      |
| 02.00    | DCN222372            | 29/07/2022 | Integrazione Rilascio SCMP 2.0.0 | D.Leone      |
| 03.00    | DCN222981            | 20/12/2022 | Integrazione Rilascio SCMP 3.0.0 | D.Leone      |
| 04.00    | DCN230550            | 30/06/2023 | Integrazione Rilascio SCMP 4.0.0 | D.Leone      |

**  
INDICE**

[1 SCOPO](#_Toc166581660)

[1.1 Identificazione](#identificazione)

[1.2 Informazioni generali sul sistema](#_Toc166581662)

[1.3 Informazioni generali sul documento](#_Toc166581663)

[2 DOCUMENTI REFERENZIATI](#_Toc166581664)

[2.1 Documenti applicabili](#_Toc166581665)

[2.2 Documenti di riferimento](#_Toc166581666)

[3 RIEPILOGO DEL SOFTWARE](#riepilogo-del-software)

[3.1 Funzionalità software](#_Toc166581668)

[3.2 Inventario del software](#inventario-del-software)

[3.3 Ambiente software](#_Toc166581670)

[3.4 Organizzazione del software e panoramica del funzionamento](#_Toc166581671)

[3.5 Contingenze e stati/modalità di funzionamento alternativi](#_Toc166581672)

[3.6 Security e privacy](#_Toc166581673)

[3.7 Assistenza e segnalazione dei problemi](#_Toc166581674)

[4 ACCESSO AL SOFTWARE](#accesso-al-software)

[4.1 Primo utilizzo del software](#primo-utilizzo-del-software)

[4.1.1 Familiarizzazione dell'attrezzatura](#familiarizzazione-dellattrezzatura)

[4.1.2 Access control](#_Toc166581678)

[4.1.3 Installazione e setup](#installazione-e-setup)

[4.2 Avvio di una sessione](#_Toc166581680)

[4.3 Interruzione e sospensione del lavoro](#interruzione-e-sospensione-del-lavoro)

[5 GUIDA DI RIFERIMENTO ALL'ELABORAZIONE](#guida-di-riferimento-allelaborazione)

[5.1 Capacità](#capacità)

[5.2 Convenzioni](#convenzioni)

[5.3 Procedure di trattamento](#procedure-di-trattamento)

[5.4 Authentication](#authentication)

[5.4.1 Gruppi](#gruppi)

[5.4.1.1 Creazione Gruppi](#creazione-gruppi)

[5.4.1.2 Gestione utenti assegnati e attributi](#gestione-utenti-assegnati-e-attributi)

[5.4.1.3 Visualizzazione Modifica ed Eliminazione di un Gruppo](#visualizzazione-modifica-ed-eliminazione-di-un-gruppo)

[5.4.2 Utenti](#utenti)

[5.4.2.1 Creazione nuovi utenti](#creazione-nuovi-utenti)

[5.4.2.2 Assegnazione Ruoli e Attributi](#assegnazione-ruoli-e-attributi)

[5.4.2.3 Reset delle credenziali](#reset-delle-credenziali)

[5.4.2.4 Visualizzazione modifica ed Eliminazione di un Utente](#visualizzazione-modifica-ed-eliminazione-di-un-utente)

[5.4.3 Gestione menù abilitati per utente/Gruppo](#gestione-menù-abilitati-per-utentegruppo)

[5.4.1 Liste profili utente e Attributi](#_Toc166581697)

[5.4.1.1 Attributi (controllare che siano tutti)](#_Toc166581698)

[5.4.1.2 Amministratore](#_Toc166581699)

[5.4.1.3 Gestore del servizio](#_Toc166581700)

[5.4.1.4 Visualizzatore](#_Toc166581701)

[5.4.1.5 Autorizzato](#_Toc166581702)

[5.5 Gestione Tenant](#gestione-tenant)

[5.5.1 Creazione di un nuovo tenant](#creazione-di-un-nuovo-tenant)

[5.5.2 Visualizzazione , Modifica ed Eliminazione di un tenant](#visualizzazione--modifica-ed-eliminazione-di-un-tenant)

[5.6 Administration](#administration)

[5.6.1 provider/sottosistemi](#_Toc166581707)

[5.6.1.1 Lista dei sottosistemi](#lista-dei-sottosistemi)

[5.6.1.2 Creazione nuovo sottosistema](#creazione-nuovo-sottosistema)

[**5.6.1.2.1** **Parametri condivisi**](#parametri-condivisi)

[**5.6.1.2.2** **Parametri Azure**](#parametri-azure)

[**5.6.1.2.3** **Parametri AzureStack**](#parametri-azurestack)

[**5.6.1.2.4** **Parametri AzureStack HCI**](#parametri-azurestack-hci)

[**5.6.1.2.5** **Parametri AzureStack Hybrid cloud**](#parametri-azurestack-hybrid-cloud)

[**5.6.1.2.6** **Parametri Amazon Web Services**](#parametri-amazon-web-services)

[**5.6.1.2.7** **Parametri Google Cloud**](#_Toc166581716)

[**5.6.1.2.8** **Parametri Openshift**](#parametri-openshift)

[**5.6.1.2.9** **Parametri Oracle**](#parametri-oracle)

[**5.6.1.2.10** **Parametri VCloud**](#parametri-vcloud)

[**5.6.1.2.11** **Parametri VMWare**](#parametri-vmware)

[5.6.1.3 Verifica della connessione e salvataggio](#_Toc166581721)

[5.6.1.4 Visualizzazione edit ed eliminazione di un sottosistema](#_Toc166581722)

[5.6.1.5 Google Cloud Folders](#google-cloud-folders)

[5.6.1.6 Azure Folder](#azure-folder)

[5.6.2 SIEM](#siem)

[5.6.2.1 Visualizzazione, modifica ed eliminazione](#visualizzazione-modifica-ed-eliminazione)

[5.6.3 Secrets Managers](#secrets-managers)

[5.6.3.1 Azure key vault](#azure-key-vault)

[5.6.3.2 Google Secret Manager](#google-secret-manager)

[5.6.4 Visualizzazione , modifica ed eliminazione](#visualizzazione--modifica-ed-eliminazione)

[5.7 Dashboard](#dashboard)

[5.8 Inventory](#inventory)

[5.8.1 Dashboard di inventario](#dashboard-di-inventario)

[5.8.1.1 Visualizzazione dettaglio risorsa](#visualizzazione-dettaglio-risorsa)

[5.8.1.2 Azioni sulle macchine di inventario](#azioni-sulle-macchine-di-inventario)

[5.8.1 Reportistica Inventory](#_Toc166581736)

[5.8.1 Funzionalità “WHAT IF”](#funzionalità-what-if)

[5.8.1.1 Scenario “What If”: Provider Migration](#scenario-what-if-provider-migration)

[5.8.1.2 Scenario “What If”: Change Resource Capacity](#_Toc166581739)

[5.8.1.3 Esportazione scenario What If](#_Toc166581740)

[5.9 Catalog](#catalog)

[5.9.1 Gestione Elementi di catalogo SCMP](#gestione-elementi-di-catalogo-scmp)

[5.9.1.1 Relazioni tra risorse](#relazioni-tra-risorse)

[*5.9.1.1.1* Export delle risorse](#export-delle-risorse)

[*5.9.1.1.2* Funzionalità Aggiornamento Forzato del Catalogo](#funzionalità-aggiornamento-forzato-del-catalogo)

[*5.9.1.1.3* Creazione relazione di Catalogo](#_Toc166581746)

[5.9.1.1.4 Utilizzo della tabella di Catalogo](#utilizzo-della-tabella-di-catalogo)

[5.9.1.1.4.1 Visualizzazione riepilogo Risorsa](#visualizzazione-riepilogo-risorsa)

[5.9.1.1.4.2 Visualizzazione delle relazioni di Catalogo](#visualizzazione-delle-relazioni-di-catalogo)

[5.9.1.1.4.3 Modifica delle relazioni di Catalogo](#modifica-delle-relazioni-di-catalogo)

[5.9.1.1.4.4 Eliminazione delle relazioni di Catalogo](#eliminazione-delle-relazioni-di-catalogo)

[5.9.1.2 Relazioni tra SKU](#relazioni-tra-sku)

[*5.9.1.2.1* Export delle risorse](#export-delle-risorse-1)

[*5.9.1.2.2* Creazione relazione di Catalogo SKU](#creazione-relazione-di-catalogo-sku)

[5.9.1.2.3 Utilizzo della tabella di Catalogo](#utilizzo-della-tabella-di-catalogo-1)

[5.9.1.2.3.1 Visualizzazione riepilogo Risorsa](#visualizzazione-riepilogo-risorsa-1)

[5.9.1.2.3.2 Visualizzazione delle relazioni di Catalogo](#visualizzazione-delle-relazioni-di-catalogo-1)

[5.9.1.2.3.3 Modifica delle relazioni di Catalogo](#modifica-delle-relazioni-di-catalogo-1)

[5.9.1.2.3.4 Eliminazione delle relazioni SKU di Catalogo](#eliminazione-delle-relazioni-sku-di-catalogo)

[5.9.2 Gestione elementi di catalogo ricevuti dai Provider](#gestione-elementi-di-catalogo-ricevuti-dai-provider)

[5.9.2.1 Risorse](#risorse)

[*5.9.2.1.1* Export dei tagli del Provider](#export-dei-tagli-del-provider)

[*5.9.2.1.2* Funzionalità Aggiornamento Forzato del Catalogo](#funzionalità-aggiornamento-forzato-del-catalogo-1)

[5.9.2.1.3 Filtri delle risorse](#filtri-delle-risorse)

[*5.9.2.1.4* Visualizzazione Riepilogo Risorsa](#visualizzazione-riepilogo-risorsa-2)

[*5.9.2.1.5* Visualizzazione dei dettagli delle Risorse](#visualizzazione-dei-dettagli-delle-risorse)

[5.9.2.2 SKU](#sku)

[*5.9.2.2.1* Export dei tagli del Provider](#export-dei-tagli-del-provider-1)

[*5.9.2.2.2* Funzionalità Aggiornamento Forzato del Catalogo](#funzionalità-aggiornamento-forzato-del-catalogo-2)

[5.9.2.2.3 Filtri delle risorse](#filtri-delle-risorse-1)

[*5.9.2.2.4* Visualizzazione Riepilogo Risorsa](#visualizzazione-riepilogo-risorsa-3)

[*5.9.2.2.5* Visualizzazione dei dettagli delle Risorse](#visualizzazione-dei-dettagli-delle-risorse-1)

[5.9.3 Gestione elementi “Servizi e Blueprint”](#gestione-elementi-servizi-e-blueprint)

[5.9.3.1 Servizi](#servizi)

[5.9.3.1.1 Filtri della pagina “Services”](#filtri-della-pagina-services)

[*5.9.3.1.2* Creazione Services](#creazione-services)

[5.9.3.1.2.1 Servizi “Standard”](#servizi-standard)

[5.9.3.1.2.2 Servizi “Custom”](#servizi-custom)

[5.9.3.1.2.3 Servizi “azure pipeline”](#servizi-azure-pipeline)

[5.9.3.1.2.4 Servizi “PaaS”](#servizi-paas)

[5.9.3.1.2.5 Servizi “AI”](#servizi-ai)

[*5.9.3.1.3* Modifica ed Eliminazione Services](#modifica-ed-eliminazione-services)

[5.9.3.2 Gestione Blueprints](#gestione-blueprints)

[5.9.3.2.1 Aggiunta nuova blueprint](#aggiunta-nuova-blueprint)

[5.9.3.2.2 Status delle Blueprint](#_Toc166581785)

[5.9.3.2.3 Visualizzazione, Modifica ed Eliminazione delle Blueprint](#visualizzazione-modifica-ed-eliminazione-delle-blueprint)

[5.9.1 Gestione Openshift ( viene spostato su administration?)](#gestione-openshift)

[5.10 Costs](#costs)

[5.10.1 Visualizzazione costi per risorse](#_Toc166581789)

[5.10.2 Gestione dei TAG nella funzionalità di Cost Management](#_Toc166581790)

[5.10.3 Forecast](#_Toc166581791)

[5.10.4 Definizione di logiche di classificazione](#definizione-di-logiche-di-classificazione)

[5.10.5 Usages](#usages)

[5.10.6 Report dei costi](#_Toc166581794)

[5.11 Monitoring](#monitoring)

[5.11.1 Metriche delle risorse “VM” “Storage” “Network”](#_Toc166581796)

[5.11.2 Ricerca per tag nel modulo di Monitoring](#_Toc166581797)

[5.11.3 Shortcut dal Clusters alle metriche delle VM che lo compongono](#shortcut-dal-clusters-alle-metriche-delle-vm-che-lo-compongono)

[5.11.4 Reportistica Monitoring](#_Toc166581799)

[5.12 Security](#security)

[5.12.1 Dashboard generale](#_Toc166581801)

[5.12.2 Dashboard specifiche per tipologia di risorsa](#dashboard-specifiche-per-tipologia-di-risorsa)

[5.12.3 Dashboard SIEM](#_Toc166581803)

[5.12.4 Dashboard Secret Manager](#_Toc166581804)

[5.12.5 Dashboard Clusters](#dashboard-clusters)

[5.13 Provisioning](#provisioning)

[5.13.1 Dashboard](#dashboard-1)

[5.13.2 Specifiche della tabella dei provisioning](#_Toc166581808)

[5.13.2.1 “Resources”, “Services”, “Custom Services”](#resources-services-custom-services)

[5.13.2.2 Blueprint](#blueprint)

[5.13.3 Creazione dei provisioning](#_Toc166581811)

[5.13.3.1 Provisioning di “Risorse fisiche”](#provisioning-di-risorse-fisiche)

[**5.13.3.1.1** **Virtual Machines**](#virtual-machines)

[5.13.3.2 Provisioning di “Servizi”](#_Toc166581814)

[**5.13.3.2.1** **Servizi “standard”**](#servizi-standard-1)

[**5.13.3.2.2** **Servizi “Custom”**](#servizi-custom-1)

[**5.13.3.2.3** **Servizi “Azure Pipeline”**](#servizi-azure-pipeline-1)

[**5.13.3.2.4** **Servizi “PaaS” e “AI Services”**](#servizi-paas-e-ai-services)

[5.13.3.3 Creazione di una richiesta di provisioning “Blueprint”](#creazione-di-una-richiesta-di-provisioning-blueprint)

[5.13.3.3.1 Richiesta di esecuzione della “Blueprint”](#richiesta-di-esecuzione-della-blueprint)

[**5.13.3.3.2** **Pagina di gestione della blueprint “da completare”**](#_Toc166581821)

[5.13.3.4 Modifica di un provisioning effettuato](#step-automatici)

[5.14 Service Detail Design](#service-detail-design)

[5.14.1 Flusso dei Work Order](#flusso-dei-work-order)

[5.15 Cloud Maturity Model](#cloud-maturity-model)

[5.16 SCMP – VARIE](#scmp--varie)

[*5.16.1* Supporto multilingua](#supporto-multilingua)

[5.16.2 Reset filtri](#reset-filtri)

[5.16.3 Light mode](#light-mode)

[5.16.4 Switch Tenant](#switch-tenant)

[5.17 Trattamento correlato](#trattamento-correlato)

[5.18 Backup dei dati](#_Toc166581832)

[5.19 Recupero da errori, malfunzionamenti ed emergenze](#recupero-da-errori-malfunzionamenti-ed-emergenze)

[5.20 Messaggi](#messaggi)

[5.21 Questa guida di riferimento rapido](#_Toc166581835)

[6 NOTE](#_Toc166581836)

[6.1 Definizioni](#_Toc166581837)

[6.2 Acronimi](#_Toc166581838)

**INDICE DELLE FIGURE**

[Figura 1 - Schermata di login](#_Toc166585133)

[Figura 2 - Lista dei ruoli presenti](#_Toc166585134)

[Figura 3 - Aggiunta di un ruolo](#_Toc166585135)

[Figura 4 - Eliminazione di un ruolo](#_Toc166585136)

[Figura 5 - Modifica di un ruolo](#_Toc166585137)

[Figura 6 - Lista degli utenti](#_Toc166585138)

[Figura 7 - Aggiunta utente](#_Toc166585139)

[Figura 8 - Eliminazione utente](#_Toc166585140)

[Figura 9 - Modifica utente](#_Toc166585141)

[Figura 10 - Assegnazione dei ruoli dell'utente](#_Toc166585142)

[Figura 11 - Schermata di login](#_Toc166585143)

[Figura 12 - Logout dalla piattaforma di SCMP](#_Toc166585144)

[Figura 13 - Dashboard](#_Toc166585145)

[Figura 14 - Pulsante "Bento"](#_Toc166585146)

[Figura 15 - Lista delle Funzionalità](#_Toc166585147)

[Figura 16 - Accesso alla funzionalità Authentication](#_Toc166585148)

[Figura 17 - Dashboard di IAM](#_Toc166585149)

[Figura 18 - Accesso alla gestione Gruppi](#_Toc166585150)

[Figura 19 - Lista dei gruppi configurati](#_Toc166585151)

[Figura 20 - Aggiunta nuovo Gruppo](#_Toc166585152)

[Figura 21 – Parametri di inserimento Gruppo](#_Toc166585153)

[Figura 22 - Accesso gestione assegnazione utenti](#_Toc166585154)

[Figura 23 - Assegnare un utente al gruppo](#_Toc166585155)

[Figura 24 - Inserire Attributi](#_Toc166585156)

[Figura 25 - Pulsanti di controllo](#_Toc166585157)

[Figura 26 - Accesso alla gestione Utenti](#_Toc166585158)

[Figura 27 - Lista degli utenti configurati](#_Toc166585159)

[Figura 28 - Creazione nuovo utente](#_Toc166585160)

[Figura 29 - Maschera di creazione utente](#_Toc166585161)

[Figura 30 - Accesso alla gestione utente](#_Toc166585162)

[Figura 31 - Associare un utente al gruppo](#_Toc166585163)

[Figura 32 – Dissociare un utente dal gruppo](#_Toc166585164)

[Figura 33 - Inserire Attributi](#_Toc166585165)

[Figura 34 - Modifica della password per l'utente](#_Toc166585166)

[Figura 35 - Pulsanti di controllo](#_Toc166585167)

[Figura 36 - Accesso alla gestione menù](#_Toc166585168)

[Figura 37 - Selezione dell' utente/gruppo da modificare](#_Toc166585169)

[Figura 38 - Gestione delle autorizzazioni del menù](#_Toc166585170)

[Figura 39 - Accesso alla gestione Tenant](#_Toc166585171)

[Figura 40 - Aggiungi nuovo tenant](#_Toc166585172)

[Figura 41 – Form di creazione nuovo tenant](#_Toc166585173)

[Figura 42 – Sezione di inizializzazione catalogo](#_Toc166585174)

[Figura 43 - Pulsanti di controllo](#_Toc166585175)

[Figura 44 - Accesso ad Administration](#_Toc166585176)

[Figura 45 - Aggiunta di un nuovo Cloud Provider](#_Toc166585177)

[Figura 46 - Parametri generali di un sottosistema](#_Toc166585178)

[Figura 47 - Maschera di configurazione Azure](#_Toc166585179)

[Figura 48 - Maschera di configurazione AzureStack](#_Toc166585180)

[Figura 49 - Maschera di configurazione AzureStack HCI](#_Toc166585181)

[Figura 50 - Maschera di configurazione AzureStack Hybrid cloud](#_Toc166585182)

[Figura 51 - Maschera di configurazione Amazon Web Services](#_Toc166585183)

[Figura 52 - Maschera di configurazione Google](#_Toc166585184)

[Figura 53 - Caricamento del file di configurazione](#_Toc166585185)

[Figura 54 - Maschera di configurazione Openshift](#_Toc166585186)

[Figura 55 - Maschera di configurazione Oracle](#_Toc166585187)

[Figura 56 - Maschera di configurazione VCloudDirector](#_Toc166585188)

[Figura 57 - Maschera di configurazione VMWare](#_Toc166585189)

[Figura 58 - Pulsanti di connessione](#_Toc166585190)

[Figura 59- Accesso al Cloud Provider in modalità visualizzazione](#_Toc166585191)

[Figura 60 - Visualizzazione cloud in modalità visualizzazione](#_Toc166585192)

[Figura 61 - Lista macchine On-Premise](#_Toc166585193)

[Figura 62 - Accesso al Cloud Provider in modalità edit](#_Toc166585194)

[Figura 63 - Avvio per l'eliminazione di un Cloud Provider](#_Toc166585195)

[Figura 64 - Conferma eliminazione del Cloud Provider](#_Toc166585196)

[Figura 65 – Parametri specifici di Google Cloud](#_Toc166585197)

[Figura 66 – Accesso a Folders](#_Toc166585198)

[Figura 67 – Visualizzazione sottosistemi della Folder](#_Toc166585199)

[Figura 68 - Opzione folder Azure](#_Toc166585200)

[Figura 69 - Maschera di configurazione Azure](#_Toc166585201)

[Figura 70 - Creazione di un cloud provider SIEM](#_Toc166585202)

[Figura 71 - Compilazione del form per la creazione di un provider SIEM](#_Toc166585203)

[Figura 72 - Accesso al SIEM in modalità visualizzazione](#_Toc166585204)

[Figura 73 - SIEM in modalità visualizzazione](#_Toc166585205)

[Figura 74 - Accesso al SIEM in modalità edit](#_Toc166585206)

[Figura 75 - SIEM in modalità edit](#_Toc166585207)

[Figura 76 - Opzione per eliminare un SIEM "Delete"](#_Toc166585208)

[Figura 77 - Conferma per eliminare un SIEM](#_Toc166585209)

[Figura 78 - Aggiunta di un nuovo Secret Manager](#_Toc166585210)

[Figura 79 - Maschera di configurazione Azure key vault](#_Toc166585211)

[Figura 80 - Maschera di configurazione Google Secret Manager](#_Toc166585212)

[Figura 81 - Accesso al manager in modalità visualizzazione](#_Toc166585213)

[Figura 82 - Visualizzazione manager in modalità visualizzazione](#_Toc166585214)

[Figura 83 - Accesso al manager in modalità edit](#_Toc166585215)

[Figura 84 - Avvio per l'eliminazione di un Secret manager](#_Toc166585216)

[Figura 85 - Conferma eliminazione del Secret manager](#_Toc166585217)

[Figura 86 - Dashboard sezione "Inventory"](#_Toc166585218)

[Figura 87 - Dashboard sezione "Monitoring"](#_Toc166585219)

[Figura 88 - Dashboard sezione "Costs"](#_Toc166585220)

[Figura 89 - Dashboard sezione "Security"](#_Toc166585221)

[Figura 90 - Accesso a Inventory](#_Toc166585222)

[Figura 91 – Dahsboard di inventario](#_Toc166585223)

[Figura 92 - Ricerca generica, per tag, per Provider e Subsystem](#_Toc166585224)

[Figura 93 - Accesso alla risorsa in modalità lettura](#_Toc166585225)

[Figura 94 - Dettaglio risorsa](#_Toc166585226)

[Figura 95 - Grafico delle relazioni](#_Toc166585227)

[Figura 96 - Selezione del tag](#_Toc166585228)

[Figura 97 - Accesso al report di Inventory](#_Toc166585229)

[Figura 98 - Accesso al report di Inventory](#_Toc166585230)

[Figura 99 - Esecuzione del report](#_Toc166585231)

[Figura 100 - Applicazione dei filtri report](#_Toc166585232)

[Figura 101 - Gestione dello storico dei report](#_Toc166585233)

[Figura 102 - Gestione pagine report](#_Toc166585234)

[Figura 103 - Sommario del report](#_Toc166585235)

[Figura 104 - Accesso a “What If”](#_Toc166585236)

[Figura 105 - Pagina di “What If”](#_Toc166585237)

[Figura 106 - Accesso alla funzionalità "What If: Migrate Provider"](#_Toc166585238)

[Figura 107 - Scelta delle risorse in cui effettuare la migrazione del provider](#_Toc166585239)

[Figura 108 - Scelta del Cloud Provider in cui migrare le risorse](#_Toc166585240)

[Figura 109 - Selezione della "Regione" e del "Cost Model"](#_Toc166585241)

[Figura 110 - Selezione dell'intervallo di tempo](#_Toc166585242)

[Figura 111 - Parametri di configurazione e consiglio sulla simulazione](#_Toc166585243)

[Figura 112 - Tabella riassuntiva della/e risorse](#_Toc166585244)

[Figura 113 - Avvio per l'aggiornamento della simulazione di tipo "Migrate to another provider"](#_Toc166585245)

[Figura 114 - Accesso alla funzionalità "What If: Change resources capacity"](#_Toc166585246)

[Figura 115 - Selezione delle risorse da cui modificare le capacità](#_Toc166585247)

[Figura 116 - Modifica della size di una risorsa](#_Toc166585248)

[Figura 117 - Selezione dell'intervallo per la simulazione](#_Toc166585249)

[Figura 118 - Parametri di configurazione e consiglio sulla simulazione](#_Toc166585250)

[Figura 119 - Export della simulazione](#_Toc166585251)

[Figura 120 - Stampa della simulazione](#_Toc166585252)

[Figura 121 - Opzione per eliminare una simulazione](#_Toc166585253)

[Figura 122 - Conferma dell'eliminazione della simulazione](#_Toc166585254)

[Figura 123 - Lista simulazioni già eseguite](#_Toc166585255)

[Figura 124 - Aggiornamento della simulazione](#_Toc166585256)

[Figura 125 - Accesso a Catalog](#_Toc166585257)

[Figura 126 - Catalogo della SCMP](#_Toc166585258)

[Figura 127 - Catalogo SCMP filtrato](#_Toc166585259)

[Figura 128 - Accesso a "Relazioni"](#_Toc166585260)

[Figura 129 – Scaricare la lista di risultati](#_Toc166585261)

[Figura 130 – Funzionalità Force Sync](#_Toc166585262)

[Figura 131 - Opzione per aggiungere una risorsa](#_Toc166585263)

[Figura 132 - Selezione del tipo di risorsa da creare](#_Toc166585264)

[Figura 133 – Esempio di form per la creazione di una relazione](#_Toc166585265)

[Figura 134 - Sezione tag e note](#_Toc166585266)

[Figura 135 - Selezione del provider per associare le risorse](#_Toc166585267)

[Figura 136 - Sezione costi delle relazioni](#_Toc166585268)

[Figura 137 - Risorse associate alla risorsa SCMP](#_Toc166585269)

[Figura 138 – Creazione automatica del Relation Chart](#_Toc166585270)

[Figura 139 – Dettaglio rapido delle risorse di catalogo](#_Toc166585271)

[Figura 140 - Accesso alla risorsa in modalità view](#_Toc166585272)

[Figura 141 - Dettaglio completo delle risorse di catalogo](#_Toc166585273)

[Figura 142 - Sezione proprietà degli elementi del catalogo](#_Toc166585274)

[Figura 143 - Sezione Tags & Note degli elementi del catalogo](#_Toc166585275)

[Figura 144 - Sezione delle relazioni del catalogo SCMP](#_Toc166585276)

[Figura 145 - Sezione Relations Chart delle risorse](#_Toc166585277)

[Figura 146 - Accesso alla risorsa in modalità edit](#_Toc166585278)

[Figura 147 - Modifica della relazione](#_Toc166585279)

[Figura 148 - Eliminazione di una risorsa](#_Toc166585280)

[Figura 149 - Conferma eliminazione della risorsa](#_Toc166585281)

[Figura 150 - Accesso a "CMP SKU"](#_Toc166585282)

[Figura 151 – Scaricare la lista di risultati](#_Toc166585283)

[Figura 152 - Opzione per aggiungere una risorsa “SKU”](#_Toc166585284)

[Figura 153 – Pagina di creazione “SKU”](#_Toc166585285)

[Figura 154 - Compilazione dei campi, selezione Properties](#_Toc166585286)

[Figura 155 - conferma della formula di conversione](#_Toc166585287)

[Figura 156 - Drag and drop Relazioni SKU](#_Toc166585288)

[Figura 157 – Creazione automatica del Relation Chart](#_Toc166585289)

[Figura 158 – Dettaglio rapido delle risorse SKU](#_Toc166585290)

[Figura 159 - Accesso alla risorsa in modalità view](#_Toc166585291)

[Figura 160 - Dettaglio completo delle risorse di catalogo](#_Toc166585292)

[Figura 161 - Sezione proprietà degli elementi SKU di catalogo](#_Toc166585293)

[Figura 162 - Sezione Tags & Note degli elementi SKU di catalogo](#_Toc166585294)

[Figura 163 - Sezione delle relazioni degli SKU di catalogo](#_Toc166585295)

[Figura 164 - Sezione Relations Chart delle risorse](#_Toc166585296)

[Figura 165 - Accesso alla risorsa in modalità edit](#_Toc166585297)

[Figura 166 - Eliminazione di una risorsa SKU](#_Toc166585298)

[Figura 167 - Conferma eliminazione della risorsa](#_Toc166585299)

[Figura 168 - Risorse del catalogo dei providers](#_Toc166585300)

[Figura 169 – Esportazione dei risultati](#_Toc166585301)

[Figura 170 - Funzionalità Force Sync](#_Toc166585302)

[Figura 171 - Filtri del Catalogo](#_Toc166585303)

[Figura 172 – Dettaglio rapido delle risorse di catalogo](#_Toc166585304)

[Figura 173 - Accesso alla risorsa in modalità view](#_Toc166585305)

[Figura 174 - Dettaglio Risorsa dal Modulo Catalog](#_Toc166585306)

[Figura 175 - Sezione costi della risorsa](#_Toc166585307)

[Figura 176 - Risorse del catalogo dei providers](#_Toc166585308)

[Figura 177 – Esportazione dei risultati](#_Toc166585309)

[Figura 178 - Funzionalità Force Sync](#_Toc166585310)

[Figura 179 - Filtri del Catalogo](#_Toc166585311)

[Figura 180 – Dettaglio rapido delle risorse di catalogo](#_Toc166585312)

[Figura 181 - Accesso alla risorsa in modalità view](#_Toc166585313)

[Figura 182 - Dettaglio Risorsa dal Modulo Catalog](#_Toc166585314)

[Figura 183 - Sezione costi della risorsa](#_Toc166585315)

[Figura 184 - Accesso ai "Services"](#_Toc166585316)

[Figura 185 - Pagina dei servizi](#_Toc166585317)

[Figura 186 - Filtri disponibili](#_Toc166585318)

[Figura 187 - Accesso al form di creazione del Service](#_Toc166585319)

[Figura 188 - Selezione della tipologia di servizio](#_Toc166585320)

[Figura 189 - Aggiunta nuova categoria](#_Toc166585321)

[Figura 190 Parametri generali dei "Custom Services"](#_Toc166585322)

[Figura 191 - Selezione della tipologia di Orchestratore](#_Toc166585323)

[Figura 192 Parametri generali "Azure pipeline service"](#_Toc166585324)

[Figura 193 - Parametri specifici delle Pipeline](#_Toc166585325)

[Figura 194 - Selezione della pipeline](#_Toc166585326)

[Figura 195 Parametri generali dei "PaaS Services"](#_Toc166585327)

[Figura 196 - Parametri dei "Servizi AI"](#_Toc166585328)

[Figura 197 - Sblocco della sezione "Docker"](#_Toc166585329)

[Figura 198 - Parametri della sezione docker](#_Toc166585330)

[Figura 199 - Operazioni disponibili per i Services](#_Toc166585331)

[Figura 200 – Pagina di edit per un servizio](#_Toc166585332)

[Figura 201 - Eliminazione di un servizio](#_Toc166585333)

[Figura 202 - Accesso alle "Blueprint"](#_Toc166585334)

[Figura 203 - Pagina delle Blueprint](#_Toc166585335)

[Figura 204 - Aggiunta nuova Blueprint](#_Toc166585336)

[Figura 205 - Blueprint step 1](#_Toc166585337)

[Figura 206 - Blueprint conferma della bozza](#_Toc166585338)

[Figura 207 - Inserimento file](#_Toc166585339)

[Figura 208 - Status delle Blueprint](#_Toc166585340)

[Figura 209 - Sezioni della pagina Blueprint "view"](#_Toc166585341)

[Figura 210 - Sezione Plan di una Blueprint](#_Toc166585342)

[Figura 211 -Sezione Topology di una Blueprint](#_Toc166585343)

[Figura 212 - Sezioni della pagina Blueprint "edit"](#_Toc166585344)

[Figura 213 - Sezione Plan di una Blueprint](#_Toc166585345)

[Figura 214 -Sezione Topology di una Blueprint](#_Toc166585346)

[Figura 215 - Sezione Model di una Blueprint](#_Toc166585347)

[Figura 216 - Eliminazione di una Blueprint](#_Toc166585348)

[Figura 217 - Accesso a "Openshift"](#_Toc166585349)

[Figura 218 - Configurazione Modello "Openshift"](#_Toc166585350)

[Figura 219 - Eliminazione Modello "Openshift"](#_Toc166585351)

[Figura 220 - Accesso a Costs](#_Toc166585352)

[Figura 221 - Visualizzazione del grafico in base al range temporale e granularità dei costi](#_Toc166585353)

[Figura 222 - Tabella delle risorse](#_Toc166585354)

[Figura 223 - Ricerca dei costi per TAG](#_Toc166585355)

[Figura 224 - Previsione dei costi giornalieri](#_Toc166585356)

[Figura 225 - Previsione dei costi accumulati](#_Toc166585357)

[Figura 226 - Aggregazione delle risorse per tipologia, provider e regione](#_Toc166585358)

[Figura 227 – Filtri modulo Usages](#_Toc166585359)

[Figura 228 – Grafici costi su base Provider e Sottosistema](#_Toc166585360)

[Figura 229 – Grafici costi su base SKU](#_Toc166585361)

[Figura 230 – Dettaglio costi su SKU](#_Toc166585362)

[Figura 231 – Dettaglio costi per risorsa](#_Toc166585363)

[Figura 232 - Accesso ai report Costs](#_Toc166585364)

[Figura 233 - Tipi di report Costs](#_Toc166585365)

[Figura 234 - Applicazione dei filtri report](#_Toc166585366)

[Figura 235 - Storico dei report](#_Toc166585367)

[Figura 236 - Gestione delle pagine report](#_Toc166585368)

[Figura 237 - Sommario report](#_Toc166585369)

[Figura 238 - Accesso al Modulo di Monitoring](#_Toc166585370)

[Figura 239 - Dashboard di Monitoring](#_Toc166585371)

[Figura 240 - Grafico delle metriche](#_Toc166585372)

[Figura 241 - Ricerca delle metriche](#_Toc166585373)

[Figura 242 - Ricerca delle metriche per TAG](#_Toc166585374)

[Figura 243 - Grafico con shortcut a sottomodulo Virtual Machines](#_Toc166585375)

[Figura 244 - Grafico delle metriche su Virtual Machines](#_Toc166585376)

[Figura 245 - Accesso al report di Monitoring](#_Toc166585377)

[Figura 246 - Esecuzione del report](#_Toc166585378)

[Figura 247 - Applicazione dei filtri report](#_Toc166585379)

[Figura 248 - Gestione dello storico dei report](#_Toc166585380)

[Figura 249 - Sommario del report](#_Toc166585381)

[Figura 250 - Gestione pagine report](#_Toc166585382)

[Figura 251 - Accesso ai report precendenti](#_Toc166585383)

[Figura 252 - Accesso a Security](#_Toc166585384)

[Figura 253 – Dashboard di Security](#_Toc166585385)

[Figura 254 - Tabella delle policies](#_Toc166585386)

[Figura 255 - Dettaglio delle policy](#_Toc166585387)

[Figura 256 - Dashboard delle compliance delle Virtual Machines](#_Toc166585388)

[Figura 257 - Dashboard SIEM](#_Toc166585389)

[Figura 258 - “Event types" della dashboard SIEM](#_Toc166585390)

[Figura 259 - Tabelle "Alert rules" e "Incidents"](#_Toc166585391)

[Figura 260 - Dettaglio degli "Incidents"](#_Toc166585392)

[Figura 261 - Dashboard di Key Vault](#_Toc166585393)

[Figura 262 - Risorse visualizzabili](#_Toc166585394)

[Figura 263 - Dettaglio della chiave](#_Toc166585395)

[Figura 264 – Dashboard dei “Cluster alerts”](#_Toc166585396)

[Figura 265 - Tabella degli alert](#_Toc166585397)

[Figura 266 - Dettaglio degli Alert sui clusters](#_Toc166585398)

[Figura 267 - Accesso a "Provisioning"](#_Toc166585399)

[Figura 268 – Grafici della pagina di provisioning](#_Toc166585400)

[Figura 269 – Filtro per tipologia di asset](#_Toc166585401)

[Figura 270 - Tabella “Resources”](#_Toc166585402)

[Figura 271 - Visualizzazione messaggio Terraform](#_Toc166585403)

[Figura 272 - Visualizzazione grafico risorse](#_Toc166585404)

[Figura 273 – Tab della tabella “Provisioning blueprint”](#_Toc166585405)

[Figura 274 – Visualizzazione flow “Da completare”](#_Toc166585406)

[Figura 275 – Visualizzazione flow “Completato”](#_Toc166585407)

[Figura 276 - Tab per la creazione di risorse](#_Toc166585408)

[Figura 277 – Selezione del sottosistema “target”, provisioning step 1](#_Toc166585409)

[Figura 278 - Compilazione dei campi del form di previsione di una risorsa](#_Toc166585410)

[Figura 279 - Schermata della previsione](#_Toc166585411)

[Figura 280 - Lista delle previsioni](#_Toc166585412)

[Figura 281 - Lista delle card](#_Toc166585413)

[Figura 282 - Provisioning di un servizio “standard”](#_Toc166585414)

[Figura 283 - Configurazione di un servizio “standard”](#_Toc166585415)

[Figura 284 - Sommario della configurazione del servizio](#_Toc166585416)

[Figura 285 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati](#_Toc166585417)

[Figura 286 - Provisioning di un servizio “Custom”](#_Toc166585418)

[Figura 287 - Configurazione di un servizio “custom”](#_Toc166585419)

[Figura 288 - Sommario della configurazione del servizio](#_Toc166585420)

[Figura 289 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati](#_Toc166585421)

[Figura 290 - Provisioning di un servizio “Azure pipeline”](#_Toc166585422)

[Figura 291 - Configurazione di un servizio “Azure pipeline”](#_Toc166585423)

[Figura 292 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati](#_Toc166585424)

[Figura 293 - Configurazione di un servizio “PaaS”](#_Toc166585425)

[Figura 294 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati](#_Toc166585426)

[Figura 295 - Lista delle blueprint](#_Toc166585427)

[Figura 296 - Step 1 della creazione di una Blueprint](#_Toc166585428)

[Figura 297 - Step 2 della creazione "Blueprint"](#_Toc166585429)

[Figura 298 - Richiesta "Blueprint" inviata correttamente](#_Toc166585430)

[Figura 299 - Flow del piano di provisioning](#_Toc166585431)

[Figura 300 – Sezione sottoprocessi delle blueprint](#_Toc166585432)

[Figura 301 - Avvio della modifica di un Provisioning](#_Toc166585433)

[Figura 302 - Parametri di configurazione](#_Toc166585434)

[Figura 303 - Modifica dei parametri](#_Toc166585435)

[Figura 304 - Prospetto del Provisioning e tabella dei preventivi](#_Toc166585436)

[Figura 305 - Accesso a modulo Service Detail Design](#_Toc166585437)

[Figura 306 – Filtri della funzionalità Service Detail Design](#_Toc166585438)

[Figura 307 - Dettagli dell'Ordine di Lavoro](#_Toc166585439)

[Figura 308 - Pagina di gestione dei work order dei Service Detail Design](#_Toc166585440)

[Figura 309 - Chiusura di un Work order](#_Toc166585441)

[Figura 310 - Inserimento parametri](#_Toc166585442)

[Figura 311 - Informazioni aggiunte durante la lavorazione](#_Toc166585443)

[Figura 312 - Menu per effettuare la modifica della lingua](#_Toc166585444)

[Figura 313 - Dettaglio impostazione filtri](#_Toc166585445)

[Figura 314 - Attivazione della light mode](#_Toc166585446)

[Figura 315 - Disattivazione della light mode](#_Toc166585447)

[Figura 316 - Menu per lo switch Tenant](#_Toc166585448)

[Figura 317 - Switch del Tenant](#_Toc166585449)

**INDICE DELLE TABELLE**

[Tabella 1 - Categorie SCMP](#_Toc166585450)

[Tabella 2 – lista degli Attributi configurabili](#_Toc166585451)

[Tabella 3 - Autorizzazioni Utente Amministratore](#_Toc166585452)

[Tabella 4 - Autorizzazioni Utente gestore](#_Toc166585453)

[Tabella 5 - Autorizzazioni Utente Visualizzatore](#_Toc166585454)

[Tabella 6 - Autorizzazioni Utente autorizzato](#_Toc166585455)

[Tabella 7 – parametri generali tenant](#_Toc166585456)

[Tabella 8 – Parametri di data persistance](#_Toc166585457)

[Tabella 9 – Campi specifici Azure](#_Toc166585458)

[Tabella 10 – Campi specifici AzureStack](#_Toc166585459)

[Tabella 11 – Campi specifici AzureStack HCI](#_Toc166585460)

[Tabella 12 – Campi specifici AzureStack Hybrid Cloud](#_Toc166585461)

[Tabella 13 – Campi specifici Amazon Web Services](#_Toc166585462)

[Tabella 14 – Campi specifici Google](#_Toc166585463)

[Tabella 15 – Campi specifici obbligatori del file “service_account.json”](#_Toc166585464)

[Tabella 16 – Campi specifici OpenShift](#_Toc166585465)

[Tabella 17 – Campi specifici Oracle](#_Toc166585466)

[Tabella 18 – Campi specifici VCloud Director](#_Toc166585467)

[Tabella 19 – Campi specifici Azure](#_Toc166585468)

[Tabella 20 – Campi specifici Google Folder](#_Toc166585469)

[Tabella 21 – Campi specifici Azure Folder](#_Toc166585470)

[Tabella 22 – Campi specifici SENTINEL](#_Toc166585471)

[Tabella 23 – Campi specifici Azure key vault](#_Toc166585472)

[Tabella 24 – Campi specifici Google Secret Manager](#_Toc166585473)

[Tabella 25 – Campi specifici obbligatori del file “service_account.json”](#_Toc166585474)

[Tabella 26 – Campi specifici relazione VM](#_Toc166585475)

[Tabella 27 – Campi “Properties” specifici SKU](#_Toc166585476)

# SCOPO

Il presente documento è il manuale d’uso della *Cloud Management Platform* nell’ambito dell’iniziativa di investimento “WP7 Cloud Management Platform (SCMP)” della linea di prodotto Digitalization.

## Identificazione

N/A

## Informazioni generali sul sistema

SCMP è la piattaforma di cloud management di Leonardo S.p.a. che permette la governance, la gestione del ciclo di vita, il brokering e l’automazione delle risorse gestite in ambiente cloud.

## Informazioni generali sul documento

Il presente documento rappresenta il Manuale di utilizzo della piattaforma SCMP e contiene informazioni relative all’accesso al software e informazioni di dettaglio sul tool.

# DOCUMENTI REFERENZIATI

## Documenti applicabili

| **Rif.** | **Identificativo**      | **Revisione** | **Titolo**                               |
|----------|-------------------------|---------------|------------------------------------------|
|          | DI-IPSC-81443           | 01            | MIL-STD-498 - SOFTWARE USER MANUAL (SUM) |
|          | S20003.02.1119WPD@01.00 | 01.00         | Sprint Statement SCMP 2023               |
|          |                         |               |                                          |

## Documenti di riferimento

| **Rif.** | **Identificativo** | **Revisione** | **Titolo**                            |
|----------|--------------------|---------------|---------------------------------------|
|          | C000SCMP01SRS01    | 05.00         | SRS: SCMP - Cloud Management Platform |
|          | C000CMM01SUM01     | 01.00         | SUM: CMM – Cloud Maturity Model       |

# RIEPILOGO DEL SOFTWARE

## Funzionalità software

Lo sviluppo della Cloud Management Platform nasce per soddisfare il bisogno di gestire, orchestrare, proteggere e governare ambienti Cloud ibridi, multi-cloud e edge computing.

La SCMP svolge un ruolo essenziale per una gestione integrata di ambienti complessi dove possono coesistere e cooperare servizi erogati da molteplici Cloud Service Provider e servizi presenti su infrastrutture on premise o in infrastrutture edge.

L’integrazione tra i vari moduli che la compongono permette la gestione di tutte le funzionalità presenti su SCMP che possono essere raggruppate per le seguenti categorie:

| **Monitoring**            | Monitoraggio Instanze Inventario.                                        |
|---------------------------|--------------------------------------------------------------------------|
| **Costs**                 | Visualizzazione e Reportistica Costi                                     |
| **Inventory**             | Visualizzazione, Reportistica e Scenari “what if” Inventario             |
| **Security**              | Visualizzazione e gestione falle di sicurezza sugli asset di inventario. |
| **Dashboard**             | Visualizzazione sintetica dei vari moduli                                |
| **Catalog**               | Gestione e definizione elementi a Catalogo                               |
| **Autentication**         | Profilatura Utenti                                                       |
| **Administration**        | Amministrazione Provider                                                 |
| **Cloud Maturity model**  | Strumento a supporto del processo di migrazione al cloud                 |
| **Provisioning**          | Provisioning asset sottosistemi e software                               |
| **Tenant Managment**      | Gestione e creazione di Tenant                                           |
| **Service Detail Design** | Ricezione e gestione di ordini di lavoro da svolgere nella SCMP          |

Tabella 1 - Categorie SCMP

## Inventario del software

N/A

## Ambiente software

Per accedere alla SCMP occorre utilizzare un laptop collegato ad internet tramite browser qualsiasi.

## Organizzazione del software e panoramica del funzionamento

N/A

## Contingenze e stati/modalità di funzionamento alternativi

N/A

## Security e privacy

## Assistenza e segnalazione dei problemi

N/A

# ACCESSO AL SOFTWARE

## Primo utilizzo del software

Sull’argomento accesso ed utilizzo al software, si rimanda al Capitolo 4.2.

### Familiarizzazione dell'attrezzatura

Per usare il software di SCMP è necessario un personal computer e un browser.

### Access control

La Web Application dello IAM è stata costruita a partire da **KeyClock** (https://www.keycloak.org/), tool opensource di uso molto comune che ne amplia le funzionalità.

La piattaforma permette di definire la granularità di permessi per utente con un alto dettaglio, fino alla visualizzazione o meno di un singolo attributo su qualsiasi pagina.

Il JWT, generato da un login andato a buon fine, viene poi utilizzato dai microservices di frontend per chiamare le API messe a disposizione dai microservices di backend, esposte tramite un proxy (kong) che verifica la validità del JWT prima di inoltrare la richiesta verso gli strati inferiori.

Di seguito la form di login del modulo di amministrazione dello IAM:

![](media/90ebebfb06288c1e101c611e9ef5f093.png)

Figura 1 - Schermata di login

Per accedervi è necessaria una utenza di amministrazione.

Nella sezione “Roles” è possibile aggiungere (Add Roles), eliminare (Delete) o modificare (Edit) i ruoli. I ruoli principali sono: globalReader, globalExporter, globalConverter, globalImporter, globalWriter e globalAdmin. Le immagini sottostanti mostrano come eseguire queste operazioni.

![](media/93aebd6b2e948d343b474113a6e01f58.png)

Figura 2 - Lista dei ruoli presenti

![](media/b3386d117090fa880728256540395d10.png)

Figura 3 - Aggiunta di un ruolo

![](media/5d49c69b6de484b5a0a07b486e5b1f17.png)

Figura 4 - Eliminazione di un ruolo

![](media/2c633ceccc460bd5e6b4ea7ae2587dac.png)

Figura 5 - Modifica di un ruolo

Nella sezione “Users” è possibile aggiungere (Add user), eliminare (Delete) o modificare (Edit) gli utenti. Una volta all’interno dell’utente potremo accedere a Details, Attributes, Credentials, Role Mappings, Groups, Consents e Sessions. In particolare, all’interno di Role Mappings è possibile aggiungere o rimuovere i ruoli elencati nella sezione “Roles”. Le immagini sottostanti mostrano come eseguire queste operazioni.

![](media/6740dd2342957d2b6b6b040c7a3e90b9.png)

Figura 6 - Lista degli utenti

![](media/b7bd9ba5d2031c4b2446bad0a810a31c.png)

Figura 7 - Aggiunta utente

![Immagine che contiene testo Descrizione generata automaticamente](media/9246af0ce9c1869fbe87865787eccb2a.png)

Figura 8 - Eliminazione utente

![](media/a2ddb8ffe46528a88ade067e6bea9db2.png)

Figura 9 - Modifica utente

![](media/7ea5f1b9208a133a217107ef74f266df.png)

Figura 10 - Assegnazione dei ruoli dell'utente

### Installazione e setup

Per accedere all’applicativo di SCMP, con un browser collegarsi al sito [https://SCMP-sspa-dev3.westeurope.cloudapp.azure.com](https://cmp-sspa-dev3.westeurope.cloudapp.azure.com)

## Avvio di una sessione

Ecco come si presenta la pagina di login:

*![](media/56be0f10437a82a327bedf93697f5a2f.png)*

Figura 11 - Schermata di login

Per accedere alla piattaforma è necessario essere accreditati e di conseguenza inserire le proprie credenziali (username e password).

## Interruzione e sospensione del lavoro

Per effettuare il logout dalla piattaforma di “SCMP”, in alto a destra, cliccare sul pulsante che raffigura un omino. A questo punto, cliccare su “Logout”. In questo modo, l’utente viene reindirizzato nella schermata di login. Nella barra del titolo del browser, cliccare sul pulsante che raffigura una “X” per chiudere la finestra.

![](media/a9c11ed6601e4cb4e874ce3f34880a51.png)

Figura 12 - Logout dalla piattaforma di SCMP

# GUIDA DI RIFERIMENTO ALL'ELABORAZIONE

## Capacità

Una volta eseguito l’accesso il sistema presenta al cliente una dashboard (Figura 13) all’interno della quale sono riepilogate le seguenti informazioni:

-   Sezione “Inventory”
-   Sezione “Monitoring”
-   Sezione “Costs”
-   Sezione “Security”

![](media/53e76dfc9ab4a0207a5f61103ccb0453.png)

Figura 13 - Dashboard

Le funzionalità sono disponibili/attivabili tramite la barra del menu visibile selezionando il tasto bento presente nell’angolo in alto a sinistra della finestra.

![](media/c8ef8c925e78639b4fec2aa576bd79ff.png)

Figura 14 - Pulsante "Bento"

Le funzionalità disponibili sono organizzate come segue:

![A screenshot of a phone Description automatically generated with low confidence](media/0c4d397d20838c6aa5053757a6908d96.png)

Figura 15 - Lista delle Funzionalità

Nota: *l’ordine delle funzionalità è dipendente dal tipo di configurazione adottata per la singola installazione e come tale potrebbe leggermente differire da una installazione all’altra senza ovviamente compromettere il funzionamento o la validità di quanto riportato nel seguente manuale.*

## Convenzioni

Non sono presenti convenzioni specifiche.

## Procedure di trattamento

A seguire verranno descritti i vari moduli che compongono la SCMP con le rispettive funzionalità.

Le funzionalità sono indipendenti tra loro e non hanno un ordine di priorità di esecuzione.

## Authentication

La funzionalità di “Authentication” permette di interagire con lo IAM per modificare la profilatura utenti.

Per le configurazioni preliminari attenersi alle specifiche indicate nei documenti allegati ( allegato 12?)

Il menu è accessibile dal tasto in alto a destra, come mostrato di seguito.

In particolare, per accedere alla profilatura utente il menu è “Authentication” (Figura 16).

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/59ba24b5e28d0b4adc0fb2dba7375cc2.png)

Figura 16 - Accesso alla funzionalità Authentication

Visualizzazione dashboard per la profilatura utente:

![](media/157cdf31bb494b7bd3c9b4c7c7d51d6a.png)![Immagine che contiene schermata, Elettrodomestico, elettrodomestico, design Descrizione generata automaticamente](media/64827d47b460ad1fb4eba493a8d647a3.png)

**Figura 17 - Dashboard di IAM**

### Gruppi

Per semplificare l’assegnazione di menù, attributi e autorizzazioni è possibile utilizzare dei gruppi di utenti.

Per accedere alla gestione Gruppi cliccare il menù “Groups” nella sezione “Entities” della dashbaord IAM (Figura 18)

![Immagine che contiene schermata, testo, design Descrizione generata automaticamente](media/3577d945eec5abd7396c81520e076bb7.png)

Figura 18 - Accesso alla gestione Gruppi

Una volta cliccato il link verrà mostrata all’utente la lista di tutti i gruppi disponibili sul portale con i rispettivi pulsanti di configurazione (Figura 19)

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/263d854c55d67843f2008730daa76f9d.png)

Figura 19 - Lista dei gruppi configurati

#### Creazione Gruppi

Per creare un nuovo gruppo all’ interno del sistema, cliccare il pusante “+” in alto a destra ,verrà visualizzata una maschera di creazione del Gruppo (Figura 20)

![Immagine che contiene testo, schermata, software Descrizione generata automaticamente](media/ced78a3ed63fa79113984cc55a4214f9.png)

Figura 20 - Aggiunta nuovo Gruppo

Inserire il nome del gruppo (Figura 21) e cliccare il tasto “Add Group” per aggiungerlo al sistema. Una volta premuto il sistema ci porta alla lista dei gruppi disponibili dove possiamo trovare il gruppo appena creato

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/1efd2e2a6612bf522255a19dc6a8adc0.png)

Figura 21 – Parametri di inserimento Gruppo

#### Gestione utenti assegnati e attributi

Per poter assegnare degli utenti ad un gruppo , dalla lista dei gruppi disponibili, cliccare sull’ icona “persone” sulla riga corrispondente al gruppo interessato. (Figura 22) L’utente verrà reindirizzato nella pagina “Members” dove è possibile visualizzare tutti gli utenti assegnati al gruppo e le loro informazioni di base

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/7f3647b2f2f3c442da6e6eb880eec2c4.png)

Figura 22 - Accesso gestione assegnazione utenti

Possiamo aggiungere un utente al gruppo (Figura 23) cliccando il tasto “+” presente in alto a Destra (1), una volta premuto nella lista degli utenti assegnati verrà creata una nuova riga (2) dove all’ interno è possibile selezionare dalla lista degli utenti disponibili un utente (3).

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/679c76f94d396041e88fc0f9e1366cbc.png)

Figura 23 - Assegnare un utente al gruppo

Analogamente è possibile rimuovere gli utenti dal gruppo, cliccando il pulsante “Cestino” in corrispondenza dell’utente da rimuovere.

Dopo aver aggiunto tutti gli utenti al gruppo cliccare il tasto “Save” in basso a sinistra per salvare le modifiche. Verrà visualizzata una modale di conferma salvataggio.

Possiamo assegnare degli attributi al gruppo che verranno automaticamente utilizzati dagli utenti assegnati, (Figura 24) per farlo selezionare il tab “Attributes” in alto nella pagina (1), poi utilizzando il tasto “+” in alto a destra (2) è possibile aggiungere un attributo, nella parte sinistra bisogna inserire la chiave (3) e nella parte bianca sulla destra bisonga inserirne il suo valore (4), durante l’inserimento vedremo sotto al campo una dropdown dove cliccando sarà possibile salvare il valore inserito (5).

La lista degli attirbuti disponibili si trova nel paragrafo (5.4.1.1)

![](media/2ce45559b3e877160201d1c5058e6b1d.png)

Figura 24 - Inserire Attributi

Una volta inseriti tutti gli attributi necessari è possibile salvare le modifiche utilizzando il tasto “Save” in basso.

Per tornare alla lista dei Gruppi disponibili cliccare il tasto “Back” presente in ogni pagina.

#### Visualizzazione Modifica ed Eliminazione di un Gruppo

Sempre dalla lista dei Gruppi disponibili per ogni gruppo sono disponibili una serie di pulsanti (Figura 25):

-   “Lente di ingrandimento” : permette la visualizzazione delle info sul Gruppo (indicato con una freccia rossa nell’ immagine)
-   “Matita” : permette la modifica delle informazioni base del gruppo (indicato con una freccia gialla nell’ immagine)
-   “Cestino”: permette l’eliminazione del gruppo dopo aver cliccato “conferma” nella modale visualizzata (indicato con una freccia viola nell’ immagine)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/b7f8044cae7de4ab971c335489ce2ebd.png)

Figura 25 - Pulsanti di controllo

### Utenti

Per poter accedere ed utilizzare il sistema è necessario che l’utenza da utilizzare sia opportunamente configurata, di seguito vedremo il processo di creazione e gestione di un utente all’ interno della SCMP utilizzando IAM come applicazione per il controllo degli accessi.

Per accedere alla gestione Utenti cliccare il menù “Users” nella sezione “Entities” della dashbaord IAM (Figura 26)

![](media/c2f73bd63bb3a4a6707fc3f1e843f878.png)

Figura 26 - Accesso alla gestione Utenti

Una volta cliccato il link verrà mostrata all’utente la lista di tutti i gruppi disponibili sul portale con i rispettivi pulsanti di configurazione (Figura 27)

![](media/de84675a09a5f9675fc8def9c34a1177.png)

Figura 27 - Lista degli utenti configurati

#### Creazione nuovi utenti

Per creare un nuovo utente all’ interno del sistema, cliccare il pusante “+” in alto a destra ,verrà visualizzata una maschera di creazione dell’ utente (Figura 28)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/b3ef66c75bf97b7fe259d39f42fead3d.png)

Figura 28 - Creazione nuovo utente

Verrà visualizzato il form di creazione di un nuovo utente, compilare i campi obbligatori della lista:

-   E-mail : l’indirizzo e-mail valido dell’ utente
-   Username : l’username da utilizzare come utenza di accesso al portale
-   First Name : Nome dell’ utente
-   Last Name : Cognome dell’ utente
-   Password : Password di almeno 8 caratteri da utilizzare per l’accesso
-   Max concurrent connections : Numero di connessioni massime in contemporanea abilitate per l’utente
-   Default Language: La lingua di base da visualizzare nel sistema

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/8d8606519d2624dbcb28923963905969.png)

Figura 29 - Maschera di creazione utente

Una volta inseriti tutti i campi obbligatori cliccare il pulsante “+ Add user” per completare l’inserimento.

Verrà visualizzato un messaggio di conferma e la pagina si resetta per permettere l’inserimento di un nuovo utente.

Per visualizzare l’utente appena creato tornare nella pagina contenente la lista degli utenti.

#### Assegnazione Ruoli e Attributi

Per gestire gli utenti è possibile cliccare il tasto “Gruppi” in corrispondenza della riga dell’ utente da modificare (Figura 30)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/de674e3d1995459be26adb66c34d1bbb.png)

Figura 30 - Accesso alla gestione utente

Una volta premuto il pulsante, la pagina si aggiorna per mostrare la pagina “Groups” (Figura 31) dove è possibile assegnare o rimuovere uno o più gruppi all’ utente.

Per aggiungere un nuovo gruppo all’ utente bisogna selezionare, nella sezione di sinistra, il gruppo che si vuole assegnare all’ utente (1) e, successivamente cliccando il pulsante “Associa” al centro della pagina (2) il gruppo passerà automaticamente nella sezione destra e le modifiche vengono salvate automaticamente.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/f6dae91ceee1aef68c1981d17f157f96.png)

Figura 31 - Associare un utente al gruppo

Analogamente è possibile rimuovere l’ utente dal gruppo cliccando prima il gruppo da rimuovere nella sezione di destra e successivamente il tasto “Dissocia” al centro della pagina (Figura 32), le modifiche verranno salvate automaticamente

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/62c89ce776d159be256554984ce607ed.png)

Figura 32 – Dissociare un utente dal gruppo

È possibile, inoltre, tramite i tasti presenti nella sezione di destra, in corrispondenza di ogni gruppo, modificare la priorità dei vari gruppi.

Anche per gli utenti è possibile assegnare degli attributi personalizzati, per farlo selezionare il tab “Attributes” (Figura 33) in alto nella pagina (1), poi utilizzando il tasto “+” in alto a destra (2) è possibile aggiungere un attributo, nella parte sinistra bisogna inserire la chiave (3) e nella parte bianca sulla destra bisonga inserirne il suo valore (4), durante l’inserimento vedremo sotto al campo una dropdown dove cliccando sarà possibile salvare il valore inserito (5).

La lista degli attirbuti disponibili si trova nel paragrafo (5.4.1.1)

![Immagine che contiene testo, schermata, software, linea Descrizione generata automaticamente](media/2ce45559b3e877160201d1c5058e6b1d.png)

Figura 33 - Inserire Attributi

Una volta inseriti tutti gli attributi necessari è possibile salvare le modifiche utilizzando il tasto “Save” in basso.

#### Reset delle credenziali

Come amministratore degli utenti è possibile resettare le password, per farlo bisogna cliccare sul tab “Credentials” visualizzato in alto nella pagina, (Figura 34) in questo tab è possibile inserire una nuova password per l’utente e configurarla come “Temporanea” che dovrà essere modificata dall’ utente dopo il primo accesso.Si puo inolte definire un periodo di validità della password espresso in giorni

![Immagine che contiene schermata, software, Software multimediale, testo Descrizione generata automaticamente](media/e03dc00e6ce351746b26a22d7cca8e9b.png)

Figura 34 - Modifica della password per l'utente

#### Visualizzazione modifica ed Eliminazione di un Utente

Sempre dalla lista degli utenti disponibili per ogni gruppo sono disponibili una serie di pulsanti (Figura 35):

-   “Lente di ingrandimento” : permette la visualizzazione delle info utente(indicato con una freccia rossa nell’ immagine)
-   “Matita” : permette la modifica delle informazioni base dell’ utente (indicato con una freccia gialla nell’ immagine)
-   “Cestino”: permette l’eliminazione dell’ utente dopo aver cliccato “conferma” nella modale visualizzata (indicato con una freccia viola nell’ immagine)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/b7f8044cae7de4ab971c335489ce2ebd.png)

Figura 35 - Pulsanti di controllo

### Gestione menù abilitati per utente/Gruppo

Il sistema IAM integrato nella SCMP permette anche la gestione degli elementi di menù disponibili per i vari utenti e gruppi, per accedere alla funzionalità basta cliccare il link “User managment X Pages” disponibile nella sezione “Administration” della dashboard IAM (Figura 36)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/686371924db9fead19471ecfce7d9438.png)

Figura 36 - Accesso alla gestione menù

All’interno della pagina in alto, sono presenti due menu a tendina, il menu a tendina a sinistra consente di selezionare un singolo utente, quello a destra consente di selezionare un gruppo.(Figura 37)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/2101218fceb976757f5104b534a8b67a.png)

Figura 37 - Selezione dell' utente/gruppo da modificare

Dopo aver selezionato un’utenza, la pagina verrà aggiornata per mostrare tutti gli “STREAM” disponibili sull’ applicazione, è possibile cliccare il tasto “+” in corrispondenza di ogni riga per visualizzarne i “MODULES” e i “COMPONENT” disponibili. (Figura 38)

Le liste di componenti visualizzate sono generate automaticamente dal sistema utilizzando le configurazioni eseguite durante l’installazione.

Per ogni component presente è possibile, cliccando il menù a tendina sulla riga corrispondente, indicarne la visibilità o meno all’ utente/gruppo che abbiamo selezionato precedentemente.

I valori selezionabili sono :

-   **Enabled and default** : può essere indicato solo un default per modulo, selezionado questa opzione rendiamo come principale la pagina selezionata; quindi, al click del menù l’utente verrà reindirizzato su questa pagina
-   **Enabled** : Indica che il menù è visibile ed utilizzabile dall’ utente/gruppo
-   **Disabled** : Indica che il menù non verrà abilitato e non sarà visibile all’ utente/gruppo
-   **N.D** : non definito (il menù è disabilitato e non sarà visibile)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/d0242594c1537ad7aa86e2cc108edb3f.png)

Figura 38 - Gestione delle autorizzazioni del menù

### Liste profili utente e Attributi

In questa sezione vengono evidenziate le diverse tipologie di utente che possono accedere e utilizzare il prodotto descritto.

Per ognuno di essi, viene riportato un elenco delle funzionalità alle quali l’utente è stato abilitato e con le quali può interagire.

Vengono indicati qui anche tutti gli attributi che possono essere assegnati a Utenti e Gruppi.

#### Attributi

| **Attributo**  | **Valori accettabili**  | **Tipologia** | **Descrizione**                                                                                                                                                                                            |
|----------------|-------------------------|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| tenantids      | Default,AS01,mase       | String array  | Inserire la lista dei tenant abillitati per l’utente inserendo una virgola tra i nomi di ogni tenant                                                                                                       |
| isTenantReader | true / false            | Boolean       | Abilitando l’attributo specifichiamo che l’utente può effettuare ricerche per TAG invece di utilizzare il tenant come discriminante                                                                        |
| costview       | ADMIN / LIMITED         | Enumeration   | Inserendo ADMIN come valore l’utente potrà visualizzare sia i costi ricevuti dal provider che i costi calcolati dalla SCMP Inserendo LIMITED sarà possibile visualizzare solo i costi calcolati dalla SCXP |
| zoneinfo       | Zona1                   | String        | x                                                                                                                                                                                                          |

Tabella 2 – lista degli Attributi configurabili

#### Amministratore

| **Funzionalità**      | **Create** | **Read** | **Undo** | **Delete** |
|-----------------------|------------|----------|----------|------------|
| Monitoring            | x          | x        | x        | x          |
| Costs                 | x          | x        | x        | x          |
| Inventory             | x          | x        | x        | x          |
| Security              | x          | x        | x        | x          |
| Dashboard             | x          | x        | x        | x          |
| Catalog               | x          | x        | x        | x          |
| Authentication        | x          | x        | x        | x          |
| Administration        | x          | x        | x        | x          |
| Cloud Maturity model  | x          | x        | x        | x          |
| Provisioning          | x          | x        | x        | x          |
| Tenant Management     |            |          |          |            |
| Service Detail Design |            |          |          |            |

Tabella 3 - Autorizzazioni Utente Amministratore

#### Gestore del servizio

| **Funzionalità**      | **Create** | **Read** | **Undo** | **Delete** |
|-----------------------|------------|----------|----------|------------|
| Monitoring            |            |          |          |            |
| Costs                 |            |          |          |            |
| Inventory             |            |          |          |            |
| Security              |            |          |          |            |
| Dashboard             |            |          |          |            |
| Catalog               |            |          |          |            |
| Authentication        | x          | x        | x        | x          |
| Administration        |            |          |          |            |
| Cloud Maturity model  |            |          |          |            |
| Provisioning          |            |          |          |            |
| Tenant Management     | x          | x        | x        | x          |
| Service Detail Design | x          | x        | x        | x          |

Tabella 4 - Autorizzazioni Utente gestore

#### Visualizzatore

| **Funzionalità**      | **Create** | **Read** | **Undo** | **Delete** |
|-----------------------|------------|----------|----------|------------|
| Monitoring            | x          | x        |          |            |
| Costs                 | x          | x        |          |            |
| Inventory             | x          | x        |          |            |
| Security              |            | x        |          |            |
| Dashboard             |            | x        |          |            |
| Catalog               |            | x        |          |            |
| Authentication        |            |          |          |            |
| Administration        |            |          |          |            |
| Cloud Maturity model  |            | x        |          |            |
| Provisioning          |            |          |          |            |
| Tenant Management     |            |          |          |            |
| Service Detail Design |            |          |          |            |

Tabella 5 - Autorizzazioni Utente Visualizzatore

#### Autorizzato

| **Funzionalità**      | **Create** | **Read** | **Undo** | **Delete** |
|-----------------------|------------|----------|----------|------------|
| Monitoring            | x          | x        | x        | x          |
| Costs                 | x          | x        | x        | x          |
| Inventory             | x          | x        | x        | x          |
| Security              |            |          |          |            |
| Dashboard             | x          | x        | x        | x          |
| Catalog               | x          | x        | x        | x          |
| Authentication        |            |          |          |            |
| Administration        | x          | x        | x        | x          |
| Cloud Maturity model  |            |          |          |            |
| Provisioning          | x          | x        | x        | x          |
| Tenant Management     |            |          |          |            |
| Service Detail Design |            |          |          |            |

Tabella 6 - Autorizzazioni Utente autorizzato

## Gestione Tenant

La SCMP è stata sviluppata come soluzione Multi-Tenant, ciò offre maggiore sicurezza, personalizzazione, flessibilità e scalabilità, con un'amministrazione più efficiente e costi ridotti.

Per permettere all’ utente di gestire i tenant presenti nell’ infrastruttura è stata resa disponibile la funzionalità “Tenant” disponibile solo per gli utenti abilitati alla Gestione del servizio (5.4.1.3)

Per accedere alla funzionalità, in alto a sinistra cliccare sul pulsante bento. Dopodiché, cliccare su “Tenant” (Figura 39)

![](media/767fb41dc192bd2531d637c3e4615a39.png)

Figura 39 - Accesso alla gestione Tenant

.

### Creazione di un nuovo tenant

A questo punto, l’utente si ritrova all’interno della pagina del tab “Tenant” che contiene la lista dei tenant configurati sul sistema, per aggiungere un nuovo tenant cliccare il “menu” disponibile in alto a destra e selezionare la voce “+ Add”, (Figura 40)

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/7165779f55b4257d14fd90d5a0605438.png)

Figura 40 - Aggiungi nuovo tenant

una volta premuto viene visualizzata la pagina di configurazione nuovo tenant (Figura 41) divisa in tre sezioni:

![](media/695959e38582d6114010cd4f0132995b.png)

Figura 41 – Form di creazione nuovo tenant

1.  **Parametri generali:**

| **Nome**                    | **Descrizione**                                                      | **Obbligatorio** |
|-----------------------------|----------------------------------------------------------------------|------------------|
| Tenant ID                   | ID univoco del nuovo tenant                                          | x                |
| Tenant Name                 | Nome del tenant che verrà visualizzato all’ utente                   | x                |
| Description                 | una descrizione del tenant                                           | x                |
| MarketPlace Subscription ID | l’id ricevuto dal marketplace Azure alla sottoscrizione del servizio |                  |

Tabella 7 – parametri generali tenant

1.  **Data persistance:**

| **Nome**   | **Descrizione**                                                                                                        | **Obbligatorio** |
|------------|------------------------------------------------------------------------------------------------------------------------|------------------|
| Inventory  | Indica il numero di giorni per cui i dati relativi all ‘inventario saranno conservati nelle collections presenti su DB | x                |
| Cost       | Indica il numero di giorni per cui i dati relativi ai costi saranno conservati nelle collections presenti su DB        | x                |
| Monitoring | Indica il numero di giorni per cui i dati relativi al monitraggio saranno conservati nelle collections presenti su DB  | x                |
| Security   | Indica il numero di giorni per cui i dati relativi allla security saranno conservati nelle collections presenti su DB  | x                |

Tabella 8 – Parametri di data persistance

1.  **Init Catalog**

In questa sezione è possibile selezionare gli elementi di catalogo che verranno copiati automaticamente sul nuovo tenant.

La sezione iniziale (1) permette di scegliere una sola opzione tra:

-   **Empty Catalog** : lasciare il catalogo vuoto senza eseguire nessuna copia di informazioni
-   **Copy Catalog from Default Tenant :** Indica che il tenant dal quale recuperare le informazioni da copiare sia il tenant di Default
-   **Copy Catalog from other Tenant :** se viene selezionato nella sezione in basso verrà visualizzato un nuovo campo contenente la lista dei tenant disponibili così da permette la selezione del tenant dal quale recuperare le informazioni da copiare

Successivamente è possibile compilare la sezione successiva (2) inserendo i campi non obbligatori:

**Providers**: lista dei provider configurati nel tenant di partenza, selezionando uno o più provider ne verranno copiati gli elementi di catalogo nel nuovo tenant

**Copy CMP Catalog :** Se attivato tutti gli elementi presenti nel catalogo CMP verranno aggiunti al nuovo tenant

**Copy Services :** Se attivato tutti gli elementi presenti nel catalogo CMP verranno aggiunti al nuovo tenant

**Copy Custom Services :** Se attivato i servizi custom disponibili sul tenant verranno aggiunti al nuovo tenant

**Copy Blueprints** : Se attivato tutte le Blueprint disponibili verranno aggiunte al nuovo tenant

![](media/05cc706d8550aa967d99dad446147e2d.png)

Figura 42 – Sezione di inizializzazione catalogo

Per confermare l’inserimento del nuovo tenant cliccare il pulsante “Save” presente in basso a destra, dopo aver aspettato il caricamento verrà visualizzato un messaggio di conferma creazione e l’utente viene riportato nella lista dei tenant dove sarà presente il nuovo tenant appena creato

### Visualizzazione , Modifica ed Eliminazione di un tenant

Nella lista dei tenant, in corrispondenza di ogni risultato è presente un “menù” con tre pulsanti (Figura 42):

-   **“Show”** : permette la visualizzazione delle info sul tenant(indicato con una freccia rossa nell’ immagine)
-   **“Edit”** : permette la modifica delle informazioni base del tenant (indicato con una freccia gialla nell’ immagine)
-   **“Delete”:** permette l’eliminazione dell’ utente dopo aver cliccato “conferma” nella modale visualizzata (indicato con una freccia viola nell’ immagine)

![](media/50b40b8fa957c8e9812b2fb2a8935606.png)

Figura 43 - Pulsanti di controllo

## Administration

La funzionalità di Administration è la base di partenza per poter utilizzare la SCMP.

I provider inseriti all’ interno di questa funzionalità verranno utilizzati dal sistema per recuperare tutte le informazioni necessarie.

All’ interno della funzionalità sarà possibile:

-   Configurare i cloud provider che potranno essere utilizzati nel Tenant di riferimento;
-   Configurare le folder dei vari provider.
-   Configurare i cloud SIEM dei vari provider.
-   Configurare i KeyVault dei vari provider.

### provider/sottosistemi

#### Lista dei sottosistemi

Per accedere alla funzionalità di Administration, in alto a sinistra cliccare sul pulsante bento. Dopodiché, cliccare su “Administration” (Figura 44).

A questo punto, l’utente si ritrova all’interno della pagina del tab “Cloud Systems” (Figura 45).

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/70a25604595ae60f9a4d774b4d1bce5f.png)

Figura 44 - Accesso ad Administration

l’utente visualizzerà la dashboard dove viene mostrato l’elenco dei provider gestiti dalla SCMP.

All’interno della tabella è possibile visualizzare, oltre alla data di creazione, se il provider è di tipo On-Permise segnalato all’ utente tramite una spunta di colore rosso sulla riga corrispondente.

Nella tabella possiamo notare che i sottosistemi recuperati dalle folder no vengono visualizzati ma cliccando in corrispondenza della “freccia in basso” sulla riga della folder viene aperta una nuova tabella che visualizza tutti i sottosistemi della folder e il loro stato.

Inoltre, per ogni provider è disponibile un “pallino” che indica lo stato attuale del sottosistema :

-   Verde : il sottosistema funziona correttamente nella SCMP “status : ok”
-   Rosso: il sottosistema non è più utilizzabile dalla SCMP “status : failed”

La SCMP effettua periodicamente dei test di connessione su ogni sottosistema configurato, quando un sottosistema fallisce questo controllo, esso viene “disabilitato” e non ne verranno più aggiornate le informazioni (costi, inventario , monitoraggio, sicurezza) .

Questo potrebbe accadere, ad esempio quando il secret o le password utilizzate per connettersi scadono e devono essere rinnovate.

Andando a modificare il sottosistema (5.6.1.3) è possibile inserire i nuovi parametri di connessione per ristabilirne il corretto funzionamento, ed il “pallino” diventerà di colore verde.

#### Creazione nuovo sottosistema

Per inserire un nuovo sottosistema all’ interno del portale bisogna cliccare sul “menu” disponibile in alto a destra e selezionare “+ Aggiungi nuovo cloud provider”

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/32d9fbc2be317c6b1dd8a0825da53eb3.png)

Figura 45 - Aggiunta di un nuovo Cloud Provider

L’utente visualizza i dati di base del sottosistema da inserire, spiegati in seguito

##### **Parametri condivisi**

All’ interno della pagina di creazione (Figura 46) possiamo notare 3 campi :

-   Nome : indica il nome che verrà visualizzato per indicare il sottosistema
-   Tipo: indica la tipologia di cloud provider al quale appartiene il sottosistema
-   Versione: la versione relativa al provider del sottosistema da installare

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/8ea7994e0d106933efdf22732fbcc287.png)

Figura 46 - Parametri generali di un sottosistema

Dopo aver selezionato la tipologia e la versione del sistema la maschera si aggiorna per visualizzare i parametri specifici in base al provider selezionato, visto che ognuno di loro gestisce l’autenticazione e le risorse in maniera differente.

Tutti i provider richiedono un’autenticazione, che può variare in base al sistema, per il recupero degli asset.

Queste informazioni sensibili, come password o certificati, vengono salvati in maniera sicura su un elemento infrastrutturale che si occupa della sicurezza dei dati (<https://www.vaultproject.io/>).

##### **Parametri Azure**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici (Figura 47) del sottosistema Azure da inserire sono esposti nella tabella

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/223277929bcebc85cf5ee472948c8f5c.png)

Figura 47 - Maschera di configurazione Azure

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo** | **Descrizione**                                                                                                                                                                           | **esempio**                               |
|----------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| clientId **\***      | string   | L'ID univoco del client che si connette al sottosistema Azure Cloud. Questo ID viene utilizzato per identificare il client e per autorizzare l'accesso alle risorse del sottosistema.     | 5a85c16c6ad-49db-a58e-e209-ee11f53d6c6b   |
| clientSecret \*      | password | La chiave segreta del client, utilizzata per autenticare il client con il sottosistema Azure Cloud. La chiave segreta deve essere tenuta segreta e non deve essere condivisa con nessuno. | np6Kc_.xwsvhR8Q\~rP05fCqYNXmbqfMGQLOEzfMt |
| tenantId \*          | string   | L'ID del tenant Azure a cui appartiene il sottosistema Azure Cloud. Il tenant è un'entità organizzativa in Azure che rappresenta un'azienda o un'organizzazione.                          | 884147733-ff13-4783-a765-834183773083     |
| subscriptionId \*    | string   | L'ID della sottoscrizione Azure utilizzata per accedere al sottosistema Azure Cloud. La sottoscrizione è un contratto per l'utilizzo dei servizi Azure.                                   | 884147733-ff13-4783-a765-834183773083     |
| usageAggregation     | boolean  | Indica se l'aggregazione per "usage" è abilitata per la sottoscrizione. Quando questa spunta viene abilitata i costi del sottosistema verranno raggruppati per Tipologia risorsa          | false                                     |
| catalogPriceDiscount | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP                                                          | 5                                         |
| odlID                | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema                                               | ODL001                                    |
| clientId             | string   | L'ID univoco del client che si connette al sottosistema Azure Cloud. Questo ID viene utilizzato per identificare il client e per autorizzare l'accesso alle risorse del sottosistema.     | 5a85c16c6ad-49db-a58e-e209-ee11f53d6c6b   |
| datsFirstCostRecover | int      | Inserire il numero di giorni precedenti alla data di creazione dei quali bisogna recuperare i costi al primo avvio del sottosistema                                                       | 15                                        |

Tabella 9 – Campi specifici Azure

##### **Parametri AzureStack**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici del sottosistema AzureStack da inserire sono esposti nella tabella

![](media/76abf0404a062e951e9a50d7e9d827b2.png)

Figura 48 - Maschera di configurazione AzureStack

Vengono indicati con \* i parametri obbligatori

| **Nome**              | **Tipo**         | **Descrizione**                                                                                                                                                                       | **esempio**                                                                     |
|-----------------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| clientId \*           | string           | L'ID univoco del client che si connette al sottosistema Azure Stack. Questo ID viene utilizzato per identificare il client e per autorizzare l'accesso alle risorse del sottosistema. | 3552d471-58e3-4099-aabe-e4973e312be7                                            |
| clientSecret \*       | password         | La chiave segreta del client, utilizzata per autenticare il client con il sottosistema Azure Stack                                                                                    | np6Kc_.xwsvhR8Q\~rP05fCqYNXmbqfMGQLOEzfMt                                       |
| tenantId \*           | string           | L'ID del tenant Azure a cui appartiene il sottosistema Azure Stack. Il tenant è un'entità organizzativa in Azure che rappresenta un'azienda o un'organizzazione.                      | npYN_.xwsvhRqXmbqf6KhRqMGQLO8Q\~rP05fCEzfMt                                     |
| url \*                | string           | L'URL dell'endpoint di Resource Manager per Azure Stack. Questo endpoint viene utilizzato per gestire le risorse Azure Stack                                                          | <https://management.infroma.microsoft.com/3552d471-58e3-4099-aabe-e4973e312be7> |
| armEndpoint \*        | string           | L'URL dell'endpoint di Resource Manager per Azure Stack. Questo endpoint viene utilizzato per gestire le risorse Azure Stack                                                          | <https://management.gfis.cloud.azurs.priv/>                                     |
| subscriptionId \*     | string           | L'ID della sottoscrizione Azure utilizzata per accedere al sottosistema Azure Stack. La sottoscrizione è un contratto per l'utilizzo dei servizi Azure                                | 3552d471-58e3-4099-aabe-e4973e312be7                                            |
| costClientId \*       | string           | L'ID client per l'accesso ai dati di costo.                                                                                                                                           | 3e312be7-58e3-4099-aabe-e4973552d471                                            |
| costClientSecret \*   | password         | La chiave segreta del client per l'accesso ai dati di costo                                                                                                                           | np6Kc_.xwsvhR8Q\~rP05fCqYNXmbqfMGQLOEzfMt                                       |
| costTenantId \*       | string           | L'ID del tenant per l'accesso ai dati di costo.                                                                                                                                       | 3e312be7-58e3-4099-aabe-e4973552d471                                            |
| costSubscriptionId \* | string           | L'ID della sottoscrizione per l'accesso ai dati di costo.                                                                                                                             | 3552d471-58e3-4099-aabe-e4973e312be7                                            |
| location \*           | string           | Inserire la regione nella quale è disponibile il sottosistema                                                                                                                         | euw-Rome-1                                                                      |
| totalCPU \*           | Positive Integer | il numero delle CPU totali disponibili nel sottosistema                                                                                                                               | 64                                                                              |
| totalRAM \*           | Positive Integer | Il valore in MB della RAM totale disponibile nel sottosistema                                                                                                                         | 25500                                                                           |
| totalStorage \*       | Positive Integer | Il vlaore in GB dello spazio totale disponibile sul sottosistema                                                                                                                      | 5000                                                                            |
| catalogPriceDiscount  | integer          | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP                                                      | -10                                                                             |
| odlID                 | string           | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema                                           | ODL001                                                                          |

Tabella 10 – Campi specifici AzureStack

Per i provider on Premise, in particolare, vengono richiesti dati sulla capacità della infrastruttura, in modo tale che la SCMP possa effettuare dei calcoli preliminari in molteplici scenari.

Per esempio, durante il provisioning, in modo tale da non superare la capacità massima consentita del provider.

##### **Parametri AzureStack HCI**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici del sottosistema AzureStack HCI da inserire sono esposti nella tabella

![](media/2e4513628c923f0994c63a3f0576c84e.png)

Figura 49 - Maschera di configurazione AzureStack HCI

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo**         | **Descrizione**                                                                                                                                                                       | **esempio**                          |
|----------------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| Username \*          | string           | Username di accesso per utilizzare la macchina Bridge                                                                                                                                 | AdminUser                            |
| Password \*          | password         | Password di accesso per utilizzare la macchina Bridge                                                                                                                                 | Pasword1                             |
| bridgeIp \*          | string           | Ip identificativo della macchine Bridge                                                                                                                                               | 192.168.1.1                          |
| clientId \*          | string           | L'ID univoco del client che si connette al sottosistema Azure Stack. Questo ID viene utilizzato per identificare il client e per autorizzare l'accesso alle risorse del sottosistema. | 3552d471-58e3-4099-aabe-e4973e312be7 |
| clientSecret \*      | password         | La chiave segreta del client, utilizzata per autenticare il client con il sottosistema Azure Stack                                                                                    |                                      |
| tenantId \*          | string           | L'ID del tenant Azure a cui appartiene il sottosistema Azure Stack. Il tenant è un'entità organizzativa in Azure che rappresenta un'azienda o un'organizzazione.                      | 3552d471-58e3-4099-aabe-e4973e312be7 |
| subscriptionId \*    | string           | L'ID della sottoscrizione Azure utilizzata per accedere al sottosistema Azure Stack. La sottoscrizione è un contratto per l'utilizzo dei servizi Azure                                | 3552d471-58e3-4099-aabe-e4973e312be8 |
| location \*          | string           | Inserire la regione nella quale è disponibile il sottosistema                                                                                                                         | euw-Milan-002                        |
| totalCPU \*          | Positive Integer | il numero delle CPU totali disponibili nel sottosistema                                                                                                                               | 64                                   |
| totalRAM \*          | Positive Integer | Il valore in MB della RAM totale disponibile nel sottosistema                                                                                                                         | 52000                                |
| totalStorage \*      | Positive Integer | Il valore in GB dello spazio totale disponibile sul sottosistema                                                                                                                      | 5000                                 |
| catalogPriceDiscount | integer          | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP                                                      | 10                                   |
| odlID                | string           | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema                                           | ODL0001                              |

Tabella 11 – Campi specifici AzureStack HCI

Per i provider on Premise, in particolare, vengono richiesti dati sulla capacità della infrastruttura, in modo tale che la SCMP possa effettuare dei calcoli preliminari in molteplici scenari.

Per esempio, durante il provisioning, in modo tale da non superare la capacità massima consentita del provider.

##### **Parametri AzureStack Hybrid cloud**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Provisioning di risorse
5.  Provisioning di servizi
6.  Provisioning di blueprint complesse

I parametri specifici del sottosistema AzureStack Hybrid cloud da inserire sono esposti nella tabella

![](media/4e4f401971f945f60ec66e679baf9e17.png)

Figura 50 - Maschera di configurazione AzureStack Hybrid cloud

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo**         | **Descrizione**                                                                                                                             | **esempio**       |
|----------------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| username \*          | string           | Username di accesso per utilizzare la macchina Bridge                                                                                       | AdminUser         |
| password \*          | password         | Password di accesso per utilizzare la macchina Bridge                                                                                       | PasswordAdmin1    |
| bridgeIp             | string           | Ip identificativo della macchine Bridge                                                                                                     | 192.168.1.1       |
| needBridge           | boolean          | Se abilitato indica che la macchina di bridge non è all'interno del cluster                                                                 | true              |
| clusterName          | string           | Nome del cluster per stabilire una sessione powershell, se il campo " needBridge = True"                                                    | my.cluster.online |
| ncUri                | string           | Inserisci qui l'URI del controllore di rete                                                                                                 |                   |
| totalCPU \*          | Positive Integer | il numero delle CPU totali disponibili nel sottosistema                                                                                     | 36                |
| totalRAM \*          | Positive Integer | Il valore in MB della RAM totale disponibile nel sottosistema                                                                               | 25000             |
| totalStorage \*      | Positive Integer | Il vlaore in GB dello spazio totale disponibile sul sottosistema                                                                            | 500               |
| catalogPriceDiscount | integer          | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP            | 10                |
| odlID                | string           | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema | ODL001            |

Tabella 12 – Campi specifici AzureStack Hybrid Cloud

Per i provider on Premise, in particolare, vengono richiesti dati sulla capacità della infrastruttura, in modo tale che la SCMP possa effettuare dei calcoli preliminari in molteplici scenari.

Per esempio, durante il provisioning, in modo tale da non superare la capacità massima consentita del provider.

##### **Parametri Amazon Web Services**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici del sottosistema Amazon Web Services da inserire sono esposti nella tabella

![](media/7f5b8b09a98b263fb5af764f51d73d78.png)

Figura 51 - Maschera di configurazione Amazon Web Services

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo** | **Descrizione**                                                                                                                             | **esempio**                               |
|----------------------|----------|---------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| clientId \*          | string   | La chiave di accesso AWS è una stringa alfanumerica che identifica l'utente AWS.                                                            | ZYKZGVAKIS4YK5IXCAXB                      |
| clientSecret \*      | password | La chiave di accesso segreta AWS è una stringa alfanumerica che viene utilizzata per autenticare l'utente AWS                               | np6Kc_.xwsvhR8Q\~rP05fCqYNXmbqfMGQLOEzfMt |
| catalogPriceDiscount | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP            | 5                                         |
| odlID                | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema | ODL001                                    |

Tabella 13 – Campi specifici Amazon Web Services

##### **Parametri Google Cloud**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici del sottosistema Google Cloud da inserire sono esposti nella tabella, il campo “Service account” può essere inserito sia automaticamente che manualmente come descritto nel paragrafo.

![](media/1f48fdae85572c91ab75485b93ff2914.png)

Figura 52 - Maschera di configurazione Google

Vengono indicati con \* i parametri obbligatori

| **Nome**              | **Tipo** | **Descrizione**                                                                                                                                                                  | **esempio**                                                                     |
|-----------------------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| serviceAccount \*     | object   | File di connessione generato dalla console Google                                                                                                                                | service_account.json                                                            |
| discoveryProjectId \* | string   | Identificativo del progetto di cui si effettuerà il discovery                                                                                                                    | Theproject-547280                                                               |
| costExportProjectId   | string   | Dataset id del service account di esportazione costi se il dataset è differente dal ProjectID                                                                                    | test-customer.test_customer.gcp_billing_export_resource_v1_01527DF_51B683_EB2A9 |
| usageAggregation      | boolean  | Indica se l'aggregazione per "usage" è abilitata per la sottoscrizione. Quando questa spunta viene abilitata i costi del sottosistema verranno raggruppati per Tipologia risorsa | false                                                                           |
| catalogPriceDiscount  | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP                                                 | -5                                                                              |
| odlID                 | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema                                      | ODL001                                                                          |
| datsFirstCostRecover  | int      | Inserire il numero di giorni precedenti alla data di creazione dei quali bisogna recuperare i costi al primo avvio del sottosistema                                              | 15                                                                              |

Tabella 14 – Campi specifici Google

![](media/e0051efb5415c0347aad66fb128f1c39.png)

Figura 53 - Caricamento del file di configurazione

Effettuando l’upload del file il form viene completato automaticamente con i parametri necessari, ma è possibile anche inserirli manualmente (riquadro giallo presente nell’ immagine, Figura 53) seguendo la tabella, tutti i campi sono obbligatori:

| **Nome**                      | **Tipo** | **Descrizione**                                                                                                                                 | **esempio**                                                                                            |
|-------------------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| Type                          | string   | Inserire il nome della tipologia di autenticazione configurata                                                                                  | service_account                                                                                        |
| project_id \*                 | string   | Inserisci qui l'id univoco del progetto associato al service account                                                                            | Theproject-367810                                                                                      |
| private_key_id \*             | string   | Inserisci qui l'id univoco della chiave privata del service account                                                                             | 55cb5cf903ee93ea1e9c294a07e46e0af0633e6                                                                |
| private_key \*                | password | Contiene la chiave privata del service account in formato PEM. È fondamentale per l'autenticazione del service account alle API di Google Cloud |  -----BEGIN PRIVATE KEY-----MIIJQgIBADANB…                                                             |
| client_e-mail \*              | string   | L'indirizzo e-mail univoco del service account. È utilizzato per identificare il service account quando si autentica alle API di Google Cloud   | [user@dominio.com](mailto:user@dominio.com)                                                            |
| client_id \*                  | string   | L'ID client del service account. È un identificatore univoco utilizzato per identificare il service account in Google Cloud                     | 104822473261100667392                                                                                  |
| auth_uri \*                   | string   | L'URI utilizzato per l'autenticazione del service account alle API di Google Cloud                                                              | https://accounts.google.com/o/oauth2/auth                                                              |
| token_uri \*                  | string   | L'URI utilizzato per ottenere un token di accesso per il service account                                                                        | https://oauth2.googleapis.com/token                                                                    |
| auth_provider_x509_cert_url\* | string   | L'URL del certificato X.509 utilizzato per l'autenticazione del service account                                                                 | https://www.googleapis.com/oauth2/v1/certs                                                             |
| client_x509_cert_url \*       | string   | L'URL del certificato X.509 nel client                                                                                                          | <https://www.googleapis.com/robot/v1/metadata/f543/myserviceaccount%40projectName.gserviceaccount.com> |

Tabella 15 – Campi specifici obbligatori del file “service_account.json”

##### **Parametri Openshift**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici del sottosistema Openshift da inserire sono esposti nella tabella

![](media/42c49fd71000f81d647dc82d585f7be0.png)

Figura 54 - Maschera di configurazione Openshift

Vengono indicati con \* i parametri obbligatori

| **Nome**    | **Tipo**         | **Descrizione**                                                                                                                             | **esempio**                                                   |
|-------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| username \* | string           | Inserisci qui il nome utente del profilo configurato                                                                                        | Admin                                                         |
| password \* | password         | Inserisci qui la password del profilo configurato                                                                                           | AdminPassword123                                              |
| Port \*     | Positive Integer | Inserisci qui la porta dell'API server                                                                                                      | 6443                                                          |
| url \*      | string           | Inserisci qui l'API url di connessione al profilo                                                                                           | [https://api.cloud.my.url.com](https://api.cloud.my.url.com/) |
| odlID       | string           | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema | ODL001                                                        |

Tabella 16 – Campi specifici OpenShift

##### **Parametri Oracle**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero dei costi delle risorse
4.  Recupero delle informazioni di sicurezza

I parametri specifici del sottosistema Oracle da inserire sono esposti nella tabella

![](media/1987c4ef157a8e4cfdc0a5b0f1295b7a.png)

Figura 55 - Maschera di configurazione Oracle

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo** | **Descrizione**                                                                                                                             | **esempio**                                                                       |
|----------------------|----------|---------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| username \*          | string   | Il nome utente utilizzato per l'autenticazione con OCI.                                                                                     | ocid5.user.oc77.aaabnbthaj6pnvsb2gqnaaaaait3mqzekefmlhwkige2wxna6hfaj3f6njma      |
| fingerprint \*       | string   | è un valore univoco che identifica il dispositivo, utilizzato per l'autenticazione con OCI.                                                 | 6a:f4:6e:9a:73:95:27:d5:64:8d11:a3:f5:0e:fb:f4:                                   |
| tenantId \*          | string   | L'ID del tenant OCI a cui ci si vuole connettere                                                                                            | ocid5.tenancy.oc77...aaabnbthaj6pnvsb2gqnaaaaait3mqzekefmlhwkige2wxna6hfaj3f6njma |
| region \*            | string   | La regione è ls posizione geografica specifica in cui si trovano le risorse OCI.                                                            | eu-dcc-rome-1                                                                     |
| Realm                | string   | Il nome del contenitore logico che raggruppa le risorse OCI e i relativi costi.                                                             | personal-realm.it                                                                 |
| keyFile \*           | password | un file PEM che contiene la chiave pubblica e privata utilizzata per l'autenticazione.                                                      | " -----BEGIN PRIVATE KEY-----MIIJQgIBADANB…"                                      |
| catalogPriceDiscount | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP            | -10                                                                               |
| odlID                | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema | ODL001                                                                            |

Tabella 17 – Campi specifici Oracle

##### **Parametri VCloud**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza

I parametri specifici del sottosistema VCloudDirector da inserire sono esposti nella tabella

![](media/30b3663aff3be4d9bb131c5b1f711e34.png)

Figura 56 - Maschera di configurazione VCloudDirector

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo** | **Descrizione**                                                                                                                             | **esempio**                                        |
|----------------------|----------|---------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| url \*               | string   | l'indirizzo del server VCloudDirector a cui ci si vuole connettere                                                                          | <https://url.westeurope.com/tenant/org-zzg-435832> |
| tenantId \*          | string   | L'ID del tenant del VCloudDirector è l'identificatore univoco del tenant a cui ci si vuole connettere.                                      | org-zzg-435832                                     |
| token \*             | password | Il token di autenticazione per il VCloudDirector è una stringa segreta che viene utilizzata per autenticare l'utente con il VCloudDirector  | aesZo6LextKTQx92VoRpyzaesZo6LextKT                 |
| catalogPriceDiscount | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP            | 5                                                  |
| odlID                | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema | ODL001                                             |

Tabella 18 – Campi specifici VCloud Director

##### **Parametri VMWare**

Funzionalità abilitate:

1.  Recupero elementi di catalogo
2.  Recupero elementi di inventario
3.  Recupero delle metriche di utilizzo
4.  Recupero dei costi delle risorse
5.  Recupero delle informazioni di sicurezza
6.  Provisioning di risorse
7.  Provisioning di servizi
8.  Provisioning di blueprint complesse

I parametri specifici del sottosistema VMWare da inserire sono esposti nella tabella

![](media/a379b0f3be55aed2794e08f44a16ffee.png)

Figura 57 - Maschera di configurazione VMWare

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo**         | **Descrizione**                                                                                                                             | **esempio**                                                   |
|----------------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| username \*          | string           | Inserisci qui il nome utente del profilo configurato                                                                                        | Admin                                                         |
| password \*          | password         | Inserisci qui la password del profilo configurato                                                                                           | AdminPassword123                                              |
| url \*               | string           | Inserisci qui l'API url di connessione al profilo                                                                                           | [https://api.cloud.my.url.com](https://api.cloud.my.url.com/) |
| Location             | String           | Inserisci qui la regione di appartenenza                                                                                                    | Euw_rome_001                                                  |
| totalCPU \*          | Positive Integer | il numero delle CPU totali disponibili nel sottosistema                                                                                     | 64                                                            |
| totalRAM \*          | Positive Integer | Il valore in MB della RAM totale disponibile nel sottosistema                                                                               | 52000                                                         |
| totalStorage \*      | Positive Integer | Il valore in GB dello spazio totale disponibile sul sottosistema                                                                            | 5000                                                          |
| catalogPriceDiscount | integer          | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP            | 10                                                            |
| odlID                | string           | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema | ODL0001                                                       |

Tabella 19 – Campi specifici Azure

Per i provider on Premise, in particolare, vengono richiesti dati sulla capacità della infrastruttura, in modo tale che la SCMP possa effettuare dei calcoli preliminari in molteplici scenari.

Per esempio, durante il provisioning, in modo tale da non superare la capacità massima consentita del provider.

#### Verifica della connessione e salvataggio

Per tutti i sottosistemi sono disponibili in basso nella pagina 3 pulsanti (Figura 58) :

Il tasto “Chiudi” che permette di annullare l’inserimento di un nuovo sottosistema

Il tasto “Test Connection” serve ad effettuare un test di connessione utilizzando i parametri inseriti, in caso di errori il sistema ritorna un messaggio di errore che indica “Error: Unauthorized system” e il pulsante diventa di colore rosso, in caso contrario il pulsante diventerà verde e sarà possibile salvare il sottosistema utilizzando il tasto “Salva”

![Immagine che contiene testo, schermata, Software multimediale, software Descrizione generata automaticamente](media/05c1b1d230de15b3e802b1bb40c75473.png)

Figura 58 - Pulsanti di connessione

Al salvataggio, la SCMP comunicherà al modulo che gestisce quella tipologia di provider, di caricare all’interno del nostro bus (Kafka) tutti gli item relativi all’inventario, metriche, costi ed elementi di security.

Lo stesso modulo, si occuperà successivamente di schedulare dei job per l’aggiornamento periodico di tutti gli asset presenti.

Dopo aver salvato, apparirà una modale che informa l’utente che non è possibile eliminare un cloud provider prima delle 24 ore. Dalla modale, cliccare su “OK”. Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina dei Cloud Provider.

#### Visualizzazione edit ed eliminazione di un sottosistema

È possibile visualizzare i dati di un Cloud Provider, all’interno della lista, cliccare sul kebab menu in corrispondenza di un Cloud Provider, e cliccare su “Show” (Figura 59).

![Immagine che contiene testo, screenshot, monitor, nero Descrizione generata automaticamente](media/2ac48325de200b83add76f501860a0db.png)

Figura 59- Accesso al Cloud Provider in modalità visualizzazione

In questa pagina è possibile visualizzare la configurazione del Provider (Figura 60).

![A screenshot of a computer Description automatically generated with medium confidence](media/75d3f7acb2d8f224b3352e8bcc74bddb.png)

Figura 60 - Visualizzazione cloud in modalità visualizzazione

Se il provider è di tipo “ON-PREMISE” sotto la configurazione sarà visibile una tabella che riporta le capacità utilizzabili sul sistema e la lista delle macchine già presenti sul provider (Figura 61).

![A screenshot of a computer Description automatically generated with medium confidence](media/f561d5320f6eef794e9ece2bc5f9daa3.png)

Figura 61 - Lista macchine On-Premise

Per tornare alla pagina dei Cloud Provider, in basso a sinistra, cliccare sul pulsante “Close”.

A questo punto, l’utente si ritroverà all’interno della pagina dei Cloud Provider.

Per modificare i dati di un Cloud Provider, all’interno della lista, cliccare sul kebab menu in corrispondenza di un Cloud Provider, e cliccare su “Edit” (Figura 62).

![Immagine che contiene testo, screenshot, monitor, nero Descrizione generata automaticamente](media/07af0477c48467c5bf4e2cee31943505.png)

Figura 62 - Accesso al Cloud Provider in modalità edit

Fatto ciò, l’utente si ritroverà all’interno della pagina del Cloud Provider in modalità edit in cui è possibile modificare i dati. Per tornare alla pagina dei Cloud Provider, in basso a sinistra, cliccare sul pulsante “Save”. A questo punto, l’utente si ritroverà all’interno della pagina dei Cloud Provider.

![Immagine che contiene testo, screenshot, monitor, nero Descrizione generata automaticamente](media/5a2cb7c7765de0fe4609e4c78a5fd250.png)

Figura 63 - Avvio per l'eliminazione di un Cloud Provider

Per eliminare un Cloud Provider, all’interno della lista, cliccare sul kebab menu in corrispondenza di un Cloud Provider, e cliccare su “Delete” (Figura 63).

![Immagine che contiene testo, monitor, screenshot, interni Descrizione generata automaticamente](media/32d0164378c2fbd9d2cfcc55c73a56ca.png)

Figura 64 - Conferma eliminazione del Cloud Provider

Fatto ciò, apparirà una modale in cui è necessario cliccare sul pulsante “Remove” (Figura 64).

A questo punto, il Cloud Provider non sarà più presente all’interno della lista e verrà lanciato il flusso di rimozione asset sul resource-manager.

#### Google Cloud Folders

Per consentire alla SCMP di sfruttare tutte le potenzialità offerte dal provider “Google Cloud” è stata inserita la possibilità di configurare delle “Folders” e la possibilità di importare il file generato dalla console del provider così da semplificare l’inserimento dello stesso.

Durante la creazione di un provider selezionando la tipologia “Google Cloud” (5.6.1.2.7) possiamo notare la presenza di 2 campi esclusivi per il provider (Figura 65):

1.  Un box di conferma per indicare alla SCMP se il provider in inserimento è una “Folder”
2.  Un box dove, cliccando all’ interno sarà possibile, tramite la finestra di selezione file di windows inserire il file di tipo “JSON” esportato direttamente dalla console Google

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/5df476cbf2a07db5cd9faacc683371e0.png)

Figura 65 – Parametri specifici di Google Cloud

I parametri specifici della Google Folder da inserire sono esposti nella tabella:

| **Nome**             | **Tipo** | **Descrizione**                                                                                                                                                                  | **esempio**          |
|----------------------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|
| serviceAccount       | object   | File di connessione generato dalla console Google                                                                                                                                | service_account.json |
| usageAggregation     | boolean  | Indica se l'aggregazione per "usage" è abilitata per la sottoscrizione. Quando questa spunta viene abilitata i costi del sottosistema verranno raggruppati per Tipologia risorsa | false                |
| catalogPriceDiscount | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP                                                 | -20                  |
| odlID                | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema                                      | ODL001               |
| datsFirstCostRecover | int      | Inserire il numero di giorni precedenti alla data di creazione dei quali bisogna recuperare i costi al primo avvio del sottosistema                                              | 15                   |

Tabella 20 – Campi specifici Google Folder

Il campo “ServiceAccount” è formato dai campi indicati nel paragrafo 5.6.1.2.7 e può essere inserito automaticamente effettuando l’upload del file o manualmente inserendo i campi disponibili nel form.

Dopo aver configurato un sistema di tipo “Folder” esso non verrà visualizzato nella lista dei cloud provider, per trovarlo dalla pagina di “Cloud System” del modulo di “Administration” cliccare in alto a destra il tab “Folders” (Figura 66) dove verrà visualizzata la lista delle folder configurate nel tenant.

All’ interno della pagina è possibile effettuare le stesse operazioni di visualizzazione modifica e eliminazione delle folder effettuate sulla pagina dei “Cloud Provider” (5.6.1.4)

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/dc9041a3211c49841c7de18f65b52c43.png)

Figura 66 – Accesso a Folders

Accedendo ad una “Folder” in modalità “View” scorrendo in basso nella pagina possiamo visualizzare la lista dei sottosistemi presenti nel provider e le relative informazioni sullo status :

-   In verde possiamo notare un sottosistema configurato correttamente nel provider e che la SCMP provvede ad inserire automaticamente nel sistema e sarà visibile nella sezione “Cloud Providers” e in tutte le funzionalità della SCMP.
-   In rosso possiamo notare un sottosistema configurato in maniera errata che, dopo le opportune modifiche dalla console di “Google Cloud”, potrà essere accettato dalla SCMP.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/da31115ecce2d0965ec0d1c4ecd699c0.png)

Figura 67 – Visualizzazione sottosistemi della Folder

#### Azure Folder

Per consentire alla SCMP di sfruttare tutte le potenzialità offerte dal provider “Azure” è stata inserita la possibilità di configurare delle “Folders”

Durante la creazione di un provider selezionando la tipologia “Azure” (5.6.1.2.7) possiamo notare la presenza di un campo esclusivo per il provider ():

-   Un box di conferma per indicare alla SCMP se il provider in inserimento è una “Folder”

![Immagine che contiene testo, schermata Descrizione generata automaticamente](media/ae5c0315845b7ea59b23d514a3d04f31.png)

Figura 68 - Opzione folder Azure

I parametri specifici del sottosistema Azure da inserire sono esposti nella tabella

Figura 69 - Maschera di configurazione Azure

Vengono indicati con \* i parametri obbligatori

| **Nome**             | **Tipo** | **Descrizione**                                                                                                                                                                           | **esempio**                               |
|----------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| clientId **\***      | string   | L'ID univoco del client che si connette al sottosistema Azure Cloud. Questo ID viene utilizzato per identificare il client e per autorizzare l'accesso alle risorse del sottosistema.     | 5a85c16c6ad-49db-a58e-e209-ee11f53d6c6b   |
| clientSecret \*      | password | La chiave segreta del client, utilizzata per autenticare il client con il sottosistema Azure Cloud. La chiave segreta deve essere tenuta segreta e non deve essere condivisa con nessuno. | np6Kc_.xwsvhR8Q\~rP05fCqYNXmbqfMGQLOEzfMt |
| tenantId \*          | string   | L'ID del tenant Azure a cui appartiene il sottosistema Azure Cloud. Il tenant è un'entità organizzativa in Azure che rappresenta un'azienda o un'organizzazione.                          | 884147733-ff13-4783-a765-834183773083     |
| usageAggregation     | boolean  | Indica se l'aggregazione per "usage" è abilitata per la sottoscrizione. Quando questa spunta viene abilitata i costi del sottosistema verranno raggruppati per Tipologia risorsa          | false                                     |
| catalogPriceDiscount | integer  | Inserisci qui uno sconto/maggiorazione da applicare sui prezzi del catalogo per tutte le risorse che non hanno una relazione CMP                                                          | 5                                         |
| odlID                | string   | Inserisci qui l'id dell'ordine di lavoro che verrà associato al sottosistema e verrà inserito come tag su tutte le risorse del sottosistema                                               | ODL001                                    |
| clientId             | string   | L'ID univoco del client che si connette al sottosistema Azure Cloud. Questo ID viene utilizzato per identificare il client e per autorizzare l'accesso alle risorse del sottosistema.     | 5a85c16c6ad-49db-a58e-e209-ee11f53d6c6b   |
| datsFirstCostRecover | int      | Inserire il numero di giorni precedenti alla data di creazione dei quali bisogna recuperare i costi al primo avvio del sottosistema                                                       | 15                                        |

Tabella 21 – Campi specifici Azure Folder

### SIEM

L’utente può creare un provider di tipo SIEM, cliccando sul tab che raffigura uno scudo, posizionato nella barra in alto, come mostrato in (Figura 70).

Dopo aver effettuato l’accesso alla pagina “Cloud SIEMs”, in alto a destra, cliccare sull’hamburger menu e poi cliccare su “Attach a SIEM” (Figura 70).

![A screenshot of a computer Description automatically generated with medium confidence](media/1e2c6fdd1b43e21c0afff90d3b867da9.png)

Figura 70 - Creazione di un cloud provider SIEM

All’interno della pagina “Add SIEM” (Figura 71), compilare tutti i campi della sezione “General properties”. Dopo aver fatto questo, compilare tutti i campi della sezione “SIEM’s properties” seguendo la tabella.

![Immagine che contiene testo, monitor, screenshot, schermo Descrizione generata automaticamente](media/c97beef1b06a98e9164cfe139d71002a.png)

Figura 71 - Compilazione del form per la creazione di un provider SIEM

Vengono indicati con \* i parametri obbligatori

| **Nome**          | **Tipo** | **Descrizione**                                                                                                    | **esempio**                             |
|-------------------|----------|--------------------------------------------------------------------------------------------------------------------|-----------------------------------------|
| clientId \*       | string   | Identificativo univoco del SIEM al quale connettersi , Fornito dal SIEM durante la registrazione dell'applicazione | 1b16698f-2df5-ed44-86b9ed-4b42c 1fe7ad9 |
| clientSecret \*   | password | Il secret da utilizzare per la connessione, fornito dal SIEM durante la registrazione dell'applicazione            | 1b16698f-2df5-ed44-86b9ed-4b42c 1fe7ad9 |
| resourceGroup \*  | string   | Il gruppo di risorse Azure in cui è ospitato il SIEM                                                               | myGroup                                 |
| subscriptionId \* | string   | L'ID sottoscrizione Azure associata al SIEM                                                                        | 1b16698f-2df5-ed44-86b9ed-4b42c 1fe7ad9 |
| tenantId \*       | string   | L'ID tenant Azure associato al SIEM                                                                                | 1b16698f-2df5-ed44-86b9ed-4b42c 1fe7ad9 |
| workspaceID\*     | string   | L'ID dell'area di lavoro Log Analytics associata al SIEM                                                           | 1b16698f-2df5-ed44-86b9ed-4b42c 1fe7ad9 |
| workspaceName\*   | string   | Il nome dell'area di lavoro Log Analytics associata al SIEM                                                        | theWorkspaceName                        |

Tabella 22 – Campi specifici SENTINEL

Infine, in basso a destra, cliccare sul pulsante “Save”. Dopodiché, in basso appare un popup di avvenuta creazione del SIEM e l’utente viene reindirizzato all’interno della lista dei SIEM.

#### Visualizzazione, modifica ed eliminazione

Per visualizzare un SIEM, in corrispondenza di un suddetto, cliccare sul kebab menu e poi cliccare su “Show” (Figura 72). A questo punto, l’utente si ritrova all’interno della pagina “Show SIEM” in cui è possibile visualizzare ma non modificare i dati (Figura 73). Dopo aver visualizzato i dati, in basso a destra, cliccare sul pulsante “Close”. Fatto questo, l’utente si ritrova all’interno della lista dei SIEM.

![Immagine che contiene testo, screenshot, monitor Descrizione generata automaticamente](media/9e1719c7a1955c376c20305d527fc90f.png)

Figura 72 - Accesso al SIEM in modalità visualizzazione

![A screenshot of a computer Description automatically generated](media/5b6176cbf0883053933569abff9fcb09.png)

Figura 73 - SIEM in modalità visualizzazione

Per modificare un SIEM, in corrispondenza di un suddetto, cliccare sul kebab menu e poi cliccare su “Edit” (Figura 74). A questo punto, ci si ritrova all’interno della pagina “Edit SIEM” in cui è possibile modificare i campi (Figura 75).

Dopo aver modificato i campi di interesse, in basso a destra, cliccare sul pulsante “Update”. Fatto ciò, in basso appare un popup di avvenuta modifica del SIEM e l’utente si ritrova all’interno della lista dei SIEM.

![Immagine che contiene testo, screenshot, monitor Descrizione generata automaticamente](media/4ce317aea454b972ddd825b49f6902c2.png)

Figura 74 - Accesso al SIEM in modalità edit

![A screenshot of a computer Description automatically generated](media/ae336737bc76fcbb01c87ccfa249ed8c.png)![A picture containing appliance, screenshot Description automatically generated](media/cd9742d4f78cd0eb73fb3bcd7f7d83ed.png)

Figura 75 - SIEM in modalità edit

Per eliminare un SIEM, in corrispondenza di un suddetto, cliccare sul kebab menu e poi cliccare su “Delete” (Figura 76). A questo punto appare una modale in cui è necessario cliccare sul pulsante “Remove” (Figura 77). Fatto questo, il SIEM non è più presente all’interno della lista.

![Immagine che contiene testo, screenshot, monitor Descrizione generata automaticamente](media/ecd00d9881606d751eca2ec8530fd6f3.png)

Figura 76 - Opzione per eliminare un SIEM "Delete"

![Immagine che contiene testo, screenshot, monitor Descrizione generata automaticamente](media/f465c5299c7f715a56c58030276dbe69.png)

Figura 77 - Conferma per eliminare un SIEM

### Secrets Managers

L’utente può creare un secret manager cliccando sul tab che raffigura un lucchetto, posizionato nella barra in alto, come mostrato in figura (Figura 78).

Dopo aver effettuato l’accesso alla pagina “Secret manager”, in alto a destra, cliccare sull’hamburger menu e poi cliccare su “Add a secret manager” (Figura 78).

![A screenshot of a computer Description automatically generated with medium confidence](media/727953526b51fc22d9a547239df155e0.png)

Figura 78 - Aggiunta di un nuovo Secret Manager

Qui un esempio di form nel caso di aggiunta di un Secret manager dal provider di tipo Azure (selezionabile dal dropdown “Type” in alto nella pagina).

Dopo aver inserito tutti i parametri richiesti, in basso, cliccare il tasto “Save” per concludere l’inserimento e l’utente viene reindirizzato alla lista dei “Secret manager” dove è possibile visualizzare il componente appena creato.

#### Azure key vault

I parametri specifici (Figura 47) per un Azure key vault da inserire sono esposti nella tabella

![](media/3b259389ee0efbafef90ed5e54874298.png)

Figura 79 - Maschera di configurazione Azure key vault

Vengono indicati con \* i parametri obbligatori

| **Nome**          | **Tipo** | **Descrizione**                                                               | **esempio**                               |
|-------------------|----------|-------------------------------------------------------------------------------|-------------------------------------------|
| clientId **\***   | string   | Identificativo univoco del key vault                                          | 09f8985-9f89d0-4623-98982-5a510fd3d2      |
| clientSecret \*   | password | Una chiave segreta utilizzata per autenticare l'applicazione con il Key Vault | np6Kc_.xwsvhR8Q\~rP05fCqYNXmbqfMGQLOEzfMt |
| resourceGroup \*  | string   | Il gruppo di risorse Azure in cui è ospitato il Key Vault                     | resoruceGroupName                         |
| subscriptionId \* | string   | L'ID sottoscrizione Azure associata al Key Vault                              | 09f8985-9f89d0-4623-98982-5a510fd3d2      |
| tenantId          | string   | L'ID tenant Azure associato al Key Vault                                      | 09f8985-9f89d0-4623-98982-5a510fd3d2      |
| privateUrl        | string   | URL privato di accesso al key Vault                                           | https://vault.azure.net/vault             |

Tabella 23 – Campi specifici Azure key vault

#### Google Secret Manager

I parametri specifici (Figura 47) del Google Secret Manager da inserire sono esposti nella tabella

![](media/7459d22733b2b1a7d40ddc8b3ecbcf0f.png)

Figura 80 - Maschera di configurazione Google Secret Manager

Vengono indicati con \* i parametri obbligatori

| **Nome**            | **Tipo** | **Descrizione**                                                                                                | **esempio**                             |
|---------------------|----------|----------------------------------------------------------------------------------------------------------------|-----------------------------------------|
| kmsProjectId **\*** | string   | l'ID del progetto Google Cloud Platform (GCP) associato al servizio Google Cloud Key Management Service (KMS). | 5a85c16c6ad-49db-a58e-e209-ee11f53d6c6b |
| serviceAccount \*   | object   | File di connessione generato dalla console Google                                                              | service_account.json                    |

Tabella 24 – Campi specifici Google Secret Manager

È possibile inserire manualmente sul form visualizzato i parametri presenti nel file “service_account.json” se non si vuole effettuarne l’upload, tutti i parametri sono obbligatori:

| **Nome**                      | **Tipo** | **Descrizione**                                                                                                                                 | **esempio**                                                                                            |
|-------------------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| Type                          | string   | Inserire il nome della tipologia di autenticazione configurata                                                                                  | service_account                                                                                        |
| project_id \*                 | string   | Inserisci qui l'id univoco del progetto associato al service account                                                                            | Theproject-367810                                                                                      |
| private_key_id \*             | string   | Inserisci qui l'id univoco della chiave privata del service account                                                                             | 55cb5cf903ee93ea1e9c294a07e46e0af0633e6                                                                |
| private_key \*                | password | Contiene la chiave privata del service account in formato PEM. È fondamentale per l'autenticazione del service account alle API di Google Cloud |  -----BEGIN PRIVATE KEY-----MIIJQgIBADANB…                                                             |
| client_e-mail \*              | string   | L'indirizzo email univoco del service account. È utilizzato per identificare il service account quando si autentica alle API di Google Cloud    | [user@dominio.com](mailto:user@dominio.com)                                                            |
| client_id \*                  | string   | L'ID client del service account. È un identificatore univoco utilizzato per identificare il service account in Google Cloud                     | 104822473261100667392                                                                                  |
| auth_uri \*                   | string   | L'URI utilizzato per l'autenticazione del service account alle API di Google Cloud                                                              | https://accounts.google.com/o/oauth2/auth                                                              |
| token_uri \*                  | string   | L'URI utilizzato per ottenere un token di accesso per il service account                                                                        | https://oauth2.googleapis.com/token                                                                    |
| auth_provider_x509_cert_url\* | string   | L'URL del certificato X.509 utilizzato per l'autenticazione del service account                                                                 | https://www.googleapis.com/oauth2/v1/certs                                                             |
| client_x509_cert_url \*       | string   | L'URL del certificato X.509 nel client                                                                                                          | <https://www.googleapis.com/robot/v1/metadata/f543/myserviceaccount%40projectName.gserviceaccount.com> |

Tabella 25 – Campi specifici obbligatori del file “service_account.json”

### Visualizzazione , modifica ed eliminazione

È possibile visualizzare i dati di un Secret manager, all’interno della lista, cliccando sul kebab menu in corrispondenza di un manager, e successivamente su “Show” (Figura 81).

![A screenshot of a computer Description automatically generated](media/0cfc78899e588167fcdc22c2aa98fc5c.png)

Figura 81 - Accesso al manager in modalità visualizzazione

In questa pagina è possibile visualizzare la configurazione del Provider (Figura 82).

![A picture containing screenshot, text Description automatically generated](media/2d34cff41d1af93e5b3c85b0ce91e4ac.png)

Figura 82 - Visualizzazione manager in modalità visualizzazione

Per tornare alla pagina dei Secret manager, in basso a sinistra, cliccare sul pulsante “Close”.

A questo punto, l’utente si ritroverà all’interno della pagina dei Secret manager.

Per modificare i dati di un Secret manager all’interno della lista, cliccare sul kebab menu in corrispondenza di un Cloud Provider, e cliccare su “Edit” (Figura 83).

![A screenshot of a computer Description automatically generated with medium confidence](media/04aa367bbda36ffb9e72fccc8a97dfd9.png)

Figura 83 - Accesso al manager in modalità edit

Fatto ciò, l’utente si ritroverà all’interno della pagina del Cloud Provider in modalità edit in cui è possibile modificare i dati. Per tornare alla pagina dei Cloud Provider, in basso a sinistra, cliccare sul pulsante “Save”. A questo punto, l’utente si ritroverà all’interno della pagina dei Cloud Provider.

![A screenshot of a computer Description automatically generated](media/3224f8f1308a25f9d7c2856ff7716222.png)

Figura 84 - Avvio per l'eliminazione di un Secret manager

Per eliminare un **Secret manager**, all’interno della lista, cliccare sul kebab menu in corrispondenza di un Secret manager, e cliccare su “Delete” (Figura 84).

Fatto ciò, apparirà una modale in cui è necessario cliccare sul pulsante “Remove” (Figura 85).

A questo punto, il Secret manager non sarà più presente all’interno della lista e verrà lanciato il flusso di rimozione asset sul resource-manager.

**![A screenshot of a computer Description automatically generated](media/130c4cd730c76b601bdb1906820f6400.png)**

Figura 85 - Conferma eliminazione del Secret manager

## Dashboard

Accedendo alla SCMP, la homepage si presenta con un riassunto di quattro sezioni: inventario, monitoring, costi e security.

In particolare:

-   La sezione Inventory mostra:
-   Un grafico a torta che riguarda le risorse SCMP (per ogni risorsa di un singolo provider viene creata una istanza di tipo SCMP quindi il dato può essere considerato come la somma di tutte le risorse presenti in tutti i provider).
-   Un grafico a torta per ogni tipo di provider.
-   La sezione monitoring mostra le metriche più popolate con il loro relativo utilizzo.
-   La sezione costi mostra la sintesi dei costi degli ultimi 30 giorni.
-   La sezione security mostra le vulnerabilità più gravi.

Il titolo di ogni sezione è cliccabile e porta alla dashboard specifica.

![](media/157cdf31bb494b7bd3c9b4c7c7d51d6a.png)**![Immagine che contiene testo, elettronico, screenshot, proiettore Descrizione generata automaticamente](media/85f125e6fd2d8068975cbdf88b8f10d1.png)![Immagine che contiene testo, elettronico Descrizione generata automaticamente](media/ff15d1e7ea14f6d9870a7fecdcad5273.png)**

Figura 86 - Dashboard sezione "Inventory"

![](media/157cdf31bb494b7bd3c9b4c7c7d51d6a.png)![Immagine che contiene schermata, design, elettrodomestico Descrizione generata automaticamente](media/d20eb71affe0e79adaf2fcfcbae302eb.png)

Figura 87 - Dashboard sezione "Monitoring"

![Immagine che contiene elettrodomestico, schermata Descrizione generata automaticamente](media/fd7fcab0385ea631d43641334078ee8f.png)

Figura 88 - Dashboard sezione "Costs"

![Immagine che contiene testo, elettronico, screenshot, proiettore Descrizione generata automaticamente](media/0c6f53d363e0c73e108d60a615128510.png)

Figura 89 - Dashboard sezione "Security"

## Inventory

La funzionalità di inventario raccoglie i metadati degli asset installati all’interno di tutti i provider presenti sulla SCMP.

Gli asset attualmente presenti sono:

-   Virtual Machine
-   Data Stores
-   Networks
-   Kubernetes
-   Security
-   Others
-   What If
-   Reports

I metadati eterogenei, provenienti da diverse fonti vengono poi normalizzati dalla SCMP per permettere una visualizzazione standard.

L’inventario è accessibile dalla voce di menu “Inventory”. Come mostrato in figura.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/8c766eaeb73044338a6d36a68ee69515.png)

Figura 90 - Accesso a Inventory

Figura 91 – Dahsboard di inventario

### Dashboard di inventario

La pagina Dashboard permette di avere una visione globale e aggregata di tutte le risorse, mentre i menu sopra il path del breadcrumb danno la possibilità di filtrare per tipologia di risorsa. () le funzionalità disponibli nelle varie pagine sono identiche tra loro.

![A screenshot of a computer Description automatically generated](media/96e132a17668133a94216f64ed186655.png)

All’interno della pagina del tab “Resources”, sono presenti dei filtri, nel primo filtro in alto è possibile inserire la ricerca delle risorse in base al nome, al gruppo di risorse, provider, ecc., viene reso possibile inoltre di filtrare le risorse per “Provider” e “Subsystem”.

L’ultimo filtro permette la ricerca tramite tag. Cliccare su di esso e selezionare un tag (Rif.5.10.2), infine cliccando sul pulsante che raffigura una lente d’ingrandimento la pagina si aggiorna e si ottiene la lista delle risorse filtrate.

![A screenshot of a computer Description automatically generated](media/c5ed15ee80b91ff0883f2d083916cf27.png)

Figura 92 - Ricerca generica, per tag, per Provider e Subsystem

È possibile, inoltre, cliccare sui grafici per applicare automaticamente i relativi filtri.

#### Visualizzazione dettaglio risorsa

Per visualizzare il dettaglio di una risorsa, si può cliccare come in figura:

![A screenshot of a computer Description automatically generated](media/613d582bea8e247fcd6833f7797c0385.png)

Figura 93 - Accesso alla risorsa in modalità lettura

Il dettaglio di un asset di inventario mostra in alto le caratteristiche principali come costo mensile, size della macchina e link esterno alla risorsa che punta al provider di riferimento.

Di seguito la visualizzazione dei dettagli di una VM:

![A screenshot of a computer Description automatically generated](media/3ca119e1c333c2e222e4828fb73d4853.png)

Figura 94 - Dettaglio risorsa

E in calce le relazioni dell’asset con altri elementi di SCMP, come mostrato in figura:

![A screenshot of a computer Description automatically generated](media/6fb6816e57acd18385d3f01fecbcf3d0.png)

Figura 95 - Grafico delle relazioni

Il grafico delle relazioni permette di navigare tra le risorse cliccando direttamente sul tondino della risorsa concatenata in relazione, al fine di atterrare sul dettaglio di quest’ultima.

Inoltre, è possibile editare alcuni attributi, come ad esempio i tags, come da figura ():

![A screenshot of a computer Description automatically generated with low confidence](media/d518651e66905f1a97083ab9a8744e1d.png)

Figura 96 - Selezione del tag

Per il campo “Provider Tags…” non è possibile selezionare un tag, in quanto i tag in questa sezione vengono recuperati direttamente dal sottosistema

Il campo “Add SCMP Tag…” permette di selezionare da un elenco o inserirne uno manualmente. All’interno del tag è presente il simbolo “X” per eliminare il suddetto.

È possibile inserire più tag per la risorsa.

Successivamente, in basso a destra della sezione “Tags & Note”, cliccare sul pulsante “Save” per salvare la modifica ed apparirà un banner in basso di avvenuto salvataggio del tag.

Scorrere la pagina verso il fondo, e cliccare sul pulsante “Close” posizionato a destra per tornare nella pagina del tab “Dashboard”.

#### Azioni sulle macchine di inventario

Sempre dalla pagina del dettaglio della risorsa è possibile effettuare le seguenti operazioni utilizzando il menu in alto nella pagina:

-   Avvio della macchina
-   Stop della macchina
-   Ridimensionamento della macchina
-   Aggiunta di dischi di memoria
-   Aggiunta di un interfaccia di rete
-   Eliminazione della risorsa
-   Rimozione del disco nella risorsa
-   Rimozione di un interfaccia di rete

    Le operazioni disponibili sono diverse per ogni provider e sono indicate in bianco quando possono essere eseguite e in grigio quando non sono supportate o non disponibili.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/3fb0d69fbe836a3900b4124b61a45fac.png)

Figura 97 - Accesso al report di Inventory

### Reportistica Inventory

Sopra il path del breadcrumb, cliccare sul tab “Reports” (Figura 98). L’utente si ritrova all’interno del tab “Report Types” in cui è necessario cliccare sul pulsante “RUN NOW” in corrispondenza di “Inventory Summary” per avviare la modale in cui è possibile inserire i filtri per la creazione del report (Figura 99).

![A screenshot of a computer Description automatically generated](media/1b6aca5c5557fe3a1077e5a9438fe023.png)

Figura 98 - Accesso al report di Inventory

![A screenshot of a computer Description automatically generated with medium confidence](media/dab138b8c9c47456da4f58f0f0fefd1b.png)

Figura 99 - Esecuzione del report

Una volta che si sarà aperta la modale dei filtri, è possibile compilare alcuni o tutti i parametri. Una volta compilati i parametri desiderati, in basso a destra della modale, cliccare sul pulsante “Submit” (Figura 100).

![A screenshot of a computer Description automatically generated](media/e95579d6cca47de5b1d41638c4510090.png)

Figura 100 - Applicazione dei filtri report

Fatto ciò, l’utente si ritrova all’interno del tab “Results” in cui è presente lo storico di tutti i report (Figura 101).

Per arrivare in questa sezione senza effettuare prima un report bisogna cliccare sopra alla lista delle tipologie di report il tab “Results”

In fondo alla pagina a destra, è possibile selezionare il numero di elementi da visualizzare per pagina. Le frecce racchiuse all’interno del rettangolo consentono all’utente di visualizzare gli elementi delle pagine successive e precedenti. Invece, le frecce al di fuori del rettangolo consentono di spostarsi nell’ultima e nella prima pagina (Figura 102).

![A screenshot of a computer Description automatically generated](media/b588a399f04e9e76f55bf01cb3ee71bd.png)

Figura 101 - Gestione dello storico dei report

![A screenshot of a computer Description automatically generated with medium confidence](media/4f0a2888fd00c246ad1871c604195758.png)

Figura 102 - Gestione pagine report

Per visualizzare i dettagli del report generato, cliccare sul report che sta nella prima riga come indicato dalla freccia (Figura 102).

A questo punto, l’utente si ritrova all’interno del sommario del report (Figura 103). All’interno del sommario del report dell’Inventory è presente la sezione “Stats” in cui sono presenti il numero dei dischi, delle interfacce, delle reti e delle Virtual Machines appartenenti al provider selezionato.

Sotto la sezione “Stats”, sono presenti i filtri usati dall’utente per generare il report. Sotto i filtri, è presente la tabella riassuntiva delle risorse appartenenti al provider. A destra sono presenti due pulsanti: “PRINT” ed “EXPORT”.

Cliccando sul pulsante “PRINT”, appare una modale di anteprima della stampa. Per stampare il report, cliccare sul pulsante in basso a destra “Stampa”, a questo punto si avvierà la stampa del suddetto.

Cliccando sul pulsante “EXPORT”, è possibile esportare il report in formato “.csv”, “. json” o “.pdf”.

Per tornare al tab “Results”, in basso a destra, cliccare sul pulsante “CLOSE” oppure in alto a sinistra cliccare sulla freccia che punta verso la sinistra, accanto al titolo del report.

![A screenshot of a computer Description automatically generated](media/56c7076bb5fdd0b1003887e93cfab07c.jpeg)

Figura 103 - Sommario del report

### Funzionalità “WHAT IF”

Questa funzionalità permette di eseguire degli scenari di simulazione per la migrazione degli asset da un provider a un altro in modo da poter confrontare i costi di gestione e mantenimento.

Per eseguire una simulazione , cliccare sopra il path del breadcrumb il tab che raffigura una relazione che collega due entità denominato ‘What If’ (Figura 104).

Dopo aver fatto ciò, ci si ritrova all’interno della pagina del tab “What If” (Figura 105).

Possiamo notare sopra la lista delle simulazioni, sulla destra, due tab che permettono di filtrare la lista per tipologia di simulazione , nello specifico:

All’ apertura della pagina verranno visualizzate tutte le simulazioni di tipo “Change Provider” mentre cliccando sul tab “Capacity” sarà possibile visualizzare la lista delle simulazioni di tipo “Change size”

![A screenshot of a computer Description automatically generated](media/dbd4b1c125e8b509a86b5c120bd684d5.png)

Figura 104 - Accesso a “What If”

![A screenshot of a computer Description automatically generated](media/cac53f52f62f824aabab392c030f69be.png) ![](media/925d4691f018db16eed72b17a3cbeed0.png)

Figura 105 - Pagina di “What If”

#### Scenario “What If”: Provider Migration

Per effettuare una simulazione del “What If: Migrate Provider”, cliccare nel riquadro a sinistra intitolato “Migrate to another provider” (Figura 106).

![A screenshot of a computer Description automatically generated](media/5c2e3880b39ea0b45e9a1cd4dad6a972.png)

Figura 106 - Accesso alla funzionalità "What If: Migrate Provider"

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Start” dello step 1 per la simulazione della migrazione da un cloud provider ad un altro (Figura 107).

A sinistra nel riquadro “Select Resources to migrate”, l’utente può ricercare le risorse tramite tre tipi di filtri tra cui:

-   “Search” che consente di cercare una risorsa per nome;
-   “Search by Type” di ottenere le risorse tramite la selezione del tipo di risorsa;
-   “Search by tags” che consente di ricercare le risorse tramite uno o più tag (5.11.2.).

All’interno della tabella delle risorse verranno visualizzate solo risorse che abbiano una relazione nel catalogo (5.9.1.1 Esportazione scenario “What If”: Provider Migration

All’interno della tabella delle risorse, cliccare su una di essa e tramite la tecnica del “drag and drop”, trascinarla a destra, all’interno nel riquadro intitolato “Currently selected ”.

È possibile inserire un numero massimo di tre risorse per simulazione.

Successivamente, in basso a destra, cliccare sul pulsante “Next”.

![A screenshot of a computer Description automatically generated](media/c4a14078687e607fb198d968ddf3bca8.png)

Figura 107 - Scelta delle risorse in cui effettuare la migrazione del provider

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Destination Providers” dello step 2 in cui è possibile cliccare sul checkbox in corrispondenza di uno o più provider ove, in base al tipo di provider selezionato, verrà automaticamente compilato in basso a sinistra il valore nel campo ‘Option selected” con i nomi dei providers selezionati (Figura 107).

Successivamente, in basso a destra, cliccare sul pulsante “Next”, mentre per tornare alla pagina “Start” dello step 1, cliccare sul pulsante “Back”.

![A screenshot of a computer Description automatically generated](media/fc7cad6b6d1bb766bbfc8effc214db8d.png)

Figura 108 - Scelta del Cloud Provider in cui migrare le risorse

Dopo aver cliccato sul pulsante “Next”, l’utente si ritroverà all’interno della pagina dello step 3 intitolato “Details” (Figura 109).

All’interno della pagina, nel riquadro a sinistra intitolato “Region”, selezionare dal menu a tendina una o più regione.

Dopodiché, a destra è presente, il riquadro intitolato “Cost Model” in cui è necessario selezionare il tipo di costo.

Dopo aver selezionato la regione e il tipo di costo, in basso a destra, cliccare sul pulsante “Next”, invece per tornare allo step 2 della pagina “Destination Providers”, cliccare sul pulsante “Back”.

![A screenshot of a computer Description automatically generated](media/e72a22c657bdf1aab0a1f9d9a3dc8bf6.png)

Figura 109 - Selezione della "Regione" e del "Cost Model"

Dopo aver cliccato sul pulsante “Next”, l’utente si ritroverà all’interno dello step 4 intitolato “Duration” (Figura 110).

Dalla pagina “Duration” dello step 4, selezionare un intervallo per la simulazione tra:

-   “One Month”
-   “Six Months”
-   “One Year”

Per tornare indietro alla pagina “Details”, in basso a destra, cliccare sul pulsante “Back”. Invece, per andare avanti con la simulazione, cliccare sul pulsante “Launch Simulation”.

![A screenshot of a computer Description automatically generated with medium confidence](media/d5cdc1031962a8e89867b761aefa5405.png)

Figura 110 - Selezione dell'intervallo di tempo

Dopo aver cliccato sul pulsante “Launch Simulation”, l’utente si ritroverà all’interno della pagina “Results” dello step 5 (Figura 111).

L’utente ritrovandosi all’interno della pagina “Results”, in alto noterà il riquadro “Simulation parameters” con i dati dei parametri per ottenere la simulazione per la migrazione ad un altro provider.

Sotto è presente il riquadro “Summary” in cui è presente il consiglio se effettuare la migrazione al cloud provider selezionato durante la simulazione.

Sotto il riquadro “Summary”, è presente un grafico a istogrammi nel riquadro “Details”, nel quale la barra viola rappresenta gli attuali costi, mentre la barra verde rappresenta il target dei costi.

In basso, è presente la tabella dei costi della/e risorse (Figura 112).

Per uscire dalla simulazione senza salvare la suddetta, in basso a destra, cliccare sul pulsante “Close”.

Fatto ciò, l’utente si ritrova all’interno della pagina “What If”. Per salvare la simulazione, cliccare sul pulsante “Save” accanto al pulsante “Close”, e poi cliccare su “Confirm”.

Dopo aver cliccato sul pulsante “Save”, l’utente viene reindirizzato nella pagina del tab “What If”.

![A screenshot of a computer Description automatically generated](media/501f5324d8601f2a5928f5bd9207049c.png)

Figura 111 - Parametri di configurazione e consiglio sulla simulazione

![A screenshot of a computer Description automatically generated](media/024ca6c12cf5df0c0150969929846006.png)

Figura 112 - Tabella riassuntiva della/e risorse

![A screenshot of a computer Description automatically generated](media/1431fa6090d9bbd542ed455c14c80537.png)

Figura 113 - Avvio per l'aggiornamento della simulazione di tipo "Migrate to another provider"

#### Scenario “What If”: Change Resource Capacity

Questa funzionalità permette di confrontare i costi di una risorsa in caso di modifica delle caratteristiche tecniche.

Sempre dalla pagina del tab “What If”, in alto a destra, cliccare sul riquadro “Change resources capacity “(Figura 114).

![A screenshot of a computer Description automatically generated with medium confidence](media/e49a6ca7762be1efded9594eae489c4f.png)

Figura 114 - Accesso alla funzionalità "What If: Change resources capacity"

Dopo aver fatto ciò, l’utente si ritroverà all’interno della pagina “Start” dello step 1 (Figura 115).

A sinistra nel riquadro “Select Resources to change”, l’utente può ricercare le risorse tramite tre tipi di filtri tra cui:

-   “Search” che consente di cercare una risorsa per nome;
-   “Search by Type” che consente di ottenere le risorse tramite la selezione del tipo di risorsa;
-   “Search by tags” che consente di ricercare le risorse tramite uno o più tag associato alle suddette (Rif.5.11.2).

Nella tabella delle risorse verranno riportate (se ci sono) solo risorse che, all’interno del catalogo SCMP, abbiamo più di una “Relazione” (5.9.1.1) con size differenti ma appartenenti alla stessa regione, stesso tipo di prezzo e sistema operativo.

In basso a sinistra, è presente la tabella delle risorse, che può essere filtrata in base ai parametri inseriti nel o nei filtri. All’interno della tabella delle risorse, cliccare su una di essa e tramite la tecnica del “drag and drop”, trascinarla a destra, all’interno nel riquadro intitolato “Currently selected :”.

È possibile inserire un numero massimo di tre risorse per simulazione.

Successivamente, in basso a destra, cliccare sul pulsante “Next”.

![A screenshot of a computer Description automatically generated](media/cb6cf358ac717e5dd2c25caf098e7a61.png)

Figura 115 - Selezione delle risorse da cui modificare le capacità

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Resource Provider” dello step 2 in cui è possibile modificare la size di una o più risorse (Figura 116).

All’interno della pagina “Resource Provider” dello step 2, in corrispondenza di una risorsa, cliccare sul menu a tendina della colonna “Size” e selezionare una size diversa da quella iniziale.

Dopodiché, in basso a destra, cliccare sul pulsante “Next” per proseguire la simulazione.

Per tornare alla pagina “Start” dello step 1, cliccare sul pulsante “Back”.

![A screenshot of a computer Description automatically generated](media/51901a3e7c67d753f7563026bf0c77c0.png)

Figura 116 - Modifica della size di una risorsa

Dopo aver cliccato sul pulsante “Next”, l’utente si ritroverà all’interno della pagina “Duration” dello step 3 (Figura 116).

All’interno della suddetta pagina, è necessario selezionare un intervallo per la simulazione.

Dopodiché, in basso a destra, cliccare sul pulsante “Launch Simulation”.

Per tornare indietro, cliccare sul pulsante “Back”, in questo modo l’utente si ritrova all’interno della pagina “Resource Provider” dello step 2.

![A screenshot of a computer Description automatically generated](media/8889b5c0ba5db8def1f1b9b24ecd6404.png)

Figura 117 - Selezione dell'intervallo per la simulazione

Dopo aver cliccato sul pulsante “Launch Simulation”, l’utente si ritrova all’interno della pagina “Results dello step 4 (Figura 117).

All’interno della pagina “Results”, in alto è presente il riquadro “Summary” che consiglia se modificare la size delle risorse. Sotto, è presente un grafico di istogrammi, in cui la barra viola rappresenta i costi attuali, mentre la barra verde rappresenta i costi target.

Per salvare la simulazione, cliccare sul pulsante “Save” accanto al pulsante “Close”, e poi cliccare su “Confirm”. Fatto ciò, l’utente viene reindirizzato nella pagina di “What If”.

Per uscire dalla simulazione senza salvare la suddetta, in basso a destra, cliccare sul pulsante “Close”. Fatto ciò, l’utente si ritrova all’interno della pagina “What If”.

![A screenshot of a computer Description automatically generated](media/ff4e62458fa38b3e9188edfd1e968f10.png) ![A screenshot of a computer Description automatically generated with medium confidence](media/c4c5da07bd65658d00e050f734609f22.png) ![](media/1700b51bd79cbc1aaf6e81aa71d19fdb.png)

Figura 118 - Parametri di configurazione e consiglio sulla simulazione

#### Esportazione scenario What If

Per una simulazione della modifica di una size di una risorsa, è possibile esportare la suddetta in formato pdf, csv e json.

All’interno della pagina di “What If”, in basso è presente una tabella delle simulazioni, cliccare sul pulsante “Capacity” posizionato nell’angolo superiore destro della suddetta tabella.

Dopo aver fatto ciò, la tabella mostra le simulazioni sulla modifica della size delle risorse.

In corrispondenza di una simulazione, cliccare sul pulsante che raffigura una freccia.

A questo punto si aprirà un sottomenu in cui è possibile effettuare l’export nei tre formati precedentemente descritti (Figura 119).

![A screenshot of a computer Description automatically generated](media/b0c1b0b226282b465d4b9bd5353e1ca3.png)

Figura 119 - Export della simulazione

Sempre per una simulazione è possibile effettuare la stampa della suddetta.

In corrispondenza di una simulazione, cliccare sul kebab menu, e a quel punto cliccare sull’opzione “Print” (Figura 120).

A questo punto, apparirà una modale dell’anteprima del documento da stampare. Infine, cliccare sul pulsante “Stampa” per avviare la stampa del documento.

![A screenshot of a computer Description automatically generated](media/c35c3577aed0bc27fbf8ce4e501cc99e.png)

Figura 120 - Stampa della simulazione

In corrispondenza di una simulazione, cliccare sul kebab menu,

Dalla lista delle opzioni, cliccare su “Delete” (Figura 121).

Dopo aver cliccare sull’opzione “Delete”, apparirà una modale in cui è necessario confermare l’eliminazione della simulazione cliccando sul pulsante “Confirm” (Figura 122).

Fatto ciò, la simulazione non è più presene all’interno della tabella.

Se invece non si vuole dare la conferma per l’eliminazione della simulazione, cliccare sul pulsante “Cancel”.

![A screenshot of a computer Description automatically generated](media/96e765acaf4fc818e087d06b0d3fd04c.png)

Figura 121 - Opzione per eliminare una simulazione

![A screenshot of a computer Description automatically generated](media/2984d9ec7431d988e3d5ba19fe2b89e8.png)

Figura 122 - Conferma dell'eliminazione della simulazione

È possibile effettuare una modifica alla simulazione, cliccando semplicemente nel rigo della suddetta simulazione. L’utente si ritroverà all’interno dello step 1 della pagina “Start” in cui può modificare la risorsa presente nel riquadro a destra, oppure può aggiungerne altre (per un massimo di tre risorse totali), e così con la modifica della size delle risorse, e dell’intervallo della simulazione. Gli step da seguire sono simili a quelli descritti precedentemente.

![A screenshot of a computer Description automatically generated](media/d00955954af6427673ec7c53572e29e1.png)

Figura 123 - Lista simulazioni già eseguite

![A screenshot of a computer Description automatically generated](media/534f7a9b1b6d6fa970463c30e2f551a0.png)

Figura 124 - Aggiornamento della simulazione

## Catalog

La sezione Catalog ha tre importanti funzionalità:

-   Mostrare l’elenco degli asset installabili recuperati dai provider con i relativi prezzi e regioni associabili.
-   Dare la possibilità all’amministratore del tenant di definire gli item utilizzabili successivamente per il provisioning.
-   Dare la possibilità all’amministratore del tenant di definire gli item utilizzabili successivamente all’ interno delle simulazioni del modulo What If.

I prezzi recuperati, oltre a essere visibili all’interno del dettaglio dell’asset, vengono utilizzati per gli scenari What If e il calcolo dei costi.

Per accedere alla funzionalità di Catalog, in alto a sinistra cliccare sul pulsante bento.

Dopodiché, cliccare su “Catalog” (Figura 125).

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/6a5199030db9d4e614c13d25f287dd49.png)

Figura 125 - Accesso a Catalog

A questo punto, l’utente si ritrova all’interno della pagina del tab “Resources” (Figura 126).

Possiamo suddividere la funzionalità in 3 sezioni per specificarne il comportamento:

\- Elementi di catalogo CMP ( riquadro giallo nell’ immagine)

\- Elementi di catalogo dei Providers (riquadro verde nell’ immagine)

\- Servizi e blueprint di catalogo CMP (riquadro rosso nell’ immagine)

Di seguito analizzeremo ogni gruppo di funzionalità separatamente.

![](media/f258c745041d099273ebbe24be410da8.png)

Figura 126 - Catalogo della SCMP

### Gestione Elementi di catalogo SCMP

All’interno della pagina sono presenti una serie di filtri che una volta selezionati e cliccando sul pulsante che raffigura una lente d’ingrandimento verranno utilizzati per filtrare la lista dei risultati (Figura 127)

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/6d609622cb7ef86b1ad366cbc4ca680e.png)

Figura 127 - Catalogo SCMP filtrato

Accanto al pulsante che raffigura una lente d’ingrandimento, è presente il pulsante che raffigura una “X” per effettuare il reset dei filtri e della tabella delle risorse.

Sotto il filtro di ricerca, è presente il filtro di ricerca per tag. (Rif.5.10.2 )

Cliccare su di esso e selezionare un tag, a questo punto la tabella restituisce le risorse associate con il tag selezionato dall’utente.

#### Relazioni tra risorse

All’ interno della SCMP è possibile configurare una risorsa di tipo “Relazione”, questa relazione consente di mappare le macchine dei vari provider per modificarne i costi e permetterne l’utilizzo nelle altre funzionalità.

Per accedere alla pagina delle relazioni cliccare il tab “CMP Resources” in alto nella funzionalità di Catalogo.(Figura 128)

![](media/2e59177e6f839cffc960892ac3bed01f.png)

Figura 128 - Accesso a "Relazioni"

In alto è presente una sezione filtri che permette la ricerca per:

-   “Search” : permette di inserire un testo libero per la ricerca
-   “Search By tags” : permette di cercare tramite i tag associati alle risorse
-   “Search by Service name”: permette la ricerca tramite nome del servizio.

##### Export delle risorse

Per esportare l’elenco delle risorse del Catalogo presenti all’interno della lista, all’interno della pagina in alto a destra cliccare sull'hamburger menu, e poi cliccare su “Export” (Figura 129).

L’operatore avrà la possibilità di esportare la lista dei risultati in formato .csv e/o .json.

![A screenshot of a computer Description automatically generated](media/d5ff98b2f171f19a13986d54b2121b27.png)

Figura 129 – Scaricare la lista di risultati

##### Funzionalità Aggiornamento Forzato del Catalogo

Attraverso la funzionalità di Force Sync, è possibile richiedere un aggiornamento del catalogo cliccando sull’hamburger menù e successivamente cliccando su “Force Sync”( Figura 130)

![A screenshot of a computer Description automatically generated with medium confidence](media/0b053a343991a98a5a4c0837fb6d0816.png)

Figura 130 – Funzionalità Force Sync

##### Creazione relazione di Catalogo

Per creare una risorsa sul Catalogo, sempre all’interno della pagina in alto a destra cliccare sull'hamburger menu, e poi cliccare su “Add Catalog Resource” (Figura 131).

![A screenshot of a computer Description automatically generated](media/ddc627743e5091fd799dcb026d4e102d.png)

Figura 131 - Opzione per aggiungere una risorsa

A questo punto, l’utente si ritrova all’interno della pagina in cui è possibile selezionare il tipo di risorsa da creare (Figura 132).

![A screenshot of a computer Description automatically generated](media/d9dbb84e3e8fa5023c53235a05cc5240.png)

Figura 132 - Selezione del tipo di risorsa da creare

Dal menu a tendina, selezionare il tipo di risorsa da creare. Dopodiché, cliccare sul pulsante “Next”. Ci si ritrova all’interno della pagina di compilazione della risorsa (Figura 133).

![](media/5796b892dc5cfb1c91a07e4d3fcb5d90.png)

Figura 133 – Esempio di form per la creazione di una relazione

I singoli parametri da inserire nella sezione “Properties” venogno specificati nella tabella:

Vengono indicati con \* i parametri obbligatori

| **Nome**        | **Tipo** | **Descrizione**                                                                                 | **esempio**      |
|-----------------|----------|-------------------------------------------------------------------------------------------------|------------------|
| cateogry        | string   | Inserire la categoria di appartenenza della risorsa                                             | CAT0004BT        |
| Price list code | string   | Inserire il codice identificativo del listino prezzi dal quale vengono ricavate le associazioni | PRC005DE         |
| confidential    | boolen   | Se abilitato indica che la risorsa è di tipo confidenziale                                      | false            |
| description     | string   | Inserire una descrizione libera della risorsa                                                   | Low end machine  |
| Name\*          | string   | Inserire il nome della risorsa                                                                  | 8Core16GB- small |
| RAM(GIB)\*      | integer  | Inserisci qui il la quantità in GiB utilizzate dalle macchine inserite nella relazione          | 16               |
| VCPU\*          | integer  | Inserisci qui il numero di vCPU utilizzate dalle macchine inserite nella relazione              | 8                |

Tabella 26 – Campi specifici relazione VM

All’interno della pagina di creazione della risorsa (Figura 134), compilare tutti i campi della sezione “Properties”. Dopo aver fatto ciò, selezionare uno o più tag per il campo “Add SCMP tag…” e compilare delle note all’interno della sezione “Tags & Note”

. ![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/d47043d138f9d380d58f0d7b2a43e98c.png)

Figura 134 - Sezione tag e note

All’interno della sezione “Relations”, aprire la sezione a sinistra (Figura 135), successivamente è possibile utilizzare i filtri “search” con testo libero o selezionare un “System Type” tra quelli disponibili per filtrare la tabella delle risorse

Una volta individuata la risorsa da associare portare , utilizzando il drag and drop, la risorsa dalla parte destra della pagina alla parte sinistra.

È possibile aggiungere una sola risorsa per tipologia di provider, se l’utente prova a inserire un'altra risorsa dello stesso provider apparirà un pop up che invita l’utente ad aggiungere una sola risorsa per provider.

![](media/2c738c4d3bb7dfa04583c5b39338292b.png)

Figura 135 - Selezione del provider per associare le risorse

Possiamo effettuare una associazione “A uno a Uno” inserendo in questa sezione una sola macchina, in questo modo il sistema ci permette di selezionare manualmente, nella sezione “Cost” in basso (Figura 136), un prezzo personalizzato da associare alla risorsa. Per farlo bisogna selezionare l’ intervallo di fatturazione (orario, giornaliero, settimanale, mensile) e inserire a destra il costo (che valuta?) relativo al periodo selezionato.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/322b0c938c985800202f19ed848ddaac.png)

Figura 136 - Sezione costi delle relazioni

Selezionando più di una macchina per provider, la sezione costi viene nascosta automaticamente, i costi applicati saranno definiti dalle percentuali configurate nei sottosistemi. (Figura 137).

![](media/504ed691645e638fa99c78f8d9df0155.png)

Figura 137 - Risorse associate alla risorsa SCMP

Una volta inserite le risorse in relazione, nella sezione ‘Relations Chart’ si creerà automaticamente un diagramma illustrativo (Figura 138).

![](media/b612f46f440c8e12952dbd28ce4a0c3c.png)

Figura 138 – Creazione automatica del Relation Chart

Infine, in basso a destra, cliccare sul pulsante “Save” per salvare le modifiche. Apparirà un banner in basso che avvisa l’utente dell’avvenuta creazione della risorsa, e viene reindirizzato nella pagina contenente la lista di risorse.

##### Utilizzo della tabella di Catalogo

###### Visualizzazione riepilogo Risorsa

Per visualizzare i dati di una risorsa di SCMP, nella pagina “Resources” di Catalog, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul record di interesse, apparirà una finestra che riporta piccole informazioni della risorsa individuata: Sistema, Nome, Taglia , Data aggiornamento , RAM e CPU come presente nell’immagine seguente (Figura 139).

![A screenshot of a computer Description automatically generated](media/5937627e0f43bb5d1698748d23fbb69b.png)

Figura 139 – Dettaglio rapido delle risorse di catalogo

###### Visualizzazione delle relazioni di Catalogo

Per visualizzare i dati di una risorsa di SCMP, nella pagina “Resources” di Catalog, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Show” (Figura 140).

![A screenshot of a computer Description automatically generated](media/69f23857fb85fd38b430a3b1ee3a8168.png)

Figura 140 - Accesso alla risorsa in modalità view

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina della risorsa in modalità view, nel quale potrà visualizzare i dati ma non potrà modificarli (Figura 141).

![A screenshot of a computer Description automatically generated with medium confidence](media/74428a1d7810edd7ce2e1c07f0b25518.png)

Figura 141 - Dettaglio completo delle risorse di catalogo

Il dettaglio di una risorsa è suddiviso in varie sezioni:

\- Details.

\- Properties (Figura 142).

\- Tags & Notes (Figura 143).

\- Relations: (Figura 144).

\- Cost, se presente

\- Relations Chart (Figura 145).

![A screenshot of a computer Description automatically generated](media/a159e71757c75876d1ac2742c59b038c.png)

Figura 142 - Sezione proprietà degli elementi del catalogo

![A screenshot of a computer Description automatically generated with medium confidence](media/30f7fab1494ea48906f7752fe5107eba.png)

Figura 143 - Sezione Tags & Note degli elementi del catalogo

![A screenshot of a computer Description automatically generated](media/8856f1731b4b35885b8ccb697d5e702a.png)

Figura 144 - Sezione delle relazioni del catalogo SCMP

![A screenshot of a computer Description automatically generated](media/d898a5aa02a7313897bdf46d970327ed.png)

Figura 145 - Sezione Relations Chart delle risorse

In basso a destra, cliccare sul pulsante “Close”. L’utente verrà reindirizzato nella pagina “Resources” di Catalog.

###### Modifica delle relazioni di Catalogo

Per modificare una risorsa di SCMP, nella pagina “Resources” di Catalog, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Edit” (Figura 146).

![A screenshot of a computer Description automatically generated](media/6d806cf8de98bcae8000ac1eb2f83e23.png)

Figura 146 - Accesso alla risorsa in modalità edit

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina della risorsa in modalità edit, a differenza della modalità ‘Show’ in quella ‘Edit’ è possibile modificare la sezione Properties e la sezione Cost (Figura 147).

In basso a destra, cliccare sul pulsante “Save”. A questo punto, in basso apparirà un banner che avvisa l’utente dell’avvenuto aggiornamento della risorsa.

Inoltre, l’utente verrà reindirizzato nella pagina “Resources” di Catalog.

![](media/71c8a894f5b097f81d548ac5cca62e0a.png)

Figura 147 - Modifica della relazione

###### Eliminazione delle relazioni di Catalogo

Per eliminare una risorsa di SCMP, nella pagina “Resources” di Catalog, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Delete” (Figura 148). Fatto ciò, appare una modale in cui è necessario cliccare sul pulsante “Remove” per confermare l’eliminazione della risorsa (Figura 149).

![A screenshot of a computer Description automatically generated](media/8d6ab0635a1369f3ae980d9477e87061.png)

Figura 148 - Eliminazione di una risorsa

![A screenshot of a computer Description automatically generated](media/0a73aeb3c818396c7694d3bc48668e59.png)

Figura 149 - Conferma eliminazione della risorsa

#### Relazioni tra SKU

All’ interno della SCMP è possibile configurare una risorsa di tipo “SKU SCMP”, questa relazione consente di mappare gli sku ricevuti dai provider per poterne definire i costi e l’unità di misura visualizzata nel sistema.

Per accedere alla pagina degli SKU cliccare il tab “CMP SKU” in alto nella funzionalità di Catalogo.(Figura 150)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/c2a4631aee52f0f45202fa61650f8656.png)

Figura 150 - Accesso a "CMP SKU"

In alto è presente una sezione filtri che permette la ricerca per:

-   “Search” : permette di inserire un testo libero per la ricerca
-   “Search By tags” : permette di cercare tramite i tag associati alle risorse
-   “Search by Service name”: permette la ricerca tramite nome del servizio.

##### Export delle risorse

Per esportare l’elenco delle risorse del Catalogo presenti all’interno della lista, sempre all’interno della pagina del tab “SCMP” in alto a destra cliccare sull'hamburger menu, e poi cliccare su “Export” (Figura 151).

L’operatore avrà la possibilità di esportare la lista dei risultati in formato .csv e/o .json.

![A screenshot of a computer Description automatically generated](media/d5ff98b2f171f19a13986d54b2121b27.png)

Figura 151 – Scaricare la lista di risultati

##### Creazione relazione di Catalogo SKU

Per creare una risorsa sul Catalogo, sempre all’interno della pagina del tab “SCMP”, in alto a destra cliccare sull'hamburger menu, e poi cliccare su “Add Catalog Resource” (Figura 152).

![](media/b311420a66359ccf7b4601ceb2899593.png)

Figura 152 - Opzione per aggiungere una risorsa “SKU”

A questo punto, l’utente si ritrova all’interno della pagina di creazione di una risorsa ”SKU”,cliccare sugli accordion presenti in pagina per visualizzarne i dettagli (Figura 153).

![](media/cde4151a24a3b2039c9b3df7102089bf.png)

Figura 153 – Pagina di creazione “SKU”

Nella sezione “Properties” (Figura 154) compilare tutti i campi definiti nella tabella:

Vengono indicati con \* i parametri obbligatori

| **Nome**                      | **Tipo** | **Descrizione**                                                                                                                                                                                                                                                 | **esempio**                               |
|-------------------------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
| Price list code               | string   | Inserire il codice identificativo del listino prezzi dal quale vengono ricavate le associazioni                                                                                                                                                                 | PRI002FG                                  |
| description                   | string   | Inserire una descrizione libera dello sku                                                                                                                                                                                                                       | This sku is the basic vm on this provider |
| name \*                       | string   | Inserire il nome dello SKU                                                                                                                                                                                                                                      | Simple vm sku                             |
| Service name                  | string   | Inserire il nome del servizio correlato allo SKU                                                                                                                                                                                                                | Informations service                      |
| unit                          | string   | Inserire un testo che verrà utilizzato come “unità di misura” visualizzata su tutte le funzionalità                                                                                                                                                             | MB/hour                                   |
| Unit conversion Expression \* | string   | Inserire la formula di conversione tra il valore ricevuto dal provider e il valore che verrà utilizzato nella cmp (conversione tra unità di misura del provider e unità di misura indicata nella relazione SKU)  “\$var” indica il valore ricevuto dal provider | \$var \* 24 / 100                         |

Tabella 27 – Campi “Properties” specifici SKU

![](media/a5c919046c73c339df22eeea075f0d85.png)

Figura 154 - Compilazione dei campi, selezione Properties

Dopo aver inserito la formula di conversione è necessario cliccare sul pulsante “Test expression” per verificarne la correttezza.

Se è stata inserita correttamente il pulsante diventerà di colore “Verde” con scritto “TEST OK” , (Figura 155) in caso contrario diventerà di colore “Rosso” “KO”, in questo caso la possibilità di salvare la relazione viene inibita.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/d50f77fd17ae8bb3786a291b7adf59ee.png)

Figura 155 - conferma della formula di conversione

Successivamente, selezionare uno o più tag per il campo “Add SCMP tag…” e compilare delle note all’interno della sezione “Tags & Note”.

Nella sezione “Relation” è possibile selezionare uno o più SKU provienienti dai vari cataloghi dei provider, per relazionarli tra loro e unificarne i costi, per farlo cliccare nella sezione “Composition” sulla sinistra, verrà aperta una sezione scura dove , tramite la tecnica del drag and drop (Figura 156) possiamo spostare gli SKU disponibili nella sezione destra .

Nella sezione destra è possibile utilizzare i filtri per visualizzare solo i risultati pertinenti, i filtri disponibili sono , il provider d’ origine , il nome del servizio e un campo di testo libero (in giallo nell’ immagine)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/06a6820d4fad24158844fdf4c928fc86.png)

Figura 156 - Drag and drop Relazioni SKU

Una volta inserite le risorse in relazione, nella sezione ‘Relations Chart’ si creerà automaticamente un diagramma illustrativo (Figura 157).

![](media/5efa96fd48d9924a09db48dbccdcb688.png)

Figura 157 – Creazione automatica del Relation Chart

Infine, cliccare il pulsante salva per confermare la creazione della relazione SKU, al termine si torna nella pagina contenente la lista di relazioni SKU dove potremo trovare all’ interno della lista la nuova relazione.

##### Utilizzo della tabella di Catalogo

###### Visualizzazione riepilogo Risorsa

Per visualizzare i dati di una risorsa SKU, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul record di interesse, apparirà una checkbox che riporta piccole informazioni della risorsa individuata: Sistema, Nome, Taglia , Data aggiornamento , nome e servizio come presente nell’immagine seguente (Figura 158).

![](media/e757da8e61d74a7e4f04a2cd550fd5f6.png)

Figura 158 – Dettaglio rapido delle risorse SKU

###### Visualizzazione delle relazioni di Catalogo

Per visualizzare i dati di una risorsa SKU , nella lista delle risorse, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Show” (Figura 159).

![](media/73111f05d83a4151f969cf7681f1de97.png)

Figura 159 - Accesso alla risorsa in modalità view

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina della risorsa in modalità view, nel quale potrà visualizzare i dati ma non potrà modificarli (Figura 160).

![](media/399db79b62926340b26c9686bcc933dc.png)

Figura 160 - Dettaglio completo delle risorse di catalogo

Il dettaglio di una risorsa è suddiviso in varie sezioni:

\- Details.

\- Properties (Figura 161).

\- Tags & Notes : ove nel campo “Provider Tags…” non è possibile selezionare un tag, in quanto si ottiene automaticamente dal sottosistema a cui appartiene; il campo “Add SCMP Tag…” permette di selezionare dei tag da un elenco o inserirne uno manualmente; nel campo Notes è possibile inserire una nota testuale (Figura 162).

\- Relations: ove presenti gli sku di provider in relazione (Figura 163).

\- Cost.

\- Relations Chart (Figura 164).

![](media/b11993866ae4a5affa2a3c3f1ee82ff1.png)

Figura 161 - Sezione proprietà degli elementi SKU di catalogo

![](media/7c6d44d12e981935eaf3c6c9c8bf57ee.png)

Figura 162 - Sezione Tags & Note degli elementi SKU di catalogo

![](media/c626787ca55a0bc29e3d248aa699c65c.png)

Figura 163 - Sezione delle relazioni degli SKU di catalogo

![A screenshot of a computer Description automatically generated](media/d898a5aa02a7313897bdf46d970327ed.png)

Figura 164 - Sezione Relations Chart delle risorse

In basso a destra, cliccare sul pulsante “Close”. L’utente verrà reindirizzato nella pagina contenente la lista delle risorse

###### Modifica delle relazioni di Catalogo

Per modificare una risorsa di SCMP, nella pagina “Resources” di Catalog, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Edit” (Figura 165).

![A screenshot of a computer Description automatically generated](media/6d806cf8de98bcae8000ac1eb2f83e23.png)

Figura 165 - Accesso alla risorsa in modalità edit

Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina della risorsa in modalità edit, a differenza della modalità ‘Show’ in quella ‘Edit’ è possibile modificare i parametri delle risorse

###### Eliminazione delle relazioni SKU di Catalogo

Per eliminare una risorsa SKU di catalogo, nella lista delle risorse, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Delete” (Figura 148). Fatto ciò, appare una modale in cui è necessario cliccare sul pulsante “Remove” per confermare l’eliminazione della risorsa (Figura 149).

![A screenshot of a computer Description automatically generated](media/8d6ab0635a1369f3ae980d9477e87061.png)

Figura 166 - Eliminazione di una risorsa SKU

![A screenshot of a computer Description automatically generated](media/0a73aeb3c818396c7694d3bc48668e59.png)

Figura 167 - Conferma eliminazione della risorsa

### Gestione elementi di catalogo ricevuti dai Provider

All’interno del Modulo Catalog è possibile visualizzare la lista ed i dettagli delle “size” disponibili sui vari provider configurati sulla SCMP sia per le singole risorse(VM,STORAGE,NETWORK) che per i gruppi di risorse “SKU”

#### Risorse

Per visualizzare la lista di risorse disponibili per un provider, selezionare in alto il menu “Cloud resources”(in rosso nell’ immagine) e selezionare uno dei provider disponibili (in giallo nell’ immagine), le funzionalità disponibili nelle pagine dei diversi provider sono identiche. (Figura 168)

![](media/f3c113865f71bc164bec39659d84da24.png)

Figura 168 - Risorse del catalogo dei providers

##### Export dei tagli del Provider

Per esportare l’elenco delle risorse del Catalogo visualizzate in pagina, in alto a destra cliccare sull'hamburger menu, e poi cliccare su “Export” (Figura 169).

L’operatore avrà la possibilità di esportare la lista dei risultati in formato .csv e/o .json.

![A screenshot of a computer Description automatically generated with medium confidence](media/0f08728084f0dfb4ae33686f610630a1.png)

Figura 169 – Esportazione dei risultati

##### Funzionalità Aggiornamento Forzato del Catalogo

È possibile forzare il sistema affinché dopo qualche minuto, vengano aggiornate automaticamente tutte le “size” e i relativi costi associati, per farlo, cliccare in alto a destra sull'hamburger menu, e poi cliccare su “Force Sync” (Figura 170).

![A screenshot of a computer Description automatically generated](media/d0c1b7fe744625c7d261c9876d9c593c.png)

Figura 170 - Funzionalità Force Sync

##### Filtri delle risorse

Viene data la possibilità all’ utente di filtrare le liste di risorse visualizzate, in alto nella pagina è presente una sezione filtri (Figura 171) , i filtri disponibili sono:

-   “search” : permette di cercare le risorse con un testo libero
-   “search by type” : permette di cercare le risorse di una sola tipologia specifica
-   “search by tags” permette di cercare tutte le risorse che contengono un tag specifico (Rif.5.10.2)

Dopo aver inserito uno o più filtri cliccare il pulsante “lente di ingrandimento” per effettuare la ricerca.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/05cae1cd51e39739eb9649ad138928dc.png)

Figura 171 - Filtri del Catalogo

##### Visualizzazione Riepilogo Risorsa

Per visualizzare l’anteprima di una risorsa in corrispondenza di una risorsa cliccare sul record di interesse, apparirà una modale che riporta le informazioni generali della risorsa individuata, tra cui : Sistema, Nome, Taglia , Data aggiornamento , RAM e CPU come presente nell’immagine seguente (Figura 172).

![A screenshot of a computer Description automatically generated](media/6a82ea1ca5f61697c33579bc36a24e09.png)

Figura 172 – Dettaglio rapido delle risorse di catalogo

##### Visualizzazione dei dettagli delle Risorse

Per visualizzare i dati di una risorsa, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Show” (Figura 173). Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina della risorsa in modalità view, nel quale potrà visualizzare i dati ma non potrà modificarli (Figura 174).

![A screenshot of a computer Description automatically generated](media/d37d66a7717934957d486eec6bf9d1d2.png)

Figura 173 - Accesso alla risorsa in modalità view

![A screenshot of a computer Description automatically generated with medium confidence](media/582d5a667e4d1dcedc86bbee29b54dc6.png)

Figura 174 - Dettaglio Risorsa dal Modulo Catalog

Il dettaglio di una risorsa è suddiviso in varie sezioni:

\- Details

\- Properties

\- Tags & Notes

\- Cost

Nella sezione Cost è possibile selezionare in successione la Regione, la Zona e la tipologia di Costo per ottenere una preview dei costi relativi alla risorsa selezionata (Figura 175).

![A screenshot of a video Description automatically generated with medium confidence](media/f55ebf6c003b2c570ef1d7fbf242aa3d.png)

Figura 175 - Sezione costi della risorsa

In basso a destra, cliccare sul pulsante “Close” per tornare alla lista.

#### SKU

Per visualizzare la lista degli sku disponibili per un provider, selezionare in alto il menu “Cloud SKU”(in rosso nell’ immagine) e selezionare uno dei provider disponibili (in giallo nell’ immagine), le funzionalità disponibili nelle pagine dei diversi provider sono identiche. (Figura 168)

![](media/a275758a87ef23957645b6e1198f2053.png)

Figura 176 - Risorse del catalogo dei providers

##### Export dei tagli del Provider

Per esportare l’elenco delle risorse del Catalogo visualizzate in pagina, in alto a destra cliccare sull'hamburger menu, e poi cliccare su “Export” (Figura 169).

L’operatore avrà la possibilità di esportare la lista dei risultati in formato .csv e/o .json.

![A screenshot of a computer Description automatically generated with medium confidence](media/0f08728084f0dfb4ae33686f610630a1.png)

Figura 177 – Esportazione dei risultati

##### Funzionalità Aggiornamento Forzato del Catalogo

È possibile forzare il sistema affinché dopo qualche minuto, vengano aggiornate automaticamente tutte le “size” e i relativi costi associati, per farlo, cliccare in alto a destra sull'hamburger menu, e poi cliccare su “Force Sync” (Figura 170).

![A screenshot of a computer Description automatically generated](media/d0c1b7fe744625c7d261c9876d9c593c.png)

Figura 178 - Funzionalità Force Sync

##### Filtri delle risorse

Viene data la possibilità all’ utente di filtrare le liste di risorse visualizzate, in alto nella pagina è presente una sezione filtri (Figura 179) , i filtri disponibili sono:

-   “search” : permette di cercare le risorse con un testo libero
-   “search by Service name” : permette di cercare le risorse relative ad una sola tipologia di servizio
-   “search by tags” permette di cercare tutte le risorse che contengono un tag specifico (Rif.5.10.2)

Dopo aver inserito uno o più filtri cliccare il pulsante “lente di ingrandimento” per effettuare la ricerca.

![](media/05990cf996653d6d796dae508ad57ff7.png)

Figura 179 - Filtri del Catalogo

##### Visualizzazione Riepilogo Risorsa

Per visualizzare l’anteprima di una risorsa in corrispondenza di una risorsa cliccare sul record di interesse, apparirà una modale che riporta le informazioni generali della risorsa individuata, tra cui : Sistema, Nome, Taglia , Data aggiornamento , nome del servizio (Figura 172).

![](media/b8aa148be381da56189f5de38786450c.png)

Figura 180 – Dettaglio rapido delle risorse di catalogo

##### Visualizzazione dei dettagli delle Risorse

Per visualizzare i dati di una risorsa, in corrispondenza di una risorsa cliccare sul kebab menu e poi cliccare su “Show” (Figura 173). Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina della risorsa in modalità view, nel quale potrà visualizzare i dati ma non potrà modificarli (Figura 174).

![A screenshot of a computer Description automatically generated](media/d37d66a7717934957d486eec6bf9d1d2.png)

Figura 181 - Accesso alla risorsa in modalità view

![](media/77f491547b400222385974a2b1386039.png).

Figura 182 - Dettaglio Risorsa dal Modulo Catalog

Il dettaglio di una risorsa è suddiviso in varie sezioni:

\- Details

\- Properties

\- Tags & Notes

\- Cost

Nella sezione Cost è possibile selezionare in successione la Regione, la Zona e la tipologia di Costo per ottenere una preview dei costi relativi alla risorsa selezionata (Figura 175).

![A screenshot of a video Description automatically generated with medium confidence](media/f55ebf6c003b2c570ef1d7fbf242aa3d.png)

Figura 183 - Sezione costi della risorsa

In basso a destra, cliccare sul pulsante “Close” per tornare alla lista.

### Gestione elementi “Servizi e Blueprint”

#### Servizi

Per accedere alla funzionalità dei “Services”, in alto a sinistra cliccare sul pulsante bento e poi cliccare su “Catalog” (Figura 184).

![A screen shot of a computer Description automatically generated with medium confidence](media/416284ac75341e4a7a30e1ad99e5b19a.png)

Figura 184 - Accesso ai "Services"

Dalla pagina “SCMP”, cliccare sul tab che raffigura tre quadrati uniti ‘Services’, posizionato sopra il path del breadcrumb. Fatto ciò, ci si ritrova all’ interno della pagina ‘Services’, viene visualizzata una lista di componenti denominati “Card”. ()

Ogni card fa riferimento ad un tipo di servizio specifico, essendo molti i servizi presenti il sistema ne esegue una paginazione, in basso possiamo utilizzare il campo “Item for page” per visualizzare più risultati oppure utilizzare le frecce per navigare tra le liste di servizi.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/125a25692eb4be48265398debb837048.png)

Figura 185 - Pagina dei servizi

##### Filtri della pagina “Services”

Per facilitare l’utente nella ricerca di un servizio specifico è stata inserita nella pagina una sezione filtri laterale(), all’ interno possiamo trovare tre filtri combinabili:

-   “Filter by Text”: inserendo un testo in questo campo la lista di servizi verrà aggiornata per mostrare i servizi che riportano nel titolo o nella descrizione il testo inserito.(di colore arancione nell’ immagine)
-   “Categories” : è possibile filtrare la lista per una o più categorie di servizi, la categoria viene inserita manualmente in fase di creazione del servizo (in verde nell’ immagine)
-   “Tags”: è possibile selezionare uno o più tag per visualizzare solo i servizi che sono stati configurati con il tag (in rosso nell’ immagine)

Utilizzando i filtri in combinazione tra loro, sarà possibile visualizzare i soli servizi che soddisfano tutte le condizioni specificate. In altre parole, la query restituirà solo i servizi che coincidono con tutti i criteri impostati.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/06c3aeacf4e9dbbd452bc51393958f32.png)

Figura 186 - Filtri disponibili

##### Creazione Services

Dalla pagina “Services”, è possibile per l’utente poter creare un Service, accedendo nell’apposita sezione come mostrato in figura (Figura 187).

![A screenshot of a computer Description automatically generated](media/517a65f30e81da94f2a2615620ae6a41.png)

Figura 187 - Accesso al form di creazione del Service

All’interno della pagina di creazione è necessario selezionare una tipologia di servizio utilizzando il campo "Service Type” per visualizzarne i parametri obbligatori (Figura 188)

![Immagine che contiene schermata, testo, Software multimediale, software Descrizione generata automaticamente](media/bac6619c13c43255557d61e571270526.png)

Figura 188 - Selezione della tipologia di servizio

Nei prossimi paragrafi analizzeremo nel dettaglio le singole tipologie di servizi.

###### Servizi “Standard”

La prima tipologia di servizi disponibile per la SCMP sono i servizi “Standard”, questi servizi sono nativamente integrati nel sistema e il loro funzionamento non può essere modificato dall’ utente.

Lista dei servizi offerti:

-   CosmosDb Cassanddra SQL
-   CosmosDb Core SQL
-   CosmosDb Mongo
-   Kafka 3.2.1 on Ubuntu 20.04 LTS
-   Kafka 3.2.1 on Ubuntu 22.04 LTS
-   Mongo DB 5.0 on Ubuntu 20.04 LTS
-   Mongo DB 6.0 on Ubuntu 20.04 LTS
-   Mongo DB 6.0 on Ubuntu 22.04 LTS
-   MySQL DB 8.0 on Ubuntu 20.04 LTS
-   MySQL DB 8.0 on Ubuntu 22.04 LTS
-   PostgreSQL 14 on Ubuntu 20.04 LTS
-   PostgreSQL 14 on Ubuntu 22.04 LTS
-   Redis DB 7.0 on Ubuntu 20.04 LTS
-   Redis DB 7.0 on Ubuntu 22.04 LTS

Per inserire un nuovo servizio è necessario compilare tutti i campi della sezione properties (Figura 189)

Nello specifico:

-   “Categories”: inserire un testo libero nel campo e selezionare dalla dropdown una categoria già configurata oppure è possibile aggiungere una nuova categoria cliccando il pulsante “+” nella dropdown (in arancione nella pagina)
-   “Name”: il nome del servizio che sarà visualizzato nella card corrispondente
-   “Description”: la descrizione del servizio che verrà mostrata nella card relativa
-   “Upload File”: cliccando questo controllo sarà possibile selezionare dal proprio PC un file di tipo “immagine” che verrà visualizzato nella card del servizio.
-   “Related Software”: in questa sezione è possibile selezionare uno o più software “Standard” che verranno poi utilizzati in fase di provisioning.

![](media/95766f48f6a9e32fe9a3b6d19f239e6c.png)

Figura 189 - Aggiunta nuova categoria

Una volta inseriti tutti i dati è possibile salvare il servizio utilizzando il pulsante “save” in basso a destra, verrà visualizzata una modale di conferma e l’utente viene reindirizzato nella lista dei servizi disponibili.

###### Servizi “Custom”

Viene data la possibilità all’ utente di definire dei servizi “Custom” tramite inserimento di un file zip con all’ interno tutti file necessari per l’esecuzione.

In questo caso specifico il sistema SCMP viene utilizzato solo per salvare il servizio e lanciarne l’esecuzione, non è quindi possibile effettuare un controllo sulla correttezza del processo, che dovrà essere gestito dall’ utente.

sono tutti orchestratori, ma con funzionalità e scopi differenti:

**1. Ansible:**

-   **Orchestrazione di server e applicazioni:** Ansible automatizza la configurazione e la gestione di server e applicazioni su diverse piattaforme.
-   **Esegue playbook YAML:** Ansible utilizza playbook YAML per definire le istruzioni da eseguire sui server.
-   **Non richiede agent:** Ansible è agentless, non richiede l'installazione di software sui server da gestire.

**2. Bicep:**

-   **Linguaggio DSL per Azure:** Bicep è un DSL specifico per Azure che facilita la definizione di infrastruttura come codice.
-   **Crea modelli ARM:** Bicep traduce i file in modelli ARM (Azure Resource Manager) che Azure utilizza per creare le risorse.
-   **Si integra con Azure DevOps:** Bicep si integra con Azure DevOps per la gestione del ciclo di vita.

**3. Kubernetes:**

-   **Orchestrazione di container:** Kubernetes è la piattaforma leader per l'orchestrazione di container su larga scala.
-   **Automatizza la distribuzione e la gestione:** Kubernetes automatizza la distribuzione, il ridimensionamento e la gestione di container in cluster.
-   **Offre un ecosistema di strumenti:** Kubernetes offre un ricco ecosistema di strumenti e librerie per la gestione dei container.

**4. Terraform:**

-   **Infrastructure as Code:** Terraform è un tool open source per la gestione dell'infrastruttura come codice.
-   **Definisce l'infrastruttura in file HCL:** Terraform utilizza file di configurazione HCL per definire l'infrastruttura desiderata.
-   **Supporta diversi provider:** Terraform supporta un'ampia gamma di provider cloud e on-premise.

**In sintesi:**

-   **Ansible:** Ideale per automatizzare la configurazione di server e applicazioni.
-   **Bicep:** Ottimo per definire l'infrastruttura su Azure in modo leggibile.
-   **Kubernetes:** Potente strumento per l'orchestrazione di container su larga scala.
-   **Terraform:** Flessibile per gestire l'infrastruttura su più cloud provider o on-premise

Nella configurazione dei servizi “Custom” possiamo individuare una sezione comune composta dai parametri iniziali (Figura 190) :

-   “Categories”: inserire un testo libero nel campo e selezionare dalla dropdown una categoria già configurata oppure è possibile aggiungere una nuova categoria cliccando il pulsante “+” nella dropdown
-   “Name”: il nome del servizio che sarà visualizzato nella card corrispondente
-   “Description”: la descrizione del servizio che verrà mostrata nella card relativa

![](media/49568a8f3413b6d1fff1cfd06ac05e2d.png)

Figura 190 Parametri generali dei "Custom Services"

Successivamente è necessario scegliere la tipologia di “orchestratore” da utilizzare (Figura 191) e inserire il file “.zip” corrispondente nella sezione “Upload File”, di seguito vengono indicate le specifiche per ogni tipologia:

| **Tipologia script** | **Contenuto obbligatorio del file .zip** |
|----------------------|------------------------------------------|
| Ansible              | Instance.yaml - Vars.yaml                |
| Bicep                | Main.bicep - Main.parameters.json        |
| Kubernetes           | Solo files di tipo .YAML                 |
| Terraform            | Main.tf - Variable.tf - Provider.tf      |

Oltre ai files descritti nella tabella è possibile aggiungere nello zip un file di tipo “.png / .jpg / .img” che verrà poi utilizzato come immagine della Card corrispondente

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/491f924d75d0b7e14dcd5c27d084064f.png)

Figura 191 - Selezione della tipologia di Orchestratore

Una volta inseriti tutti i dati è possibile salvare il servizio utilizzando il pulsante “save” in basso a destra, verrà visualizzata una modale di conferma e l’utente viene reindirizzato nella lista dei servizi disponibili

###### Servizi “azure pipeline”

Viene data la possibilità all’ utente di definire dei servizi “Azure Pipeline” Questa tipologia di servizio permette alla SCMP di invocare l’esecuzione di una pipeline remota DEVOPS e successivamente potrà esssere richiamata dalla funzionalità di “Provisioning”.

Nella configurazione dei servizi “Azure Pipeline” possiamo individuare una sezione generale composta dai parametri (Figura 192) :

-   “Categories”: inserire un testo libero nel campo e selezionare dalla dropdown una categoria già configurata oppure è possibile aggiungere una nuova categoria cliccando il pulsante “+” nella dropdown
-   “Name”: il nome del servizio che sarà visualizzato nella card corrispondente
-   “Description”: la descrizione del servizio che verrà mostrata nella card relativa

![](media/31bf5e5b0ffae2f670be052c73afce60.png)

Figura 192 Parametri generali "Azure pipeline service"

Anche per questo servizio sarà possibile, tramite il campo “upload File” , inserire un file di tipo “.zip” che contenga nello zip un file di tipo “.png / .jpg / .img” che verrà poi utilizzato come immagine della Card corrispondente.

Successivamente sarà necessario compilare i parametri specifici del servizio(Figura 193), in particolare bisognera inserire:

-   “Organizzazione” : il nome dell’ organizzazione DevOps dove risiede la pipeline
-   “Project”: il nome del progetto DevOps dove risiede la pipeline
-   “PAT”: il personal access token privato generato dal portale “Azure DevOps” (rif a come si fa?)

Una volta compilati questi campi è possibile cliccare il pulsante “Test” per verificare i parametri inseriti.(Figura 193)

Se i dati inseriti non sono validi verranno visualizzati diversi messaggi di errore che indicano quale parametro è errato (ad esempio: “Specified Organization is not valid.”) e il pulsante diventa rosso con scritto “KO”, quando tutti i parametri sono corretti il pulsante diventa di colore Verde con scritto “OK”.

![](media/3564c2cd9f6a11fd366a989edf256827.png)

Figura 193 - Parametri specifici delle Pipeline

Dopo aver effettuato il test correttamente sarà possibile selezionare la pipeline da eseguire utilizzando il campo “Select Pipeline” e cliccando su una opzione disponibile(Figura 194)

![Immagine che contiene testo, software, Software multimediale, Icona del computer Descrizione generata automaticamente](media/e3065a58fc1b05a3095f7d28850d33d8.png)

Figura 194 - Selezione della pipeline

Una volta inseriti tutti i dati è possibile salvare il servizio utilizzando il pulsante “save” in basso a destra, verrà visualizzata una modale di conferma e l’utente viene reindirizzato nella lista dei servizi disponibili

###### Servizi “PaaS”

Possiamo configurare all’ interno della SCMP anche dei servizi di tipo “PaaS”, per la configurazione di questi servizi è necessario inserire questi parametri (Figura 195) :

-   “Categories”: inserire un testo libero nel campo e selezionare dalla dropdown una categoria già configurata oppure è possibile aggiungere una nuova categoria cliccando il pulsante “+” nella dropdown
-   “Name”: il nome del servizio che sarà visualizzato nella card corrispondente
-   “Description”: la descrizione del servizio che verrà mostrata nella card relativa
-   “Company” : il nome della società che ha rilasciato il servizio
-   “Publisher”: il nome del pubblicatore del servizio

![](media/8f51d1fd5b68a79bbde38ef84ae45b3a.png)

Figura 195 Parametri generali dei "PaaS Services"

Successivamente è necessario inserire un file “.zip” che contenga solo file di tipo “.json” e un file di tipo “.png / .jpg / .img” che verrà poi utilizzato come immagine della Card corrispondente

Una volta inseriti tutti i dati è possibile salvare il servizio utilizzando il pulsante “save” in basso a destra, verrà visualizzata una modale di conferma e l’utente viene reindirizzato nella lista dei servizi disponibili

###### Servizi “AI”

Infine, è possibile configurare all’ interno della CMP, dei servizi di tipo “AI Services”, per farlo è necessario compilare i seguenti campi (Figura 196) :

-   “Categories”: inserire un testo libero nel campo e selezionare dalla dropdown una categoria già configurata oppure è possibile aggiungere una nuova categoria cliccando il pulsante “+” nella dropdown
-   “Name”: il nome del servizio che sarà visualizzato nella card corrispondente
-   “Description”: la descrizione del servizio che verrà mostrata nella card relativa
-   “Algorithm”: nome dell’ algoritmo utilizzato dalla AI
-   “Company” : il nome della società che ha rilasciato il servizio
-   “Publisher”: il nome del pubblicatore del servizio
-   “Platform”: piattaforma sulla quale è stata rilasciata l’ api
-   “Machine Learning Task”:
-   “Swagger”: inserire il link allo swagger che contiene tutte le API del servizio
-   “resource Link”: il link diretto alla risorsa

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/56bc36fa3a8091b32fc960491a6e7d58.png)

Figura 196 - Parametri dei "Servizi AI"

Se necessario è possibile inserire una sezione di informazioni relative alle propietà del docker che ospita l’ AI, per sbloccare il pannello è necessario cliccare sulla sezione “Click here to add” , a questo punto la pagina si aggiorna per mostrare i parametri(Figura 197)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/c01ce83366f686f472cc8cf06ca4d667.png)

Figura 197 - Sblocco della sezione "Docker"

All’ interno di questa sezione inserire tutti i parametri visualizzati (Figura 198) e salvare il servizio utilizzando il pulsante “save” in basso a destra, verrà visualizzata una modale di conferma e l’utente viene reindirizzato nella lista dei servizi disponibili

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/baa2f99d9c89f7bb2c6720887bc53df0.png)

Figura 198 - Parametri della sezione docker

##### Modifica ed Eliminazione Services

Oltre alla creazione di un Service, è possibile effettuare la visualizzazione, modifica ed eliminazione del suddetto (Figura 199).

-   Per modificare le informazioni di un “Service”, cliccare sul pulsante “Edit” all’interno della card. Dopodiché, all’interno del form, l’utente può modificare i dati necessari. Dopo aver effettuato le operazioni di edit, in basso a destra, cliccare sul pulsante “Submit”. Dopo aver fatto ciò, l’utente si ritrova all’interno della pagina “Service”. (Figura 200)
-   Per eliminare un “Service”, cliccare sul kebab menu di un suddetto e poi cliccare su “Delete”. Fatto ciò, appare una modale di conferma di eliminazione del Service. A questo punto, è necessario cliccare sul pulsante “Remove”. (Figura 201)

![A screenshot of a computer Description automatically generated](media/54d063fea2f22ed0bfc473b8826b894f.png)

Figura 199 - Operazioni disponibili per i Services

![Immagine che contiene software, Software multimediale, testo, computer Descrizione generata automaticamente](media/57e20d79ec53db0f3172b012e7a07191.png)

Figura 200 – Pagina di edit per un servizio

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/2b884d7f033fd4e258b1a44c9428773f.png)

Figura 201 - Eliminazione di un servizio

#### Gestione Blueprints

Per accedere alla funzionalità dei “Services”, in alto a sinistra cliccare sul pulsante bento e poi cliccare su “Catalog” (Figura 202).

![A screen shot of a computer Description automatically generated with medium confidence](media/416284ac75341e4a7a30e1ad99e5b19a.png)

Figura 202 - Accesso alle "Blueprint"

Dalla pagina “SCMP”, cliccare sul tab che raffigura tre quadrati uniti ‘Blueprint’, posizionato sopra il path del breadcrumb. Fatto ciò, ci si ritrova all’ interno della pagina ‘Blueprint’, viene visualizzata la lista delle blueprint configurate nel sistema. (Figura 203)

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/0012d48a27589d84f7d86126c996da92.png)

Figura 203 - Pagina delle Blueprint

##### Aggiunta nuova blueprint

Dalla pagina “Blueprint”, è possibile per l’utente poter creare una nuova blueprint, accedendo nell’apposita sezione come mostrato in figura (Figura 204), cliccando l’ “hamburgher menu” presente in alto a destra e selezionando come opzione “Add Blueprint”

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/acc97cacc43f1405c401891f26273e3f.png)

Figura 204 - Aggiunta nuova Blueprint

L’utente viene reindirizzato nello step 1 della creazione di una “Blueprint” dove è possibile inserire tutte le informazioni generali della blueprint.(Figura 205). Dopo aver inserito i dati cliccare il pulsante “Save blueprint” per salvare la bozza della blueprint , per i dettagli sullo status è possibile consultare il paragrafo successivo (5.9.3.2.2)

![Immagine che contiene testo, software, Software multimediale, Sistema operativo Descrizione generata automaticamente](media/18285115bfa2c9b466b6edb18db79fe0.png)

Figura 205 - Blueprint step 1

Viene aperta una modale di conferma inserimento, (Figura 206) una volta cliccato “yes” per continuare l’utente visualizzerà lo stato 2 della creazione di una blueprint.

Cliccando “No” verrà annullato l’inserimento della bozza.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/62b337dbc1cf2d3da4c7ff87ea575590.png)

Figura 206 - Blueprint conferma della bozza

Nello step 2 della creazione di una Blueprint è necessario cliccare all’ interno del campo “Upload File” e utilizzando la finestra di upload windows selezionare il file “.CSAR” che contiene la Blueprint. (Figura 207)

Dopo aver selezionato una file cliccare sul pulsante ”Upload” in basso a destra per lanciare il processo di validazione del file, seguendo la lista di stati presente nel paragrafo (5.9.3.2.2)

(ESTRATTO DI COME SI CREA UNA BLUEPRINT?)

![](media/d7ce1ae54b71e0afbabfb09f0b2c18f7.png)

Figura 207 - Inserimento file

##### Status delle Blueprint

Essendo le “Blueprint” degli oggetti complessi, che devono essere opportunamente configurati, è stato inserito un sistema di validazione dei files inviati per permettere l’utilizzo dei soli servizi “Blueprint” configurati correttamente. (Figura 208)

Nello specifico esistono 4 possibili “STATUS”:

1.  READY TO USE (spunta di colore verde): indica che la blueprint è configurata correttamente e sarà possibile utilizzarla durante il “Provisioning”
2.  VERIFY (cerchio di colore giallo) indica che la SCMP sta validando il contenuto della Blueprint
3.  FAILED (“X” di colore rosso): indica che il file inviato non è valido e dovrà essere reinserito dall’utente dopo averlo corretto.
4.  DRAFT (di colore arancione) indica che la “blueprint” è stata creata come bozza ma non contiene all’ interno il file CSAR necessario, una volta inserito il file la blueprint passerà allo status VERIFY

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/769b90bf6a8613ddfc82e7f749d4bf9f.png)

Figura 208 - Status delle Blueprint

##### Visualizzazione, Modifica ed Eliminazione delle Blueprint

Nella tabella delle blueprint disponibili in corrispondenza di ogni riga, sulla destra è presente un menu contestuale, una volta aperto all’ interno troviamo tre funzionalità:

la funzionalità “View”: permette di visualizzare i dettagli della blueprint, una volta cliccato l’utente verrà reindirizzato nella pagina di visualizzazione della blueprint (Figura 209) che contiene le sezioni :

-   Properties: in questa sezione sono disponibili le informazioni base della blueprint (Figura 209)
-   Provisioning plan: in questa sezione è presente il grafico BPNM che ci fornisce una rappresentazione grafica degli “step” previsti dalla “Blueprint” (Figura 210) utilizzando il pulsante in alto a sinistra “Download” è possibile scaricare il file BPNM visualizzato.
-   Topology : La topologia di una blueprint è la disposizione dei componenti in un cluster Kubernetes. ,in questa sezione possiamo visualizzare graficamente la struttura del sistema tra i diversi pod, servizi e componenti. (Figura 211)

![](media/2cd8b8ece237170fdcf2203feb01e546.png)

Figura 209 - Sezioni della pagina Blueprint "view"

![Immagine che contiene schermata, schermo, software, Software multimediale Descrizione generata automaticamente](media/9e6ead0ca2fe33986be686ef3da3e089.png)

Figura 210 - Sezione Plan di una Blueprint

![Immagine che contiene schermata, Rettangolo, testo, design Descrizione generata automaticamente](media/96dba844f5003852845b770ebd210d4d.png)

Figura 211 -Sezione Topology di una Blueprint

La funzionalità “Edit”: permette di modificare tutti i parametri della blueprint, compreso il file CSAR relativo(Figura 212),contiene le seguenti sezioni :

-   Properties: in questa sezione è possibile modificare le informazioni base della blueprint (Figura 212)
-   Provisioning plan: in questa sezione è presente il grafico BPNM che ci fornisce una rappresentazione grafica degli “step” previsti dalla “Blueprint” (Figura 213) in questa sezione sono presenti tre pulsanti per modificare il plan, il primo a forma di “cartella” permette l’upload sulla pagina di edit di un nuovo file BPMN , il secondo “download” permette di scaricare l’attuale file BPNM visualizzato , il terzo sulla destra “Upload” effettua la sovrascrizione dell’ attuale file BPNM disponibile per la blueprint
-   Topology : La topologia di una blueprint è la disposizione dei componenti in un cluster Kubernetes. ,in questa sezione possiamo visualizzare graficamente la struttura del sistema tra i diversi pod, servizi e componenti. (Figura 214)
-   Update Model: in questa sezione è possibile eseguire l’upload del file CSAR , effettuando questa modifica la Blueprint tornerà nello stato di “VERIFY” per validarne il contenuto (Figura 215)

![](media/b5c377bdd74483b848a7dddbbf52718a.png)

Figura 212 - Sezioni della pagina Blueprint "edit"

![](media/b44a261231c5229b362b982064190798.png)

Figura 213 - Sezione Plan di una Blueprint

![Immagine che contiene schermata, Rettangolo, testo, design Descrizione generata automaticamente](media/96dba844f5003852845b770ebd210d4d.png)

Figura 214 -Sezione Topology di una Blueprint

![Immagine che contiene testo, schermata, software, Carattere Descrizione generata automaticamente](media/ee40e83957fa816279ff4e97847c81fc.png)

Figura 215 - Sezione Model di una Blueprint

La funzionalità “Delete”: permette di eliminare definitivamentela blueprint dal sistema, per farlo basta confermare l’eleiminazione cliccando il tasto “Yes” visualizzato nella modale di conferma eliminazione(Figura 216)

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/8a88372f9491afe63e43385b2aebe866.png)

Figura 216 - Eliminazione di una Blueprint

### Gestione Openshift

Per configurare un modello che verrà utilizzato per calcolare i costi dei sistemi di Openshift, selezionare dal modulo Catalog il TAB ‘Openshift’ (Figura 217)

![A screenshot of a computer Description automatically generated](media/f16c740b7f10034c13b32859c004208e.png)

Figura 217 - Accesso a "Openshift"

Dopo aver fatto ciò, l’utente si ritroverà all’interno della pagina del tab “Openshift”.

Per settare il prezzo delle risorse Openshift che verrà usato sul modulo Cost selezionare una Valuta e lo Sconto o Maggiorazione che si vuole predisporre al modello, inserire nei riquadri ‘CPU Hourly Cost’, ‘RAM Hourly Cost’ e ‘Storage Hourly Cost’ i vari costi.

Fatto ciò, una volta cliccato sul tasto ‘Apply’ viene visualizzata una notifica di conferma della modifica e la data "Last Updated" in basso a sinistra viene aggiornata . (Figura 218).

![A screenshot of a computer Description automatically generated](media/f05b230cd3adf8d1a67305fd528c9b48.png)

Figura 218 - Configurazione Modello "Openshift"

Premendo il tasto "DELETE", apparirà un pop up che richiede la conferma dell’eliminazione del componente, una volta confermato quest’ultimo verrà eliminato dal sistema (Figura 219).

![A screenshot of a computer Description automatically generated](media/e4c456f98683d8aba46b701880924088.png)

Figura 219 - Eliminazione Modello "Openshift"

## Costs

La SCMP raccoglie, attraverso le API messe a disposizione dai provider, i dettagli dei costi degli asset di inventario.

Nella eventualità che i provider non espongano dati riguardo i costi, questi potranno essere inseriti editorialmente nel catalogo in modo che possano essere poi conteggiati all’interno di questa funzionalità.

I costi vengono raccolti con la suddivisione per costo giornaliero e per risorsa. Successivamente, come avviene per la parte delle metriche, i dati vengono normalizzati e aggregati per permettere una visualizzazione uniforme della dashboard.

Per accedere alla sezione costi, è necessario utilizzare il menu come da figura:

![A screenshot of a computer Description automatically generated with low confidence](media/d9a8c5fa00e02e81bbab5ca7fa2c222c.png)

Figura 220 - Accesso a Costs

A questo punto, l’utente si ritroverà all’interno della pagina del tab “Dashboard” dei costi (Figura 221).

All’interno del riquadro “Total costs”, è presente un grafico che mostra i costi giornalieri degli ultimi trenta giorni con granularità di un giorno.

![Immagine che contiene testo, elettronico, interni, screenshot Descrizione generata automaticamente](media/a4acba01f7df11e22476eb648bdffa95.png)

Figura 221 - Visualizzazione del grafico in base al range temporale e granularità dei costi

Sempre mantenendo come parametro gli ultimi trenta giorni di riferimento, selezionare dal menu a tendina “Granularity”, una granularità disponibile tra cui: “1 Day”, “1 Week” e “1 Month”. In questo modo, il grafico si aggiornerà in tempo reale per mostrare la granularità in base alla selezione.

È possibile per l’utente selezionare dal menu a tendina “Select Date” l’opzione “Last 90 days” e, dal menu a tendina “Granularity”, selezionare una delle granularità disponibili all’interno del suddetto menu per ottenere la granularità di riferimento negli ultimi novanta giorni.

È possibile filtrare per un determinato range di date. Nel menu a tendina cliccare su “Select Date” l’opzione “Last year” e dal menu a tendina “Granularity” selezionare una delle granularità disponibili all’interno del suddetto menu per ottenere la granularità di riferimento del precedente anno.

Infine, dal menu a tendina “Select Date”, selezionare l’opzione “Custom Date”. Fatto ciò, sarà possibile cliccare sul pulsante che raffigura un calendario all’interno del menu a tendina “Enter a date range” per selezionare un range di date dal calendario. Dopodiché, dal menu a tendina “Granularity”, sarà possibile selezionare una granularità disponibile in base al range di date selezionato.

Alla sinistra del grafico, è presente il costo totale delle risorse. È possibile filtrare i costi selezionando per “Provider” e “Subsystem”.

### Visualizzazione costi per risorse

Scorrendo verso il basso la pagina della dashboard dei costi, è presente la tabella di tutte le risorse (Figura 222).

Possiamo escludere dai risultati delle risorse non necessarie alla nostra ricerca, deselezionando il chekbox sulla riga corrispondente nella tabella in fondo alla pagina.

Nella barra “Filtering by:” apparirà il filtro di tutte le risorse ad eccezione di quelle in cui è stato rimosso il check dal checkbox. Cliccando sui tab “Virtual Machines”, “Storage” e “Virtual Network” posizionati nella barra laterali per filtrare i tipi di risorse in base alla categoria di appartenenza.

![Immagine che contiene testo, elettronico, computer, screenshot Descrizione generata automaticamente](media/aac86be4ab113366c727dbe85433ca4e.png)

Figura 222 - Tabella delle risorse

### Gestione dei TAG nella funzionalità di Cost Management

È possibile ricercare i costi delle risorse in base al TAG associato alle suddette. Cliccare sul menu a tendina “Filter by tags…” e dal menu a tendina, selezionare un TAG dal menu a tendina (Figura 223) (Rif. **Errore. L'origine riferimento non è stata trovata.**). Dopo aver fatto ciò, il grafico delle granularità varierà in base al TAG selezionato, e allo stesso modo varierà in costo totale delle risorse.

![A screenshot of a computer Description automatically generated](media/c3c602a9390b5402f595f15c00ce722c.png)

Figura 223 - Ricerca dei costi per TAG

### Forecast

Per ottenere la previsione dei costi giornalieri all’interno della sezione “Total costs”, nel grafico, cliccare su “Daily Forecast Costs”, e poi cliccare su “Daily Costs” per rimuovere il filtro. Apparirà un grafico giallo che indica la previsione dei costi giornalieri (Figura 224).

![A screenshot of a computer Description automatically generated with medium confidence](media/5f6eca81de55c142157e4a886e8d95f9.png)

Figura 224 - Previsione dei costi giornalieri

Per conoscere la previsione dei costi accumulati all’interno della sezione “Total costs”, cliccare su “Accumulated Forecast Costs”, e poi cliccare su “Daily Forecast Costs” per rimuovere il filtro. Apparirà un grafico rosso che indica la previsione dei costi accumulati (Figura 225).

![A screen shot of a graph Description automatically generated with medium confidence](media/7e8f634417a1f85b62a44ed3f640459e.png)

Figura 225 - Previsione dei costi accumulati

Le funzionalità di rappresentazione dei costi presentate nei paragrafi (5.10.1 5.10.2 5.10.3) vengono estese ai sotto moduli Virtual Machines, Storage, Virtual Network e Clusters.

Cliccando infatti sui singoli sotto moduli verranno presentate le stesse modalità di filtro e visualizzazione dei costi che mostreranno i dati associati, non al complessivo delle risorse, ma di volta in volta solo alla tipologia specifica del sotto modulo scelto.

### Definizione di logiche di classificazione

Sotto il grafico dei costi sono presenti dei grafici a torta che permettono di visualizzare:

-   i diversi provider che generano costi;
-   i diversi sottosistemi che generano costi;
-   le diverse regioni;
-   i diversi gruppi di risorse.

È possibile cliccare su uno spicchio colorato del grafico a torta per raggruppare le risorse per tipologia, provider e provenienza. A questo punto, la tabella visualizzerà solo le risorse in base allo spicchio selezionato nei vari grafici a torta. Inoltre, appena sopra la tabella apparirà il tag che rappresenta il tipo di filtro applicato. All’interno del suddetto, è presente il simbolo “X” che permette di resettare il grafico e la tabella (Figura 226). Per i tab “Virtual Machines”, “Data Stores”, “Networks”, “Kubernetes”, “Security” e “Others” è possibile aggregare le risorse solo per tipologia di appartenenza.

![A screenshot of a computer Description automatically generated](media/e2b26bfe36a8d844ee4cc219c1315a25.png)

Figura 226 - Aggregazione delle risorse per tipologia, provider e regione

### Usages

Il sotto modulo Usage permette di fare un riepilogo dei costi di utilizzazione legati alle risorse di un determinato sottosistema.

Al momento tale funzionalità è attiva solo sul provider Google.

![A screenshot of a computer Description automatically generated](media/41488ad640f8c5c577f84014fe3a8e2a.png)

Figura 227 – Filtri modulo Usages

Il filtro di default presenterà i dati relativi agli ultimi 30 giorni con granularità di 1 giorno associati a tutti i sottosistemi.

Sulla base del filtro selezionato verranno presentati i seguenti dati aggregati.

Grafico dei costi relativi a:

-   provider selezionato;
-   sottosistema selezionato;
-   dettaglio costi generati dai singoli SKU (funzionalità o servizi utilizzati dalle risorse selezionate);
-   dettaglio costi generati dalle singole risorse selezionate

![A screenshot of a computer Description automatically generated](media/ede615d5d2178e16717a5987068a4f45.png)

Figura 228 – Grafici costi su base Provider e Sottosistema

![A screenshot of a computer Description automatically generated with low confidence](media/c42b947447a897bb8c452d61d32a71a7.png)

Figura 229 – Grafici costi su base SKU

![A screenshot of a computer Description automatically generated with medium confidence](media/9c13321b17e5e1203d12a62a24c6c643.png)

Figura 230 – Dettaglio costi su SKU

![A screen shot of a computer Description automatically generated with medium confidence](media/9d2a5e30abe31cd65009ad5208eae162.png)

Figura 231 – Dettaglio costi per risorsa

### Report dei costi

Nella barra in alto, cliccare sul tab “Reports” (Figura 232). L’utente si ritrova all’interno del tab “Report Types” in cui sono presenti quattro report:

-   “Costs Summary” (si ottengono i costi di ciascuna risorsa);
-   “Costs Summary – Group By Resource” (si ottengono i costi raggruppati per tipo di risorsa);
-   “Costs Details” (si ottengono i costi per ogni risorsa, per location, resource group e data di riferimento);
-   “Costs Details – Group By Resource” (si ottengono i costi raggruppati per tipo di risorsa e per giorno).

In corrispondenza del tipo di report “Costs Summary”, è possibile cliccare sul pulsante “RUN NOW” per avviare la modale in cui inserire i filtri per la creazione del report (Figura 232).

![A screenshot of a computer Description automatically generated](media/1783c6382a74f3e6ad88a7945b456b9d.png)

Figura 232 - Accesso ai report Costs

![Immagine che contiene testo, monitor, screenshot, nero Descrizione generata automaticamente](media/8f8337fb7dbe124efd7d840a14ac2dc1.png)

Figura 233 - Tipi di report Costs

Una volta che si sarà aperta la modale dei filtri, è possibile compilare alcuni o tutti i parametri. Una volta compilati i parametri desiderati, in basso a destra della modale, cliccare sul pulsante “Submit.

Fatto ciò, l’utente si ritrova all’interno del tab “Results” in cui è presente lo storico di tutti i report (Figura 235).

In basso a destra della pagina, è possibile selezionare il numero di elementi da visualizzare per pagina. Le frecce racchiuse all’interno del rettangolo consentono all’utente di visualizzare gli elementi delle pagine successive e precedenti. Invece, le frecce al di fuori del rettangolo consentono di spostarsi nell’ultima e nella prima pagina (Figura 236).

![Immagine che contiene testo, monitor, screenshot, schermo Descrizione generata automaticamente](media/46ff29feef0aef3c006d1264639a1b48.png)

Figura 234 - Applicazione dei filtri report

![Immagine che contiene testo, computer, elettronico, portatile Descrizione generata automaticamente](media/2e3f7255f3a2c054856fc55875c1317f.png)

Figura 235 - Storico dei report

![Immagine che contiene testo, elettronico, computer, portatile Descrizione generata automaticamente](media/0fb05ed7a1578c9f6d6cc843275e15e8.png)

Figura 236 - Gestione delle pagine report

![A screenshot of a computer Description automatically generated](media/a7d9888e28719ad6ea6c6c771c899520.png)

Figura 237 - Sommario report

Per visualizzare i dettagli del report generato, cliccare sul report che sta in coda come indicato dalla freccia.

A questo punto, l’utente si ritrova all’interno del sommario del report (Figura 236). All’interno del sommario del report dell’Inventory è presente la sezione “Stats” in cui sono presenti il numero dei dischi, delle interfacce, delle reti e delle virtual machines appartenenti al provider selezionato.

Sotto la sezione “Stats”, sono presenti i filtri usati dall’utente per generare il report. Sotto i filtri, è presente la tabella riassuntiva delle risorse appartenenti al provider. A destra sono presenti due pulsanti: “PRINT” ed “EXPORT”.

Cliccando sul pulsante “PRINT”, appare una modale di anteprima della stampa. Per stampare il report, cliccare sul pulsante in basso a destra “Stampa”, a questo punto si avvierà la stampa del suddetto.

Cliccando sul pulsante “EXPORT”, è possibile esportare il report in formato “.csv”, “. json” o “.pdf”.

Per tornare al tab “Results”, in basso a destra, cliccare sul pulsante “CLOSE” oppure in alto a sinistra cliccare sulla freccia che punta verso la sinistra, accanto al titolo del report.

## Monitoring

La SCMP raccoglie le metriche su tutti i cloud provider e le aggrega per macrocategorie.

Questa aggregazione (modificabile editorialmente) permette il confronto tra metriche su provider diversi.

Accedendo alla dashboard, possiamo vedere come questo meccanismo di aggregazione, permetta di avere una panoramica sull’utilizzo delle risorse suddivise per provider e organizzate per tipo di risorsa associata.

Visualizzando il dettaglio delle singole metriche invece, questo meccanismo, ci permette di confrontare metriche cross provider.

Utilizzando i menu in alto sopra il breadcrumb, è possibile accedere al dettaglio delle metriche per tipologia di asset. Qui si potranno confrontare asset su provider diversi, visualizzare le metriche fino a due anni, modificare la granularità dei dati ed esportare i risultati in vari formati.

Si può accedere al modulo di monitoring tramite l’apposito menu. Come mostrato in figura:

![](media/82d6a9625c244ed8c9894729f7730d41.png)

Figura 238 - Accesso al Modulo di Monitoring

La dashbord si presenta con un overview di tutti i provider associati, mostrando metriche per vm, dischi, network e cluster k8s. Come mostrato in figura:

![](media/157cdf31bb494b7bd3c9b4c7c7d51d6a.png)

![Immagine che contiene testo, monitor, interni, schermo Descrizione generata automaticamente](media/4b27facaae39dd1cf699cab0d889a19d.png)

Figura 239 - Dashboard di Monitoring

L’utente si ritroverà all’interno della pagina del tab “Dashboard” di Monitoring in cui sono presenti le seguenti sezioni: “VM”, “Storage”, “Network”, “Clusters”, “Pods” e “Reports”. In ciascuna sezione sono presenti dei grafici di andamento delle metriche in funzione del tempo (time-series singola) con percentuale di utilizzo di una determinata metrica rispetto ad un tipo di servizio **(**Figura *240* - Grafico delle metriche**)**.

### Metriche delle risorse “VM” “Storage” “Network”

Cliccare sul tab “Virtual Machines” per accedere all’interno della dashboard delle metriche delle “VM” **(**Figura *240***)**.

![A screenshot of a computer Description automatically generated](media/b778ce891e243e9f32303aa5a663074b.png)

Figura 240 - Grafico delle metriche

Per ottenere il grafico delle metriche (Figura 241) cliccare sul menu a tendina “Provider”. All’interno del menu, è possibile cliccare su uno o più checkbox per selezionare più provider, è anche possibile selezionarli tutti cliccando sul checkbox “Select all”.

Successivamente, cliccare sul menu a tendina “Subsystem”. All’interno del menu, è possibile cliccare su uno o più checkbox per selezionare più sottosistemi, è anche possibile selezionarli tutti cliccando sul checkbox “Select all”.

Successivamente, cliccare sul menu a tendina “Metric Name”. All’interno del menu, è possibile cliccare solo su un tipo di metrica.

Il pulsante che raffigura un calendario all’interno del menu a tendina “Date range” permette la selezione del range delle date.

Sopra il menu a tendina di “Date range”, è presente il menu a tendina “Granularity” in cui sono disponibili le seguenti granularità:

-   1 Minute
-   5 Minutes
-   15 Minutes
-   30 Minutes
-   1 Hour
-   6 Hours
-   1 Day
-   1 Week

In base al range di date selezionato, si otterrà una determinata granularità:

-   La granularità a 1 minuto non sarà disponibile se il range di date \> di 24 ore;
-   La granularità a 5 minuti non sarà disponibile se il range di date \> di 7 giorni;
-   La granularità a 30 minuti non sarà disponibile se il range di date \> di 30 giorni;
-   La granularità a 1 ora non sarà disponibile se il range di date \> di 6 mesi.

Le metriche possono essere ricercate in base ai TAG associate alle risorse (Rif. **Errore. L'origine riferimento non è stata trovata.**).

Cliccare sul campo “Search tags...” e cliccare sul menu a tendina su un TAG, oppure compilarne uno manualmente. Si possono inserire uno o più TAG.

È possibile selezionare dal menu a tendina di “Granularity” altre granularità, ma come spiegato prima, tutto dipenderà dal range di date selezionato. Inoltre, è possibile recuperare un grafico delle metriche fino a due anni.

![A screen shot of a computer Description automatically generated with low confidence](media/f8d0426d74ab4ce67953f27070062007.png)

Figura 241 - Ricerca delle metriche

### Ricerca per tag nel modulo di Monitoring

![A screen shot of a computer Description automatically generated with low confidence](media/f8d0426d74ab4ce67953f27070062007.png)

Figura 242 - Ricerca delle metriche per TAG

Le metriche possono essere ricercate in base ai TAG associate alle risorse (Rif. **Errore. L'origine riferimento non è stata trovata.**).

Cliccare sul campo “Search tags...” e cliccare nel menu a tendina su un TAG, oppure compilarne uno manualmente **(**Figura 242**)**. Si possono inserire uno o più TAG.

È possibile filtrare, inoltre, per provider. Selezionare il menu a tendina “Subsystem”, all’interno del menu, è possibile cliccare su uno o più checkbox per selezionare più sottosistemi, è anche possibile selezionarli tutti cliccando sul checkbox “Select all”.

Fatto ciò, cliccare sul menu a tendina “Resource”. All’interno del menu, è possibile cliccare su uno o più checkbox per selezionare più risorse, è anche possibile selezionarli tutti cliccando sul checkbox “Select all (max. 10)” limitandosi però ad una selezione di massimo dieci risorse.

Il menu “Metric Name” è a singola selezione. Questo per evitare di confrontare metriche diverse.

Per ottenere le metriche degli “Storage”, “Network”, “Clusters” o “Pods” cliccare nei rispettivi tab posizionati nella barra superiore e ripetere gli step descritti precedentemente.

### Shortcut dal Clusters alle metriche delle VM che lo compongono

Accedendo al sottomenu Clusters è possibile spostarsi dal grafico delle metriche del cluster direttamente alle metriche delle risorse che compongono il cluster mediante la seguente procedura:

-   Accedere al sottomodulo Clusters;
-   Selezionare sul filtro:
-   Provider: OpenShift;
-   Sottosistema: uno tra quelli disponibili;
-   Risorsa: una tra quelle disponibili;
-   Metriche: una tra quelle disponibili che restituisca grafici con dati;
-   Passando il mouse sul grafico restituito verrà mostrata una finestra che riporta la risorsa del cluster di cui sono evidenziate le metriche misurate;
-   Su tale grafico cliccare sul puntino associato alla finestra.

![A screenshot of a computer Description automatically generated](media/b104e021640fc674ba2835e763ac592e.png)

Figura 243 - Grafico con shortcut a sottomodulo Virtual Machines

Verranno aperte le metriche delle risorse all’interno del sottomenu Virtual Machines (Figura *244*)

**![A screenshot of a computer Description automatically generated](media/d7a96fb3ae8cb6352818e87f3515102f.png)**

Figura 244 - Grafico delle metriche su Virtual Machines

### Reportistica Monitoring

È possibile esportare i risultati in formato csv, excel o pdf.

Per accedere alla funzionalità cliccare su Reports come da Figura 245.

![A screen shot of a computer Description automatically generated with medium confidence](media/71f999eb396eacf00efa8888565a3181.png)

Figura 245 - Accesso al report di Monitoring

L’utente si ritrova all’interno del tab “Report Types” in cui è necessario cliccare sul pulsante “RUN NOW” in corrispondenza di “Monitoring Summary” per avviare la modale in cui è possibile inserire i filtri per la creazione del report **(**Figura 246**)**.

![](media/e90f441d0e322c8eb691f0efcbb957f7.png)![A screenshot of a computer Description automatically generated](media/c89b6f371e5caff78b02d1a0822fb5ba.png)

Figura 246 - Esecuzione del report

Una volta che sarà aperta la modale dei filtri, è possibile compilare alcuni o tutti i parametri. Una volta compilati i parametri desiderati, in basso a destra della modale, cliccare sul pulsante “Submit” (Figura 247**)**.

![A screenshot of a computer Description automatically generated](media/5faa1d439844bf8dd845b3443c921a82.png)

Figura 247 - Applicazione dei filtri report

Fatto ciò, l’utente si ritrova all’interno del tab “Results” in cui è presente lo storico di tutti i report (Figura 248).

![A screenshot of a computer Description automatically generated](media/f5670dd507b2f8403367b051cef66e0a.png)

Figura 248 - Gestione dello storico dei report

Per visualizzare i dettagli del report generato, cliccare sul report come indicato dalla freccia. A questo punto, l’utente si ritrova all’interno del sommario del report (Figura 249).

All’interno del singolo report sono riportati i filtri usati dall’utente per generare il report stesso. Sotto i filtri, è presente la tabella riassuntiva delle risorse appartenenti al provider. A destra sono presenti due pulsanti: “PRINT” ed “EXPORT”. Cliccando sul pulsante “PRINT”, appare una modale di anteprima della stampa. Per stampare il report, cliccare sul pulsante in basso a destra “Stampa”, a questo punto si avvierà la stampa del suddetto.

Cliccando sul pulsante “EXPORT”, è possibile esportare il report in formato “.csv”, “. json” o “.pdf”.

Per tornare al tab “Results”, in basso a destra, cliccare sul pulsante “CLOSE” oppure in alto a sinistra cliccare sulla freccia che punta verso la sinistra, accanto al titolo del report.

![A screenshot of a computer Description automatically generated](media/46ca1cac110403b0bff7d7217c3797bc.png)

Figura 249 - Sommario del report

Nel tab “Results” in cui è presente lo storico di tutti i report, in basso a destra della pagina, è possibile selezionare il numero di elementi da visualizzare per pagina.

Le frecce racchiuse all’interno del rettangolo consentono all’utente di visualizzare gli elementi delle pagine successive e precedenti. Invece, le frecce al di fuori del rettangolo consentono di spostarsi nell’ultima e nella prima pagina (Figura 250).

![Immagine che contiene testo, elettronico, screenshot, computer Descrizione generata automaticamente](media/e3f0ef9979d7ed7aa819e64f21a6a4c4.png)

Figura 250 - Gestione pagine report

È possibile accedere al tab “Result” cliccando nel menù presente sulla pagina di scelta della tipologia di report (Figura 251)

![](media/6aa6f4f6aa9dca9db050d1a4ab9a2f25.png)

Figura 251 - Accesso ai report precendenti

## Security

La funzionalità della SCMP che riguarda la security mostra le vulnerabilità degli asset di inventario presenti sulla SCMP.

Per accedere alla funzionalità di “Security”, in alto a sinistra cliccare sul pulsante bento. Fatto ciò, apparirà la barra dei menu in cui è necessario cliccare su “Security” (Figura 252).

![](media/1a5f36251f1324a6125dc220b4f5fa98.png)

Figura 252 - Accesso a Security

### Dashboard generale

A questo punto, l’utente si ritrova all’interno della pagina del tab “Dashboard” (Figura 253) dove vengono mostrati in modalità aggregata, i dati della compliance delle risorse per tutti i provider configurati.

In alto è presente una barra dei filtri che permette di filtrare i risultati per sottosistema di appartenenza , status e/o nome della policy.(Figura 253).

Dopodiché, l’utente nota la presenza del grafico a barre che indica lo stato di compliance delle risorse suddiviso per sottosistema.

Passando il mouse su una sezione del grafico possiamo notare che i valori visualizzati in pagina vengono aggiornati per mostrare un anteprima del dettaglio.

È possibile cliccare su una sezione del grafico per applicare automaticamente i filtri “sottosistema” e “status” alla pagina.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/241862c2a4580ac51686e3dbad3ab903.png)

Figura 253 – Dashboard di Security

Scorrendo la pagina verso il basso, è presente la tabella delle policies (Figura 254) che verrà filtrata automaticamente in base ai filtri selezionati.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/6ba2bdee84151afd8b98e487d67f7a63.png)

Figura 254 - Tabella delle policies

Cliccando su una riga della tabella verrà aperta una finestra di dettaglio,(Figura 255) dove all’interno possiamo trovare tutte le informazioni relative alla policy selezionata, inoltre sarà disponibile la lista delle risorse interessate. È possibile cliccare sul nome di una macchina per visualizzarne i dettagli , in questo caso l’utente verrà reindirizzato all’ interno della risorsa di inventario SCMP in modalità “view”

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/2f505cae12c7d55984b1fd59c79def93.png)

Figura 255 - Dettaglio delle policy

Per uscire dal dettaglio bisogna cliccare all’ esterno della finestra che verrà chiusa automaticamente.

### Dashboard specifiche per tipologia di risorsa

Viene data la possibilità di filtrare ulteriormente le policy per tipologia di risorsa, utilizzando i tab presenti in alto nella pagina (Figura 256)

Una volta selezionata la tipologia di risorsa è possibile navigare nelle pagine seguendo le modalità descritte nel paragrafo precedente (5.12.1)

![](media/d78736dce1968d513278f7fc588b47a2.png)

Figura 256 - Dashboard delle compliance delle Virtual Machines

### Dashboard SIEM

Per visualizzare la dashboard del SIEM, cliccare sul tab che raffigura uno scudo. Nella parte superiore è presente un menu a tendina in cui è possibile selezionare la sottoscrizione di interesse, mentre accanto è presente il menu a tendina in cui è possibile selezionare un intervallo di tempo.

Sotto, è presente la sezione “Summary” in cui sono presenti delle informazioni, tra cui ad esempio “Alerts” che indica il numero degli avvisi. Sempre all’interno della sezione “Summary” è presente il grafico “”Incidents by status” che indicano gli incidenti per stato.

Sotto la sezione “Summary”, è presente la sezione “Hourly Events Grouped By Type” in cui è presente un grafico a istogrammi che indica gli eventi orari per tipo.

![](media/d6ce0500b7ac3299fe7b3d5a5b351e32.png)

Figura 257 - Dashboard SIEM

Scorrendo la dashboard del SIEM, è presente il grafico “Event types” che indica tutti i tipi di eventi (Figura 258).

![A screenshot of a computer Description automatically generated with medium confidence](media/97764625aa86ffaa06c5d596af555639.png)

Figura 258 - “Event types" della dashboard SIEM

Infine, nella parte inferiore della pagina, sono presenti due tabelle: a sinistra la tabella “Alert rules” in cui mostra un insieme di regole degli allarmi, mentre a destra è presente la tabella “Incidents” che mostra invece gli incidenti (Figura 259).

![Immagine che contiene testo, interni, screenshot Descrizione generata automaticamente](media/47a5b697b4b507bea266133b2db39d38.png)

Figura 259 - Tabelle "Alert rules" e "Incidents"

Cliccando su una riga della tabella verrà aperta una finestra di dettaglio,(Figura 260) dove all’interno possiamo trovare tutte le informazioni relative alla regola o incident selezionato”.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/46b20879489bd8691be65f5f9b4bed8c.png)

Figura 260 - Dettaglio degli "Incidents"

### Dashboard Secret Manager

Per visualizzare la dashboard del SIEM, cliccare sul tab che raffigura una chiave (Figura 261). Nella parte superiore è presente un menu a tendina in cui è possibile selezionare la sottoscrizione di interesse.

![A screenshot of a computer Description automatically generated with medium confidence](media/385e2684a6519080d4435c19bda94ea7.png)

Figura 261 - Dashboard di Key Vault

All’ interno della pagina in basso è possibile notare dei pulsanti per navigare la tabella e una tabella.

A seconda della pagina selezionata (Figura 262) la tabella mostrerà rispettivamente:

-   Secret
-   Keys
-   Certificates

![](media/26416675407c45d4ac76fb530089d26d.png)

Figura 262 - Risorse visualizzabili

Cliccando su una riga della tabella è possibile visualizzare il dettaglio della risorsa selezionata. (Figura 263)

![A screenshot of a computer Description automatically generated](media/fe26a37e0688f2b34c096aa1426e34b3.png)

Figura 263 - Dettaglio della chiave

### Dashboard Clusters

A questo punto, l’utente si ritrova all’interno della pagina del tab “Dashboard” (Figura 264) dove vengono mostrati in modalità aggregata, tutti gli alert generati dai sottosistemi configurati di tipo “Cluster” nella SCMP

In alto è presente una barra dei filtri che permette di filtrare i risultati per namespace , sottoscrizione e/o nome della policy.(Figura 264).

Dopodiché, l’utente nota la presenza del grafico a barre che indica il totale degli “alert” ricevuti suddiviso per sottosistema

Passando il mouse su una sezione del grafico possiamo notare che i valori visualizzati in pagina vengono aggiornati per mostrare un anteprima del dettaglio.

È possibile cliccare su una sezione del grafico per applicare automaticamente i filtro “sottosistema” .

![](media/622a45f8c988e20138210e01df8f24f9.png)

Figura 264 – Dashboard dei “Cluster alerts”

Scorrendo la pagina verso il basso, è presente la tabella degli “alert” (Figura 265) che verrà filtrata automaticamente in base ai filtri selezionati.

![](media/df024c8ddf23d82bb424eabcc2d686e2.png)

Figura 265 - Tabella degli alert

Cliccando su una riga della tabella verrà aperta una finestra di dettaglio,(Figura 266) dove all’interno possiamo trovare tutte le informazioni relative all’ “alert” selezionato.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/2f505cae12c7d55984b1fd59c79def93.png)

Figura 266 - Dettaglio degli Alert sui clusters

Per uscire dal dettaglio bisogna cliccare all’ esterno della finestra che verrà chiusa automaticamente

## Provisioning

Il provisioning è una delle funzionalità più importanti della SCMP,Attraverso questi moduli, è possibile allocare degli asset runtime all’interno dei provider gestiti dalla SCMP.

Per poter utilizzare questa funzionalità è necessario che all’ interno della cmp siano definite delle relazioni (5.9.1.1.3)

Questo vincolo è stato reso disponibile per blindare l’associazione di certe caratteristiche al provisioning, ad esempio, la size della VM non è selezionabile durante il provisioning ma rientra in quelle caratteristiche predefinite dagli amministratori, all’ interno del catalogo.

![A screenshot of a phone Description automatically generated with low confidence](media/0c4d397d20838c6aa5053757a6908d96.png)

Figura 267 - Accesso a "Provisioning"

### Dashboard

Accedendo alla funzionalità la prima pagina disponibile è la Dashboard dei provisioning effettuati all’interno del sistema.

La pagina si presenta con una serie di grafici, filtri e l’elenco dei provisioning effettuati.

I grafici permettono di visualizzare le informazioni presenti in tabella raggruppate per:

-   Il totale di tutti i provisioning effettuati suddivisi per tipologia;
-   Lo stato dei provisioning effettuati suddivisi per esito e categoria dell’ asset provisionato

![A screenshot of a computer Description automatically generated with medium confidence](media/5437dbd78388cbbc79de1a0ae11a79fd.png)

Figura 268 – Grafici della pagina di provisioning

In basso nella pagina possiamo utilizzare la sezione filtri per modificare i risultati presenti nella tabella, il filtro “Provisioning Type” (Figura 269)è il filtro principale che permette di selezionare la tipologia di asset da visualizzare, nello specifico:

-   Selezionando “Resources” viene aggiunto un filtro che permette di selezionare il tipo di risorsa di cui si vuole visualizzare lo stato dei provisioning di default, il sistema mostra la lista di VM provvisionate.
-   Selezionando “Services” e “Custom services” non ci sono filtri aggiuntivi e la lista viene aggiornata con i soli provisioning relativi ai Servizi
-   Selezionando “Blueprint” viene aggiunto un filtro che permette di cambiare il flusso (cioè la tipologia di blueprint da visualizzare) e la tabella viene modificata per visualizzare solo i flussi non ancora completati, sopra la tabella è presente un controllo che permette di cambiare tab, per passare dai flussi “in corso” ai flussi “Completati” (**Errore. L'origine riferimento non è stata trovata.**).

![](media/b8de8f9382ba91c7ea2bff280b36b9c0.png)

Figura 269 – Filtro per tipologia di asset

### Specifiche della tabella dei provisioning

#### “Resources”, “Services”, “Custom Services”

L’elenco ha i seguenti attributi, quando viene selezionato come filtro “Resources”, “Services”, “Custom Services” (Figura 270)

-   Uuid, Identificativo del provisioning;
-   Data di completamento del provisioning;
-   Data di richiesta del provisioning;
-   Utente che ha creato l’istanza;
-   Status;
-   Output dei sistemi di provisioning;
-   Json di dettaglio del provisioning effettuato;
-   Informazioni sullo stato;
-   Tipo di risorsa.

![A screenshot of a computer Description automatically generated](media/6692e0cbc6823ae4533db8487ae5c248.png)

Figura 270 - Tabella “Resources”

Quando siamo in questa visualizzazione è possibile effettuare le seguenti operazioni:

-   Cliccando sulla riga di un provisioning fallito è possibile modificarlo e rieseguirlo (0).
-   Cliccando sull’ icona “Output Message) in corrispondenza di un provisioning è possibile visualizzare la risposta ricevuta dal modulo di “Terraform” (Figura 271).
-   Cliccando il tasto “Download” è possibile scaricare i file restituiti dalla funzionalità.
-   Cliccando il tasto “State” è possibile visualizzare il grafico e la lista delle risorse provvisionate (Figura 272).

![A screenshot of a computer Description automatically generated](media/aa6eb00936490c947f1de33580efe9a8.png)

Figura 271 - Visualizzazione messaggio Terraform

![A screenshot of a computer Description automatically generated](media/d70872eaf86b537da88a843f60410954.png)

Figura 272 - Visualizzazione grafico risorse

#### Blueprint

L’elenco ha i seguenti attributi, quando viene selezionato come filtro “Blueprint” (Figura 273)

-   Nome della blueprint
-   Data di creazione
-   Utente che ha effettuato il provisioning della blueprint

    Sopra la tabella possiamo notare due tab, cliccando su di essi la tabella viene filtrata rispettivamente per Blueprint da completare e Blueprint completate (in rosso nell’ immagine)

![](media/a7bef9976cd977da7e21839d1e63f50d.png)

Figura 273 – Tab della tabella “Provisioning blueprint”

In questa visualizzazione è possibile cliccare su una riga della tabella per visualizzare i dettagli della blueprint.

Quando la blueprint selezionata è “da completare” verremo riportati nella pagina di provisioning blueprint (Figura 274) dove potremo effettuare le operazioni necessarie al completamento, per i dettagli consultare la sezione(5.13.3.3.2).

![](media/7d62ebd3dc251ba5ac1071cf9dccdf3b.png)

Figura 274 – Visualizzazione flow “Da completare”

Se viene selezionata invece una blueprint completata verremo riportati nella pagina di dettaglio del provisioing della blueprint dove non verra visualizzato il “flow” di previsione perché gia completato.

**![](media/232f82744678ed22764c107cd655cf29.png)**

Figura 275 – Visualizzazione flow “Completato”

### Creazione dei provisioning

#### Provisioning di “Risorse fisiche”

Utilizzando i tab presenti nella funzionalità di provisioning(Figura 276). è possibile visualizzare le liste di risorse provvisionabili all’ interno della SCMP, come ad esempio Virtual Machines, Storage e Kuberneetes.

Per poter visualizzare degli elementi all’ interno delle liste di risultati (Figura 276). è necessario che nel catalogo SCMP sia presente una relazione con la risorsa di catalogo del provider da provvisionare(5.9.1.1.3)

Le funzionalità disponibili per questi elementi sono identiche, cambiano solo i parametri da inserire negli step di creazione.

![A screenshot of a computer Description automatically generated](media/01f46229b7798b5e422aac2011bdfe20.png)

Figura 276 - Tab per la creazione di risorse

##### **Virtual Machines**

Per iniziare il provisioning di una risorsa cliccare sulla riga corrispondente per visualizzare la pagina contenente lo step 1 della creazione di un provisioning (Figura 277), in questo step è necessario selezionare, tramite il dropdown presente sulla sinistra, il sottosistema “target” nel quale si vogliono provvisionare le risorse, una volta selezionato verrà visualizzato sulla destra uno specchietto informativo che indica le caratteristiche della risorsa che verrà provisionata, per continuare In basso a destra, cliccare sul pulsante “Next” per passare alla pagina dello step 2 “Config” (Figura 278).

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/5f49e7254cc041bdabc8ab53fb30ef85.png)

Figura 277 – Selezione del sottosistema “target”, provisioning step 1

Nella pagina “Config” dello step 2 (Figura 278), compilare tutti i campi obbligatori di tutte le sezioni del form. In basso a sinistra, cliccare sul pulsante “Reset” per resettare tutti i campi della pagina.

Invece a destra, cliccare sul pulsante “Submit” per passare allo step 3 “Plan”.

![A screenshot of a computer Description automatically generated](media/008cbbb8d14a5ff23e8178f14fd7e939.png)![A screen shot of a computer Description automatically generated with low confidence](media/c60683f1763e2892242acceb13e3f2fd.png)

Figura 278 - Compilazione dei campi del form di previsione di una risorsa

Dopo aver cliccato sul pulsante “Submit”, l’utente viene reindirizzato nella pagina “Plan” dello step 3 dove possiamo visualizzare il piano di provisioning inviato da terraform , che indica tutti i parametri delle risorse che verranno configurate e in basso è presente una lista con una prospettiva dei costi da sostenere(Figura 279).

![Immagine che contiene testo, monitor, interni, screenshot Descrizione generata automaticamente](media/6cb7bf5d7775d32eac77c4c05a8588e2.png)

Figura 279 - Schermata della previsione

Sempre dalla pagina “Plan” dello step 3, in basso a destra, sono presenti tre pulsanti: “Back”, “Reset” e “Apply”. Se si clicca sul pulsante “Back”, l’utente torna nella pagina “Config” dello step 2 in cui è possibile modificare i parametri.

Se si clicca sul pulsante “Reset”, l’utente viene reindirizzato nella pagina “Subscription” dello step 1 in cui è necessario selezionare un sottosistema, e successivamente inserire i parametri all’interno della pagina “Config” dello step 2.

Infine, se si clicca sul pulsante “Apply”, la previsione viene salvata e l’utente viene reindirizzato nella pagina del tab “Dashboard” in cui l’utente verifica la presenza della previsione appena creata (Figura 280).

![A screenshot of a computer Description automatically generated](media/93fb874106092f8a8553f6234e281db3.png)

Figura 280 - Lista delle previsioni

#### Provisioning di “Servizi”

Per accedere alla pagina dei servizi cliccare sul tab che raffigura uno scaffale posizionato nel menu in alto. Fatto questo, ci si ritrova all’interno della pagina “Service” (Figura 281).

![](media/5e4c91bc3522e0217b98fa7fec855b40.png)

Figura 281 - Lista delle card

All’ interno della pagina viene visualizzata una lista di componenti denominati “Card”. Ogni card fa riferimento ad un tipo di servizio specifico, in particolare vengono visualizzate le seguenti informazioni:

-   Nome del servizio;
-   Icona del servizio;
-   Tipologia di script utilizzato per il provisioning del servizio;
-   Descrizione del servizio;
-   Tasto ”Subscribe” per procedere con la creazione del servizio.

A seconda della tipologia di servizio selezionato cambiano i passaggi per effettuarne i provisioning, di seguito verranno analizzati in dettaglio.

##### **Servizi “standard”**

Cliccare il tasto “Subscribe” in corrispondenza di un servizio “standard”, l’utente verrà reindirizzato alla pagina dello step 1 della creazione del servizio e verranno visualizzate tutte le versioni del servizio instanziabili dalla SCMP (Figura 282) in particolare verranno visualizzati vari blocchi ognuno con una lista di configurazioni:

-   Nome e versione del servizio che verrà instanziato;
-   Nome e versione del sistema operativo che verrà installato sulla macchina;
-   Provider di appartenenza sul quale verrà provvisionato il servizio.

![A screenshot of a computer Description automatically generated](media/0b2e954673e9ae7c9ca94a98af2ee760.png)

Figura 282 - Provisioning di un servizio “standard”

Selezionare una versione del software e premere il tasto “Continue”, l’utente viene reindirizzato allo step 2 del provisioning di un servizio.(Figura 283)

Allo step 2 sarà necessario selezionare un sottosistema e compilare il form con i dettagli del sottosistema scelto.

![Immagine che contiene software, testo, Software multimediale, computer Descrizione generata automaticamente](media/6dd27bf8f0ad53eca7dd8eea2ed495ee.png)

Figura 283 - Configurazione di un servizio “standard”

A valle del completamento di tutti i campi del form cliccare su “submit”.

Verrà inviata una richiesta al servizio Terrafom che validerà la configurazione di attivazione del flusso indicato e restituirà il risultato. (Figura 284)

![](media/75e3af431902646a931f07f26987489d.png)

Figura 284 - Sommario della configurazione del servizio

Cliccare su “Apply” per validare il flusso e attivare la sottoscrizione del servizio.

Verrà aperta la pagina della dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati.(Figura 284)  
Nello specifico il nuovo servizio provvisionato avrà come stato “In esecuzione” di colore giallo, successivamente a seconda del risultato anche lo stato verrà aggiornato in “Completato” di colore verde o “Errore” di colore rosso

![Immagine che contiene testo, software, Software multimediale, schermata Descrizione generata automaticamente](media/9ec671f95b9b496a5e1cf1aa6e68233e.png)

Figura 285 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati

##### **Servizi “Custom”**

Cliccare il tasto “Subscribe” in corrispondenza di un servizio “custom”, l’utente verrà reindirizzato alla pagina dello step 1 della creazione del servizio dove si può selezionare il sottosistema, nel quale effettuare il provisioining, dalla dropdown al centro della pagina (Figura 286)

![](media/a46638963a4644ac461356903e1bd338.png)

Figura 286 - Provisioning di un servizio “Custom”

Selezionando il sosttossitema la pagina si aggiorna per passare allo step 2 del provisioning di un servizio.

In questo step 2 sarà necessario compilare il form con i parametri di configurazione specifici del servizio selezionato (Figura 287)

![Immagine che contiene software, testo, Software multimediale, computer Descrizione generata automaticamente](media/6dd27bf8f0ad53eca7dd8eea2ed495ee.png)

Figura 287 - Configurazione di un servizio “custom”

A valle del completamento di tutti i campi del form cliccare su “launch”.

Verrà inviata una richiesta al servizio Terrafom che validerà la configurazione di attivazione del flusso indicato e restituirà il risultato. (Figura 288)

![](media/75e3af431902646a931f07f26987489d.png)

Figura 288 - Sommario della configurazione del servizio

Cliccare su “Apply” per validare il flusso e per far iniziare le operazioni automatiche di configurazione

Verrà aperta la pagina della dashboard (Figura 289) con la lista di tutti i servizi sottoscritti ed il loro relativi stati.  
Nello specifico il nuovo servizio provvisionato avrà come stato “In esecuzione” di colore giallo, successvamente a seconda del risultato anche lo stato verrà aggiornato in “Completato” di colore verde o “Errore” di colore rosso

![Immagine che contiene testo, software, Software multimediale, schermata Descrizione generata automaticamente](media/9ec671f95b9b496a5e1cf1aa6e68233e.png)

Figura 289 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati

##### **Servizi “Azure Pipeline”**

Cliccare il tasto “Subscribe” in corrispondenza di un servizio “Azure pipeline”, l’utente verrà reindirizzato alla pagina dello step 1 della creazione del servizio, dalla dropdown al centro della pagina selezionare il “Branch” della pipeline da eseguire (Figura 290)

![](media/41e5c1751d0591823b4c0db7a193e88a.png)

Figura 290 - Provisioning di un servizio “Azure pipeline”

Selezionando il branch la pagina si aggiorna per passare allo step 2 della creazione di un servizio.

In questo step 2 sarà necessario compilare il form con i parametri di configurazione recuperati direttamente dalla Pipeline che verrà eseguita (Figura 291)

![](media/b137791403ddc2398d48620b2aca108d.png)

Figura 291 - Configurazione di un servizio “Azure pipeline”

A valle del completamento di tutti i campi del form cliccare su “launch” per lanciare la richiesta di avvio della pipeline, Verrà aperta la pagina della dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati. (Figura 292)  
Nello specifico il nuovo servizio provvisionato avrà come stato “In esecuzione” di colore giallo, successvamente a seconda del risultato anche lo stato verrà aggiornato in “Completato” di colore verde o “Errore” di colore rosso

![Immagine che contiene testo, software, Software multimediale, schermata Descrizione generata automaticamente](media/9ec671f95b9b496a5e1cf1aa6e68233e.png)

Figura 292 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati

##### **Servizi “PaaS” e “AI Services”**

Cliccare il tasto “Subscribe” in corrispondenza di un servizio “PaaS”, l’utente verrà reindirizzato alla pagina dello step 1 della creazione del servizio dove sarà necessario compilare il form con i parametri di configurazione specifici del servizio selezionato (Figura 293)

![](media/6ab4c3badfbac6d82998da9b20d72d93.png)

Figura 293 - Configurazione di un servizio “PaaS”

A valle del completamento di tutti i campi del form cliccare su “launch”.

Verrà aperta la pagina della dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati.(Figura 294)  
Nello specifico il nuovo servizio provvisionato avrà come stato “In esecuzione” di colore giallo, successivamente a seconda del risultato anche lo stato verrà aggiornato in “Completato” di colore verde o “Errore” di colore rosso

![Immagine che contiene testo, software, Software multimediale, schermata Descrizione generata automaticamente](media/9ec671f95b9b496a5e1cf1aa6e68233e.png)

Figura 294 - Dashboard con la lista di tutti i servizi sottoscritti ed il loro relativi stati

#### Creazione di una richiesta di provisioning “Blueprint”

Per accedere alla pagina dei servizi cliccare sul tab che raffigura delle finestre, nel menu in alto. Fatto questo, ci si ritrova all’interno della pagina “Blueprints” (Figura 281).

All’ interno della pagina viene visualizzata una lista di componenti denominati “Card”. Ogni card fa riferimento ad un tipo di servizio specifico, in particolare vengono visualizzate le seguenti informazioni:

-   Nome del servizio;
-   Icona del servizio;
-   Tipologia di script utilizzato per il provisioning del servizio;
-   Descrizione del servizio;
-   Tasto ”Subscribe” per procedere con la creazione del servizio.

A seconda della blueprint selezionata cambiano i parametri per effettuarne i provisioning, mentre le funzionalità rimangono invariate.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/5e4c91bc3522e0217b98fa7fec855b40.png)

Figura 295 - Lista delle blueprint

##### Richiesta di esecuzione della “Blueprint”

Cliccare il tasto “Subscribe” in corrispondenza di una “Blueprint”, l’utente verrà reindirizzato alla pagina dello step 1 della creazione, in questo step è necessario selezionare dal dropdown il sottosistema nel quale si vuole effettuare il provisioning()

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/49f57e16456b89302ca9cb5b65bf386c.png)

Figura 296 - Step 1 della creazione di una Blueprint

Selezionando un sottosistema la pagina passerà nello step 2 della creazione dove sarà necessario compilare il form con i parametri di configurazione specifici della blueprint selezionata ()

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/35b9817c08b07b62cea1e2916ac8b42a.png)

Figura 297 - Step 2 della creazione "Blueprint"

Completato l’inserimento dei parametri è possibile cliccare il pulsante “Start” in basso a destra per avviare il provisioning (), dopo alcuni secondi verremo reindirizzati nella pagina “Dashboard” filtrata per “Blueprint da completare”

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/e6bb46a0a0d217d78fe65a1416d2d486.png)

Figura 298 - Richiesta "Blueprint" inviata correttamente

##### **Pagina di gestione della blueprint “da completare”**

Per poter lavorare la blueprint è necessario , dalla dashboard , selezionare una blueprint “da completare” , cliccando sulla riga corrispondente verrà visualizzata la sua pagina di gestione ()

Questa pagina è divisa in sezioni, nello specifico:

-   “Process Diagram”: in questa sezione viene visualizzata una immagine che rappresenta graficamente tutti i passaggi da eseguire nella blueprint, inoltre viene indicato in rosso lo step in esecuzione.
-   “Variables”: in questa sezione possiamo visualizzare tutti i parametri inseriti manualmente o automaticamente durante l’esecuzione della blueprint.
-   “Task”: in questa sezione è possibile tramite i controlli disponibili, gestire gli step della blueprint che richiedono un intervento manuale.
-   “Subprocess”: in questa sezione potremo visualizzare lo stato di tutte le operazioni automatiche effettuata durante l’esecuzione della blueprint

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/4b67b2e0eabf05aad37be01c81119152.png)

Figura 299 - Flow del piano di provisioning

![Immagine che contiene software, Software multimediale, schermata, testo Descrizione generata automaticamente](media/399662c8dfbdf3463d188c46f6c328a6.png)

Figura 300 – Sezione sottoprocessi delle blueprint

L’ esecuzione , e quindi il relativo cambio, tra gli step della Blueprint può essere effettuato in due modi, automaticamente o manualmente, esattamente come descritto all’ interno della Blueprint stessa.

###### Step automatici

Il sistema gestisce automaticamente la creazione, configurazione di risorse e deploy di applicazioni, lo stato e il risultato di questi step sono visibili nella sezione “Subprocess” in basso. ()

Per ogni riga presente nella tabella è possibile, cliccando i pulsanti presenti sulla destra, verificare il messaggio di output generato e scaricarne il contenuto.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/1b43bb9d432978345d84b6cca4d964ff.png)

Figura 301 - Sezione sottoprocessi delle blueprint

###### Step manuali

I task manuali, quando presenti e richiesti nella blueprint, appariranno nella relativa sezione, per poterlo lavorare è necessario prima cliccare sul pulsante “Assign” (di colore rosso nella figura) per prendere in carico il task.()

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/d6848d7438c792fd07041d3cd33b7381.png)

verrà visualizzata una modale di conferma assegnazione , cliccando “Yes” il task verrà preso in carico dall’ utente e non potrà essere lavorato da un utente diverso.

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/ead14ca1b0c1f6944430bf46b69a1cd5.png)

In basso apparirà un messaggio di conferma e possiamo notare che la sezione “Task” () è stata aggiornata, viene indicato sulla sinistra, sotto il nome del task , il relativo assegnatario e sulla destra sono presenti 2 pulsanti:

-   “Rimuovi assegnazione” (di colore rosso nella figura)
-   “Completa il task manuale”(di colore giallo nella figura)

![](media/ff38c3ea58820348a2f587371e2a9c79.png)

Cliccando “Rimuovi assegnazione” verrà aperta una modale di conferma () cliccando “Yes” il task verrà reso disponibile per gli altri utenti che potranno prenderlo in carico.

![Immagine che contiene testo, software, Software multimediale, Software per la grafica Descrizione generata automaticamente](media/38d42047ba4821034e4ae1e7df47daf4.png)

Cliccando il pulsante “Completa il task” verrà aperta una modale con all’ interno uno o più campi personalizzabili, i campi possono essere di diverse tipologie.

Possiamo inserire campi numerici , booleani () e di testo() una volta inseriti è possibile confermare cliccando il pulsante “Continue” presente in basso a destra.

![Immagine che contiene testo, schermata, Software multimediale, software Descrizione generata automaticamente](media/756c7b30664855dd10d9f1e1dd9b5d65.png)

Figura 302 - Campi numerici delle blueprint

![Immagine che contiene testo, schermata, Software multimediale, software Descrizione generata automaticamente](media/c35ccfbfe7f281f2dd8f8e333d13b993.png)

Figura 303 - Campi di testo nelle Blueprint

Una volta premuto, possiamo notare che il grafico BPMN presente in pagina è stato aggiornato e che il successivo step della blueprint è attivo e presenta un contorno di colore rosso.()

![Immagine che contiene schermata, software, Software multimediale, Icona del computer Descrizione generata automaticamente](media/dc2caf96f58978179a5cc170a466369a.png)

Tutti i task manuali presenti nella blueprint seguiranno la procedura descritta precedentemente; quindi, indipendentemente dalla tipologia di dato da inserire è sempre necessario assegnarsi il task.

Viene data la possibilità di inserire all’ interno degli step manuali delle blueprint anche un campo temporale, () utilizzando un calendario sarà possibile selezionare manualmente il giorno e l’orario corretto.

![Immagine che contiene testo, Software multimediale, software, Software per la grafica Descrizione generata automaticamente](media/7422253189b30d5c24411f78ef3a2cf9.png)

L’ ultima tipologia di step che possiamo trovare all’ interno delle blueprint è il campo “Multiscelta”, questo campo permette di gestire il flusso della blueprint ()

![Immagine che contiene schermata, testo, Software multimediale, software Descrizione generata automaticamente](media/6272ac1bee8ce78ba51626abe1e62f11.png)

Figura 304 - Campo Multi scelta

Questo campo è di tipo “Selezione” , non sarà quindi possibile inserire un valore personalizzato ma verranno proposte delle opzioni selezionabili,() nello specifico possiamo trovare tre scelte:

-   “Repeat” : permette di rieseguire gli step precedenti come descritto nella blueprint (percorso in rosa nella figura)
-   “End”: permette di concludere l’esecuzione della blueprint senza eseguire ulteriori operazioni (percorso in giallo nella figura)
-   “Insert date”: permette di spostarsi ad uno step successivo della blueprint (percorso in verde nella fiugra)

![Immagine che contiene schermata, testo, Software multimediale, software Descrizione generata automaticamente](media/ce7eefbf90820890bd98083a0ebaf7cf.png)

Figura 305 - Valori del campo Multi scelta

![](media/ec316036d50656694aa940d5c8f6acbe.png)

Figura 306 - Possibili cambi di stato per Multi scelta

Una volta completati tutti i passaggi della blueprint il grafico verrà automaticamente eliminato dalla pagina e nella sezione step non sarà più possibile prendere in carico una operazione, inoltre nella sezione “sottoprocessi” potremo visualizzare il risultato di tutti gli step atuomatizzati nella blueprint

![Immagine che contiene schermata, testo, software, Software multimediale Descrizione generata automaticamente](media/5abc41dce387d015b7a7b0ad8fcfd429.png)

Figura 307 - Completamento della Blueprint

#### Modifica di un provisioning effettuato

Per un provisioning effettuato e che non è andato a buon fine, è possibile effettuare la modifica al suddetto.

La modifica del provisioning è disponibile solo per le risorse di tipo.

Per avviare la modifica di un provisioning, cliccare su una previsione non andata a buon fine ).

![Immagine che contiene testo, monitor, screenshot, nero Descrizione generata automaticamente](media/462b0b98c3ac9573e7162928b43981ce.png)

Figura 308 - Avvio della modifica di un Provisioning

Dopo aver fatto ciò, ci si ritroverà all’interno della pagina “Config” dello step 2 in cui è possibile modificare i parametri precedentemente inseriti (Figura 303).

![Immagine che contiene testo, screenshot, monitor, interni Descrizione generata automaticamente](media/ced7004af32a0047df15586022df2011.png)

Figura 309 - Parametri di configurazione

![A screen shot of a computer Description automatically generated with low confidence](media/c96cb0904c1cf48a71e7399079ad2738.png)

Figura 310 - Modifica dei parametri

Dopo aver modificato i parametri necessari, in basso a destra, cliccare sul pulsante “Submit”.

Facendo ciò, ci si ritroverà all’interno della pagina “Plan” dello step 3 in cui è presente la previsione, e in basso la tabella dei preventivi (Figura 304).

In basso a destra, cliccare sul pulsante “Apply”. Dopo aver cliccato sul pulsante “Apply”, ci si ritroverà all’interno della pagina del tab “Dashboard”.

Successivamente, dalla pagina “Dashboard”, l’utente nota che la modifica è andata a buon fine.

È possibile modificare un provisioning non andato a buon fine anche per gli altri elementi gestiti dalla SCMP.

![Immagine che contiene testo, monitor, interni, screenshot Descrizione generata automaticamente](media/a9a81effca7838b7442a3d1bfb970c71.png)

Figura 311 - Prospetto del Provisioning e tabella dei preventivi

## Service Detail Design

Il servizio service detali design è la soluzione implementata per la gestione delle richieste, che devono essere poi lavorate all’ interno del nostro ambiente da un utente abilitato.

Per accedere ai Service Detail Design accedere a SCMP con l’utente Gestore del servizio.

Dopo aver effettuato il login cliccare dal tasto bento il modulo “Service Detail Design”.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/a0658129503998fbdc3f44194850675e.png)

Figura 312 - Accesso a modulo Service Detail Design

Verrà mostrata la pagina di ricerca dove è possibile filtrare i work order già creati sulla base di:

-   Stato;
-   Customer;
-   Service Type;
-   Fase
-   Data di creazione.

La tabella mostrerà le informazioni generali dell’Ordine di Lavoro.

![](media/53d0cf7fbcedaf856d815b07ece8e4bb.png)

Figura 313 – Filtri della funzionalità Service Detail Design

Cliccare al centro della riga di un ordine di lavoro per visualizzarne il contenuto, verrà aperta una modale dove, all’ interno possiamo espandere le varie sezioni cliccando su di esse.

Per uscire dalla visualizzazione dei dettagli cliccare all’ esterno della finestra grigia.

![A screenshot of a computer Description automatically generated](media/66738428956f09f140373440cfe5ad68.png)

Figura 314 - Dettagli dell'Ordine di Lavoro

### Flusso dei Work Order

Per prendere in carico un ordine di lavoro cliccare, in corrispondenza di un ordine in stato “New” il simbolo “Play”.

Verrà visualizzata una notifica a schermo di cambio stato, e lo stato attuale dell’Ordine diventa “In progress”, i pulsanti del relativo ordine vengono modificati:

-   cliccando il tasto “Pause” l’ordine passerà nello stato “Idle”;
-   cliccando il tasto “Mark as completed” è possibile chiudere l’Ordine di Lavoro;
-   cliccando il tasto “Rejected” è possibile segnalare l’annullamento dell’Ordine;

![A screenshot of a computer Description automatically generated](media/d27624037a684ae327a5cd39cfcae5f5.png)

Figura 315 - Pagina di gestione dei work order dei Service Detail Design

Quando viene cliccato il tasto “Mark as completed” viene visualizzata a schermo una finestra dove inserire le informazioni da allegare all’ ordine, in particolare:

-   il risultato della lavorazione.
-   una descrizione della scelta del risultato;
-   una nota per l’operatore.

![A screenshot of a computer Description automatically generated](media/857fae497719daaf2934fd6ea9ed9921.png)

Figura 316 - Chiusura di un Work order

Scorrendo in basso la pagina possiamo trovare la sezione dei parametri dove è possibile inserire diverse combinazioni chiave/valore dei parametri utilizzati durante la lavorazione.

Dopo aver inserito la chiave e il valore cliccare sul tasto “Più” per confermare l’inserimento, vengono aggiunti nuovi campi vuoti dove inserire ulteriori parametri. Per eliminare una coppia chiave/valore cliccare il tasto “Meno”, una volta inseriti tutti i parametri cliccare il tasto “Finish”.

![A screenshot of a computer Description automatically generated with medium confidence](media/7252403e5d15acb6e1e4c43a7c91c0a4.png)

Figura 317 - Inserimento parametri

Dopo aver completato l’ordine è possibile, aprendo i rispettivi menù, visualizzare all’ interno delle info tutte le informazioni inserite durante la lavorazione.

![Immagine che contiene testo, schermata, software, Software multimediale Descrizione generata automaticamente](media/423a572c0570aca5565fc8f42cac19b7.png)

Figura 318 - Informazioni aggiunte durante la lavorazione

## Cloud Maturity Model

Per questa sezione si rimanda al documento R2 riportato nella tabella di riferimento.

## SCMP – VARIE

All’interno della presente sezione sono riportati alcuni comportamenti generali

### Supporto multilingua

L’interfaccia operatore è disponibile in due lingue (inglese – italiano) e l’operatore può scegliere la lingua semplicemente selezionando la scritta in alto a sinistra della schermata.

![](media/6919fb24d4dfaa9fb957cc1b9203e514.png)

Figura 319 - Menu per effettuare la modifica della lingua

### Reset filtri

Per le funzionalità Monitoring, Costs, Inventory, Catalog e Security, all’interno dei filtri, è possibile effettuare il reset dei suddetti e delle liste, cliccare sul pulsante che raffigura una “X”, presente sotto il filtro calendario.

![](media/157cdf31bb494b7bd3c9b4c7c7d51d6a.png)![Immagine che contiene testo, screenshot, monitor, nero Descrizione generata automaticamente](media/a645074d96513c7cc3b365ba3b7b7030.png)

Figura 320 - Dettaglio impostazione filtri

### Light mode

Per attivare la light mode in tutta la piattaforma SCMP, in alto a destra sulla barra dei menu, cliccare sul pulsante che raffigura il sole come mostrato sotto in Figura 314.

![Immagine che contiene testo, elettronico, screenshot, proiettore Descrizione generata automaticamente](media/66be32a34a4f82e6c7006ddc46d13307.png)

Figura 321 - Attivazione della light mode

Per disattivare la light mode, cliccare sul pulsante che raffigura la luna come mostrato in Figura 315.

![](media/787d15ef310ff6b49cf145505b400507.png)

Figura 322 - Disattivazione della light mode

### Switch Tenant

Per passare da un Tenant ad un altro, cliccare sul pulsante che raffigura un omino. A questo punto appare un menu a tendina in cui è necessario cliccare su “Switch Tenant” (Figura 316).

![Immagine che contiene testo, screenshot, elettronico, proiettore Descrizione generata automaticamente](media/9ba8e1c7269458560c6dafe52b6f7d7d.png)

Figura 323 - Menu per lo switch Tenant

Dopo aver cliccato su “Switch Tenant”, appare un modale in cui è possibile selezionare un Tenant in cui effettuare il cambio (Figura 317). Dopo aver selezionato il Tenant desiderato, cliccare sul pulsante “Confirm”.

Dopo aver fatto ciò, la pagina si aggiorna con il Tenant desiderato in cui può visualizzare tutti i dati appartenenti al suddetto su tutte le funzionalità della piattaforma.

![Immagine che contiene testo, monitor, interni, schermo Descrizione generata automaticamente](media/8eb9d50d28b16ccbc4eecfc71c76ba6f.png)

Figura 324 - Switch del Tenant

## Trattamento correlato

N/A

## Backup dei dati

N/A

## Recupero da errori, malfunzionamenti ed emergenze

N/A

## Messaggi

N/A

## Questa guida di riferimento rapido

N/A

# NOTE

## Definizioni

| **Definizione** | **Descrizione**                         |
|-----------------|-----------------------------------------|
| Azure           | Piattaforma cloud pubblica di Microsoft |

## Acronimi

| **Acronimo** | **Descrizione**                            |
|--------------|--------------------------------------------|
| API          | Application Programming Interface          |
| DBMS         | Data Base Management System                |
| FHIR         | Fast Healthcare Interoperability Resources |
| HMP          | Health Management Platform                 |
| IAM          | Identity Access Management                 |
| N/A          | ?                                          |
| ODL          | Ordine Di lavoro                           |
| RDBMS        | Relational Database Management System      |
| REST         | Representational State Transfer            |
| SQL          | Structured Query Language                  |
| VM           | Virtual Machine                            |
| WP           | Work Package                               |
| JWT          | Json web token                             |
| CURD         | Create, Read, Update, and Delete           |
| SIEM         | Security Information & Events Manager      |
| SKU          | Stock Keeping Unit                         |
