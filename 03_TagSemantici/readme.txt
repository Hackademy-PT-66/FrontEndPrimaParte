Tag semantici: elementi HTML con un "ruolo" ben specifico in relazione alla SEO


L'elemento header è un contenitore per del contenuto informativo che introduce
il contenuto informativo presente nell'elemento parent

L'elemento footer è un contenitore per del contenuto informativo accessorio
relativo all'elemento parent




L'elemento article è un contenitore per del contenuto informativo per l'utente:
- indipendente dal contenuto informativo di altri article
- self-contained

Ogni article deve avere un titolo (heading tag)


L'elemento section è un generico contenitore utile per raggruppare una "categoria" di contenuti
legati tra loro al livello tematico

Dobbiamo utilizzare section se non è possibile utilizzare tag semantici più specifici

Ogni section deve avere un titolo (heading tag)





Elemento aside: contenuto informativo indirettamente collegato al contenuto del main
- sidebar cioè menù verticale (laterale)
- contenitore per la pubblicità





form è un contenitore di dati:
- action dove inviare i dati
- method il metodo della richiesta HTTP (da vedere più avanti)
- enctype cioè encoding type quindi il formato dei dati (di default application/x-www-form-urlencoded)
        name1=value1&name2=value2&name3=value3
    ad esempio:
        firstname=Eric&lastname=Cartman&age=14


input di type differente:
- text
- number        posso utilizzare gli attributi min e max
- email
- password
- checkbox


Elementi block:
    form

Elementi inline:
    input
    label
    button
    select
    textarea



