# GIT
## Comandi
```
git init => inizializza una repository di git sul folder corrente
git status => lo stato currente della repo (le info principali)
git add nomefile => aggiunge file al tracking di git
git commit => committa un change (salva uno snapshot)
git add . => aggiunge tutti i file della cartella al trackinggit
git checkout idcommit => torna allo stato di quel commit
git checkout nome-branch => spostati su uno specifico branch
git branch => visualizza i branch
git branch -d nome-branch => elimina
git branch nome-branch => crea un nuovo branch
git merge nome-branch => prende le modifiche del branch e le mette in quello attivo
```
Un branch è un ramo
Una repository può estendersi in diversi rami
Io posso creare un ramo a partire da un qualsiasi altro ramo
Una volta creato un ramo ed effettuato le modifiche
posso prenderle e fonderle nel ramo da cui è partito
Più sviluppatore possono lavorare su rami differenti
Alla fine basterà andare ad effettuare il merge delle modifiche

Nel vari merge potrebbero saltare fuori dei conflitti!
Se due branch hanno fatto modifiche sugli stessi file
negli stessi posti, questo potrebbe non essere semplice
da gestire per git

EDIT tp e ls

