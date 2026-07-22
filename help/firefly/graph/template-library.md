---
title: Libreria modelli
description: Sfoglia modelli predefiniti di grafici a Firefly che puoi aprire e adattare al tuo progetto
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: facfbfbe45a25cbaf430446a326adb320d4e6968
workflow-type: tm+mt
source-wordcount: '874'
ht-degree: 0%

---

# &#x200B;5. Libreria di modelli

Un indice di riferimento rapido dei modelli di grafici di Firefly, organizzati in base a ciò che ciascuno di essi produce o fa. Ogni esempio è un punto di partenza: scambia il tuo marchio, il tuo prodotto e le tue richieste prima di utilizzare un modello in produzione.

## Generazione e stile delle immagini

* [**Guida introduttiva - Genera un&#39;immagine**](/help/firefly/graph/templates/get-started-gen-image.md) - Questo modello è un grafico di base: un nodo prompt in un nodo di generazione in un unico output. Usalo come primo modello da aprire con qualsiasi nuovo utente.
* [**Generazione coerente dei caratteri**](/help/firefly/graph/templates/character-gen.md): in questo modello di grafico carichi un’immagine di riferimento di un personaggio, quindi scambia la scena o il prompt della posa per ogni nuova ripresa. Il riferimento al personaggio rimane bloccato mentre cambia la scena circostante.
* [**Estrazione dello stile**](/help/firefly/graph/templates/style-extraction.md): in questo modello di grafico viene inserita un’immagine di riferimento per estrarne il trattamento di colore, luce e texture. Potete quindi applicare quel trattamento a qualsiasi nuova immagine che attraversi lo stesso grafico.
* [**Atmosfera al tramonto**](/help/firefly/graph/templates/sunset-vibes.md): in questo modello di grafico puoi creare un’immagine tipografica 3D da un messaggio di testo. Il modello gestisce automaticamente il posizionamento e il bilanciamento del colore.

## Segmentazione e composizione

* [**Guida introduttiva - Segmentazione di un&#39;immagine**](/help/firefly/graph/templates/get-started-segment-image.md) - In questo modello di grafico è possibile caricare qualsiasi immagine di origine ed eseguire il nodo di segmentazione per isolare il soggetto dallo sfondo. Abbinalo a un nodo di sostituzione dello sfondo per un ritaglio pulito.
* [**Comporre e fondere i livelli**](/help/firefly/graph/templates/composite-blend-layers.md): in questo modello di grafico sovrapponi un ritaglio di prodotto e una scena di sfondo come input di livello separati. Regolate i nodi del metodo di fusione e della luce fino a quando la composizione non viene letta come una ripresa.
* [**Correzione colore selettiva**](/help/firefly/graph/templates/selective-color-correction.md): in questo modello di grafico viene mascherata un&#39;area specifica che deve essere corretta e viene impostato il colore di destinazione solo su quel nodo. Il resto dell’immagine passa attraverso il grafico inalterato.

## Video e animazione

* [**Guida introduttiva - Generazione di video**](/help/firefly/graph/templates/get-started-video-gen.md) - In questo modello di grafico viene inserito un elemento grafico a chiave fissa approvato e un breve prompt di animazione. Il modello genera un taglio video creato sulla base della stessa grafica chiave, anziché un nuovo servizio.
* [**Tempo punto elenco VFX**](/help/firefly/graph/templates/bullet-time-vfx.md): in questo modello di grafico, inserisci un prodotto eroe o un’immagine del soggetto per generare una sequenza di angoli di rotazione attorno ad esso, quindi unisci automaticamente lo sweep di fermo fotogramma.

## Storyboard

* [**Da testo a storyboard**](/help/firefly/graph/templates/text-to-storyboard.md): in questo modello di grafico i nodi di input di testo vengono sostituiti con elementi del brano. Ogni riga diventa un proprio frame di storyboard, generato in sequenza e disposto per la revisione come un singolo set di pannelli.
* [**Generatore storyboard**](/help/firefly/graph/templates/storyboard-builder.md): in questo modello di grafico si crea uno storyboard scena per scena, aggiungendo un nodo per battuta del commento. Riordinate i nodi per provare una sequenza diversa prima di bloccare l&#39;ordine finale del pannello.

## 3D e carattere

* [**Shader in tempo reale**](/help/firefly/graph/templates/real-time-shaders.md): in questo modello di grafico si inizia con un&#39;immagine, si applicano tre diversi shader personalizzati e si visualizza in anteprima il risultato in tempo reale. Regolate i parametri dello shader direttamente sul nodo, invece di eseguire nuovamente il rendering da zero.
* [**Generazione del modello di carattere**](/help/firefly/graph/templates/character-model-generation.md): in questo modello di grafico crei uno stile animato 3D di un&#39;illustrazione. Il modello genera un passaggio del modello 3D di base pronto per essere consegnato a un modeler per la pulizia, anziché partire da una scena vuota.
* [**Progettazione di giocattoli in vinile**](/help/firefly/graph/templates/vinyl-toy-design.md): in questo modello di grafico inserisci un riferimento a un carattere o a una mascotte ed esegui il rendering in un giocattolo in vinile stilizzato. Sono disponibili angoli di rotazione per un deck di licenza o di revisione del prodotto.
* [**Disegna per trasformare in 3D**](/help/firefly/graph/templates/sketch-to-3d.md): in questo modello di grafico puoi trasformare uno schizzo in un carattere 3D. Il grafico ne crea un risultato 3D rotante, pronto per una revisione del progetto interno prima di qualsiasi prototipo fisico.

## Modelli di prodotti e marchi

* [**Visualizzazione del branding**](/help/firefly/graph/templates/branding-visualization.md): in questo modello di grafico scopri come visualizzare le scene di prodotto. Feed in linee guida del marchio o un logo e una tavolozza di colori e il grafico genera sia grafica statica chiave e un passaggio di breve movimento in un&#39;unica esecuzione, in modo che entrambi i formati rimangano visivamente allineati.
* [**Modello di prodotto del marchio**](/help/firefly/graph/templates/brand-product-mockup.md): in questo modello di grafico scopri come visualizzare il prodotto in diverse scene. Puoi inserire una foto o un rendering del prodotto nel nodo del modello e il grafico lo inserisce all’interno di una scena con marchio completo, in cui illuminazione e ombre corrispondono automaticamente alla scena.
* [**Photoshop editoriale**](/help/firefly/graph/templates/editorial-photoshoot.md): in questo modello di grafico carichi un riferimento al modello e scambia l’input dell’indumento per ogni nuovo aspetto. I nodi di posizione e illuminazione rimangono bloccati sul set per un&#39;atmosfera editoriale uniforme.
* [**Studio fotografico**](/help/firefly/graph/templates/photography-studio.md): in questo modello di grafico inserisci il rendering di un prodotto sullo sfondo dello studio e regola l’illuminazione finché il risultato non assume l’aspetto di una vera e propria acquisizione da studio.
* [**Applica decalcomania alle superfici**](/help/firefly/graph/templates/decal-to-surfaces.md): in questo modello di grafico vengono caricati il modello di prodotto di base e la risorsa decalcomania o logo come input separati. La maschera avvolge la decalcomania sulla geometria della superficie in modo che segua correttamente i contorni.

## Operazioni in batch e di coerenza

* [**Generatore di sistemi di progettazione**](/help/firefly/graph/templates/design-system-generator.md): in questo modello di grafico viene generato un sistema di progettazione basato sulla schermata di un sito Web. Il grafico produce un insieme corrispondente di icone, pattern e componenti di layout in una singola esecuzione batch.
* [**Generazione di headshots**](/help/firefly/graph/templates/headshots-generation.md): in questo modello di grafico si armonizza un batch di headshot aziendali. Caricate le foto sorgente, una a persona, e il grafico normalizza l’illuminazione, lo sfondo e il ritaglio sull’intero set in un’unica sequenza.

Torna a [Introduzione al grafico del Firefly](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph).