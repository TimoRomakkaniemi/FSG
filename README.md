# FSG Financial Services Group - Verkkosivusto

Innovatiivinen verkkosivusto FSG Financial Services Groupille, joka yhdistää modernin graafisen ilmeen, 3D-animaatiot ja tekoälyavusteiset finanssivisualisoinnit.

## Tekniset ominaisuudet

- **Responsiivinen design**: Toimii täydellisesti kaikilla laitteilla (mobiili, tabletti, työpöytä)
- **3D-animaatiot**: Interaktiiviset fotorealistiset eläinhahmot React Three Fiberin ja Three.js:n avulla
- **Moderni frontend-teknologia**: Next.js, React, Framer Motion
- **Datavisualisointi**: D3.js-pohjainen finanssidatan interaktiivinen visualisointi
- **SEO-optimoitu**: Hakukoneystävällinen rakenne ja meta-tagit

## Käyttöönotto

### Vaatimukset

- Node.js (versio 16 tai uudempi)
- npm tai yarn
- Git

### Asennus

1. Kloonaa repositorio:
```bash
git clone https://github.com/yrityksesi/fsg-website.git
cd fsg-website
```

2. Asenna riippuvuudet:
```bash
npm install
# tai
yarn install
```

3. Käynnistä kehityspalvelin:
```bash
npm run dev
# tai
yarn dev
```

4. Avaa selaimessa osoite [http://localhost:3000](http://localhost:3000)

### 3D-mallien lisääminen

Ennen sivuston käyttöönottoa, lisää fotorealistiset 3D-mallit hakemistoon `public/models/`:

- `sloth.glb` - Laiskiainen (Pitkäjänteinen sijoittaminen)
- `kangaroo.glb` - Kenguru (Ketterä markkinareagoiminen)
- `monkey.glb` - Apina (Analyyttinen datankäsittely)

Katso lisäohjeet tiedostosta `public/models/README.md`.

## Tuotantoon vienti

Rakenna tuotantoversio:

```bash
npm run build
# tai
yarn build
```

Käynnistä tuotantoversio:

```bash
npm start
# tai
yarn start
```

## Mukautus ja jatkokehitys

### Värimaailman muokkaus

Päävärit löytyvät tyylitiedostosta `src/styles/globals.css`. Sinisen sävyjä voi muokata yrityksen brändin mukaisesti.

### Blogi-ominaisuuden käyttöönotto

Sivustoon on integroitavissa tekoälypohjainen blogiominaisuus, joka generoi SEO-optimoitua sisältöä. Tätä varten voidaan käyttää esimerkiksi:

1. OpenAI:n API:a sisällön generointiin
2. Next.js:n API Routes -ominaisuutta rajapinnan luomiseen
3. Tietokantaa (esim. MongoDB tai PostgreSQL) sisällön tallentamiseen

### Kieliversioiden lisääminen

Kieliversioiden toteuttamiseen suositellaan käytettäväksi next-i18next -kirjastoa.

## Ylläpito ja tuki

- Päivitä riippuvuudet säännöllisesti
- Huolehdi 3D-mallien optimoinnista 
- Testaa toimivuus eri selaimilla säännöllisesti

## Tekijät

FSG Financial Services Group Oy

---

© 2024 FSG Financial Services Group Oy. Kaikki oikeudet pidätetään.
