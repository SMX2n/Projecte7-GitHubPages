# Desplegant en GitHubPages

## Tasca per desplegar la  web corporativa a GitHub Pages

![web](https://img.shields.io/badge/web-FCC624?style=for-the-badge&logo=web&logoColor=green)
![IA](https://img.shields.io/badge/IA-3DDC84?style=for-the-badge&logo=Google&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-FF5733?style=for-the-badge&logo=github&logoColor=white)

## Introducció

Tal com s'ha explicat a la tasca del projecte, el teu objectiu és crear una web corporativa per a la vostra empresa client i després desplegar-la a GitHub Pages. Aquesta guia et proporcionarà els passos necessaris per aconseguir-ho.

És una tasca individual, és a dir, cada membre de l'equip ha de crear i desplegar la seva pròpia web corporativa a GitHub Pages. No obstant això, podeu compartir idees i recursos entre vosaltres per ajudar-vos mútuament en el procés. Finalment, com equip triareu la solució que més us agradi per presentar-la com solució final.

## Pasos per desplegar la web a GitHub Pages

### Creació del repositori

En primer lloc, has de crear un repositori a GitHub on allotjaràs els fitxers de la teva web . Pots fer-ho seguint aquests passos:

1. Inicia sessió al teu compte de GitHub.
2. Fes clic al botó "New" per crear un nou repositori.
3. Dona un nom al teu repositori (per exemple, "web-corporativa").
4. Marca l'opció "Private" i, si vols, afegeix una descripció, car no volem compartir el projecte públicament.
5. Fes clic al botó "Create repository".
6. Copia l'URL del repositori per poder clonar-lo localment.

### Clonar el repositori i afegir els fitxers de la web

Ara que tens el repositori creat, has de clonar-lo al teu ordinador i afegir els fitxers de la teva web corporativa. Pots fer-ho amb els següents passos:

1. Obre Code i a l'opció de clonar repositori, enganxa l'URL del repositori que has copiat anteriorment.
2. Un cop clonat el repositori, crea una carpeta anomenada `docs` a l'arrel del repositori.
3. Crea un arxiu README.md a l'arrel del repositori i afegeix una breu descripció de la tasca. A continuació, tens un exemple de contingut per al README.md:

```markdown

# Web Corporativa de [Nom de l'Empresa]

Aquesta és la web corporativa de [Nom de l'Empresa], una empresa fictícia dedicada a [descripció breu de l'empresa] dins el mòdul *Projecte Intermodular*.

## Demostració

[🌐 URL de la web](https://[usuari].github.io/[nom-del-repositori])

## Tecnologies Utilitzades

Per la creació d'aquesta web, s'han utilitzat les següents tecnologies i eines:

- Indiqueu l'eina IA que heu utilitat.
- HTML5/CSS3
- Statcounter per l'analítica

## Autor

👤 [El teu nom]
```

### Creació de la web corporativa i estructura

La pàgina web ha de tenir la següent estructura bàsica:

- Inici
- Serveis
- Sobre nosaltres
- Contacte

És obligatori que la secció de "Contacte" inclogui un formulari de contacte per clients potencials (no cal que envïi les dades recollides). Aquest formulari haurà de tenir els següents camps:

- Nom
- Correu electrònic
- Telèfon de contacte
- Missatge

Per crear el contingut, pots fer-ho directament o et recomanem utilitzar una eina d'IA com `Canva de Gemini`, que et permetrà generar contingut visual atractiu per a la teva web corporativa. És important que citis amb quina eina d'IA has creat el contingut, ja sigui text o imatges, i que ho incloguis al README.md del teu repositori.

Un cop tinguis el codi, cal que el guardis a la carpeta `docs` del teu repositori local. Assegura't que el fitxer principal de la teva web es digui `index.html`, ja que GitHub Pages el reconeixerà com a pàgina d'inici. Pots separar el estils CSS en un fitxer anomenat `styles.css` i col·locar-lo també dins de la carpeta `docs`. Pel que fa a les imatges, et recomanem que utilitzis imatges lliures de drets d'autor i les vinculis a la teva web mitjançant URL i les pròpies com poden ser logotips, etc. posa-les dins una carpeta anomenada `images` dins de `docs`.

Treballa en local, usant la Vista Prèvia de Code per veure com queda la teva web corporativa abans de pujar-la a GitHub. Fes fent commits regulars per guardar els canvis i permetre versionar el treball, desfent canvis si cal.

Un cop tinguis tots els fitxers de la teva web corporativa a la carpeta `docs`, és hora de pujar-los al repositori de GitHub. Fes un commit amb un missatge descriptiu (per exemple, "Afegir fitxers de la web corporativa") i després fes push per pujar els canvis al repositori remot.

### Desplegar la web a GitHub Pages

Un cop tinguis tots els fitxers de la teva web corporativa a la carpeta `docs`, és hora de desplegar-la a GitHub Pages. Segueix aquests passos:

1. A la pàgina del teu repositori a GitHub, fes clic a la pestanya "Settings".
2. Desplaça't cap avall fins a la secció "GitHub Pages".
3. A la secció "Source", selecciona "main" com a branca i "/docs" com a carpeta.
4. Fes clic al botó "Save".
5. Després de guardar, GitHub Pages generarà una URL per a la teva web corporativa. Aquesta URL tindrà el format `https://[usuari].github.io/[nom-del-repositori]`.

### Verificar el desplegament

Un cop hagis configurat GitHub Pages, espera uns minuts i després visita la URL proporcionada per verificar que la teva web corporativa s'ha desplegat correctament. Si tot està configurat bé, hauràs de veure la teva web en línia.

Si fas modificacions a la teva web corporativa, només has de fer commit i push dels canvis al repositori, i GitHub Pages actualitzarà automàticament la teva web en línia. Assegura't de verificar els canvis després de cada actualització per assegurar-te que tot funciona correctament, d'aquesta manera evites fer accions innecessàries de desplegament.

### Alta a Statcounter i afegir analítica a la web

Statcounter és una eina d'analítica web que et permet fer un seguiment del trànsit i el comportament dels visitants a la teva web corporativa. Existeixen eines similars com Google Analytics, però en aquest cas utilitzarem Statcounter per la seva facilitat d'ús i integració amb GitHub Pages.

Per afegir analítica a la teva web corporativa, segueix aquests passos:

1. Visita el lloc web de Statcounter [https://statcounter.com/](https://statcounter.com/) i crea un compte, no cal que utilitzis el compte de correu corporatiu, pots utilitzar un compte personal.
2. Un cop hagis creat el compte, inicia sessió i crea un nou projecte per a la teva web corporativa. Tria el pla gratuït.
3. Project URL: Introduïu la URL de la vostra web corporativa desplegada a GitHub Pages.
4. Project Title: Dona un nom al teu projecte (per exemple, "Web Corporativa de [Nom de l'Empresa]").
5. Tria "Invisible Counter" com a tipus de comptador, ja que no volem que el comptador sigui visible als visitants de la teva web.

Un cop hagis creat el projecte, Statcounter et proporcionarà un codi de seguiment que hauràs d'afegir a la teva web corporativa. Aquest codi és un fragment de JavaScript que has de col·locar abans de la etiqueta `</body>` al fitxer `index.html` de la teva web.

Un cop hagis afegit el codi de seguiment a la teva web corporativa, fes commit i push dels canvis al repositori de GitHub. Després de pujar els canvis, espera uns minuts i després visita el teu compte de Statcounter per verificar que el seguiment està funcionant correctament. Prova a que gent des de diverses ubicaciones: familiars, amics o col·legues entrin a la pàgina. Hauries de començar a veure les dades de trànsit i comportament dels visitants a la teva web corporativa. Documenta alguna captura dels resultats i la incorpores a la documentació del projecte.

Exemple d'informació de Statcounter:

![Statcounter I](https://statcounter.com/images/statcounter_summary_stats.png)

![Statcounter II](https://statcounter.com/images/statcounter_visitor_activity.png)

### Detalls finals

Al repositori veuràs que hi ha una secció anomenada "About" on pots afegir una descripció breu de la teva web corporativa, allà a "Website" pots afegir la URL de la teva web desplegada a GitHub Pages simplement marcant l'opció "Use your GitHub Pages website" i a "Topics" pots afegir etiquetes relacionades amb el teu projecte, com per exemple "web-corporativa", "github-pages", etc.
