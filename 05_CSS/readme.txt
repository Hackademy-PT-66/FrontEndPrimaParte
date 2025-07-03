Commento rapido:
ctrl + ù
command + shift + 7


unità di misura:
- assolute
- relative

unità di misura assolute:
- px

unità di misura relative (relative a qualche altra cosa):
- % rispetto alla width dell'elemento parent (caso particolare se utilizzato per la height dell'elemento)
- vw % rispetto alla viewport width
- vh % rispetto alla viewport height


la viewport è la porzione di pagina HTML che l'utente visualizza



box-model descrive quanto spazio occupa un elemento HTML attraverso le proprietà CSS:
- margin
- border
- padding
- width e height (di default si riferiscono al contento dell'elemento)


# margin collapsing (funziona solo per margini verticali)

# margin centering
Utilizzo il valore auto per distribuire automaticamente lo spazio vuoto restante attorno all'elemento
Sono necessarie 2 condizione:
- può essere utilizzato su un elemento block
- l'elemento deve avere un width fissata

box-sizing permette di specificare "a cosa" si riferiscono width e height




Gli elementi block:
- hanno width: 100%
- si impilano in verticale (uno sotto l'altro)


Gli elementi inline:
- hanno una width strettamente necessaria a contenere il contenuto testo
- si impilano in orizzontale

Gli elementi inline NON rispettano il box model!!!! Per risolvere il problema hanno introdotto il valore inline-block


proprietà display:
- block
- inline
- inline-block
- flex


FlexBox:
- flex-container (elemento parent)
- flex-item (figli diretti)