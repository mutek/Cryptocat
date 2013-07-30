per creare il package .nw è sufficiente entrare nella cartella di riferimento e dare il comando:

zip -r Nomepacchetto.nw *

questo crea un archivio zip con estensione .nw compatibile con Node Webkit

A questo punto è disponibile per essere valutato da nw 
Ricordarsi sempre di trasportare tutti i files dei binari di nw

ATTENZIONE: pe motivi ancora ignoti non funziona

alternativa:

eseguire nw su un URL

./nw --url=file://....... 
