# django-tutorial-1
Following https://www.youtube.com/watch?v=sm1mokevMWk&amp;t=1s

Spørsmål
Hva menes med template-tags i Django?
    Curly brackets og % teng slik: {%%}. Det lar deg skrive in ulik kode og snakke mellom forskjellige templates, sende variabler osv.

Hvordan kan man bruke template-tags til å gjøre følgende:
    Loope over en liste med objekter
        {% for variabel in ... %}

        {% endfor % }

    Lage en if-spørring
        {% if ... %}

        {% else %}
        
        {% endif %}

    Arve fra en annen template
        {% extends "path til arv" %}

Hva menes med en View i Django?
    Nettsiden hvor man ser innholdet, altså URLen. ip/home er en view mens ip/admin er en annen

Hvordan sender man variabler og annen informasjon over til templaten fra viewet?
    lager en dictonary på slutten av return render. Altså return render(response, ...., {"navn":variabel})

Hva menes med Context?

Hva menes med begrepet “Business logic”?

