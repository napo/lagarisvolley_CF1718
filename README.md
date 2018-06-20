# Analisi dati Lagaris Volley C femminile stagione 2017/2018
## Statistiche
vedi  [analisi.ipynb](analisi.ipynb) 

### Risultati ottenuti
- primo posto [serie C femminile](http://www.fipav.tn.it/risultati-classifiche.aspx?ComitatoId=16&StId=1328&DataDa=&StatoGara=1&CId=39890&SId=2781&PId=110&btFiltro=CERCA) (promozione)
- primo posto [coppa trentino alto adige](http://www.fipav.tn.it/risultati-classifiche.aspx?ComitatoId=16&StId=1328&DataDa=&StatoGara=1&CId=41019&SId=&PId=110&btFiltro=CERCA) 
- terzo posto [coppa triveneto](http://www.fipavveneto.net/archivio-news?NewsId=35509&)

### Raccolta dati
ad ogni partita viene trascritto su un foglio di carta le performance di ogni singolo giocatore nella sequenza di tocchi secondo questo schema:

| numero |   |   |   |   |   |   |   |   |   |   |   | 
| ------ |:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|--:|
| 6      |A#|R+|A-|B+|A#|A/|A+|M#|A#|A=|..|
| ...    |..|..|..|..|..|..|..|..|..|..|..|                                                                  
| 3      |B+|B+|B+|B+|A-|B+|A=|  |  |  |  |

secondo lo schema:  **F**_v_  (= fondamentale e sua valutazione)

Le lettere per i fondamentali sono:

|simbolo|fondamentale|
|--|-:|
|*A*|Attacco|
|*R*|Ricezione|
|*B*|Battuta|
|*P*|Pallegggio|
|*M*|Muro|

I simboli delle valutazioni:

|simbolo|valutazione|
|--|-:|
|**&#35;**|punto (M, B, A) o perfetto (R)|
|**&plus;**|positivo (R) o difficile (A)|
|**=**|punto avversario (A,B,R,P,M)|
|**/**|murata (A) o palla oltre rete (R)|
|**!**|giocabile (R,B) o attacco murato e recuperato da copertura (A, M)|
|**&minus;**|facile (B,A) o non giocabile (R)|

e poi trascritti in un file Excel che genera a sua volta il tabellino [#2](https://github.com/napo/lagarisvolley_CF1718/issues/2)

#### nota
il file xls va configurato con l'elenco atleti e con le schede dei singoli giocatori [#1](https://github.com/napo/lagarisvolley_CF1718/issues/1)

### Dati aggregati
lo script [analisi.ipynb](analisi.ipynb)  estrae i dati aggregati e genera grafici e statistiche di squadra

#### nota
lo script va migliorato [#3](https://github.com/napo/lagarisvolley_CF1718/issues/3)
