---
title: Note sulla versione più recente
description: Scopri le note sulla versione più recente, le nuove funzioni e la nuova documentazione dei  [!DNL Experience Cloud]  prodotti e servizi. Trova nuove guide e tutorial su [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] e [!DNL Document Cloud].
doc-type: release notes
last-update: April 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 68df02857374608feb9ae1c848b6ca1357d73382
workflow-type: tm+mt
source-wordcount: '6428'
ht-degree: 43%

---

# Note sulla versione di Adobe Experience Cloud - aprile 2022

![Banner](assets/experience-cloud-banner-3.png)

In qualità di creatore di esperienza, il tuo percorso per il successo inizia con [Adobe Experience League](https://experienceleague.adobe.com/?lang=it#home). Trova una vasta libreria di documentazione, esercitazioni guidate, video dimostrativi e corsi per tutti i livelli e i ruoli, una community online di colleghi e una porta di supporto esperti quando necessario.

Pronti per iniziare? [Vinci con un quiz di 5 minuti](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)

>[!NOTE]
>
>Per ricevere una notifica e-mail mensile sugli aggiornamenti di questa pagina, abbonati ad [Aggiornamento sui prodotti priority Adobe](https://www.adobe.com/subscription/priority-product-update.html). Torna spesso a controllare per essere sempre al corrente delle novità di Experience League.

Ultimo aggiornamento: **22 aprile 2022**

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
* [[!DNL Adobe Commerce]](#commerce)
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

Aggiornato **5 aprile 2022**

| Evento | Tipo | Descrizione |
| -----------|---------- | ----|
| [Adobe Summit 2022](https://business.adobe.com/summit/adobe-summit.html) | Sessioni on-demand | Imparare dai dirigenti di Adobe, Ryan Reynolds, Rosalind Brewer, CEO, Walgreens Boots Alliance, Inc, John Donahoe, CEO, NIKE, Inc., e Gail J. McGovern, CEO, American Red Cross come condividono come le esperienze dei clienti sono la valuta della nostra economia digitale.<br>Esplora [sessioni on-demand](https://business.adobe.com/summit/2022/sessions.html) dall&#39;Adobe Summit 2022. |
| [AEM da headful a Headless (e tutto nel mezzo)](https://www.youtube.com/watch?v=idByz7WrhbQ) | Experience League LIVE  | Guarda un dettaglio delle implementazioni Adobe Experience Manager Sites più comuni con l&#39;ospite Danny Gordon e gli ospiti Amol Anand, Sachin Mali e Sean Steimer. <br>**Data:** 21 aprile 2022 @ 9 PDT<br>[Pianificazione ed eventi passati](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=it) |
| [Come posso gestire tutti questi tipi di pubblico?](https://www.youtube.com/watch?v=I8HKFkx16-E) | Experience League LIVE  | Definizione della strategia del pubblico tramite CDP in Audience Manager e in tempo reale. L&#39;ospite Doug Moore accoglie Nick Cammuso e Jackie Chevallier in questo evento Experience League LIVE.<br>**Data:** 28 aprile 2022 @ 9 PDT<br>[Pianificazione ed eventi passati](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [Adobe Campaign Classic v7 e Campaign v8](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic/adobe-campaign-community-q-amp-a-coffee-break-april-21st-8am-pt/td-p/444060) | Interruzione caffè Q&amp;A | Unisciti a Scott Segrin, Eric Knee, David Loyd e Peter Mancuso - Adobe Campaign Enterprise Architecture Team nella community Adobe Campaign per una serie di domande e risposte live.<br>**Data:** 21 aprile 2022 @ 8 PDT<br>[Dettagli e registrazione](https://adobe.ly/3NB6kuG) |
| [Community Adobe Target](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940#M3096) | Interruzione caffè Q&amp;A | Jim McTiernan risponde alle tue domande su Adobe Target Recommendations, AB Testing e Personalizzazione MVT nella community Adobe Target <br>**Data:** 27 aprile 2022 @ 8 PDT<br>[Dettagli e registrazione](https://adobe.ly/3joCuvU%C2%A0) |
| [Framework AEM e CIF](https://adobe.ly/3O0uXl5) | AEM Gems | Integrare il framework AEM e CIF per creare un&#39;esperienza di e-commerce ricca e coinvolgente <br>**Data:** 27 aprile 2022 @ 8:00 PDT / 5:00 p.m. CET / 8:30 p.m. IST<br>[Dettagli e registrazione](https://adobe.ly/3O0uXl5) |
| [AEM Gems](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/overview.html?lang=en) | Webinar Adobe Live | Sono disponibili gli aggiornamenti AEM Gems per il 2022! AEM Gems è la serie webinar di Adobe di approfondimenti tecnici su Adobe Experience Manager, fornita da esperti Adobi. <br>Per gli ultimi AEM Gems, vedi [Adobe Experience Manager as a Cloud Service: Recensione 2021 e Outlook 2022](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aemcloudservice-2021-review-and-outlook.html?lang=en) e [Creare siti più rapidamente con AEM Headless e App Builder](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/build-sites-faster-with-headless-and-appbuilder.html?lang=en).<br>Visita frequentemente queste note sulla versione o abbonati al [Adobe di aggiornamento prioritario del prodotto](https://www.adobe.com/subscription/priority-product-update.html) per stare al di sopra di AEM Gems e altri eventi Experienci League. |
| [Experience Makers - The Skill Exchange for Adobe Workfront](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Webinar Adobe Live | L&#39;Adobe è entusiasta di annunciare la prima edizione di _Experience Makers - Lo scambio di competenze per Adobe Workfront_. <br>Questo evento di apprendimento digitale gratuito di tre ore è interamente incentrato su Workfront. Puoi fare domande a esperti e colleghi che conoscono meglio la gestione del lavoro. Consigliato per tutti, principianti o utenti esperti di Workfront.<br>**Data:** Mercoledì 13 aprile alle 9.00 - 12:00 PDT [Dettagli e registrazione](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true): Adobe consiglia di registrarsi anche se non è possibile partecipare, in modo da garantire l&#39;accesso alle registrazioni on-demand. |
| [Adobe Workfront System Admin Essentials: Progettazione di un’esperienza utente ideale](https://webinars.on24.com/adobe_workfront/AdminEssentialsUserExp?partnerref=field) | Webinar Adobe Live | Unisciti a Mary Ann Erickson, Customer Success Manager di Adobe Workfront, e Steve Enos, Creative Operations Analyst di Liberty Mutual Insurance per scoprire come progettare un&#39;esperienza utente ideale. <br>**Data:** Mercoledì 27 aprile. Ora: 8:00 PDT / 4:00pm UK. <br>[Dettagli e registrazione](https://webinars.on24.com/adobe_workfront/AdminEssentialsUserExp?partnerref=field) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=it) | Video on-demand | [!DNL Developers Live] presenta i progressi tecnologici più recenti e strumenti per sviluppatori che supportano la progettazione, i flussi di lavoro per la creazione di contenuti, i servizi di documentazione e la gestione dell’esperienza dei clienti nei vari settori. Visualizza l’indirizzo keynote, scopri le API di Analytics, il livello dati client, i progetti open source di Adobe Developer e molto altro. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fornisce informazioni dettagliate, aggiornamenti sullo stato e notifiche e-mail relative agli eventi di sospensione, interruzione e manutenzione di prodotti e servizi di Adobe. Consulta [status.adobe.com](https://status.adobe.com/it).

Per informazioni sulla versione più recente, consulta le [note sulla versione](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=it#status) di Adobe System Status.

## ![Icona](/assets/ec_appicon_24.png) Experience Cloud: componenti e amministrazione dell’interfaccia centrale {#ecloud}

I [componenti dell’interfaccia utente centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=it) di Experience Cloud includono le funzioni disponibili nella home page e l’intestazione persistente del prodotto. Queste funzioni includono le impostazioni del profilo utente, le preferenze e la ricerca. Puoi anche trovare aiuto sulla gestione di utenti e prodotti, sugli attributi del cliente e sui tipi di pubblico di Experience Cloud.

| Funzione | Descrizione |
| ------- |-------|
| Ricerca nella lingua naturale | Puoi trovare risposte immediate a tutte le tue domande di aiuto tramite un’unica interfaccia tramite Unified Search. Questa funzione è sempre disponibile su ogni pagina di Experience Platform e Journey Optimizer. |

{style=&quot;table-layout:auto&quot;}

**Altre risorse di aiuto su [!DNL Experience Cloud Central UI Components] e amministrazione**

* [Note sulla versione](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=it) per i componenti dell’interfaccia utente centrale di Experience Cloud
* [Gestione di utenti e prodotti](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) per Experience Cloud (amministrazione)
* [Note sulla versione](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=it) di Places Service 
* Documentazione del prodotto per [Persone - Attributi del cliente e libreria del pubblico](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=it)
* [Ricerca unificata di oggetti ed entità](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Informazioni sulla versione più recente e nuova documentazione per [!DNL Experience Platform] e [!UICONTROL SDK per dispositivi mobili]:

Data di rilascio: **27 aprile 2022**

* [Note sulla versione di Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=it)

### Nuovi corsi e tutorial su [!DNL Experience Platform] {#tutorials-platform}

Nuove esercitazioni video, articoli e corsi pubblicati per [!DNL Experience Platform].

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Aprile 2022 | [Guida introduttiva di Privacy Service in Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2021.1.prvsvc) | Corso | Scopri le funzionalità di base di Adobe Experience Platform [!UICONTROL Privacy Service], tra cui come preparare i dati per le operazioni sulla privacy e inviare le richieste sulla privacy dei clienti al servizio. |
| Aprile 2022 | [API server di rete Adobe Experience Platform Edge](https://experienceleague.adobe.com/docs/platform-learn/data-collection/server-api/overview.html) | Video | Scopri i vantaggi dell’invio di dati a Platform [!UICONTROL Rete Edge] utilizzando un’API server sicura e autenticata. |
| Aprile 2022 | [Registri di controllo](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-governance/audit-logs.html) | Video | Scopri come la funzione dei registri di controllo può aiutarti a soddisfare i tuoi requisiti di conformità e a risolvere i problemi relativi all’implementazione di Adobe Experience Platform. |
| Aprile 2022 | [Preparazione per la raccolta dei dati](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/data-prep.html) | Video | Scopri come aggiungere il livello dati a un nuovo datastream in [!UICONTROL Raccolta dati]. Inoltre, scopri come eseguire le funzioni di mappatura di base utilizzando [!UICONTROL Preparazione per la raccolta dei dati] funzionalità. |
| Aprile 2022 | [Prendi in considerazione lo spostamento di tag fornitore lato client all’inoltro eventi](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/consider-moving-tags.html) | Video | Scopri come valutare un tag fornitore lato client per spostarlo potenzialmente in una proprietà di inoltro eventi. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consulta le [note sulla versione e registri di modifica](https://aep-sdks.gitbook.io/docs/release-notes) per gli SDK di Adobe Experience Platform Mobile.

## ![Icona](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data di rilascio: **20 aprile 2022**

* Adobe Analytics [note sulla versione](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=it)
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/analytics.html?lang=it) di Adobe Analytics

### AppMeasurement {#appm}

Versione di rilascio: **2.22.4**

* [Note sulla versione di AppMeasurement per JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=it)

### Nuovi corsi e tutorial su [!DNL Analytics] {#tutorials-analytics}

Nuove esercitazioni video, articoli e corsi pubblicati per Adobe Analytics.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Aprile 2022 | [Filtrare i dati con segmentazione personalizzata e date](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.filterdata) | Corso | Scopri come applicare segmenti, creare segmenti personalizzati e utilizzare intervalli di date per lavorare in modo più intelligente nella tua analisi. |
| Aprile 2022 | [Configurare e amministrare suite di rapporti in Adobe Analytics](https://experienceleague.adobe.com/?recommended=Analytics-A-1-2021.1.administration) | Corso | Scopri come impostare elementi di configurazione generali della suite di rapporti, configurare variabili di traffico e conversione, impostare canali di marketing e altro ancora. |
| Aprile 2022 | [Raccontare storie di grande impatto con i dati](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/telling-impactful-stories-with-data.html?lang=en) | Video | La narrazione dei dati è il luogo in cui arte e scienza si riuniscono utilizzando dati, visualizzazioni e narrazioni. Raccontando in modo efficace una storia con i dati, Adobe Analytics può diventare più accessibile a un pubblico più ampio e puoi aumentare il valore che apporti alla tua organizzazione attraverso processi decisionali basati sui dati. |
| Aprile 2022 | [Guadagnare un posto a tavola](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/gaining-a-seat-at-the-table.html?lang=en) | Video | Scopri il tuo ruolo di amministratore di Analytics e scopri come ottenere le competenze necessarie per poter sedere al tavolo decisionale della tua azienda. |
| Aprile 2022 | [Tradurre il linguaggio tecnico Adobe Analytics in modo non tecnico](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/translating-adobe-analytics-technical-language.html?lang=en#) | Video | In qualità di esperto Adobe Analytics della tua organizzazione, sei fondamentale per aiutare le parti interessate a comprendere i dettagli tecnici e trarre il massimo dal tuo investimento Adobe Analytics. |
| Aprile 2022 | [Segmenti rapidi in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/quick-segments-in-analysis-workspace.html?lang=en) | Video | _Segmenti rapidi_ è un’esperienza di segmentazione semplificata direttamente nel [!UICONTROL Area di lavoro] tela. Scopri come creare al volo segmenti con fino a tre regole senza dover uscire dal flusso di lavoro di analisi. |
| Aprile 2022 | [Annotazioni in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/annotations-in-analysis-workspace.html?lang=en) | Video | Scopri come annotare un intervallo di date o date con problemi di dati noti, festività pubbliche e avvii di campagne per informare meglio gli utenti del motivo per cui visualizzano ciò che visualizzano in grafici a linee, tabelle e altro ancora. |
| Aprile 2022 | [Funzionamento interfunzionale](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/working-cross-functionally.html?lang=en) | Video | Scopri da un campione di Adobe Analytics come lavorare in modo interfunzionale all’interno della tua organizzazione. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Data di rilascio: **20 aprile 2022**

* Customer Journey Analytics [note sulla versione](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=it)
* [Documentazione del prodotto e tutorial](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=it) di Customer Journey Analytics

## ![Icona](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Data di rilascio: **20 aprile 2022**

* [!DNL Streaming Media Analytics] [note sulla versione](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=en)  (**nuova posizione**)
* [!DNL Streaming Media Analytics] [documentazione ed esercitazioni del prodotto](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

### Nuovi corsi ed esercitazioni per Customer Journey Analytics {#tutorials-cja}

Nuovi video tutorial, articoli e corsi pubblicati per Customer Journey Analytics.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Aprile 2022 | [Panoramica sulla configurazione delle visualizzazioni dati per Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en) | Video | Informazioni sulla configurazione [!UICONTROL Visualizzazioni dati] per Customer Journey Analytics. [!UICONTROL Visualizzazioni dati] sono simili a [!UICONTROL Suite di rapporti virtuali] in Adobe Analytics. Consentono di configurare i dati in arrivo in modo che possano essere più utili per le attività di reporting e analisi. |
| Aprile 2022 | [Esperienza dei dettagli delle connessioni in CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en) | Video | Scopri come controllare lo stato dei set di dati della connessione e del processo di acquisizione. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/audience-manager.png) Audience Manager {#aam}

Correzioni e miglioramenti in Audience Manager:

| Miglioramenti | Descrizione |
| -----------| ---------- |  
| Convalida per le origini dati di destinazione appartenenti ad altre società | In Audience Manager è stato migliorato il [processo di onboarding dei dati in batch](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=it). Per evitare l’onboarding accidentale di file e dati nelle origini dati target di proprietà di altri partner, Audience Manager ora prevede un requisito di mappatura tra l’ID partner (PID) e le origini dati (DPID) di proprietà di altri partner. <ul><li>Consulta anche il campo __DPID_TARGET_DATA_OWNER_ in [Requisiti di nome e dimensione file Amazon S3 per i file di dati in entrata](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=it#name-elements).</li><li>Per informazioni sul nuovo miglioramento relativo alla mappatura necessaria, e su come richiederne una, i consulenti interni ad Adobe e l’assistenza clienti possono consultare [Gestire l’accesso all’onboarding per i dati di seconde parti](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=it).</li><li>_Non_ è necessario per richiedere la mappatura per le relazioni di condivisione dei dati esistenti. Inoltre, la mappatura _non_ è richiesta quando si inseriscono dati in origini dati di destinazione che appartengono al tuo PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Per risorse di supporto autonomo, consulta [Documentazione e tutorial di Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=it) in Experience League.

## ![Icona](/assets/aem.png) Adobe Experience Manager {#aem}

Per gli ultimi aggiornamenti sulle varie versioni, visita regolarmente la pagina [Aggiornamenti e roadmap delle versioni di Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=it).

### Rilasci di prodotti Experience Manager

* **Experience Manager as a Cloud Service**

   Guarda il [Video di panoramica sulla versione di marzo 2022](https://video.tv.adobe.com/v/341465) per un riepilogo delle funzioni aggiunte nella versione 2022.3.0 (marzo 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [Video di panoramica della versione di gennaio 2022](https://video.tv.adobe.com/v/340120) sulle nuove funzioni.
   * [Video di panoramica sulla versione di dicembre 2021](https://video.tv.adobe.com/v/339278) sulle nuove funzioni.
   * [Video di panoramica della versione di ottobre 2021](https://video.tv.adobe.com/v/338253) sulle nuove funzioni.
   * [Video di panoramica della versione di settembre 2021](https://video.tv.adobe.com/v/337381) sulle nuove funzioni.

* **Experience Manager Assets as a Cloud Service**

   _Nuove funzioni di Assets_

   * Experience Manager Dynamic Media offre ora la flessibilità di [configura un account alias](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=it) nell’interfaccia utente, garantendo così [!UICONTROL Dynamic Media] Gli URL e il codice di incorporamento del visualizzatore vengono aggiornati. Questo aggiornamento influisce positivamente sull’ottimizzazione SEO (Search Engine Optimization) per riflettere gli aggiornamenti apportati al contesto aziendale, ad esempio il rebranding.
   * È ora possibile utilizzare l’interfaccia utente di Experience Manager Assets per:
      * Configura il [rilevamento delle risorse duplicate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets.html?lang=en#detect-duplicate-assets) in un archivio.
      * Configura l’[aggiunta di filigrane digitali](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/watermark-assets.html?lang=en) alle immagini.
   * Gli amministratori possono ora configurare il servizio e-mail per i download di grandi dimensioni. Consente agli utenti di [abilitare le notifiche e-mail per i download di grandi dimensioni](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) dall’interfaccia di Experience Manager Assets. Al termine del processo di download, l’utente riceve una notifica e-mail contenente il link per scaricare la cartella zip archiviata.
   * La funzione [Gestisci pubblicazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en) è stata ottimizzata con un’interfaccia utente migliorata. Un utente può pubblicare o annullare la pubblicazione dei contenuti da e verso la destinazione selezionata, oppure [Aggiungi contenuto](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) all’elenco di pubblicazione dall’archivio DAM. Possono [Includi impostazioni cartella](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) per pubblicare il contenuto delle cartelle selezionate e applicare i filtri, e [pianificazione della pubblicazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) a una data o un&#39;ora successiva.

      _Nuove funzioni nel canale prerelease di Experience Manager Assets_

   * È possibile [ordinare tag](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=en#use-tags-to-organize-assets) durante la creazione di tag avanzati e quando si applicano filtri di ricerca utilizzando il predicato tags.

* **Experience Manager Forms as a Cloud Service**

   _Novità in Forms_

   * **Comunicazioni - API per la generazione di documenti** — [API per la generazione di documenti](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=it) combinare, ridisporre e convalidare i documenti PDF. Il servizio consente di generare documenti in modalità sincrona. Le API consentono di creare applicazioni per eseguire le seguenti operazioni:

      * Assemblare documenti PDF
      * Separare i documenti PDF
      * Convertire e convalidare documenti conformi a PDF/A.
   * **Conversione automatica di PDF forms con più di 15 pagine in moduli adattivi** — È ora possibile utilizzare il servizio automated forms conversion per convertire PDF forms con un massimo di 40 pagine in moduli adattivi. Il servizio ora offre la possibilità di convertire sezioni di moduli con più di 15 pagine in frammenti di modulo adattivi. Consente di migliorare la velocità di rendering dei moduli convertiti e di caricare più facilmente i moduli di grandi dimensioni nell’editor di moduli adattivi.

   _Novità del canale prerelease di Forms_

   * **Utilizza XCI personalizzato per generare un documento di record** — È ora possibile utilizzare un file XCI personalizzato per impostare varie proprietà di un documento di record. Sostituisce l’XCI principale con le modifiche personalizzate.
   * **Utilizzare il CAPTCHA invisibile in un modulo adattivo** — È possibile utilizzare il CAPTCHA invisibile per mostrare la sfida CAPTCHA solo se si trova un&#39;attività sospetta. Se non viene trovata alcuna attività sospetta, la sfida CAPTCHA non viene visualizzata.



* **Componente aggiuntivo CIF**

   _Nuove funzioni_

   * Beta - Experience Manager di supporto per i componenti core CIF per la ricerca supporta Commerce LiveSearch.
   * SEO migliorato per scenari multi-store: i formati URL per PDP/PLP possono ora essere configurati a livello di archivio tramite le proprietà CIF Cloud Config.
   * Il selettore prodotti supporta i prodotti in staging tramite la nuova opzione di filtro nell’interfaccia utente. Questa funzionalità consente ai professionisti dei contenuti di preparare la gestione dei contenuti dei prodotti per i prossimi lanci.
   * Gestione semplificata della configurazione CIF e degli errori utilizzando il nome di configurazione CIF Cloud invece di configurare l’URL proxy.
   * Selezione manuale della categoria per l’elenco dei prodotti e i componenti Carosello. Questa funzionalità consente agli utenti del settore dei contenuti di utilizzare questi componenti sulle pagine di contenuto, al di fuori dell’esperienza di catalogo.

* **Fondamenti di Experience Manager as a Cloud Service**

   _Nuove funzioni_

   * Per una risoluzione più efficiente ed efficace dei problemi relativi alle funzioni personalizzate negli ambienti Cloud, Adobe ha rilasciato un nuovo strumento per sviluppatori: [Browser del repository](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developer-tools/repository-browser.html?lang=en). È un browser HTML leggero e di sola lettura che può essere avviato da Developer Console. Ottieni visibilità nell’archivio dei contenuti sui livelli di pubblicazione, authoring e anteprima e in tutti gli ambienti, compresi produzione, stage e sviluppo. Sfoglia la struttura del contenuto, visualizza le proprietà e visualizza in anteprima e scarica i dati binari.
   * Le credenziali utilizzate per autenticare le chiamate API da server a server (ad esempio, per le richieste API GraphQL) ora possono essere aggiornate prima della scadenza in modo self-service dalla Console per sviluppatori. Consulta la [documentazione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/generating-access-tokens-for-server-side-apis.html?lang=en#refresh-credentials) per ulteriori informazioni.
   * Le attività di manutenzione dell’eliminazione della versione e del registro di controllo, che non erano state precedentemente abilitate, ora sono abilitate per i nuovi ambienti. Vedi i valori associati nell’articolo [Attività di manutenzione](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/maintenance.html?lang=en).
   * Gli strumenti di Dispatcher SDK as a Cloud Service di Experience Manager ora supportano i computer Mac con il chip M1.

* **Cloud Manager**

   _Data di rilascio_

   La data di rilascio per Cloud Manager in Experience Manager as a Cloud Service 2022.02.0 era il 10 febbraio 2022.
La prossima versione è prevista per il 10 marzo 2022.

   _Nuove funzioni_

   * Sono state introdotte nuove [pipeline di configurazione a livello web](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#web-tier-config-pipelines) accelerate per distribuire esclusivamente la configurazione HTTPD/dispatcher.

      * È necessario utilizzare AEM versione `2021.12.6151.20211217T120950Z` o più recenti e [consenso alla modalità flessibile degli strumenti di Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/content-delivery/disp-overview.html?lang=en#validation-debug) per utilizzare questa funzione.
      * Questa funzione è pianificata per l’implementazione in un approccio graduale nelle due settimane successive al rilascio della versione 2022.02.0.
   * L’esperienza della pagina di destinazione di Cloud Manager è stata aggiornata per migliorarne la navigazione e facilitare il passaggio tra le visualizzazioni a griglia o a schede. Inoltre fornisce delle informazioni a comparsa per un rapido riepilogo del programma.
   * Una nuova soglia di errore (`< D`) è stata aggiunta alla [metrica di valutazione dell’affidabilità](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/code-quality-testing.html?lang=en#understanding-code-quality-rules).

      * I clienti con gravi problemi di qualità che influiscono sulla stabilità del sistema, principalmente correlati a indici e processi di flusso di lavoro non validi, non possono distribuire finché tali problemi non vengono risolti.
   * La gravità del BannedPath [regola di qualità](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/code-quality-testing.html?lang=en#understanding-code-quality-rules) è stato modificato da blocker a critico.
   * La procedura guidata della pipeline informa l’utente quando potrebbe essere necessario un aggiornamento dell’ambiente di Experience Manager prima di configurare un [pipeline di configurazione a livello web](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#web-tier-config-pipelines) associato.


### Community

* **Webinar Experience Manager GEMs in arrivo**

   * Argomento: _Integrare il framework AEM e CIF per creare un&#39;esperienza di e-commerce ricca e coinvolgente_
      * Data: Mercoledì 27 aprile 2022
      * Ora: 8:00 PDT / 5:00 p.m. CET / 8:30 IST
      * [Registrati qui](https://adobe.ly/3O0uXl5)
   * Adobe Summit 2022 | Elenco completo delle sessioni e registrazioni [disponibile qui](https://adobe.ly/3rti6gF).

### Nuovi corsi ed esercitazioni su Experience Manager {#tutorials-aem}

Nuovi video, esercitazioni e corsi pubblicati nell’ultimo mese.

| Data di pubblicazione | Nome | Tipo | Descrizione | Prodotto |
| ------| ----- | ------ | ------ |-----|
| Aprile 2022 | [Generazione di documenti tramite l’API di comunicazione](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2022.3.formscs) | Corso | Unisci i dati con il modello xdp richiamando gli endpoint HTTP di Forms CS. | AEM Forms |
| Aprile 2022 | [Assemblare PDF utilizzando l&#39;operazione DDX di richiamo](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-assembler/introduction.html?lang=en) | Video | Repository Browser è un potente strumento che fornisce visibilità AEM&#39;archivio dati sottostante, consentendo un facile debug dell&#39;ambiente as a Cloud Service AEM. Il browser Repository supporta l’analisi di tutte le risorse e proprietà di AEM in Produzione, Stage e Sviluppo, nonché dei servizi Author, Publish e Preview. | AEM CS |
| Aprile 2022 | [Implementa la soluzione per salvare e recuperare le istanze di lettere](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/store-retrieve-letters/introduction.html?lang=en) | Video | Scopri come implementare utilizzando SPI per salvare e recuperare le istanze di lettere della comunicazione interattiva. | AEM Forms |
| Aprile 2022 | [Creazione e convalida di documenti PDF/A](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-assembler/pdfa-utilities.html?lang=en) | Video | Scopri come creare e convalidare documenti PDF/A. PDF/A è una versione standard ISO del formato portatile (PDF) specializzato nell&#39;archiviazione e nella conservazione a lungo termine dei documenti elettronici. | AEM Forms |
| Aprile 2022 | [Integrazione di AEM Forms con [!DNL ServiceNow] ](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/service-now.html?lang=en) | Video | Crea e visualizza un problema in ServiceNow utilizzando il modello dati modulo in AEM Forms. | AEM Forms |
| Aprile 2022 | [Panoramica delle risorse](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/overview.html) | Tutorial | Adobe Experience Manager (AEM) [!DNL Assets] è uno strumento di gestione delle risorse digitali su AEM Platform che consente agli utenti di creare, gestire e condividere le proprie risorse digitali (immagini, video, documenti e clip audio) in un archivio basato su Web. Questa guida utente contiene video ed esercitazioni sulle numerose funzioni e funzionalità di AEM Assets. | AEM Assets |
| Aprile 2022 | [Gestione delle autorizzazioni Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/permissions-management.html) | Video | Scopri come la gestione delle autorizzazioni di AEM Assets Essentials consente alle organizzazioni di controllare l’accesso alle risorse, proteggere il proprio marchio e garantire la conformità. | AEM Assets |
| Aprile 2022 | [Metadati Forms in Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html) | Video | Scopri come Assets Essentials Metadata Forms può essere configurato in modo rapido e semplice per personalizzare la risorsa. | AEM Assets |
| Aprile 2022 | [Utilizzo del testo RTF in Adobe Experience Manager Headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/rich-text.html) | Video | Scopri come lavorare con il testo RTF in AEM Headless. Il campo di testo su più righe è un tipo di dati Frammenti di contenuto che consente di creare contenuti in formato RTF. | AEM Headless |
| Aprile 2022 | [Debug AEM as a Cloud Service con il browser del repository](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/repository-browser.html) | Video | Scopri Repository Browser, uno strumento potente che fornisce visibilità all’archivio dati sottostante di AEM, consentendo un facile debug dell’ambiente as a Cloud Service AEM. | AEM CS |
| Aprile 2022 | [Indirizzo IP in uscita dedicato](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html) | Video | Scopri come impostare e utilizzare l’indirizzo IP in uscita dedicato, che consente alle connessioni in uscita da AEM di provenire da un IP dedicato. | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Informazioni sulla versione di Experience Manager

Nelle pagine seguenti trovi tutte le note sulla versione di Experience Manager:

* [Informazioni sulla versione di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
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

* [Guide di Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
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

### Nuove risorse per Adobe Commerce {#new-commerce}

Nuova documentazione e tutorial per Adobe Commerce su Experience League.

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Aprile 2022 | [Panoramica di Upgrade Compatibility Tool](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade/upgrade-compatibility-tool-overview.html) | Video | Scopri lo strumento di compatibilità per l’aggiornamento e come può aiutarti a identificare rapidamente gli errori e le correzioni necessari per l’aggiornamento a una versione più recente di Adobe Commerce. |
| Aprile 2022 | [Utilizzo dello strumento di compatibilità per l’aggiornamento su PhpStorm](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade/uct-phpstorm.html) | Video | Lo strumento di compatibilità per l’aggiornamento (UCT) è uno strumento gratuito che analizza in pochi minuti le incompatibilità tra la versione corrente e la versione di aggiornamento di destinazione. Adobe fornisce un plugin PhpStorm per rendere lo strumento ancora più facile da usare. |
| Aprile 2022 | [Guida a Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/guide-overview.html) | Documentazione del prodotto | Live Search di Adobe Commerce offre un&#39;esperienza di ricerca rapida, super-rilevante e intuitiva ed è disponibile gratuitamente per Adobe Commerce. |
| Aprile 2022 | [Guida al prodotto Recommendations](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/guide-overview.html) | Documentazione del prodotto | Questa guida è destinata agli amministratori di Adobe Commerce. Include informazioni dettagliate sull&#39;installazione e l&#39;onboarding del Product Recommendations, nonché sulla configurazione e la gestione dei servizi. |
| Aprile 2022 | [[!DNL Site-Wide Analysis Tool]](https://experienceleague.adobe.com/docs/commerce-operations/tools/site-wide-analysis-tool/intro.html?lang=en) | Documentazione | Informazioni complete sui [!DNL Site-Wide Analysis] Strumento, compresi gli usi, il processo di installazione e l&#39;accesso. | Adobe Commerce |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/target.png) [!DNL Adobe Target] {#target}

Ultimo aggiornamento: **21 marzo 2022**

* Per informazioni pre-release, consulta [Adobe Target prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=it)
* Per informazioni aggiornate, consulta [Note sulla versione di Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![Icona](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un modo intuitivo e automatico di inviare messaggi a singoli utenti tra canali di marketing online e offline. Ora è possibile prevedere cosa vogliono i clienti, mediante esperienze determinate dalle loro abitudini e preferenze.

### Ultime versioni di Campaign

Ulteriori informazioni sulle funzionalità, i miglioramenti e le correzioni più recenti nel [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=it), [Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=it) e [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=it) note sulla versione.

### Nuovi corsi e tutorial su [!DNL Campaign] {#tutorials-campaign}

Nuove esercitazioni video e corsi pubblicati per Adobe Campaign.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazioni |
| -----------| ---------- | ---------- | ---------- | ----|
| Aprile 2022 | [Migliorare la consegna e-mail con contenuto di Experience Manager](https://experienceleague.adobe.com/?recommended=Campaign-A-1-2022.v8.aemcontent) | Corso | Scopri come collegare Adobe Campaign V8 con Adobe Experience Manager (AEM) per gestire modelli di consegna e-mail, risorse e moduli in Experience Manager. | Campaign v8, AEM |
| Aprile 2022 | [Traccia di audit](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/monitoring/audit-trail.html?lang=en) | Video | Scopri come accedere ai registri di Audit Trail e quali impostazioni possono essere configurate. | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Risorse per Campaign

* Adobe Campaign v8: [Documentazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guide all’implementazione](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=it)
* Adobe Campaign Standard: [Documentazione Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=it) - [Piano delle versioni future](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=it)
* Adobe Campaign Classic: [Documentazione Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=it)
* Pannello di controllo di Adobe Campaign: [Documentazione](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - Video introduttivi per [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=it) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Con Journey Optimizer puoi gestire campagne omnicanale pianificate e momenti &quot;a uno&quot; per milioni di clienti da una singola applicazione, ottimizzando l’intero percorso con decisioni intelligenti e informazioni approfondite.

### Ultime versioni del prodotto Journey Optimizer

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle [Note sulla versione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=it).

### Corsi e tutorial su Journey Optimizer {#tutorials-ajo}

Ultimi tutorial su Journey Optimizer:

| Data di pubblicazione | Nome | Tipo | Descrizione |
| -----------| ---------- | ---------- | ---------- |
| Aprile 2022 | [Panoramica di Progettazione messaggi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/message-designer-overview.html?lang=en) | Video | Comprendere le caratteristiche e le funzionalità principali di Adobe Journey Optimizer [!UICONTROL Progettazione messaggi]. |
| Aprile 2022 | [Funzionalità mobili per sviluppatori](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/mobile-capabilities-for-developers.html) | Video | Scopri le funzionalità mobili di Adobe Journey Optimizer per gli sviluppatori. |
| Aprile 2022 | [Panoramica di Assets Essentials](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html?lang=en) | Video | Panoramica delle funzioni di Assets Essentials e di come possono essere utilizzate in Adobe Journey Optimizer. |
| Aprile 2022 | [Panoramica sull’area di lavoro del percorso](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/overview-over-the-journey-canvas.html?lang=en) | Video | Comprendere le funzionalità dell’area di lavoro del percorso. |
| Aprile 2022 | [Profilo e segmentazione unificati](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/profiles-segments-subscriptions/unified-profile-and-segmentation-overview.html?lang=en) | Video | Scopri come creare un profilo unificato e quindi segmenti basati sugli attributi del profilo per personalizzare i percorsi dei clienti. |
| Aprile 2022 | [Funzionalità mobili per gli addetti al marketing](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/mobile-capabilities.html) | Video | Scopri le funzionalità mobili di Adobe Journey Optimizer per gli esperti di marketing. |
| Aprile 2022 | [Creare offerte personalizzate](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/create-personalized-offers.html) | Video | Scopri come creare offerte personalizzate in Offer Decisioning. Alle offerte personalizzate vengono associate delle regole di idoneità che consentono di mostrarle solo ai clienti rilevanti. |
| Aprile 2022 | [Creare i tag](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/create-tags.html?lang=en) | Video | Scopri come creare i tag in Offer Decisioning. I tag sono componenti di blocco predefinito facoltativi delle offerte. Possono essere utilizzati per organizzare le offerte e raggrupparle in raccolte dinamiche. |
| Aprile 2022 | [Demo delle funzionalità di gestione delle decisioni](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/demo-of-offer-decisioning.html?lang=en) | Video | Scopri come i brand possono utilizzare le funzionalità di gestione delle decisioni per definire e gestire le loro offerte, applicare dati sui clienti in tempo reale e fornire le esperienze giuste rispetto alle attese dei clienti. |

{style=&quot;table-layout:auto&quot;}

### Altre risorse per [!DNL Journey Optimizer]

* [Documentazione di Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=it)
* [Documentazione di Decision Management](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=it)

## ![Icona](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilizza Experience Platform per orchestrare il percorso di un cliente su grande scala tra i diversi canali di esperienza, anticipando in modo intelligente le esigenze di ogni cliente in tempo reale.

### Ultime versioni dei prodotti [!DNL Journey Orchestration]

Scopri di più sulle funzionalità, i miglioramenti e le correzioni più recenti nelle note sulla versione di [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=it).

#### Altre risorse per [!DNL Journey Orchestration]

* [Documentazione di Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=it) - [Note sulla versione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Video dimostrativi](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=it) - [Ultimi aggiornamenti della documentazione](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=it)

## ![Icona](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] è un’applicazione completa per chi si occupa di lead management e B2B e intende trasformare le esperienze dei clienti coinvolgendoli in ogni fase di complessi percorsi d’acquisto.

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

{style="table-layout:auto"}
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

<!--
{style="table-layout:auto"}
-->

### Nuove funzioni in [!DNL Advertising Cloud Search] {#adcloud-search}

Ultimo aggiornamento: **22 aprile 2022** per la versione del 23 aprile

| Funzione | Descrizione |
| ------- | ----------- |
| [!UICONTROL Audiences] | ([!DNL Microsoft Advertising] account idonei per Customer Match (Corrispondenza cliente) Ora tutti gli utenti possono creare e gestire audience customer match caricando file CSV con indirizzi e-mail. È necessario eseguire l’hashing dei dati con l’algoritmo SHA-256. |
| [!UICONTROL Campagne] | Le seguenti funzionalità beta sono disponibili per gli inserzionisti che effettuano il consenso:<ul><li>([!DNL Microsoft Advertising] account) Supporto per sincronizzazione, visibilità di sola lettura e reporting (inclusi i dati di visualizzazione) per le campagne pubblicitarie native esistenti sul [!DNL Microsoft Audience Network], tra cui [!DNL Microsoft Audience Ads].</li><li>([!DNL Google Ads] e [!DNL Microsoft Advertising] account) Possibilità di importare [!DNL Google Ads] campagne e struttura della campagna in [!DNL Microsoft Advertising] da Advertising Cloud Search.</li></ul>Contatta il tuo Adobe Account Manager se sei interessato a entrambi i programmi beta. |
| [!UICONTROL Campagne]<br><br>[!UICONTROL Portfoli] | ([!DNL Microsoft Advertising] campagne) Il supporto è disponibile per le seguenti strategie di offerta:<ul><li>(Disponibilità generale) [!UICONTROL Massimizza conversioni], [!UICONTROL CPA di destinazione]e [!UICONTROL Rendimento di Target sulla spesa pubblicitaria]: Queste strategie sono ora a disposizione di tutti. Puoi aggiungere campagne di ricerca con questa strategia di offerta a portfolio ibridi (ma non standard).</li><li>(funzione Beta) [!UICONTROL Condivisione immagini di Target]: Se stai partecipando alla versione beta dell’ottimizzazione ibrida, puoi configurare le campagne con questa strategia e facoltativamente impostare una condivisione delle impression target, una posizione pubblicitaria target e un costo massimo per clic. Attenzione: Questa opzione non è ancora supportata nei portfolio ibridi e non può essere aggiunta ai portfolio standard.</li><li>(funzione Beta) [!UICONTROL Massimizza clic]: Se stai partecipando alla versione beta dell’ottimizzazione ibrida, puoi configurare le campagne con questa strategia e facoltativamente impostare un costo massimo di destinazione per clic. Puoi includere le campagne con questa strategia in portfolio standard o ibridi. Per utilizzare questa strategia in un portafoglio ibrido, l&#39;obiettivo del portafoglio deve includere solo [!DNL Adobe] proprietà (metriche) e devi abilitare il caricamento degli obiettivi di Advertising Cloud Search in [!DNL Microsoft Ads].</li></ul>Se non stai già partecipando alla versione beta dell&#39;ottimizzazione ibrida e desideri partecipare, contatta il tuo [!DNL Adobe] account manager. |
| [!UICONTROL Insight sulla pubblicità] | Tutte le informazioni tranne [!UICONTROL Corrispondenza tra query] e [!UICONTROL Preparazione alla configurazione del Portfolio ibrido] sono ora fuori versione beta. |
| [!UICONTROL Campagne]<br><br>[!UICONTROL Approfondimenti sulla pubblicità] | (11 aprile) [!DNL Google Ads] account) Advertising Cloud Search ha eseguito la transizione di tutte le chiamate API dalla versione precedente [!DNL Google AdWords API] al più tardi [!DNL Google Ads API]. Passare alla nuova [!DNL Google Ads API] assicura la continuità con le funzionalità esistenti e consente l&#39;accesso [!DNL Google’s] più recente [!DNL Ads] funzionalità.<br><br>Alcune funzionalità non sono ancora state aggiornate alla nuova API e sono temporaneamente non disponibili:<ul><li>Estensioni posizione:<ul>Le estensioni della posizione non sono visibili nel [!UICONTROL Estensioni] visualizza.</li><li>Non puoi creare un&#39;estensione.</li><li>I filtri sulle posizioni non funzionano.</li></li></ul><li>[!UICONTROL Approfondimenti sulla pubblicità]: La [!UICONTROL Quota impression perduta] e [!UICONTROL Query Cross Matching Beta] le analisi non sono disponibili.</li></ul>Prevediamo di ripristinare le funzionalità di estensione della posizione entro la fine di aprile. Una volta stabilito quando l&#39;interessato [!UICONTROL Approfondimenti sulla pubblicità] i moduli possono anche essere ripristinati, invieremo un aggiornamento con la data stimata. |
| Integrazione con Adobe Analytics | (7 aprile) Nel feed di dati che Advertising Cloud invia a [!DNL Analytics], dati per [!DNL Google Ads] e [!DNL Microsoft Advertising] gli annunci adattabili alla ricerca (RSA, responsive search ads) vengono riclassificati con il [!UICONTROL Tipo di annuncio] &quot;[!UICONTROL Annunci di ricerca reattivi]&quot; quando ricevono nuovi clic. In precedenza, i dati venivano inclusi per [!UICONTROL Tipo di annuncio] &quot;[!UICONTROL Annunci di testo].&quot; Le RSA nelle campagne inattive non verranno riclassificate.<br><br>Per gli RSA riclassificati, la [!UICONTROL Titolo dell’annuncio reattivo] ora viene compilato con il primo titolo e il [!UICONTROL Descrizione dell&#39;annuncio reattivo] viene compilato con la prima descrizione. |

{style=&quot;table-layout:auto&quot;}

## ![Icona](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nuovi tutorial e corsi pubblicati per Adobe Document Cloud.

| Data di pubblicazione | Nome | Tipo | Descrizione | Applicazione |
| -----------| ---------- | ---------- | ---------- | -----|
| Aprile 2022 | [Guida introduttiva ad Adobe Acrobat](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.1.acrobatgetstarted) | Corso | Scopri perché oltre 5 milioni di organizzazioni in tutto il mondo si rivolgono ad Acrobat per creare documenti digitali senza precedenti che portano avanti le attività. Scopri nuovi modi per automatizzare i flussi di lavoro manuali per i documenti e creare esperienze coinvolgenti. | Adobe Acrobat |
| Aprile 2022 | [Attività avanzate in Adobe Acrobat](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.1.advancedtasks) | Corso | Acquisisci competenze Acrobat di livello superiore con tecniche avanzate per la modifica, l’utilizzo dei moduli, l’ottimizzazione e l’automazione delle attività. Scopri come automatizzare i flussi di lavoro manuali per i documenti, proteggere le informazioni aziendali sensibili e fornire esperienze eccezionali con i file PDF. | Adobe Acrobat |
| Aprile 2022 | [Modifica di un documento dopo l’invio](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/modify-in-flight.html?lang=en) | Video | Scopri come modificare un documento già inviato per la firma, ad esempio quando il documento sbagliato viene inviato per errore. | Adobe Acrobat Sign |
| Aprile 2022 | [Impostazione dell’ordine di firma](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/setting-up-routing.html?lang=en) | Video | Scopri come impostare l’ordine di firma per più firmatari. Inviare un documento in sequenza e/o in parallelo o a specifici gruppi di singoli utenti. | Adobe Acrobat Sign |
| Aprile 2022 | [Sostituzione di un firmatario](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/replace-signer.html) | Video | Scopri come sostituire un firmatario, ad esempio quando è stata utilizzata l’e-mail errata durante l’invio di un documento per la firma. | Adobe Acrobat Sign |
| Aprile 2022 | [Accelerare il processo di vendita](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/acceleratesales.html) | Corso | Scopri come Adobe Document Services è in grado di integrare le esperienze dei documenti in questo percorso per accelerare le vendite. | Document Services |
| Aprile 2022 | [Automatizzare i flussi di lavoro legali](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/automatelegalworkflows.html) | Articolo | Scopri come gestire ed eseguire in modo sicuro i termini dell’accordo utilizzando modelli predefiniti che cambiano in base alla lingua approvata. | Servizi basati su documenti |
| Aprile 2022 | [Modernizzazione dell&#39;onboarding dei dipendenti](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/employeeonboarding.html) | Video | Scopri come modernizzare l’onboarding dei dipendenti con le API di Adobe Document Services. | Servizi basati su documenti |

{style=&quot;table-layout:auto&quot;}

Per Document Cloud, consulta:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=it)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=it)
* [Formazione e supporto per Document Cloud](https://helpx.adobe.com/it/support/document-cloud.html)

## ![Icona](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

Per i tutorial più recenti, consulta i [tutorial Creative Cloud for enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=it).

## ![Icon](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) raccoglie contenuti di interesse sulla gestione dei dati cliente per tutti i leader e specialisti tecnici e di marketing. Questa raccolta di tutorial rappresenta un punto di riferimento dove potrai sentire cosa dicono altri professionisti come te, trarre spunti e scoprire le novità in ambito MarTech. Non è necessario registrarsi: basta fare clic e guardare.

## ![Icona](/assets/experience-league.png) Blueprint per esperienze digitali {#blueprints}

[I blueprint di esperienze digitali](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=it) sono implementazioni ripetibili per affrontare strategie e risolvere problemi di business consolidati. Ogni Blueprint offre una serie di artefatti che spiegano il problema di business di alto valore, le architetture, le fasi di implementazione, le considerazioni tecniche e i collegamenti alla documentazione pertinente.

[Top](#events)
