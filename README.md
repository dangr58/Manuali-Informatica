## Manuali d'Informatica

__Disclaimer:__ _Questi libri sono esclusivamente a fini informativi e per uso personale._

## Come cercare libri "GRATIS"?
### Introduzione
__"Google Dorking"__ noto anche come __"Google Hacking"__ è una tecnica utilizzata dall'organizzazioni investigative, hacker ed esperti di sicurezza per interrogare i vari motori di ricerca (google,bing,...) per la ricerca d'informazioni "nascoste", vulnerabilità esposte, documenti,..ecc. __"Google Dorking"__ è stato documentato sin dal 2000, non è una tecnica sofisticata, richiede semplicemente l'utilizzo di determinate parole chiavi supportate dal motore di ricerca.

![googlehacking1](https://raw.githubusercontent.com/m4ll0k/Manuali-Informatica/master/googlehacking1.PNG)

### Precauzioni
Se volete utilizzare "Google Dorking" come una tecnica investigativa durante le fasi di penetration non completamente
legali, ci sono diverse precauzioni da prendere. Anche se siete liberi di cercare qualsiasi cosa, l'accesso a determinate
pagine web o il download di file potrebbe essere un reato, specialmente negli Stati Uniti. È possibile che le vostre ricerche
possono essere registrate e utilizzate in futuro contro di voi.

Come protezione, vi consiglio di utilizzare il browser [Tor](https://www.torproject.org/projects/torbrowser.html.en) o il sistema operativo [Tails](https://tails.boum.org/). [Secutity-in-a-Box](https://securityinabox.org/en/) include guide dettagliate su come utilizzare il browser tor.

### Funzionamento
Il "dorking" può essere utilizzato in vari motori di ricerca, non solo su Google.
I motori di ricerca accettano il termine cercato e restituendo i risultati corrispondenti, ma
sono anche programmati per accettare operatori più avanzati che perfezionano la nostra ricerca.
Un operatore è una parola chiave o una frase che ha un significato ben preciso per il motore di ricerca.

Es:
- `site:governo.it filetype:pdf`
Qualsiasi pdf appartenente al dominio governo.it
- `site:.governo.it -inurl:www.governo.it`
Tutti i subdomain appartenente al dominio governo.it escludendo www.governo.it

![goolehacking2](https://raw.githubusercontent.com/m4ll0k/Manuali-Informatica/master/googlehacking2.PNG)

## Parole Chiave 

| Dork | Descrizione | Google | DuckDuckGo | Yahoo | Bing |
| --- | --- | --- | --- | --- | --- |
| __cache__:[url] | None | Si | No | No | No |
| __related__:[url] | None | Si | No | No | No |
| __info__:[url] | None | Si | No | No | No |
| __site__:[url] | None | Si | Si | Si | Si |
| __intitle__:[testo]/__allintitle__:[testo] | None | Si | Si | Si | Si |
| __inurl__:[testo]/__allinurl__:[testo] | None | Si | Si | No | No |
| __meta__:[testo] | None | No | No | No | Si|
| __filetype__:[estensione]/__ext__:[estensione] | None | Si | Si | Si | Si |
| __intext__:[testo]/__allintext__:[testo]/__inbody__:[test] | None | Si | Si | Si | Si |
| __inanchor__:[testo] | None | Si | No | No | Si |
| __location__:[iso code]/__loc__:[iso code]/__region__:[region code] | None | No | Si | No | Si |
| __contains__:[testo] | None | No | No | No | Si|
| __altloc__:[iso code] | None | No | No | No | Si |
| __domain__:[url] | None | No | No | No | Si |
| __feed__:[rss] | None | No | Si | Si | Si |
| __hasfeed__:[url] | None | No | Si | No | Si |
| __imagesize__:[es: 600] | None | No | No | No | Si |
| __ip__:[ip] | None | No | Si | Si | Si |
| __keyword__:[testo] | None | No | No | No | Si |
| __language__:[es: it] | None | No | No | Si | Si |
| __book__:[titolo] | None | Si | No | No | No |
| __maps__:[posizione] | None | Si | No | No | No |
| __linkfromdomain__:[url] | None | No | No | No | Si |



