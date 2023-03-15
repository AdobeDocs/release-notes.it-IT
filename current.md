---
title: Note sulla versione più recente
description: Leggi le ultime note sulla versione di Adobe [!DNL Experience Cloud]  prodotti e servizi. Scopri i prossimi eventi e la nuova documentazione su Experience League. Scopri le esercitazioni e i corsi più recenti per applicazioni  [!DNL Experience Cloud] .
doc-type: release notes
last-update: March 2023
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: 419494f5ae61e2c39d36efa15d00bf878a6a00dc
workflow-type: tm+mt
source-wordcount: '4607'
ht-degree: 45%

---

# Note sulla versione di Experience Cloud

![Banner](assets/release-notes-header.png)

## Marzo 2023

Questa pagina ti aiuta a rimanere aggiornato sulle informazioni sulla versione del prodotto, sugli eventi e sulle opportunità di apprendimento di Experience League.

>[!TIP]
>
>Per ricevere una notifica e-mail mensile sugli aggiornamenti di questa pagina, abbonati ad [Aggiornamento sui prodotti priority Adobe](https://www.adobe.com/subscription/priority-product-update.html). Torna spesso a controllare per essere sempre al corrente delle novità sulle applicazioni enterprise di Adobe.

**Hai bisogno di aiuto?**

Il tuo percorso per il successo inizia con [Experience League](https://experienceleague.adobe.com/?lang=it#home). Sfoglia la nostra vasta libreria sulla [documentazione del prodotto](https://experienceleague.adobe.com/docs/?lang=it) di supporto autonomo e i [video tutorial](https://experienceleague.adobe.com/docs/home-tutorials.html?lang=it) guidati. Trova [corsi](https://experienceleague.adobe.com/?lang=it#courses) per tutti i livelli e ruoli, poni domande dalla [community](https://experienceleaguecommunities.adobe.com/?profile.language=en) online di colleghi e ottieni il [supporto](https://experienceleague.adobe.com/?support-tab=home&amp;lang=it#support) esperto quando necessario.

## Aggiornamenti ed eventi del rilascio del prodotto

Ultimo aggiornamento: **15 marzo 2023**

* [Eventi di [!DNL Experience League]](#events)
* [[!DNL Adobe System Status]](#status)
* [[!DNL Experience Cloud] interfaccia e amministrazione](#ecloud)
* [[!DNL Experience Platform]](#platform)
* [[!DNL Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)<!-- * [[!DNL Streaming Media Analytics]](#sma) -->
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Commerce]](#commerce)
* [[!DNL Target]](#target)
* [[!DNL Campaign]](#ac)
* [[!DNL Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [[!DNL Advertising]](#advertising)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)<!-- * [Digital Experience Blueprints - tutorials](#blueprints) -->

## ![Icona](/assets/experience-league.png) Eventi di [!DNL Experience League] {#events}

Scoprite cosa sta succedendo sull&#39;Experience League. Gli eventi sono un ottimo luogo per imparare, interagire e ottenere le risposte dagli esperti di prodotto di Adobe!

+++Prossimi eventi

* **[!DNL Analytics]** | _Accelerare i tempi di analisi con Adobe Analytics_ | **9 marzo alle 8:00 PT** |  [Registro](https://adobeanalyticsvirtualanalyst2023.experienceleague.adobeevents.com/)

* **[!DNL Marketo Engage]** | _Marketo e Moche: Recapito (Parte 1)_ | **9 marzo alle 1:00 PM ET** | [Registro](https://register.gotowebinar.com/register/6250682251177513567)

* **[!DNL Workfront]** | _Connetti: Chat per amministratori strategici_ | **13 Marzo alle 7:00 MT** | [Registro](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,lgDkllfW8EatH2CVDH9nVQ,JWCg6TzBMUS5dX7i0qHSsA,CjE7t_FXgEaepx27DZn_7g?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Workfront]** | _Nozioni di base sull&#39;amministratore di sistema: Miglioramento dell’esperienza utente con la progettazione dell’interfaccia_ | **15 Marzo alle 8:00 PT** | [Registro](https://event.on24.com/wcc/r/4123271/D486841B3D743479F12BAC0C583C10ED?partnerref=exl)

* **[!DNL Marketo Engage]** | _Interruzione caffè Q&amp;A nella community Marketo_ | **15 marzo alle 08:00 PT** | [Registro](https://mecommunityqacoffeebreak0315.splashthat.com/?utm_source=email&amp;utm_medium=Outbound&amp;utm_campaign=coffee_talk_ME&amp;utm_content=230315)

* **[!DNL Adobe Summit]** |_L&#39;esperienza definitiva è tornata. Unisciti a noi a Vegas per sviluppare competenze, imparare dai migliori marchi del mondo ed essere ispirati_ | **19 marzo alle 09:00 PT** | [Registro](https://summit.adobe.com/na/?promoid=2K4PC9V3&amp;mv=other)

Vedi [Experience League eventi](https://experienceleague.adobe.com/events/?lang=it) per una pianificazione completa dei prossimi eventi e degli eventi passati on-demand.

+++

## ![Icona](/assets/system-status.png) [!DNL Adobe System Status] {#status}

Scopri le funzioni e gli aggiornamenti più recenti di [!DNL Adobe System Status].

+++Dettagli

[!DNL Adobe System Status] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative a interruzioni di prodotti e servizi Adobe, interruzioni ed eventi di manutenzione. Consulta [status.adobe.com/it](https://status.adobe.com/it).

Data di rilascio: **15 febbraio 2023**

**Novità**

* [!DNL Status] è stato aggiunto il supporto API che ti consente di chiamare direttamente i server di Adobe per eseguire query e visualizzare eventi come su [status.adobe.com](https://status.adobe.com/it) Interfaccia utente. Puoi utilizzare queste API per integrare nel sistema di monitoraggio o nelle dashboard per visualizzare gli eventi in tempo reale dallo stato Adobe. Gli eventi possono essere filtrati in base a Prodotto, Offerta prodotto, Area geografica, Ambiente (se disponibile), Impostazioni internazionali ed Tipo evento.

| Funzione | Descrizione |
| ------- | -------|
| API di stato di Adobe | <ul><li>Le API di stato di Adobe forniscono informazioni dettagliate e aggiornamenti in tempo reale sugli eventi di interruzione, interruzione e manutenzione di prodotti e servizi cloud di Adobe.</li><li>È necessario configurare le API in [Console Adobe Developer](https://developer.adobe.com/console) prima che possano essere utilizzati. Per accedere alle API di Adobe, l’organizzazione deve disporre di adesioni per almeno un prodotto Adobe. È necessario un account Console per sviluppatori con le autorizzazioni corrette.</li><li>Consulta la documentazione [qui](https://developer.adobe.com/adobe-status/) e seguire le guide per la configurazione.</li><li>Una volta completata la configurazione, puoi utilizzare la [Documento di riferimento API](https://developer.adobe.com/adobe-status/api/) per visualizzare le API disponibili e le firme per richiamarle.</li></ul> |

{style="table-layout:auto"}

+++

## ![Icona](/assets/ec_appicon_24.png) Interfaccia e amministrazione di Experience Cloud {#ecloud}

Scopri gli aggiornamenti della home page dell’interfaccia di Experience Cloud, dell’amministrazione (gestione di prodotti e utenti), delle impostazioni del profilo utente, delle preferenze, della ricerca e dei cookie.

+++Dettagli

_Non aggiornato a marzo._

Per assistenza, consulta la sezione [Guida all’interfaccia e all’amministrazione di Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=it) (include [!UICONTROL Attributi del cliente] e [!UICONTROL Tipi di pubblico]).

+++

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Experience Platform] {#platform}

Trova informazioni sulla versione più recente e nuova documentazione per [!DNL Experience Platform] e [!UICONTROL SDK per dispositivi mobili]. Visualizza ad Experience League nuovi tutorial e articoli della Knowledge Base.

+++Dettagli

* [Note sulla versione di Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=it) - rilascio pianificato - **29 marzo 2023**

### Nuovi corsi e tutorial su [!DNL Experience Platform]

Nuovi video, tutorial o corsi pubblicati per Adobe Experience Platform.

| Tipo | Funzionalità del prodotto | Descrizione | Applicazione |
| -----------| ---------- |---------- |---------- |
| Marzo 2023 | [Inserire i dati utilizzando il connettore di origine Adobe Analytics](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=it) | Video aggiornato | Trasmetti, mappa e filtra i dati da Adobe Analytics in Adobe Experience Platform Profilo cliente in tempo reale e lago di dati di esperienza. | Acquisizione dei dati |

{style="table-layout:auto"}

### [!DNL Experience Platform] knowledge base di supporto

Nuovi articoli e aggiornamenti ad articoli esistenti per [!DNL Experience Platform].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Febbraio 2023 | [Nessuna dimensione del pubblico in [!DNL Microsoft Bing] Destinazione AEP](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21544.html?lang=it) | Nuovo articolo | Scopri perché [!DNL Bing] non mostra le dimensioni del pubblico per i segmenti AEP inviati ad AEP [!DNL Bing] destinazione. |
| Febbraio 2023 | [Qual è il numero di ambienti (sviluppo, staging, produzione) che viene fornito con la licenza RTCDP?](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21590.html?lang=it) | Nuovo articolo | Ulteriori informazioni sul numero di ambienti e sandbox che sono forniti con la licenza RTCDP. |
| Febbraio 2023 | [Effettua la _Applica trasformazione_ l’opzione all’attivazione della destinazione normalizza (ad esempio minuscolo) prima dell’hashing?](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21591.html?lang=it) | Nuovo articolo | Scopri di più sulla normalizzazione generale dei dati e la relativa soluzione alternativa. |

{style="table-layout:auto"}

### [!DNL Mobile] SDK

Aggiornato: **11 novembre 2022** - Vedi [Note sulla versione e registri delle modifiche](https://aep-sdks.gitbook.io/docs/release-notes) per [!DNL Adobe Experience Platform] [!DNL Mobile SDKs].

+++

## ![Icona](/assets/analytics.png) [!DNL Analytics] {#analytics}

Trova le informazioni più recenti sulla versione di [!DNL Adobe Analytics] e [!DNL AppMeasurement]. Visualizza ad Experience League nuove esercitazioni e nuovi corsi.

+++Dettagli

Data di rilascio: **8 marzo 2023**

* [Note sulla versione](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=it) di [!DNL Analytics]
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/analytics.html?lang=it) di [!DNL Analytics]

### AppMeasurement {#appm}

Versione: **2.23.0**

* [Note sulla versione di AppMeasurement per JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=it)

### Nuovi corsi e tutorial su [!DNL Analytics] {#tutorials-analytics}

Nuovi tutorial, articoli e corsi pubblicati per Adobe Analytics.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Marzo 2023 | [Editor Rich Text in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/rich-text-editor-in-analysis-workspace.html?lang=en) | Video aggiornato | Scopri le funzioni che consentono ad analisti e addetti al marketing di applicare modifiche alle visualizzazioni di testo (o alle descrizioni) in Analysis Workspace: grassetto, corsivo, intestazioni, collegamenti ipertestuali e altro ancora. |

{style="table-layout:auto"}

+++

## ![Icona](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Trova le informazioni più recenti sulla versione di [!DNL Customer Journey Analytics]. Visualizza ad Experience League nuove esercitazioni e nuovi corsi.

+++Dettagli

Versione successiva: **8 marzo 2023**

* [Note sulla versione](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=it) di Customer Journey Analytics
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=it) di Customer Journey Analytics

### Nuovi corsi ed esercitazioni per Customer Journey Analytics {#tutorials-cja}

Nuovi video, tutorial o corsi pubblicati per CJA.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Marzo 2023 | [Collegare Customer Journey Analytics alle sorgenti dei dati di Experience Platform](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=en) | Video | Il Customer Journey Analytics utilizza i set di dati acquisiti in Adobe Experience Platform. Prima di iniziare l’analisi dei dati in Workspace, è necessario creare una connessione. |

{style="table-layout:auto"}

+++

<!-- ## ![Icon](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Latest release: **September 22, 2022**

* [!DNL Streaming Media Analytics] [release notes](https://experienceleague.adobe.com/docs/media-analytics/using/release-notes/release-notes.html?lang=en)
* [!DNL Streaming Media Analytics] [product documentation and tutorials](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Updates and new content for [!DNL Audience Manager]. -->

<!--### [!DNL Audience Manager] support knowledge base

New articles and updates to existing articles for [!DNL Adobe Audience Manager]

For self-help resources, see [Audience Manager documentation and tutorials](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) on Experience League.-->

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Scopri nuove funzioni, correzioni e aggiornamenti in Experience Manager. Visualizza ad Experience League le esercitazioni e gli articoli della Knowledge Base più recenti.

+++Dettagli

### [!DNL Experience Manager] Roadmap e rilascio di video

Adobe consiglia di visitare le seguenti risorse per informazioni sempre aggiornate sulle verrsioni:

* [Aggiornamenti e roadmap delle versioni di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=it): scopri la roadmap delle versioni di Experience Manager, aggiornamenti sulle versioni precedenti e aggiornamenti della documentazione.
* [Aggiornamenti della versione di Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/overview.html?lang=it): guarda le panoramiche video delle versioni attuali e precedenti di [!DNL Experience Manager as a Cloud Service].
* [Note sulla versione attuale di Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=it): leggi le note sulla versione più recente di [!DNL Experience Manager as a Cloud Service].

### Video di panoramica sulla versione più recente

Guarda il [video di panoramica sulla versione di gennaio 2023](https://video.tv.adobe.com/v/3413479/?quality=12) per un riepilogo delle funzioni aggiunte nella versione 2023.01.0 (gennaio 2023).

### [!DNL Experience Manager Sites] as a [!DNL Cloud Service]

_Nuove funzioni_

* La [!DNL Experience Manager] L’API di distribuzione dei contenuti GraphQL ora supporta GraphQL [Paging](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/graphql-api/content-fragments.html?lang=en#paging) e [Ordinamento](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/graphql-api/content-fragments.html?lang=en#sorting), per rendere più efficiente il recupero e il rendering di set di contenuti di grandi dimensioni. L’impaginazione di GraphQL migliora il tempo di risposta delle query restituendo risultati in sottoinsiemi anziché tutti contemporaneamente. L’ordinamento GraphQL consente di ordinare i set di contenuti nell’ordine desiderato, facilitando l’elaborazione dei contenuti da parte di un’applicazione client. Il tempo di risposta della query viene ulteriormente migliorato con Filtro ibrido nella sezione [!DNL Experience Manager] Motore GraphQL. Il contenuto viene ora letto da JCR in set più piccoli che corrispondono ai filtri di query.

### [!DNL Experience Manager Assets] as a [!DNL Cloud Service]

_Nuova funzionalità_

* I rapporti di Assets ora includono la possibilità per gli amministratori di [generare rapporti di download delle risorse](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/asset-reports.html?lang=en) dal [!DNL Experience Manager Assets] come [!DNL Cloud Service] distribuzione. Questi dati consentono inoltre agli amministratori di ricavare informazioni dalle metriche di successo chiave al fine di misurare l’adozione di Assets all’interno della tua azienda e da parte dei clienti.
* [!DNL Experience Manager Assets], oltre alla chiave di accesso per l’autenticazione durante la connessione all’origine dati dell’Archivio Azure Blob, ora [supporta il token SAS](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=it#asset-bulk-ingestor) per l’acquisizione delle risorse utilizzando lo strumento Importazione in blocco.
* È stata migliorata la gestione delle immagini CMYK in Asset compute, consentendo di generare ritaglio avanzato e tag avanzati per le immagini CMYK.

_Nuova funzionalità disponibile nel canale prerelease_

* [!DNL Experience Manager Assets] ora supporta [acquisizione su larga scala di risorse da Google Cloud Platform](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=it#asset-bulk-ingestor) utilizzando lo strumento di importazione in blocco.

### [!DNL Experience Manager Forms] as a [!DNL Cloud Service]

_Nuove funzioni_

* **[Passaggi del flusso di lavoro per generare documenti PDF non interattivi e output stampabile](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-form-centric-workflows/aem-forms-workflow-step-reference.html?lang=en)** - Automatizzare la creazione di documenti PDF non interattivi e di output stampabili per i processi aziendali con [!DNL Experience Manager] Procedura del flusso di lavoro, semplificazione del processo di generazione dei documenti e risparmio di tempo.
* **[Utilizza le note a piè di pagina per fornire citazioni o informazioni aggiuntive in Adaptive Forms](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/add-components-to-an-adaptive-form/footnotes-richtextsupport.html?lang=en)** - Utilizzare le note a piè di pagina in un modulo adattivo per visualizzare le informazioni su come compilare o utilizzare un modulo. Puoi anche utilizzarlo per fornire informazioni parentetiche, autorizzazioni di copyright e altre informazioni utili.


_Nuove funzioni nel canale prerelease_

* [Utilizzare i componenti core di acquisizione dati per creare Forms adattivo](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/adaptive-forms/introduction.html?lang=en) - [Utilizza l’editor Forms adattivo](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/creating-adaptive-form-core-components.html?lang=en) per creare moduli basati su componenti di acquisizione dati standardizzati (componenti core). Questi componenti offrono funzionalità di personalizzazione, tempi di sviluppo ridotti e costi di manutenzione inferiori per le esperienze di iscrizione digitale.
* [Supporto della pipeline front-end per lo stile basato su componenti adattativi Forms](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/using-themes-in-core-components.html?lang=en) - Utilizza temi basati su BEM facilmente personalizzabili per Forms adattivo basato su componenti core distribuendoli con la pipeline di distribuzione Frontend per migliorare l’aspetto dei moduli.
* [Genera documento di record per Forms adattivo basato su componenti core](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/generate-document-of-record-core-components.html?lang=en) - Crea un record per i moduli adattivi basati su componenti core all’invio per l’archiviazione a lungo termine, in stampa o nel formato del documento.
* [Inviare Forms adattivo a Microsoft® SharePoint e Microsoft® OneDrive](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/configure-submit-actions-and-metadata-submission/configuring-submit-actions.html?lang=en) - Semplifica l’invio dei dati con la possibilità di inviare direttamente i dati del modulo adattivo a Microsoft® SharePoint e Microsoft® OneDrive. È possibile inviare sia dati basati su schema che dati privi di schema. Queste azioni di invio si aggiungono alle azioni di invio già disponibili.
* [Creazione efficiente di moduli con la funzione Salva un modulo adattivo come modello](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/create-an-adaptive-form-on-forms-cs/template-editor.html?lang=en#save-an-adaptive-form-as-template-saving-adaptive-form-as-template) - Semplificare il processo di creazione dei moduli salvando un modulo adattivo come modello e riutilizzando i modelli per il modulo adattivo successivo.
* [Connetti [!DNL Experience Manager Forms] ai database supportati da JDBC](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/use-form-data-model/configure-data-sources.html?lang=en#configure-relational-database-configure-relational-database) - Facile connessione [!DNL Experience Manager Forms] modello dati per database che supportano JDBC, che consente di leggere e scrivere i dati senza problemi.
* [Integrare con gli endpoint REST utilizzando Open API 3.0](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/use-form-data-model/configure-data-sources.html?lang=en#configure-restful-services-open-api-specification-version-20-configure-restful-services-swagger-version30) - Connetti [!DNL Experience Manager Forms] come [!DNL Cloud Service] Modelli di dati per moduli per endpoint REST che supportano la versione 3.0 della specifica Open API, che consente di inviare e ricevere dati con facilità.
* [Condivisione di un modulo adattivo per la revisione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/create-reviews-forms.html?lang=en) - Utilizzare il meccanismo di revisione di Adaptive Forms per consentire a uno o più utenti di rivedere il modulo.

### Componente aggiuntivo CIF

_Nuove funzioni_

* Gli autori possono arricchire dinamicamente gli elenchi di prodotti con Frammenti di esperienza (ad esempio, inserendo un banner tra le voci dei prodotti elencati).
* Il componente Elenco ora supporta le pagine o categorie di prodotti associate per mostrare in modo dinamico le pagine correlate.
* È stato aggiunto il supporto per i componenti Peregrine 12.5.
* È stato aggiunto il supporto per il caricamento dei prezzi lato client nei teaser e nei caroselli di prodotti.

### [!DNL Experience Manager as a Cloud Service] Foundation

_Nuove funzioni_

* [Ambiente di sviluppo rapido](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/rapid-development-environments.html?lang=en) - Gli RDE consentono agli sviluppatori di risolvere rapidamente i problemi e di implementare nuove funzioni su [!DNL Experience Manager] come [!DNL Cloud Service].

   Gli ambienti di sviluppo rapido sono un nuovo tipo di ambiente cloud inteso come modo rapido, coerente ed estensibile di convalidare tale codice che funziona localmente funziona anche come previsto nel cloud. Utilizzando strumenti da riga di comando, puoi &quot;sincronizzare&quot; rapidamente pacchetti di contenuto, bundle, file di contenuto, configurazione OSGI o configurazione del Dispatcher all’RDE.

   Dopo aver convalidato correttamente il codice in RDE, ti consigliamo di distribuirlo in un ambiente di Cloud Development. Nell’ambiente, puoi sfruttare i gate di qualità di Cloud Manager prima di distribuirli tramite una pipeline di produzione per gli ambienti di stage e produzione.

   Ogni programma include un RDE ed eventualmente un altro può essere concesso in licenza.

   >[!NOTE]
   >
   >Le RDE sono previste per l’introduzione graduale nelle prossime settimane. Puoi inviare un’e-mail a [aemcs-rde-support@adobe.com](mailto:aemcs-rde-support@adobe.com) per saltare in primo piano.

* [Supporto esteso per token di accesso API lato server](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/generating-access-tokens-for-server-side-apis.html?lang=it) - È ora possibile generare più credenziali, utili in scenari in cui le API hanno caratteristiche diverse. Ora è anche possibile revocare le credenziali in modo self-service.

### [!DNL Cloud Manager]

_Nuove funzioni_

* Gli utenti possono scaricare [test personalizzato dell&#39;interfaccia utente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/ui-testing.html?lang=en) risultati dall’interfaccia utente di .
* [Ambienti di sviluppo rapidi](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/rapid-development-environments.html?lang=en) (RDE) è un nuovo tipo di ambiente Cloud progettato come modo veloce, coerente ed estensibile per convalidare il codice che funziona localmente anche funziona come previsto nel cloud.
   * Gli RDE consentono agli sviluppatori di risolvere rapidamente i problemi e di implementare nuove funzioni su [!DNL Experience Manager] come [!DNL Cloud Service].
   * Utilizzando gli strumenti della riga di comando, gli sviluppatori possono sincronizzare rapidamente pacchetti di contenuto, bundle, file di contenuto, configurazioni OSGi o configurazioni del Dispatcher agli RDE.

_Modifiche API_

* Sono state apportate modifiche all’API per supportare [RDE](https://developer.adobe.com/experience-cloud/cloud-manager/reference/api/#tag/Rapid-Development-Environments).
* L’API ora consente il recupero di [artifact di esecuzione](https://developer.adobe.com/experience-cloud/cloud-manager/reference/api/#tag/Execution-Artifacts).

### Informazioni sulla versione di Experience Manager

Tutto [!DNL Experience Manager] le informazioni sulla versione sono disponibili all&#39;indirizzo:

* [Informazioni sulla versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=it)
* [Aggiornamenti della versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/overview.html?lang=it)
* [Note sulla versione attuale di Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=it)
* [Informazioni sulla versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=it)
* [Note sulla versione di Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=it)
* [Note sulla versione del Servizio di conversione automatica dei moduli](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=it)
* [Note sulla versione di Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=it)
* [Note sulla versione dell’app desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=it)
* [Note sulla versione di Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=it)
* [Note sulla versione di Livefyre](https://experienceleague.adobe.com/docs/discontinued/using/livefyre.html?lang=it)

### Nuovi corsi ed esercitazioni su Experience Manager {#tutorials-aem}

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazioni |
| -----------| ---------- | ---------- | ---------- | ------|
| Marzo 2023 | [Ambienti di sviluppo rapidi](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/rde/overview.html) | Video | Scopri l’ambiente di sviluppo rapido (RDE), come configurarlo e utilizzarlo e come comprendere il ciclo di vita dello sviluppo utilizzando RDE. | AEM CS |
| Marzo 2023 | [Asset Share Commons Asset Kit](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/assets-share/asset-share-commons-asset-kits.html) | Video | Scopri come utilizzare la funzionalità del kit di risorse di Asset Share Common per generare pagine web personalizzate che elencano le risorse dalle cartelle o raccolte di AEM Assets. | AEM Assets |

{style="table-layout:auto"}

### [!DNL Experience Manager] knowledge base di supporto

Nuovo articolo e aggiornamenti ad articoli esistenti per [!DNL Adobe Experience Manager].

| Data di pubblicazione | Nome | Tipo | Descrizione |
|---------|--------|---------|---------|
| Febbraio 2023 | [Come consentire agli utenti non amministratori di accedere alla Web Console?](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21527.html?lang=it) | Nuovo articolo | Scopri come consentire agli utenti non amministratori di accedere alla console Web (OSGi Console). |
| Febbraio 2023 | [Come scaricare le risorse con cURL?](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21528.html?lang=it) | Nuovo articolo | Scopri come scaricare risorse con cURL. |
| Febbraio 2023 | [Errore: BUILD_MAVEN_PACKAGE_ERROR in [!DNL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21577.html?lang=it) | Nuovo articolo | Scopri come risolvere l’errore - `Build_Maven_Package_Error` in [!DNL Cloud Manager]. |
| Febbraio 2023 | [La distribuzione della pipeline non riesce durante il passaggio di generazione](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21419.html?lang=it) | Nuovo articolo | Trova la soluzione per il problema in cui l’esecuzione della pipeline non riesce durante il passaggio di compilazione, a causa di errori nel `ui.frontend` codice. |
| Febbraio 2023 | [Aggiornamento del token non supportato per token incapsulato](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21491.html?lang=it) | Nuovo articolo | Trova la soluzione per il problema in cui non è supportato il token refresh per il token incapsulato. |

{style="table-layout:auto"}

### Altre risorse di assistenza per Experience Manager

* [Guide di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=it)
* [Guida utente di Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=it)
* [Formazione e supporto per Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=it)
* [Formazione e supporto per Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=it)
* [Documentazione delle versioni precedenti di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it#previous-updates)
* [Pagina iniziale della guida di Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=it)
* [Documentazione di Experience Manager: ultimi aggiornamenti](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=it#aem-as-a-cloud-service)

+++

<!-- ## ![Icon](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] is an application deployed onto AEM. It is a powerful, enterprise-grade component content management solution (CCMS) which enables native DITA support in Adobe Experience Manager, empowering AEM to handle DITA-based content creation and delivery.

Learn more about [[!DNL Experience Manager Guides]](https://business.adobe.com/products/experience-manager/guides/features.html).

### Additional resources

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - tutorials on Experience League
* [[!DNL Experience Manager Guides] Learn & Support](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - product documentation -->

## ![Icona](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Accedere alle note sulla versione, ai nuovi tutorial e agli articoli della Knowledge Base per [!DNL Adobe Commerce] Experience League.

+++Dettagli

* Consulta [Note sulla versione di Adobe Commerce e Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/release/notes/overview.html?lang=it) per restare al corrente.

>[!NOTE]
>
>Fine del servizio di [!DNL Adobe Search&Promote] a partire del **1° settembre 2022**. Per la ricerca di prodotti e commercio, [Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html?lang=it) è l&#39;applicazione di ricerca di Adobe. Consulta la sezione [annuncio di fine del ciclo di vita](https://experienceleague.adobe.com/docs/discontinued/using/search-promote.html?lang=it) per ulteriori informazioni.

### Nuovi tutorial e documentazione per [!DNL Adobe Commerce] {#tutorials-commerce}

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Marzo 2023 | [Configurare Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/io-events/configure-commerce.html) | Video | Scopri come configurare Adobe Commerce per esporre gli eventi. |
| Marzo 2023 | [Introduzione all’utilizzo di mesh API](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/api-mesh/getting-started-api-mesh.html?lang=en) | Video | Scopri come utilizzare API Mesh in Adobe Commerce e Adobe App Builder. Scopri come installare Adobe App Builder, lavorare con i progetti, creare un proxy inverso graphql e molto altro ancora. |
| Marzo 2023 | [Eventi di I/O per Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/io-events/2-4-5-installation.html?lang=en) | Video (multiplo) | Scopri come installare diversi nuovi moduli in Adobe Commerce utilizzando Composer per le versioni 2.4.5, 2.4.6 e altro ancora. Questo imposta i moduli richiesti da utilizzare nell’applicazione Adobe Commerce. |

{style="table-layout:auto"}

### [!DNL Commerce] knowledge base di supporto

Nuovi articoli e aggiornamenti agli articoli esistenti per Adobe Commerce.

| Data di pubblicazione | Nome | Tipo | Descrizione |
|---------|--------|---------|---------|
| Febbraio 2023 | [Quality Patches Tool (QPT)](https://experienceleague.adobe.com/docs/commerce-knowledge-base/kb/support-tools/patches/patches-available-in-qpt-tool-overview.html?lang=it) | Nuovi articoli | Sono stati pubblicati nuovi articoli su come applicare le patch disponibili nel QPT 1.1.26 e QPT 1.1.27, reperibili nelle rispettive sezioni. |

{style="table-layout:auto"}

+++

## ![Icona](/assets/target.png) [!DNL Target] {#target}

Accedi alle note pre-release, alle note sulla versione corrente e ai nuovi tutorial per Adobe Target.

+++Dettagli

* Per informazioni pre-release, consulta [[!DNL Adobe Target] prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=it)
* Per informazioni sulla versione attuale, consulta [[!DNL Adobe Target] note sulla versione](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=it)

+++

## ![Icona](/assets/campaign.png) [!DNL Campaign] {#ac}

Scarica gli aggiornamenti più recenti per [!DNL Adobe Campaign]. Trova ad Experience League nuovi tutorial, corsi e articoli di supporto della Knowledge Base.

+++Dettagli

### Ultime versioni di Campaign

Vai qui per scoprire le funzionalità, i miglioramenti e le correzioni più recenti in [!DNL Adobe Campaign]:

Scopri le funzionalità, i miglioramenti e le correzioni più recenti nelle note sulla versione di [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=it), [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/releases/release-notes.html?lang=it) e [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=it).

### Nuovi corsi e tutorial su [!DNL Campaign] {#tutorials-campaign}

Nuovi video, tutorial o corsi pubblicati su Adobe Campaign.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazioni |
| -----------| ---------- | ---------- | ---------- |---------- |
| Febbraio 2023 | _Dieci best practice per il successo Adobe Campaign per gli addetti al marketing_ | Articolo | Scopri le dieci best practice per aiutare i professionisti di Adobe Campaign a sfruttare e accelerare la trasformazione digitale del consumatore e una migliore esperienza per i loro clienti. | Consulta: <ul><li>[Campaign v8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/strategy/10-best-practices-for-marketers.html?lang=it)<li>[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/strategy/10-best-practices-for-marketers.html?lang=it)</li><li>[Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/strategy/10-best-practices-for-marketers.html?lang=it) |

{style="table-layout:auto"}

### [!DNL Campaign] knowledge base di supporto

Nuovi articoli e aggiornamenti ad articoli esistenti per [!DNL Adobe Campaign].

| Data di pubblicazione | Nome | Tipo | Descrizione |
|---------|----|----|-----------|
| Febbraio 2023 | [TLS 1.3 è supportato?](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21516.html?lang=it) | Nuovo articolo | Scopri lo stato di supporto di TLS 1.3. |
| Febbraio 2023 | [Gli aggiornamenti API a profili e servizi non vengono visualizzati](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21517.html?lang=it) | Nuovo articolo | Scopri la soluzione al problema per cui le API non vengono aggiornate quando pubblichi le modifiche personalizzate delle risorse agli attributi a testo lungo nelle versioni recenti di ACS. |

{style="table-layout:auto"}

### Risorse dell’Aiuto di [!DNL Campaign]

* [!DNL Campaign] V8: [Documentazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=it) - [Guide all’implementazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/config/implement/implement.html?lang=it)
* [!DNL Campaign] Standard: [Documentazione Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=it) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=it) - [Pianificazione delle versioni future](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=it)
* [!DNL Campaign] Classic: [Documentazione Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=it) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=it)
* [!DNL Campaign] Pannello di controllo: [Documentazione](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=it) - Video dimostrativi per [Video dimostrativi](https://experienceleague.adobe.com/docs/control-panel-learn/tutorials/control-panel-overview.html?lang=it)

+++

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Journey Optimizer] {#journey-opt}

Informazioni sull’ultima versione di [!DNL Journey Optimizer]. Visualizza ad Experience League le esercitazioni e gli articoli di supporto della Knowledge Base più recenti.

+++Dettagli

### Ultime versioni del prodotto [!DNL Journey Optimizer]

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle [Note sulla versione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it).

### Nuovi corsi e tutorial su [!DNL Journey Optimizer] {#tutorials-ajo}

Nuovi video, tutorial o corsi pubblicati su Adobe [!DNL Journey Optimizer].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Marzo 2023 | [Configurare una sandbox di formazione](https://experienceleague.adobe.com/docs/journey-optimizer-learn/configure-a-training-sandbox/introduction-and-prerequisites.html?lang=en) | Tutorial | Scopri come configurare una sandbox a scopo di formazione. Segui i passaggi necessari per configurare gli schemi, acquisire dati di esempio e creare eventi. |
| Marzo 2023 | [Sfide Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/introduction-and-prerequisites.html?lang=en) | Sfide | Le sfide forniscono uno scenario e i requisiti necessari per mettere in pratica ciò che hai imparato. Ogni sfida risolve un caso d’uso univoco implementato dall’utente. <p>Nuove sfide:<ul><li>[Crea un annuncio sulla collezione estiva](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/summer-collection-announcement-challenge.html?lang=en)     </li><li>[Creare una conferma dell’ordine](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/order-confirmation-challenge.html?lang=en)</li></ul> |

{style="table-layout:auto"}

### [!DNL Journey Optimizer] knowledge base di supporto

Nuovi articoli e aggiornamenti ad articoli esistenti per [!DNL Adobe Journey Optimizer].

| Data di pubblicazione | Nome | Tipo | Descrizione |
|---------|-------|--------|---------|
| Febbraio 2023 | [Opt-in non nella pagina di destinazione](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21416.html?lang=it) | Nuovo articolo | Trova la soluzione per il problema in cui le opzioni di consenso non sono presenti nella pagina di destinazione. |
| Febbraio 2023 | [Notifiche del flusso di dati mancanti](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21415.html?lang=it) | Nuovo articolo | Trova la soluzione per il problema in cui non ricevi notifiche sui flussi di dati. |

{style="table-layout:auto"}

### Altre risorse per [!DNL Journey Optimizer]

* [Documentazione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=it)
* [Documentazione di Decision Management](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=it)

+++

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Accedi alle ultime note sulla versione, ad Journey Orchestration su Experience League.

+++Dettagli

### Ultime versioni dei prodotti [!DNL Journey Orchestration]

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle Note sulla versione di [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it).

#### Altre risorse per [!DNL Journey Orchestration]

* [Documentazione del Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it)

* [Note sulla versione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it)

* [Video sulle procedure](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=it)

* [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=it)

+++

## ![Icona](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

Scopri le ultime note sulla versione e la pianificazione della versione per [!DNL Marketo Engage].

+++Dettagli

### Aggiornamenti principali di Marketo Engage

* Vedi [Marzo 2023 - note sulla versione corrente](https://experienceleague.adobe.com/docs/marketo/using/release-notes/current.html?lang=it) per informazioni aggiornate
* Per informazioni aggiornate sulla pianificazione delle versioni e sulle relative note sulla versione, consulta la [pianificazione delle versioni](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=it) di [!DNL Marketo Engage].

<!-- ### New Marketo tutorials and courses {#tutorials-marketo}

New videos, tutorials, or courses published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|August 2022 |[Marketo Engage tutorials](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en)|Videos |Visit the [Marketo Engage tutorial home](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) on Experience League for all past and new tutorials for Marketo Engage.|

{style="table-layout:auto"} -->

Per la documentazione più recente sul prodotto, consulta la Home della [Documentazione del prodotto Marketo](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=it)

+++

## ![Icona](/assets/workfront.png) [!DNL Workfront] {#workfront}

Scopri le ultime note sulla versione di [!DNL Adobe Workfront]. Trova nuove esercitazioni su Experience League.

+++Dettagli

<!-- ### New Adobe [!DNL Workfront] courses and tutorials {#tutorials-workfront}

New [!DNL Workfront] course and collections of tutorials on Experience League.

**Note:** Translation on Experience League for all [[!DNL Workfront]](https://experienceleague.adobe.com/docs/workfront.html?lang=en) tutorials and product documentation is coming soon!

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2023|[Take charge of an existing Adobe Workfront instance](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/system-perfomance-and-maintenance/take-charge-of-an-existing-workfront-instance.html?lang=en)|Video |Learn the key phases to evaluate, understand, and optimize your instance of [!DNL Workfront] as a new system or group administrator.|
|February 2023|[Customize project headers with layout templates](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-project-headers-with-layout-templates.html)|Video |Learn how to add and remove fields from project headers through layout templates.|

{style="table-layout:auto"} -->

Per una raccolta delle informazioni più recenti per tutti i prodotti, consulta la pagina delle [[!DNL Workfront] versioni di prodotto](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html?lang=it).

+++

## ![Icona](/assets/advertising-cloud.png) Adobe Advertising {#advertising}

Note sulla versione di [!DNL Adobe Advertising].

+++Dettagli

<!-- * [New features across [!DNL Advertising]](#advertising-all) -->
* [Nuove funzioni in  [!DNL Advertising DSP]](#advertising-dsp)
* [Nuove funzioni in  [!DNL Advertising Search]](#advertising-search)
<!-- * [New [!DNL Advertising] tutorials](#tutorials-advertising) -->

<!--
### New features across [!DNL Advertising] {#advertising-all}

Last updated: **August 9, 2022**

| Feature | Description |
| ------- | ----------- |
| Integration with [!DNL Adobe Analytics] | (August 6 release) Improvements to the data feed that Advertising sends to [!DNL Analytics] result in fewer mismatches between click/cost/impression data from the search engines and related conversion data in [!DNL Analytics]. |

{style="table-layout:auto"}

-->

### Nuove funzioni in [!DNL Advertising DSP] {#advertising-dsp}

Scopri le funzioni più recenti di Adobe Advertising.

Ultimo aggiornamento: **2 marzo 2023**

| Funzione | Descrizione |
| ------- | ----------- |
| [!UICONTROL Campagne] | È ora possibile visualizzare i registri delle modifiche sotto forma di grafico e aggiungere note a qualsiasi voce (rilascio del 15 febbraio). |

{style="table-layout:auto"}

### Nuove funzioni di [!DNL Advertising Search] {#advertising-search}

Ultimo aggiornamento: **2 marzo 2023**

| Funzione | Descrizione |
| ------- | ----------- |
| [!UICONTROL Campagne] | (account Google Ads; funzione beta aperta; Versione del 23 febbraio) Supporto della sincronizzazione in sola lettura per [!DNL Google Ads] le campagne di individuazione sono in modalità beta per tutti gli inserzionisti. Le campagne di individuazione [!UICONTROL Tipo di campagna] &quot;[!UICONTROL Individuazione]&quot; [!UICONTROL Tipo di gruppo di annunci] &quot;[!UICONTROL Individuazione],&quot; e [!UICONTROL Tipo creativo] &quot;[!UICONTROL Annuncio Discovery]&quot; (per annunci a immagine singola) o &quot;[!UICONTROL Annuncio carosello di scoperta]&quot; (per gli annunci carosello con più immagini). È possibile includere le campagne di tipo discovery in portfolio standard e ibridi.<br><br>I dati a livello di annuncio per le campagne di tipo discovery sono disponibili nei rapporti. Per gli inserzionisti con un’integrazione Adobe Analytics, i dati a livello di annuncio sono disponibili in [!DNL Analytics]. Analogamente, i dati di [!DNL Analytics] sono disponibili in [!DNL Search]; i dati vengono inviati utilizzando il parametro di tracciamento `s_kwcid`, indipendentemente dal formato del `s_kwcid` normalmente utilizzato per l’account. Se normalmente utilizzi la versione precedente di `s_kwcid`, i dati di costo/clic e i dati sui profitti vengono tracciati utilizzando `s_kwcids` diversi, ma entrambi i set di dati sono completamente classificati e aggregati nella stessa campagna e nello stesso account. |
|  | ([!DNL Google Ads] conti; Versione dell’11 febbraio) Supporto per &quot;[!UICONTROL Condivisione immagini di Target]&quot; la strategia di offerta è ora disponibile solo per le campagne sulla rete di ricerca. Per questa strategia di offerta, [!DNL Google Ads] (non [!DNL Search]) ottimizza le offerte al fine di raggiungere una quota di impression target e una posizione dell’annuncio. Facoltativamente, è possibile inserire un [!UICONTROL Condivisione immagini di Target] come percentuale [!UICONTROL Posizione dell’annuncio di Target]e [!UICONTROL Max CPC] (costo per clic). Questa opzione non è ancora supportata nei portfolio ibridi. |
| [!UICONTROL Bulksheet] | ([!DNL Microsoft] campagne; Versione dell’11 febbraio) I bulksheet ora includono &quot;[!UICONTROL Invito all&#39;azione]&quot; e &quot;[!UICONTROL Lingua dell&#39;invito all&#39;azione]&quot; colonne per gli annunci multimediali (in formato annuncio reattivo), che utilizzano il &quot;[!UICONTROL Creative (eccetto RSA)]&quot; riga. |
| Account di Google Manager | Nuovo (rilascio del 23 febbraio) [!UICONTROL Amministratore] > [!UICONTROL Account Manager] consente di fornire l’autenticazione per [!DNL Google Ads] conti di gestione a cui [!DNL Search] carica conversioni tra account diversi. Utilizzare questa funzione se si desidera a) caricare [!DNL Adobe]metriche di conversione incrociate tracciate su un [!DNL Google Ads] account manager o b) carica gli obiettivi del portfolio che includono conversioni tra account in [!DNL Google Ads] per l&#39;ottimizzazione ibrida.<br><br>Una volta aggiunte le credenziali per un account manager, l&#39;opzione &quot;[!UICONTROL Account Manager per le conversioni tra account]&quot; nella colonna [!UICONTROL Campagne] > [!UICONTROL Account] visualizza indica l&#39;ID account manager per ogni account figlio e la colonna mostra un errore quando l&#39;account manager non è autenticato. |

{style="table-layout:auto"}

+++

## ![Icona](/assets/document-cloud-24.png) [!DNL Document Cloud] {#doc-cloud}

Nuovi tutorial e corsi pubblicati per [!DNL Document Cloud], inclusi [!DNL Document Services] e [!DNL Acrobat Sign].

+++Dettagli

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazione |
| -----------| ---------- | ---------- | ---------- |---------- |
| Marzo 2023 | [Invio di documenti per la notarizzazione](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/notarize/send-document-notarize.html?lang=en) | Video | Scopri come inviare un documento per la notarizzazione, visualizzare l’esperienza del firmatario e ricevere i risultati. | Acrobat Sign |

{style="table-layout:auto"}

Per la guida di [!DNL Document Cloud], consulta:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=it)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=it)
* [Formazione e supporto per Document Cloud](https://helpx.adobe.com/it/support/document-cloud.html)

+++

<!-- ## ![Icon](/assets/creative-cloud-24.png) [!DNL Creative Cloud] for enterprise {#creative-cloud}

New videos, tutorials, or courses published for [!DNL Creative Cloud] for enterprise.

+++Details

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2023|[Professional motion graphics templates](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/videooverview/videotutorials/motion-graphics-templates.html?lang=en)|PDF tutorial|Using the Essential Graphics workflow in Adobe After Effects and Adobe Premiere Pro, editors can import MOGRTs and set properties. Properties include text, fonts, color, size, speed, or layout editable, while maintaining the sequence's consistent look and design.|
|January 2023|[Collaboration: The Future of Creativity](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/collaboration-the-future-of-creativity.html?lang=en)|PDF tutorial |Get free access to more than 20,000 professionally designed and curated fonts from Adobe Fonts. Originally known as Typekit, Adobe Fonts are available through a single licensing agreement that gives designers unlimited creative use for personal or commercial projects.|
|January 2023|[3D design and rendering](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/substance-3d-stager.html?lang=en)|PDF tutorial |Import content, arrange your scene, apply materials and textures, adjust image-based and physical lighting, save cameras with different resolutions, and render photorealistic imagery - all in Adobe Substance 3D Stager.|
|January 2023|[Adobe Express: Content that stands out](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/adobe-express-content-that-stands-out.html?lang=en)|PDF tutorial |Create beautiful graphics, web pages, and video stories in minutes with Adobe Express (formerly known as Adobe Spark). Working from thousands of professionally designed templates, make social posts and stories, flyers, logos, booklets, posters, and more. Start for free, and make content that always stands out.|

{style="table-layout:auto"} 

See [Creative Cloud for enterprise tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.

+++
-->

<!-- ## ![Icon](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) is your destination as a customer data management technical and marketing practice leader and specialist. This collection of tutorials is your one-stop-shop to hear from your peers, get inspired, and learn about developments in MarTech. No registration required, simply click and watch.

## ![Icon](/assets/experience-league.png) Digital Experience Blueprints {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) are repeatable implementations that let you address strategy and quickly solve established business problems. Each Blueprint provides a series of artifacts that explain the high-value business problem, architectures, implementation steps, technical considerations, and links to the relevant documentation.

### New Digital Experience Blueprints tutorials

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2023|[Customer Journeys - AEP + Apps & AJO Architecture](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en)|Diagram updates|Deliver individual, just-in-time customer experiences across screens.| 
-->

