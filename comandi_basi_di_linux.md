# Comandi base di linux
## Comandi per la gestione dei file e director
## ls
mostra i file e le directory nella directory corrente
Sintassi: ls [opzioni] [directory]
## Varie opzioni di ls
-l: mostra i dettagli dei file  
-a: mostra anche i file nascosti  
-lh: mostra file in formato leggibile ovvero in KB, MB, GB, ecc...

## cd
si usa per spostarsi nelle varie directory  
Sintassi: cd [directory]  
## Vari utilizzi
cd /percorso/directory  
cd .. si torna alla directory superiore  
cd si torna nella home dell' utente

## pwd
Si usa per mostrare la drectory corrente

## mkdir
Si usa per creare una directory  
Sintassi: mkdir [opzioni] [nome della directory]
##Varie opzioni
-p: crea directory genitore  
esempio: mkdir -p dir1/dir2/dir3
-m puoi impostare i permessi della directory  
esempio: mkdir -m 700 directory_importante
