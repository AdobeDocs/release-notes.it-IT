---
title: Note sulla versione più recente
description: Scopri le note sulla versione più recente, le nuove funzioni e la nuova documentazione dei prodotti e servizi  [!DNL Experience Cloud] . Trova nuove guide e tutorial su [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] e [!DNL Document Cloud].
doc-type: release notes
last-update: May 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8ddc70389416b26d1cd0c6be5a60c1d34f2cc954
workflow-type: tm+mt
source-wordcount: '4974'
ht-degree: 50%

---

# Note sulla versione di Adobe Experience Cloud - maggio 2022

![Banner](assets/experience-cloud-banner-3.png)

In qualità di creatore di esperienza, il tuo percorso per il successo inizia con [Adobe Experience League](https://experienceleague.adobe.com/?lang=it#home). Consulta una vasta libreria di documentazione, esercitazioni guidate, video dimostrativi e corsi per tutti i livelli e i ruoli, una community online di colleghi e supporto esperto quando necessario.

Pronti per iniziare? [Vinci con un quiz di 5 minuti](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)

>[!NOTE]
>
>Per ricevere una notifica e-mail mensile sugli aggiornamenti di questa pagina, abbonati ad [Aggiornamento sui prodotti priority Adobe](https://www.adobe.com/subscription/priority-product-update.html). Torna spesso a controllare per essere sempre al corrente delle novità di Experience League.

Ultimo aggiornamento: **13 maggio 2022**

* [Eventi di [!DNL Experience League]](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - Componenti dell’interfaccia centrale e amministrazione](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience Blueprint: tutorial](#blueprints)

Hai bisogno di aiuto? Visita [Adobe Experience League](https://experienceleague.adobe.com/?lang=it#home) per trovare documentazione tecnica e di prodotto, corsi curati da Adobe, tutorial video, risposte rapide, approfondimenti sulla community e corsi di formazione condotti da istruttori.

## ![Icona](/assets/experience-league.png) Eventi di [!DNL Experience League] {#events}

Gli eventi di Experience League offrono l’occasione di imparare, interagire e ricevere risposte dagli esperti di prodotto di Adobe.

Aggiornato il **13 maggio 2022**

| Evento | Tipo | Descrizione |
| -----------|---------- | ----|
| [Adobe Analytics - Experience Makers - Lo scambio di competenze](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) | Lo scambio di competenze | Partecipa a questo evento digitale gratuito di tre ore interamente dedicato ad Adobe Analytics. Fai domande in diretta con esperti e colleghi che conoscono meglio Workspace.<br>18 maggio 2022 @ 1:30pm-4:30pm EST<br> [Dettagli e registrazione](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) |
| [Adobe Campaign - Serie di webinar Customer Success](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) | Peer2Peer: Miglioramento dei Percorsi dei clienti tramite Adobe Campaign. | Partecipa a questa discussione in diretta Peer2Peer con Anja Starun, responsabile delle operazioni di coinvolgimento attraverso i marchi Kayo, Binge e Flash di Streamotion. Ascolta direttamente da lei le strategie di successo che il suo team ha implementato per creare percorsi di clienti personalizzati utilizzando Adobe Campaign. <br>**Data:** 26 maggio alle 15.00 EST <br>[Dettagli e registrazione](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) |
| [Notifiche push con Journey Optimizer - Come configurare facilmente la tua app mobile per il push](https://www.youtube.com/watch?v=t36Xjhukmro) | Experience League LIVE  | Scopri i casi d’uso comuni per le notifiche push con Adobe Journey Optimizer e come configurare un’app per push con tecnologia Adobe Experience Platform . <br>**Data:** 12 maggio 2022 alle 9:30 PDT<br>[Pianificazione ed eventi passati](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=it) |
| [Community Adobe Target](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940#M3096) | Q&amp;A Coffee Break | Partecipa a Brent Kostak e Drew Burns del team di prodotto Adobe Target che può rispondere alle tue domande Adobe Target su tipi di pubblico condivisi, Real-Time CDP, dati di prime parti, flussi di lavoro di personalizzazione end-to-end e altro ancora.<br>Guarda il recente [Webinar sulla personalizzazione in tempo reale](https://experienceleaguecommunities.adobe.com:443/t5/adobe-target-discussions/webinar-recording-4-28-22-real-time-personalization-with-adobe/td-p/449012) e rivolgiti agli esperti per le domande successive sulle [Filo di rottura del caffè](https://adobe.ly/3MyiDHa) nella community Adobe Target!<br>**Data:** 25 maggio 2022 alle 8 PDT<br>[Dettagli e registrazione](https://adobe.ly/3MyiDHa) |
| [Adobe [!DNL Developers Live]: Commerce](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | Video on-demand | _Adobe Developers Live: Commerce 2022_ riunisce sviluppatori e sviluppatori di esperienze con background diversi e uno scopo unico, per creare esperienze end-to-end incredibili. Questa conferenza virtuale di un giorno presenta importanti aggiornamenti per gli sviluppatori di Commerce e Open Source, sessioni tecniche, opportunità di rete per la community e altro ancora. |
| [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Video on-demand | Scopri l’importanza della roadmap di Marketo e come evitare una pianificazione scorretta. Ottieni consigli su come sbloccare il potenziale dei campi personalizzati dei membri del programma, suggerimenti e trucchi per i Marketi Engage e molto altro ancora nel [!DNL Marketo] Skill Exchange dall&#39;agosto 2021, ora ad Experience League. |
| [Adobe Summit 2022](https://business.adobe.com/summit/adobe-summit.html) | Sessioni on-demand | Impara dai dirigenti di Adobe, Ryan Reynolds, Rosalind Brewer, CEO, Walgreens Boots Alliance, Inc, John Donahoe, CEO, NIKE, Inc., e Gail J. McGovern, CEO, American Red Cross mentre discutono di come le esperienze dei clienti siano la valuta della nostra economia digitale.<br>Esplora le [sessioni on-demand](https://business.adobe.com/summit/2022/sessions.html) dall’Adobe Summit 2022. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi di Adobe. Consulta [status.adobe.com](https://status.adobe.com/it).

Per informazioni sulla versione più recente, consulta le [note sulla versione](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=it#status) di Adobe System Status.

## ![Icona](/assets/ec_appicon_24.png) Experience Cloud: componenti e amministrazione dell’interfaccia centrale {#ecloud}

I [componenti dell’interfaccia utente centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=it) di Experience Cloud includono le funzioni disponibili nella home page e l’intestazione persistente del prodotto. Queste funzioni includono le impostazioni del profilo utente, le preferenze e la ricerca. Puoi anche trovare aiuto sulla gestione di utenti e prodotti, sugli attributi del cliente e sui tipi di pubblico di Experience Cloud.

Non aggiornato.

**Altre risorse di aiuto su [!DNL Experience Cloud Central UI Components] e amministrazione**

* [Note sulla versione](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=it) per i componenti dell’interfaccia utente centrale di Experience Cloud
* [Gestione di utenti e prodotti](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) per Experience Cloud (amministrazione)
* [Note sulla versione](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=it) di Places Service 
* Documentazione del prodotto per [Persone - Attributi del cliente e libreria del pubblico](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=it)
* [Ricerca unificata di oggetti ed entità](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Informazioni sull’ultima versione e documentazione per [!DNL Experience Platform] e [!UICONTROL SDK di Mobile]:

Data di rilascio prevista: **25 maggio 2022**

* [Note sulla versione di Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=it)

### Nuovi corsi e tutorial su [!DNL Experience Platform] {#tutorials-platform}

Nuovi tutorial, articoli e corsi pubblicati per [!DNL Experience Platform].

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazione |
| -----------| ---------- | ---------- | ---------- |---------- |
| Maggio 2022 | [Approfondimenti pre-condivisione della corrispondenza dei segmenti](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-pre-share-insights.html) | Video | Quando decidi un partner strategico con cui condividere i dati, è importante sapere in che modo i clienti si combinano, in modo da sapere quanto sarà utile tale condivisione. Segment Match (Corrispondenza segmento) consente di visualizzare la sovrapposizione con potenziali partner dati prima di condividere qualsiasi dato. | [!DNL Real-time Customer Data Platform] |
| Maggio 2022 | [Impostazione connessione di corrispondenza segmento](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-connection-setup.html?lang=en) | Video | scopri come impostare la connessione tra te e un partner in modo da poter condividere i tipi di pubblico. Dopo aver configurato questa funzione, potrai condividere i dati avanti e indietro con il tuo partner dati. | [!DNL Real-time Customer Data Platform] |
| Maggio 2022 | [Governance dei dati di corrispondenza dei segmenti](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-data-governance.html?lang=en) | Video | Scopri come impostare e utilizzare i controlli di governance dei dati in Real-Time CDP in modo da poter limitare quali set di dati (e quindi quali segmenti utilizzano tali set di dati) possono essere condivisi con i partner di dati. | [!DNL Real-time Customer Data Platform] |
| Maggio 2022 | [Flusso di configurazione della corrispondenza del segmento](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-configuration-flow.html?lang=en) | Video | Scopri il processo di configurazione di un [!UICONTROL Corrispondenza segmento] istanza per una condivisione di dati. | [!DNL Real-time Customer Data Platform] |
| Maggio 2022 | [Connessione alle destinazioni](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/connecting-to-destinations.html) | Video | Prima di poter inviare dati ai partner di destinazione da Real-time CDP, devi prima effettuare le connessioni a tali partner. Questo video illustra il processo, in genere eseguito dagli amministratori. | [!DNL Real-time Customer Data Platform] |
| Maggio 2022 | [Creare schemi](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html) | Video | Questo video mostra come creare schemi in Adobe Experience Platform utilizzando la classe Profilo individuale XDM e vari gruppi di campi. | Experience Platform |
| Maggio 2022 | [Analizzare e visualizzare informazioni omni-channel in Tableau utilizzando Query Service](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/analyze-and-visualize.html) | Video | Scopri come utilizzare Adobe Experience Platform’s Query Service con strumenti di visualizzazione dati esterni utilizzando un esempio di analisi di abbandono. | Experience Platform |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consulta le [note sulla versione e registri di modifica](https://aep-sdks.gitbook.io/docs/release-notes) per gli SDK di Adobe Experience Platform Mobile.

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data di rilascio: **18 maggio 2022**

* [Note sulla versione ](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=it)di Adobe Analytics
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/analytics.html?lang=it) di Adobe Analytics

### AppMeasurement {#appm}

Versione di rilascio: **2.22.4**

* [Note sulla versione di AppMeasurement per JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=it)

### Nuovi corsi e tutorial su [!DNL Analytics] {#tutorials-analytics}

Nuovi tutorial, articoli e corsi pubblicati per Adobe Analytics.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Maggio 2022 | [Guida introduttiva a Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/get-started-with-report-builder.html?lang=en) | Video | Scopri le nozioni di base sull’utilizzo di Report Builder, incluse l’installazione, l’accesso e le richieste di dati. |
| Maggio 2022 | [Passa alla nuova pagina di destinazione](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/navigating-the-new-landing-page.html?lang=en) | Video | Scopri come sfruttare al meglio la nuova pagina di destinazione di Analytics e le relative funzioni. |
| Maggio 2022 | [Pannelli e rapporti dell’area di lavoro Successivo/Precedente e Riepilogo pagina](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/next-previous-and-page-summary-workspace-panels-reports.html) | Video | Consulta i due nuovi tipi di pannelli in Analysis Workspace: Successivo/Precedente e Riepilogo pagina. Queste soluzioni mettono Workspace in parit à con alcuni dei più popolari [!UICONTROL Reports &amp; Analytics] rapporti. |
| Maggio 2022 | [Aggiornamenti delle pagine di destinazione di Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-landing-page-updates.html?lang=en) | Video | Scopri alcuni dei grandi miglioramenti e aggiunte alla nuova pagina di destinazione. Abbiamo raccolto il feedback dei clienti e cercato di incorporare le funzioni più importanti come il ridimensionamento delle colonne, i nuovi tipi di colonna, i collegamenti ai rapporti in tempo reale e bot e molti altri. |
| Maggio 2022 | [State facendo le domande giuste?](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/are-you-asking-the-right-questions.html) | Video | Scopri in che modo è più utile identificare e raccogliere i punti dati utilizzabili che registrare ogni elemento possibile. L&#39;identificazione efficiente di tali punti di dati richiede un piano di base e discussioni creative con le parti interessate. |
| Maggio 2022 | [Utilizzo [!UICONTROL Report Builder] opzioni di consegna avanzate per Power BI](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/use-report-builder-advanced-delivery-options-for-power-bi.html?lang=en) | Video | Scopri come impostare una pianificazione avanzata per inviare una cartella di lavoro di Report Builder a Power BI. |
| Maggio 2022 | [Pianificazione di una richiesta di Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/schedule-a-report-builder-request.html?lang=en) | Video | Scopri come impostare una pianificazione di base per una cartella di lavoro di Report Builder. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Data di rilascio: **18 maggio 2022**

* [Note sulla versione](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=it) di Customer Journey Analytics
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=it) di Customer Journey Analytics

## ![Icona](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Ultimo aggiornamento: **23 marzo 2022**

* [!DNL Streaming Media Analytics][Note sulla versione di ](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=it)
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=it) di [!DNL Streaming Media Analytics]

<!-- ### New Customer Journey Analytics tutorials and courses {#tutorials-cja}

New video tutorials, articles, and courses published for Customer Journey Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2022|[Overview of configuring Data Views for Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en)|Video |Learn about configuring [!UICONTROL Data Views] for Customer Journey Analytics. [!UICONTROL Data Views] are similar to [!UICONTROL Virtual Report Suites] in Adobe Analytics. They allow you to configure the incoming data so that it can be most useful for your reporting and analysis. |
|April 2022|[Connections Details Experience in CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en)|Video |Learn how to check the status of your connection’s datasets and of the ingestion process.|
-->

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Correzioni e miglioramenti in Audience Manager:

| Miglioramenti | Descrizione |
| -----------| ---------- |  
| Convalida per le origini dati di destinazione appartenenti ad altre società | In Audience Manager è stato migliorato il [processo di onboarding dei dati in batch](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=it). Per evitare l’onboarding accidentale di file e dati nelle origini dati target di proprietà di altri partner, Audience Manager ora prevede un requisito di mappatura tra l’ID partner (PID) e le origini dati (DPID) di proprietà di altri partner. <ul><li>Consulta anche il campo __DPID_TARGET_DATA_OWNER_ in [Requisiti di nome e dimensione file Amazon S3 per i file di dati in entrata](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=it#name-elements).</li><li>Per informazioni sul nuovo miglioramento relativo alla mappatura necessaria, e su come richiederne una, i consulenti interni ad Adobe e l’assistenza clienti possono consultare [Gestire l’accesso all’onboarding per i dati di seconde parti](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=it).</li><li>_Non_ è necessario per richiedere la mappatura per le relazioni di condivisione dei dati esistenti. Inoltre, la mappatura _non_ è richiesta quando si inseriscono dati in origini dati di destinazione che appartengono al tuo PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Per risorse di supporto autonomo, consulta [Documentazione e tutorial di Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=it) in Experience League.

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Nuove funzioni, correzioni e aggiornamenti di Experience Manager. Ai clienti con implementazioni on-premise, Adobe consiglia di implementare le ultime patch in modo da garantire stabilità, protezione e prestazioni migliori.

Per gli ultimi aggiornamenti sulle varie versioni, visita regolarmente la pagina [Aggiornamenti e roadmap delle versioni di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=it).

### Rilasci di prodotti Experience Manager

* **Experience Manager as a Cloud Service**

   Guarda il [Video introduttivo sulla versione di aprile 2022](https://video.tv.adobe.com/v/342612?quality=12) per un riepilogo delle funzioni aggiunte nella versione 2022.4.0 (aprile 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [Video introduttivo sulla versione di marzo 2022](https://video.tv.adobe.com/v/341465).
   * [Video introduttivo sulla versione di gennaio 2022](https://video.tv.adobe.com/v/340120).
   * [Video introduttivo sulla versione di dicembre 2021](https://video.tv.adobe.com/v/339278).
   * [Video introduttivo sulla versione di ottobre 2021](https://video.tv.adobe.com/v/338253).
   * [Video introduttivo sulla versione di settembre 2021](https://video.tv.adobe.com/v/337381).

* **Experience Manager Sites as a Cloud Service**

   _Nuova funzionalità_

   * È ora possibile definire i tipi di dati del modello di contenuto come [traducibile](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/content-fragments/content-fragments-models.html?lang=en#properties) utilizzando una casella di controllo nell’editor del modello di contenuto. Inoltre, le regole e le configurazioni di traduzione di Experience Manager vengono aggiornate automaticamente.

   _Nuova funzione nel canale prerelease_

   * Pubblicare frammenti esperienza in Anteprima : per visualizzare in anteprima le esperienze finali che possono essere visualizzate dai visitatori, puoi pubblicare frammenti esperienza autonomi in Experience Manager as a Cloud Service Preview Service.


* **Experience Manager Assets as a Cloud Service**

   _Nuova funzionalità_

   * Ora puoi [ordinare tag](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=it#use-tags-to-organize-assets) nella finestra del selettore tag in ordine crescente o decrescente in base al nome del tag, alla data di creazione o alla data di modifica.

* **Experience Manager Forms as a Cloud Service**

   _Nuove funzionalità_

   * **Comunicazioni - Supporto delle API di manipolazione documenti nell’SDK as a Cloud Service di Forms** - [API di manipolazione documenti](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=it) combinare, ridisporre e convalidare i documenti PDF. Ora puoi utilizzare le API Communications - Document Generation in un ambiente di sviluppo locale con l’aiuto dell’SDK as a Cloud Service di Experience Manager Forms.
   * **Utilizza XCI personalizzato per generare un documento di record** - Ora è possibile [utilizzare un file XCI personalizzato per impostare varie proprietà di un documento di registrazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html?lang=en#use-a-custom-xci-file). Sostituisce l’XCI principale con le modifiche personalizzate. Offre un maggiore controllo sulla generazione di documenti di record, aumentando le opportunità di personalizzazione e personalizzazione.
   * **Utilizzare il CAPTCHA invisibile in un modulo adattivo** - È possibile utilizzare [CAPTCHA invisibile per mostrare la sfida CAPTCHA solo se c&#39;è attività sospetta](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/add-components-to-an-adaptive-form/captcha-adaptive-forms.html?lang=en). Se non viene trovata alcuna attività sospetta, la sfida CAPTCHA non viene visualizzata. Consente di valutare il completamento dei moduli senza bisogno di caselle di controllo, ridurre le operazioni di personalizzazione e migliorare l’esperienza dell’utente finale.
   * **Configurazioni del modello dati del modulo** - Ora è possibile [riutilizzo delle configurazioni del modello dati modulo in ambienti diversi](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/create-form-data-models.html?lang=en#runmode-specific-context-aware-config), semplificando le integrazioni di dati e riducendo i costi IT.

* **Experience Manager Screens as a Cloud Service**

   _Nuova funzionalità_

   * Assegnazione dei canali di massa : gli utenti possono selezionare più canali e assegnarli a più visualizzazioni contemporaneamente, in un&#39;unica operazione.

* **Fondamenti di Experience Manager as a Cloud Service**

   _**SDK Build Analyzer**_

   Il plug-in Maven di Experience Manager as a Cloud Service Build Analyzer SDK rileva i problemi in un progetto Maven, incluse le dipendenze mancanti. Offre agli sviluppatori l’opportunità di scoprire i problemi durante lo sviluppo locale, molto prima di distribuirli in ambienti Cloud con Cloud Manager.

   È stato aggiunto di recente un nuovo analizzatore:

   * content-packages-validation : convalida della sintassi e della struttura dei contenuti ben formate per i pacchetti installati durante la distribuzione.
   Adobe consiglia di aggiornare il progetto maven con l’ultima versione dell’analizzatore o di includere l’analizzatore, se non lo hai ancora fatto. Consulta la sezione [documentazione](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=it) per ulteriori informazioni.

* **Cloud Manager**

   _Nuove funzioni_

   * La pagina Ambienti dispone di una colonna per visualizzare l’Experience Manager Versione dell’ambiente.
   * L’esecuzione della pipeline ora visualizza gli errori di primo livello dell’interfaccia utente nella schermata di esecuzione.
   * Esegui nuovamente il passaggio di distribuzione della produzione tramite l’interfaccia utente di Cloud Manager.
   * Riutilizza le immagini di build per eseguire nuovamente il passaggio di distribuzione di produzione.
   * Nuova API per consentire l’eliminazione self-service dell’infrastruttura di rete.

* **Best Practices Analyzer**

   _Nuove funzioni_

   * Possibilità di rilevare e creare rapporti sull’utilizzo delle API di Asset Manager non supportate. Ci sono quattro API che non sono più supportate in Experience Manager as a Cloud Service. I clienti devono assicurarsi di non utilizzare più queste API e devono utilizzare il nuovo metodo di caricamento delle risorse.
   * Possibilità di rilevare l’utilizzo di modelli di frammenti di contenuto. I modelli per frammenti di contenuto non sono più supportati per la creazione di nuovi frammenti di contenuto in Experience Manager as a Cloud Service. Per sostituire i modelli di frammento di contenuto, i clienti devono creare modelli di frammento di contenuto.
   * Possibilità di rilevare le risorse con più di 100 discendenti sotto il nodo di metadati della risorsa nell’archivio. Adobe consiglia di rimuovere i nodi di metadati non necessari, per migliorare le prestazioni durante il caricamento delle cartelle costituite da tali risorse.
   * Possibilità di rilevare e segnalare il tipo di archivio dati utilizzato.
   * Pattern aggiornato per Experience Manager Form Portal.

### Community

* **Webinar Experience Manager GEM registrato**

   * [_Integrare il framework AEM e CIF per creare un&#39;esperienza di e-commerce ricca e coinvolgente_](https://adobe.ly/3jorz5r).

* Experience Manager as a Cloud Service [Aggiornamento sulla versione 2022.4.0](https://adobe.ly/3LO0gOo).

### Nuovi corsi ed esercitazioni su Experience Manager {#tutorials-aem}

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazioni |
| -----------| ---------- | ---------- | ---------- | ------|
| Maggio 2022 | [Aggiornamento AEM versione 2021.4.0 di as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2021/2021-4-0.html?lang=en) | Video | Ascolta il team AEM di prodotto e scopri le funzionalità e le innovazioni per l’ultima versione di Adobe Experience Manager. | AEM Asset Essentials, Sites, Screens, Forms e Cloud Foundation |
| Maggio 2022 | [Cloud 5 AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-introduction.html) | Video | Ottieni tutte le informazioni utili AEM as a Cloud Service in brevi video di 5 minuti o meno. Inizia con la prima stagione. | AEM CS |
| Maggio 2022 | [Ottenimento di un token di accesso per le integrazioni](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-getting-login-token-integrations.html) | Video | Una guida dettagliata su come ottenere un token di accesso per le integrazioni di Cloud Service e alcuni casi d’uso per farlo. | AEM CS |
| Maggio 2022 | [Visualizzare più documenti pdf in un carosello](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/display-pdf-in-carousel.html?lang=en) | Video | Scopri il caso d’uso comune per la visualizzazione di più documenti PDF al compilatore da esaminare prima di inviare il modulo. | AEM Forms |
| Maggio 2022 | [Immagini con AEM headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/images.html) | Video | Scopri come sviluppare un’esperienza ricca e coinvolgente AEM headless utilizzando immagini e altro ancora. | AEM Headless |
| Maggio 2022 | [Rich text con AEM headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/localized-content.html) | Video | Scopri come utilizzare il campo di testo su più righe, un tipo di dati Frammenti di contenuto che consente agli autori di creare contenuti di testo RTF. | AEM senza testa |
| Maggio 2022 | [Indirizzo IP in uscita dedicato](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html?lang=it) | Video | Scopri come impostare e utilizzare l’indirizzo IP in uscita dedicato, che consente alle connessioni in uscita da AEM di provenire da un IP dedicato. | AEM CS |
| Maggio 2022 | [Implementazione del codice](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/deploy-code.html) | Video | Scopri come distribuire il codice in Produzione utilizzando le pipeline di Cloud Manager in AEM as a Cloud Service. | AEM CS, Cloud Manager |
| Maggio 2022 | [Disattiva l’esecuzione del flusso di lavoro di post-elaborazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/asset-microservices-configure-and-use.html#disable-post-processing-workflow-execution) | Documentazione | Scopri come creare un modello di flusso di lavoro vuoto nella sezione Flusso di lavoro con avvio automatico quando non è necessaria la post-elaborazione. | AEM CS |
| Maggio 2022 | [Filigrane](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/watermarks.html?lang=en) | Video | AEM le funzionalità as a Cloud Service di watermarking consentono di applicare alle rappresentazioni personalizzate delle immagini una filigrana utilizzando qualsiasi immagine PNG. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Informazioni sulla versione di Experience Manager

Nelle pagine seguenti trovi tutte le note sulla versione di Experience Manager:

* [Informazioni sulla versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=it)
* [Note sulla versione di Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=it)
* [Note sulla versione del Servizio di conversione automatica dei moduli](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=it)
* [Note sulla versione di Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=it)
* [Note sulla versione dell’app desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=it)
* [Note sulla versione di Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=it)
* [Note sulla versione di Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=it)
* [Note sulla versione di Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=it)

### Altre risorse di assistenza per Experience Manager

* [Guide di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=it)
* [Guida utente di Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=it)
* [Formazione e supporto per Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=it)
* [Formazione e supporto per Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=it)
* [Formazione e supporto per Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it)
* [Formazione e supporto per Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=it#previous-updates)
* [Documentazione delle versioni precedenti di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Pagina iniziale della guida di Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=it)
* [Documentazione di Experience Manager: ultimi aggiornamenti](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=it#aem-as-a-cloud-service)

## ![Icona](/assets/ec_appicon_24.png) Documentazione XML per Adobe Experience Manager {#xml-doc}

Documentazione XML per Adobe Experience Manager è un’applicazione distribuita su AEM. Si tratta di una potente soluzione di gestione dei contenuti per componenti di livello aziendale (CCMS) che consente il supporto DITA nativo in Adobe Experience Manager, permettendo ad AEM di gestire la creazione e la distribuzione di contenuti basati su DITA.

Ulteriori informazioni su [XML Documentation for AEM](https://www.adobe.com/it/products/xml-documentation-for-experience-manager/features.html).

### Risorse aggiuntive

* [Documentazione XML per Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=it): tutorial su Experience League
* [Informazioni e supporto su Documentazione XML per Adobe Experience Manager](https://helpx.adobe.com/it/support/xml-documentation-for-experience-manager.html): documentazione di prodotto

## ![Icona](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Consulta i seguenti collegamenti per le note sulla versione di Adobe Commerce:

* [Note sulla versione di Adobe Commerce e Magenti Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Note sulla versione per Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Icona](/assets/target.png) [!DNL Adobe Target] {#target}

Ultimo aggiornamento: **9 maggio 2022**

* Per informazioni pre-release, consulta [Adobe Target prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=it)
* Per informazioni aggiornate, consulta [Note sulla versione di Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=it)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Ultime versioni di Campaign

Ulteriori informazioni sulle funzionalità, i miglioramenti e le correzioni più recenti nel [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=it), [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=it)e [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=it) note sulla versione.

### Risorse per Campaign

* Adobe Campaign v8: [Documentazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guide all’implementazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=it)
* Adobe Campaign Standard: [Documentazione Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=it) - [Piano delle versioni future](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=it)
* Adobe Campaign Classic: [Documentazione Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=it)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=it)  - Video introduttivi per [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=it) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer puoi gestire campagne omnichannel pianificate e momenti “uno a uno” per milioni di clienti da una singola applicazione, ottimizzando l’intero percorso con decisioni intelligenti e informazioni approfondite.

### Ultime versioni del prodotto Journey Optimizer

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle [Note sulla versione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it).

### Corsi e tutorial su Journey Optimizer {#tutorials-ajo}

Ultimi tutorial su Journey Optimizer:

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Maggio 2022 | [Creare regole di decisione](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-rules.html?lang=en) | Video | Scopri come creare regole di decisione per la gestione delle decisioni. Regole o _norme decisionali_ sono uno dei componenti di base richiesti per le offerte personalizzate. |
| Maggio 2022 | [Creare posizionamenti](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-placements.html) | Video | Scopri come creare posizionamenti per la gestione delle decisioni. I posizionamenti sono uno degli elementi principali delle offerte. Un posizionamento è la combinazione di tipo di contenuto e canale, ad esempio un’immagine in un messaggio e-mail o un codice HTML in un sito web. |
| Maggio 2022 | [Creare decisioni](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-decisions.html) | Video | Scopri come creare decisioni per la gestione delle decisioni. Una decisione combina posizionamenti e raccolte in un’unica entità, in modo che sia possibile determinare l’offerta più rilevante da fornire al cliente. |
| Maggio 2022 | [Distribuisci le offerte con l’API dell’hub Decisions](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/deliver-offers-with-the-decisions-api.html) | Video | Scopri come distribuire le offerte con l’API dell’hub Decisions. |
| Maggio 2022 | [Creare offerte di fallback](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-fallback-offers.html) | Video | Scopri come creare offerte di fallback per la gestione delle decisioni. Le offerte di fallback sono offerte predefinite che vengono mostrate ai clienti che non si qualificano per nessuna delle offerte personalizzate. |
| Maggio 2022 | [Creare raccolte](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-collections.html?lang=en) | Video | Scopri come creare raccolte per la gestione delle decisioni. Le raccolte vengono utilizzate per gestire le offerte in gruppi logici e devono essere create per le attività di gestione delle decisioni |

{style=&quot;table-layout:auto&quot;}

### Altre risorse per [!DNL Journey Optimizer]

* [Documentazione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=it)
* [Documentazione di Decision Management](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilizza Experience Platform per orchestrare il percorso di un cliente su grande scala tra i diversi canali di esperienza, anticipando in modo intelligente le esigenze di ogni cliente in tempo reale.

### Ultime versioni dei prodotti [!DNL Journey Orchestration]

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle note sulla versione di [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it).

#### Altre risorse per [!DNL Journey Orchestration]

* [Documentazione di Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=it)

## ![Icona](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per chi si occupa di lead management e B2B e intende trasformare le esperienze dei clienti coinvolgendoli in ogni fase di complessi percorsi d’acquisto.

Nuovi eventi video pubblicati sull&#39;Experience League:

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Maggio 2022 | [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Video | Inizia con scoprire la roadmap di Marketo. Quindi, scopri l’importanza di considerare la tua istanza Marketo come un prodotto. Ottieni consigli su come sbloccare il potenziale dei campi personalizzati dei membri del programma, suggerimenti e trucchi per i Marketi Engage e altro ancora, in questa nuova pubblicazione [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) dall&#39;agosto 2021, ora all&#39;Experience League. |

### Aggiornamenti principali di Marketo Engage

Per informazioni aggiornate sulla pianificazione delle versioni e sulle relative note sulla versione, consulta [!DNL Marketo Engage] [- Pianificazione delle versioni](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=it).

## ![Icona](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] è un’applicazione unificata di gestione del lavoro per condividere idee, creare contenuti, gestire processi complessi e lavorare al meglio.

Per una raccolta delle informazioni più recenti per tutti i prodotti, consulta la pagina delle versioni di [[!DNL Workfront] ](https://one.workfront.com/s/product-releases).

## ![Icona](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Note sulla versione di [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Nuove funzioni in  [!DNL Advertising Cloud Search]](#adcloud-search)

<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

<!--
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

### Nuove funzioni in [!DNL Advertising Cloud Search] {#adcloud-search}

Ultimo aggiornamento: **** 12 maggio 2022 per la versione del 14 maggio

| Funzione | Descrizione |
| ------- | ----------- |
| [!UICONTROL Campagne] | Le seguenti funzionalità beta sono disponibili per tutti gli inserzionisti:<ul><li>([!DNL Microsoft® Advertising] account) Supporto per sincronizzazione, visibilità di sola lettura e reporting (inclusi i dati di visualizzazione) per le campagne pubblicitarie native esistenti sul [!DNL Microsoft® Audience Network], tra cui [!DNL Microsoft® Audience Ads].</li><li>([!DNL Google Ads] e [!DNL Microsoft® Advertising] account) Possibilità di importare [!DNL Google Ads] campagne e struttura della campagna in [!DNL Microsoft® Advertising] da [!UICONTROL Ricerca] > [!UICONTROL Strumenti] > [!UICONTROL Importa campagne beta].<br><br>Dopo aver importato le campagne, puoi controllare lo stato del processo di importazione, esaminare tutti i registri degli errori e modificare, mettere in pausa o eliminare la pianificazione delle importazioni.</li></ul> |
| [!UICONTROL Campagne]<br><br>[!UICONTROL Portfoli] | ([!DNL Microsoft® Advertising] campagne) Le seguenti strategie di offerta sono ora disponibili per tutti gli utenti:<ul><li>[!UICONTROL Condivisione immagini di Target]: Puoi configurare le campagne con questa strategia e, facoltativamente, impostare una condivisione di impression target, una posizione dell’annuncio target e un costo massimo per clic. Attenzione: Questa opzione non è ancora supportata nei portfolio ibridi e non può essere aggiunta ai portfolio standard.</li><li>[!UICONTROL Massimizza clic]: Puoi configurare le campagne con questa strategia e, facoltativamente, impostare un costo massimo per clic. Puoi includere le campagne con questa strategia in portfolio standard o ibridi. Per utilizzare questa strategia in un portafoglio ibrido, l&#39;obiettivo del portafoglio deve includere solo [!DNL Adobe] proprietà (metriche) e devi abilitare il caricamento degli obiettivi di Advertising Cloud Search in [!DNL Microsoft® Ads].</li></ul> |
| Integrazione con Adobe Analytics | (7 aprile) Nel feed di dati che Advertising Cloud invia a [!DNL Analytics], dati per [!DNL Google Ads] gli annunci per ricerca dinamica sono disponibili solo a livello di gruppo di annunci a partire dal 7 maggio 2022. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuovi tutorial e corsi pubblicati per Adobe Document Cloud.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazione |
| -----------| ---------- | ---------- | ---------- |---------- |
| Maggio 2022 | [Condivisione dell&#39;accesso all&#39;account](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/share-account-access.html) | Video | Scopri come impostare l’accesso in sola visualizzazione alle transazioni nel conto di un altro utente. | [!DNL Acrobat Sign] |
| Maggio 2022 | [Gestione dei modelli di documento](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/edit-a-template.html?lang=en) | Video | Scopri come modificare o eliminare un modello nella libreria. | [!DNL Acrobat Sign] |
| Maggio 2022 | [Crea il tuo primo flusso in Microsoft® Power Automation](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/create-workflow-power-automate.html?lang=en) | Articolo | Scopri come creare il tuo primo flusso in Microsoft® Power Automate utilizzando il connettore Adobe PDF Services. | Document Services |
| Maggio 2022 | [Recupero credenziali per Microsoft® Power Automate](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/getting-credentials-power-automate.html?lang=en) | Articolo | Scopri come ottenere le credenziali per iniziare a utilizzare o provare Adobe PDF Services. A seconda che tu sia un utente di prova o un cliente esistente, questo tutorial illustra i passaggi appropriati per ottenere le credenziali. | Servizi basati su documenti |

{style=&quot;table-layout:auto&quot;}

Per Document Cloud, consulta:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=it)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=it)
* [Formazione e supporto per Document Cloud](https://helpx.adobe.com/it/support/document-cloud.html)

## ![Icona](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

Per i tutorial più recenti, consulta i [tutorial Creative Cloud for enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=it).

## ![Icon](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=it) raccoglie contenuti di interesse sulla gestione dei dati cliente per tutti i leader e specialisti tecnici e di marketing. Questa raccolta di tutorial rappresenta un punto di riferimento dove potrai sentire cosa dicono altri professionisti come te, trarre spunti e scoprire le novità in ambito MarTech. Non è necessario registrarsi: basta fare clic e guardare.

## ![Icona](/assets/experience-league.png) Blueprint per esperienze digitali {#blueprints}

[I blueprint di esperienze digitali](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=it) sono implementazioni ripetibili per affrontare strategie e risolvere problemi di business consolidati. Ogni Blueprint offre una serie di artefatti che spiegano il problema di business di alto valore, le architetture, le fasi di implementazione, le considerazioni tecniche e i collegamenti alla documentazione pertinente.

[superiore](#events)
