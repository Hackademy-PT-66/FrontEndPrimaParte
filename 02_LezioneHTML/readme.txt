HTML hypertext markup language (linguaggio di formattazione per ipertesti)
HTML utile per strutturare una pagina al fine di mostrare i dati all'utente in maniera logica

Sintassi
un elemento HTML assume una forma del genere:
<tagname attribute1="value1" attribute2="value2" attribute3="value3">content</tagname>


Headings tag (in ordine decrescente di importanza)
h1
h2
h3
...
h6

Paragraphs
p

Anchor tag
a   - href hypertext reference

Ogni pagina HTML è individuata da un URL


Web server anni 90 all'inizio del WWW

URL in rete                                                 PATH del File System
http://127.0.0.1:5500/index.html                    ->      /Users/kutta/Desktop/HPT66/02_LezioneHTML/index.html 
http://127.0.0.1:5500/about-us.html                 ->      /Users/kutta/Desktop/HPT66/02_LezioneHTML/about-us.html 
http://127.0.0.1:5500/ricette/tagliatelle.html      ->      /Users/kutta/Desktop/HPT66/02_LezioneHTML/ricette/tagliatelle.html


http://127.0.0.1:5500/pennette-arrabbiata.jpg



Block level element:
- Occupano tutto lo spazio a dispozione in orizzontale
- impilati in verticale (uno sotto l'altro)
h1, h2, ..., h6
p
div division il contenitore per eccellenza di tipo block
ul li
ol li


Inline level element:
- Occupano solo lo spazio strettamente necessario a contentere il proprio contentuto
- impilati in orizzontale (uno di fianco all'altro)
a
img
strong
span division il contenitore per eccellenza di tipo inline



Gli elementi possono avere come contentuto:
- testo
- altri elementi HTML innestati

Tra elementi HTML innestati nascono delle relazioni di tipo parent-child:

Regole per gli elementi HTML innestati:
- dentro un elemento block posso avere contenuto sia elementi block, sia elementi inline, sia testo
- dentro un elemento inline posso avere contenuto sia elementi inline sia testo (NO block)

Eccezione alle regole per gli elementi HTML innestati:
- gli elementi HTML block h1, h2, ... h6 e il p NON possono contenere altri elementi block


Self closing tag: elementi che non potendo avere contenuto non hanno tag di chiusa
meta
img


attributi globali:
id per identificare in maniera univoca (cioè senza ambiguità) un elemento HTML
class utile per definire un insieme di elementi
style