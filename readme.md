# CAROSELLO DI IMMAGINI #

---

### Il programma visualizza un carosello di immagini (slider), con frecce di scorrimento e miniature selezionabili ###

---

**Il progetto si compone dei seguenti files:**
-   ***index.html* con i links alle risorse esterne e poche righe di codice costituenti la struttura base, realizzata con il minimo ausilio di *Bootstrap 5***
-   ***style.css* in cui sono definite le poche classi sviluppate (*attributi delle immagini nel carosello e nelle miniature*) ed un effetto di transizione che si verifica al click sulle frecce di scorrimento del carosello.**
-   ***main.js* in cui e' sviluppata tutta la logica di funzionamento del progetto.**

---

### Funzioni *Javascript*: ###

-   `function init_img_array(where_to_append, array)`.**Funzione utilizzata per inizializzare i due contenitori delle immagini (carosello e miniature) con gli url locali delle immagini stesse. Il parametro *where_to_append* consente di selezionare i contenitori.**
-   `function set_thumbnail_img_onclick()`.**Questa funzione è stata pensata per immettere, specificamente, nelle immagini delle miniature (*thumbnail*) un attributo *onclick* con invocazione di una funzione parametrica, atta a consentire l'attivazione di una specifica immagine, agendo direttamente dal thumbnail.**
-   `function thumbnail_img_clicked(img_index)`.**Questa funzione realizza concretamente il puntamento e l'attivazione della foto selezionata nel thumbnail, ricevendone la posizione mediante il parametro *img_index*.**
-   `prev_arrow.addEventListener("click", function()`.**Funzione di call back che realizza lo scorrimento a sinistra delle immagini del carosello.**
-   `next_arrow.addEventListener("click", function()`.**Funzione di call back che realizza lo scorrimento a destra delle immagini del carosello.**

---
---
---
