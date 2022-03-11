---
title: Nozioni fondamentali sulla scadenza del numero di serie Creative Cloud for enterprise e Acrobat
description: Esperienza di scadenza del numero di serie per Creative Cloud for enterprise e Acrobat
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# Nozioni fondamentali sulla scadenza del numero di serie Creative Cloud for enterprise e Acrobat

Storicamente, Adobe ha assegnato numeri di serie con le nostre app (ad es. Creative Suite, Creative Cloud for enterprise, Acrobat XI, Acrobat DC) ai clienti con gli Enterprise Term License Agreement (ETLA). Questi numeri di serie hanno una data di scadenza. Una volta passata la data di scadenza, il prodotto non funzionerà più ed è importante pianificare la migrazione prima della scadenza dei numeri di serie. Questa pagina descrive i passaggi necessari per garantire che gli utenti finali abbiano accesso continuo alle app e ai servizi di Adobe.

## Verifica dei numeri di serie per la data di scadenza

### Trova i numeri di serie

Le licenze con numero di serie associate al contratto di ETLA sono disponibili tramite [Adobe sito Web delle licenze](https://licensing.adobe.com/) (LWS). Segui queste istruzioni per visualizzare e scaricare:

1. Accedi a [Adobe sito Web delle licenze](https://licensing.adobe.com/) (LWS) con l&#39;Adobe ID e la password.
1. Scegli **Licenze > Recupera numeri di serie**.
1. Inserisci il **ID utente finale** o **Deploy-to ID**.
1. (Facoltativo) Selezionate un **Nome prodotto**, **Versione prodotto** o **Piattaforma** per filtrare i risultati.
1. Fate clic su Cerca.
1. Vengono visualizzati il nome del prodotto e i numeri di serie.
1. (Facoltativo) Selezionate &quot;ESPORTA IN CSV&quot; per scaricare l’elenco dei numeri di serie.

![Trovare i numeri di serie](assets/retrieveserialnumbers.png)

### Verifica la data di scadenza

Il [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) è un’utilità della riga di comando per gli amministratori IT per verificare se i prodotti di Adobe su un computer utilizzano numeri di serie scaduti o in scadenza. Lo strumento visualizzerà informazioni quali l&#39;identificatore di licenza del prodotto (LEID), il numero di serie crittografato e la data di scadenza. Questo [pagina](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contiene istruzioni su come scaricare e utilizzare lo strumento sui computer Mac o Windows.

## Comprendere l’esperienza dell’utente finale prima e dopo la scadenza del numero di serie

Sia Acrobat che Creative Cloud for enterprise inizieranno a visualizzare messaggi (nelle app) a partire da 60 giorni prima della scadenza. Una volta scaduto il numero di serie, i prodotti smettono di funzionare e chiedono all&#39;utente di agire.

### Creative Cloud per l’esperienza enterprise

Le informazioni seguenti descrivono l&#39;esperienza dell&#39;utente finale. Di seguito è riportato un breve video che mostra l’esperienza dell’utente finale.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Prima della scadenza**

A partire da 60 giorni prima della scadenza del numero di serie, tutte le app Creative Cloud for enterprise visualizzano una finestra di dialogo nel prodotto all&#39;utente finale. Questo messaggio apparirà settimanalmente, fino a 30 giorni prima della scadenza, apparirà poi quotidianamente fino alla data di scadenza, indicando *La tua licenza sta scadendo. Questo prodotto di Adobe utilizza una licenza che scadrà il 29 novembre 2020. Contatta l’amministratore per assicurarti di continuare ad accedere*.

![CCE prima della scadenza](assets/cceexpiring.png)

**Dopo la scadenza**

Una volta scaduto il numero di serie, gli utenti non avranno più accesso al Creative Cloud per le app aziendali. Al primo avvio dopo la scadenza, all&#39;utente verrà visualizzata una finestra di dialogo in cui viene indicato che *Il numero di serie immesso è scaduto. Questo prodotto non può essere concesso in licenza. Contatta l&#39;Assistenza clienti*.

![Messaggio CCE dopo la scadenza](assets/cceafterexpire.png)

Per tutti i tentativi successivi di avviare le app, all&#39;utente finale verrà richiesto di **Accedi** seguito dall&#39;opzione per creare il proprio Adobe ID e passare alla modalità di prova. Tuttavia, qualsiasi nuova Adobe ID creata dall&#39;utente finale non sarà associata alle licenze dell&#39;organizzazione e causerà ulteriore confusione per gli utenti. Per evitare interruzioni di attività e/o confusione non necessaria, effettua la migrazione degli utenti alle licenze nominative prima della scadenza dei numeri di serie.

![Finestra di dialogo di accesso CCE 1](assets/ccesignin1.png)

![Finestra di dialogo di accesso CCE 2](assets/ccesignin2.png)

### Acrobat

Le informazioni seguenti descrivono l&#39;esperienza dell&#39;utente finale. Di seguito è riportato un breve video che mostra l’esperienza dell’utente finale.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Prima della scadenza**

A partire da 60 giorni prima della scadenza del numero di serie, Acrobat visualizza un messaggio a comparsa nel prodotto per l’utente finale. Questo apparirà una volta alla settimana fino a 7 giorni prima della scadenza. Comincerà quindi ad apparire ogni giorno affermando *La licenza Adobe Acrobat scade il 30/11/2020. Contatta l’amministratore per continuare a utilizzare Acrobat senza interruzioni.*

![Messaggio di scadenza di Acrobat](assets/acrobatexpiring.png)

**Dopo la scadenza**

Una volta scaduto il numero di serie, gli utenti non avranno più accesso ad Acrobat. Al primo avvio dopo la scadenza, all&#39;utente verrà visualizzata una finestra di dialogo in cui viene indicato che *Il numero di serie immesso è scaduto. Questo prodotto non può essere concesso in licenza. Contatta l’Assistenza clienti.*

![Messaggio Acrobat dopo la scadenza](assets/acrobatafterexpire.png)

Per tutti i tentativi successivi di avviare Acrobat, all&#39;utente finale verrà richiesto di **Accedi** seguito dall&#39;opzione per creare il proprio Adobe ID e passare alla modalità di prova. Tuttavia, qualsiasi nuova Adobe ID creata dall&#39;utente finale non sarà associata alle licenze dell&#39;organizzazione e causerà ulteriore confusione per gli utenti.

![Finestra di dialogo di accesso di Acrobat 1](assets/acrobatsignin1.png)

![Finestra di dialogo di accesso di Acrobat 2](assets/acrobatsignin2.png)

## Contattaci se hai bisogno di aiuto

In caso di domande sull&#39;uso del metodo [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) o se hai bisogno di aiuto durante la migrazione dalla distribuzione del numero di serie a un utente non anonimo, hai alcune opzioni:
* Invia un messaggio e-mail al team di registrazione aziendale Adobe: **entonb@adobe.com**
* Apri un ticket di supporto in [Admin Console](https://adminconsole.adobe.com/support)
* Contatta il tuo Account Manager di Adobe o il Customer Success Manager
