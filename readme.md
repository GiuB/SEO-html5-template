#  Readme Daniele VB Italia - BoxDocciaIdromassaggio.it new template project

## 11 Ottobre 2013

Ho cercato di utilizzare un layout che potesse contenere più spazio in larghezza per il testo e ugualmente molto funzionale.
Ho inoltre cercato, per quanto possibile di controllare il corretto funzionamento dei contenuti inseriti nel vostro cms senza 
andare ad incidere nel gestionale (l'unica cosa importante è che torni a funzionare la gestione delle immagini di categoria, 
vedi mail di Lucia) mantenendo un contenuto che si presti ad essere SEO oriented.

Per la corretta implementazione del layout nel cms potete partire dal file blank.html che appunto non ha contenuto.

Sono partito da un html5 reset per normalizzare il sito nei vari browser (per quello che ho potuto testare sembra andare bene anche in IE7).
Attenzione: Unica avvertenza è che quando si utilizzano i table il css reset mette in automatico i td con vertical align top,
basta aggiungere la classe "valign-middle" per tornare all'allineamento standard.

Per quanto riguarda il javascript è stato utilizzato solo il jQuery per le varie piccole animazioni e/o controlli delle form.
Le librerie implementate sono:
	- jQuery 1.9.1 (nell'header caricato da CDN e da locale se fallback)
	- Modernizr per il detect del browser sempre nell'header
	- Tutto il resto delle librerie sono caricate a fondo pagina, inserire le funzioni personalizzate in _/js/functions.js
	- jQuery Placeholder per ricreare i placeholder anche su vecchi browser che non lo supportano in automatico
	- jQuery Numeric poco utilizzato, utile per validare textbox numerici nel carrello (vedi shoppingcart-correggere.html)
	- jQuery Catslider utilizzato nell'homepage per creare quella semplice "slide" dei prodotti

Le pagine XXXX-correggere.html hanno delle cose relativamente importanti da sistemare 
(ho scritto in alto, alla riga zero cosa tenere in considerazione).

*In homepage ho scritto le istruzioni per la query prodotti per le varie slide subito sopra all'html delle slide.

Penso che possa risultare un buon lavoro e funzionale se implementato correttamente, spero riusciremo ad ottenere un
buon risultato finale.

Cordiali saluti,
Daniele Covallero

VB Italia srl
