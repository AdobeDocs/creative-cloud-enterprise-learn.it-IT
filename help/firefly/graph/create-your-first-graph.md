---
title: ​3. Crea il tuo primo grafico
description: Procedura dettagliata per la creazione del primo flusso di lavoro di Grafico Firefly
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: 4dd919a2b06f0852dc0010b0f79d5a0b2eae4c1a
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 1%

---

# &#x200B;3. Crea il tuo primo grafico

Una volta individuato il nodo, la connessione e il modello disponibili, è possibile creare il primo flusso di lavoro.

1. Apri il Firefly e seleziona **Grafico** dal menu a sinistra.
1. Seleziona **Crea nuovo grafico**.
1. Fare clic con il pulsante destro del mouse sull&#39;area di lavoro vuota e selezionare **+ nuovo nodo**.
1. Selezionare **Input** nel menu a sinistra, quindi **Input immagine**.
   ![Nodo](../assets/node.png)
Questo è un nodo che consente di importare un elemento grafico.
1. Trascinare un&#39;immagine sul nodo.
   ![Nodo con immagine](../assets/node-image.png)
1. Fai clic con il pulsante destro del mouse sull&#39;area di lavoro vuota e seleziona **+ nuovo nodo** e seleziona **Maschera sfumatura** nella finestra di dialogo.
1. Fai clic con il pulsante destro del mouse sull&#39;area di lavoro vuota e seleziona **+ nuovo nodo** e seleziona **Applica maschera** nella finestra di dialogo.
1. Collegare l&#39;output del nodo **Immagine di input** all&#39;input del nodo dell&#39;immagine **Applica maschera**.
1. Collegate l&#39;output della **Maschera sfumatura** all&#39;input della **Maschera di applicazione** Maschera/canale.
   ![Collegare i nodi](../assets/plug-in.png)

## Passaggio successivo

Stai partendo da un modello? Vai a [4. Personalizzare un modello](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/customize-template) in modo che rifletta le proprie istruzioni.
