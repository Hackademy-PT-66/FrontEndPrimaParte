combinazione di selettori:
- descendant selector    space
- child selector         >

group selector           ,
class selector multipli (SOLO CLASSI)


Ereditarietà:
quelle proprietà legate al testo sono ereditate dall'elemento antenato



Viewport virtuale -> larghezza 980px
Viewport reale -> <meta name="viewport" content="width=device-width, initial-scale=1.0">


Responsive design: dobbiamo gestire il CSS (a mano) affinchè le pagine HTML siano ben visualizzate su larghezze di schermo (e quindi di viewport) differenti
Possiamo mettere in pratica il Responsive design seguendo 2 approcci:
- mobile first
- desktop first

Nel Responsive design con approccio mobile first:
1) scriveremo il CSS che già conosciamo a partire da smartphone in portrait
2) aumenteremo la larghezza di schermo andando ad effettuare il numero minimo di modifiche al layout



Position modificare il luogo in cui un elemento HTML viene disegnato sulla pagina
La proprietà position può assumere i seguenti valori:
- static (valore di default)
- relative posizionare l'elemento rispetto a se stesso
- absolute
- fixed posizionare l'elemento rispetto alla viewport
- sticky una via di mezzo tra relative e fixed

La proprietà position al valore absolute posiziona l'elemento:
- rispetto al primo elemento antenato avente position diversa dal valore di default (diversa da static)
- altrimenti rispetto al body

In combinazione con position possiamo utilizzare la proprietà z-index
Valore di default 0