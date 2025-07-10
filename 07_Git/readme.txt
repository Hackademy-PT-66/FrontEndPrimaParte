git è un distributed version control system:
- version control system è un software che traccia i cambiamenti apportati ai file del progetto nel tempo
- distributed cioè git permette di collaborare in team


Chi ha il mac deve installare gli xcode command line tools eseguendo:
xcode-select --install


git config --global user.name "Eric Cartman"
git config --global user.email "eric.cartman@gmail.com"






- repository è una struttura dati (un contenitore di dati sottoforma di directory) che traccia i cambiamenti apportati ad un progetto nel tempo
- branch è una linea di sviluppo indipendente nel tempo (timeline)
- commit istantanee del progetto








La cartella del progetto si chiama working directory

Creo una repository locale eseguendo il comando (operazione one-time):
git init


Possiamo aggiungere un file della working directory dentro la staging area (anteprima di stampa) attraverso il comando:
git add nomeDelFile

Possiamo aggiungere tutti i file della working directory dentro la staging area attraverso il comando:
git add .

Come possiamo controllare la staging area?
git status

A partire dai file presenti nella staging area possiamo creare un commit eseguendo il comando:
git commit -m "un messaggio descrittivo e significativo del commit"

Possiamo visualizzare i commit presenti all'interno del branch (attulmente selezionato) eseguendo:
git log

oppure:
git log --oneline






GitHub è un servizio di hosting per repository git

E' necessario collegare l'utente del sistema operativo con il profilo github tramite chiavi SSH
per permettere una autenticazione automatica su GitHub.

Creiamo una coppia di chiavi pubblica e privata eseguendo:
    ssh-keygen



Il comando git push effettua l'upload dei commit presenti nel branch specificato (main) della repository locale
verso lo stesso branch della repository remota all'URL origin
git push origin main

Il comando git pull effettua il download dei commit presenti nel branch specificato (main) della repository remota all'URL origin
verso lo stesso branch della repository locale 
git pull origin main




Alla creazione di un nuovo progetto devo:
1) creare la directory del progetto
2) creo una nuova repository locale con git init
3) creo una repository remota
4) collego le repository locale e remota
5) scrivo codice all'interno dei file
6) creo un commit eseguendo:
    git add .
    git commit -m "un messaggio descrittivo e significativo del commit"
    git push origin main
7) ripeto i passi 5 e 6 q.b.





Dai settings della repository remota su GitHub, l'owner del progetto può aggiungere dei collaborators

Il collaborator sul suo pc:
1) si posizionerà all'interno della directory di tutti i progetti
2) aprirà un terminale nella directory di tutti i progetti
3) esegue il comando:
    git clone URLRepositoryRemota

il comando git clone permette di:
1) copiare il progetto
2) crea una repository locale come copia della repository remota





Al git push potrebbe nascere un conflitto.
Il conflitto ci viene mostrato con dei delimitatori:
<<<<<<< HEAD
        <a href="">Facebookissimo</a>
======
        <a href="">Istagrammissimo</a>
>>>>>>> dasdsadsada

Il conflitto deve terminare con nuovo commit di risoluzione del conflitto!!!


