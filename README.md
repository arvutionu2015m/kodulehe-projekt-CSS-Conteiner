# kodulehe-projekt-CSS-Conteiner
Lisame igale lehele sisu konteineri, mille mõõtmed on 600x400px. Muudame CSS-i, et need mõõtmed oleksid rakendatud kõigile lehtedele ja kohandame HTML-i vastavalt.


HTML:

Lisatud on .container div, mis ümbritseb iga lehe põhisisu ja mille mõõtmed on 600x400px.
Kõik sisu sektsioonid on paigutatud selle konteineri sisse.


CSS:

.container klassile on määratud kindlad mõõtmed 600x400px ja keskendamine, et konteiner asuks lehe keskel.
Lisatud on kasti varjuefekt ja valge taust, et eraldada sisu taustast.
Kõik sisu sektsioonid (#home, #about, #services, #contact) on määratud konteineri sees.


JavaScript:

Kontrollib, kas nupud ja vormid on olemas enne sündmuste kuulajate lisamist.
Tagab, et JavaScripti kood töötab ainult vastavatel lehtedel (näiteks tekstimuutmise nupp ainult index.html lehel ja kontaktvorm ainult contact.html lehel).
See struktuur tagab, et iga lehe sisu mahub täpselt määratud konteinerisse ja on keskendatud lehe keskele, pakkudes puhta ja korraliku välimuse.
