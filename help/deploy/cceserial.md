---
title: Informazioni sulla scadenza dei numeri di serie di Enterprise e Acrobat per il cloud creativo
description: Informazioni sull'esperienza di scadenza dei numeri di serie per Creative Cloud per aziende e Acrobat
role: User
level: Beginner, Intermediate
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: 6b819aef801e003e5a160d24ba69522cf6a7e715
workflow-type: tm+mt
source-wordcount: '848'
ht-degree: 3%

---

# Informazioni sulla scadenza dei numeri di serie di Enterprise e Acrobat per il cloud creativo

Storicamente, Adobe ha rilasciato numeri di serie con le nostre app (ad esempio, Creative Suite, Creative Cloud for enterprise, Acrobat XI, Acrobat DC) ai clienti che si trovano in contratti di licenza a termine Enterprise (ETLA). Questi numeri di serie hanno una data di scadenza. Una volta passata la data di scadenza, il prodotto non funzionerà più, pertanto è importante pianificare la migrazione prima che i numeri di serie scadano. In questa pagina vengono descritti i passaggi necessari per garantire agli utenti finali l&#39;accesso continuo alle app e ai servizi Adobe.

## Controllo dei numeri di serie per la data di scadenza

### Trova i numeri di serie

Le licenze per il numero di serie associate al contratto ETLA sono disponibili sul sito Web [Adobe Licensing](https://licensing.adobe.com/) (LWS). Seguire le seguenti istruzioni per visualizzare e scaricare:

1. Accedi a [Sito Web di Adobe Licensing](https://licensing.adobe.com/) (LWS) con il tuo ID Adobe e la password.
1. Scegliere **Licenze > Recupera numeri di serie**.
1. Immettere il **ID utente finale** o **Distribuisci-in-ID**.
1. (Facoltativo) Selezionare **Nome prodotto**, **Versione prodotto** o **Piattaforma** per filtrare i risultati.
1. Fate clic su Cerca.
1. Vengono visualizzati il nome del prodotto e i numeri di serie.
1. (Facoltativo) Selezionare &quot;EXPORT TO CSV&quot; per scaricare l&#39;elenco dei numeri di serie.

![Trova i numeri di serie](assets/retrieveserialnumbers.png)

### Controlla la data di scadenza

[AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) è un&#39;utilità della riga di comando per gli amministratori IT per verificare se i prodotti Adobe in un computer utilizzano numeri di serie scaduti o in scadenza. Lo strumento visualizzerà informazioni quali l&#39;identificativo di licenza del prodotto (LEID), il numero di serie crittografato e la data di scadenza. Questa [pagina](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) contiene istruzioni sul download e l&#39;utilizzo dello strumento nei computer Mac o Windows.

## Informazioni sull&#39;esperienza dell&#39;utente finale prima e dopo la scadenza del numero di serie

Acrobat e Creative Cloud per app aziendali inizieranno a visualizzare messaggi (nelle app) a partire da 60 giorni prima della scadenza. Una volta scaduto il numero di serie, i prodotti smettono di funzionare e chiedono all&#39;utente di agire.

### Cloud creativo per l&#39;esperienza aziendale

Le informazioni seguenti descrivono l&#39;esperienza dell&#39;utente finale. Di seguito è riportato un breve video, seguito dalla recensione dell&#39;esperienza dell&#39;utente finale.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Prima della scadenza**

A partire da 60 giorni prima della scadenza del numero di serie, tutte le app Creative Cloud per l&#39;organizzazione visualizzano una finestra di dialogo in prodotto per l&#39;utente finale. Questo messaggio verrà visualizzato settimanalmente, fino a 30 giorni prima della scadenza, quindi verrà visualizzato giornalmente fino alla data di scadenza che indica la scadenza della licenza. *Questo prodotto Adobe utilizza una licenza che scade il 29 novembre 2020. Contattare l&#39;amministratore per garantire l&#39;accesso continuo*.

![CCE prima del messaggio di scadenza](assets/cceexpiring.png)

**Scadenza**

Una volta scaduto il numero di serie, gli utenti non avranno più accesso al cloud creativo per le app aziendali. Al primo avvio dopo la scadenza, all&#39;utente verrà visualizzata una finestra di dialogo con l&#39;indicazione *Il numero di serie immesso è scaduto. Impossibile concedere in licenza il prodotto. Contattare il supporto tecnico*.

![CCE dopo il messaggio di scadenza](assets/cceafterexpire.png)

Per tutti i tentativi successivi di avviare le app, all&#39;utente finale verrà richiesto di **Accedi ora**, seguito dall&#39;opzione per creare un proprio Adobe ID e accedere alla modalità di prova. Tuttavia, qualsiasi nuovo Adobe ID creato dall&#39;utente finale non sarà associato alle licenze dell&#39;organizzazione e causerà ulteriore confusione agli utenti. Per evitare interruzioni dell&#39;attività e/o confusione non necessaria, migrare gli utenti alla licenza utente denominata prima della scadenza dei numeri di serie.

![Finestra di dialogo Accesso CCE 1](assets/ccesignin1.png)

![Finestra di dialogo Accesso CCE 2](assets/ccesignin2.png)

### Esperienza di Acrobat

Le informazioni seguenti descrivono l&#39;esperienza dell&#39;utente finale. Di seguito è riportato un breve video, seguito dalla recensione dell&#39;esperienza dell&#39;utente finale.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Prima della scadenza**

A partire da 60 giorni prima della scadenza del numero di serie, Acrobat visualizza un messaggio popup in prodotto all&#39;utente finale. Questa operazione verrà visualizzata una volta alla settimana fino a 7 giorni prima della scadenza. Comincerà a comparire giornalmente indicando *La licenza di Adobe Acrobat scade il 30/11/2020. Contattare l&#39;amministratore per continuare a utilizzare Acrobat senza interruzioni.*

![Messaggio di scadenza di Acrobat](assets/acrobatexpiring.png)

**Scadenza**

Una volta scaduto il numero di serie, gli utenti non avranno più accesso ad Acrobat. Al primo avvio dopo la scadenza, all&#39;utente verrà visualizzata una finestra di dialogo con l&#39;indicazione *Il numero di serie immesso è scaduto. Impossibile concedere in licenza il prodotto. Contattare il supporto tecnico.*

![Acrobat dopo il messaggio di scadenza](assets/acrobatafterexpire.png)

Per tutti i tentativi successivi di avviare Acrobat, all&#39;utente finale verrà richiesto di **Accedi ora**, seguito dall&#39;opzione per creare un proprio Adobe ID e accedere alla modalità di prova. Tuttavia, qualsiasi nuovo Adobe ID creato dall&#39;utente finale non sarà associato alle licenze dell&#39;organizzazione e causerà ulteriore confusione agli utenti.

![Finestra di dialogo Accesso Acrobat 1](assets/acrobatsignin1.png)

![Finestra di dialogo Accesso Acrobat 2](assets/acrobatsignin2.png)

## Contattateci se avete bisogno di aiuto

Per domande sull&#39;utilizzo dello strumento [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) o per la migrazione dalla distribuzione dei numeri di serie all&#39;utente denominato, sono disponibili alcune opzioni:
* Invia un&#39;e-mail al team Adobe Enterprise Onboarding - **entonb@adobe.com**
* Aprire un ticket di supporto in [Console amministrazione](https://adminconsole.adobe.com/support)
* Visitate Adobe Account Manager o Customer Success Manager
