I comandi per interagire con il file system del sistema operativo cioè con:
- file
- directory

Sia i file sia le directory sono individuate da un path (percorsi)




Comandi + opzioni + argomenti




Nei sistemi operativi unix, i nomi dei file e i nomi delle directory NON devono contenere spazi!!!!

clear


path:
- assoluto a partire dalla radice del file system (in unix è /) iniziano /
- relativo  iniziano ./

alias per i path:
~       il path della home dell'utente attualmente loggato sul sistema operativo
.       nella directory in cui mi trovo attualmente
..      la directory parent della directory in cui mi trovo attualmente

Comandi per i path:
pwd (print working directory)

Comandi per le directory:
ls -A                        (list)
cd path                      (change directory)
mkdir test                        (make directory)
mv oldPath newPath                             (move)
cp -r srcPath destPath      (copy opzione recursive per le directory)
rm -r path


Comandi per le file:
touch nomeDelFile       (crea un file vuoto)
cat path                (print contenuto nel file nella console)
mv
cp
rm




L'editor di testo di default su unix si chiama vim

vim ha due modalità di funzionamento:
- command mode (modalità selezionata all'apertura di vim)
- insert mode


possiamo passare:
- da command mode a insert mode -> premendo il tasto i
- da insert mode a command mode -> premendo il tasto esc



i comandi a disposizione:
:wq         (write quit)
:q!          (quit forced)