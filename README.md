# Fabrique landing pagina

Deze repo is gemaakt als deel van het sollicitatieproces bij Fabrique.

## Installatie

Om de website lokaal te draaien dien je de repo uit te checken en in de folder met een http-server te starten.

Indien je VSCode gebruikt raad ik de plugin Live Server aan.

Na het starten van de server, navigeer je naar localhost en poort waarop de server is gestart.
<br /><br />

# Aanpak

Voordat ik aan de opdracht begon, heb ik een eerste indruk even laten inzinken. Er werd vermeld wat wel en niet belangrijk is en heb op basis daarvan het design in stukken verdeeld:

## De vijf secties

- Landing met actie
- De vraag
- Propositie
- Tweede hero + actie
- Kaarten

## Wat is er belangrijk -- vanuit de opdracht en zelf naar het design kijkend

- Hoofdafbeelding waar content overheen scrollt
- Kleuren die matchen met deze afbeelding
- Groot lettertype, veel ruimte
- Responsive

## Waar ligt de uitdaging

Omdat ik nog niet eerder een website heb gemaakt waar alle content over de afbeelding heen scrollt, leek dit me de grootste uitdaging.

## Wat heb ik nodig

Ik heb voor mezelf een korte lijst gemaakt met resources die ik nodig heb, welke ik zelf ga schrijven en waar ik een library voor gebruik. Omdat ik zo dicht mogelijk op het design wilde werken, heb ik enkel voor het grid systeem en animatie een library gebruikt

- Grid systeem -> PureCSS omdat ik dan enkel de Grid module kon importeren
- AnimateOnScroll -> Simpele library om nieuwe content met animatie in te brengen
- Parallax Scrolling
- Eigen Button component
- Eigen Card component
- 2 fonts voor header en content
- Enkele inspirerende afbeeldingen

## Uitvoering

Ik ben begonnen met uitzoeken hoe het Parallax Scrolling effect precies werkt en heb de globale styling op te zetten:

- Header en content fonts implementeren en responsive maken

Vervolgens heb ik de eerste sectie gemaakt en de button styling. Eens ik deze op de goede plek stond, ging het maken van de andere secties redelijk vlot.

Nadat alle secties af waren heb ik wat animatie toegevoegd aan enkele stukken content en heb ik gecontroleerd of het geheel zowel op mobiel, tablet als desktop goed werkt. Hier merkte ik dat ik de Parallax Scrolling nog niet helemaal door heb want er begon best wat content te overlappen. Dit heb ik zo goed mogelijk proberen oplossen met de tijd die ik nog had. Omdat ik wel wat moois wil afleveren, ben ik wat over de opgegeven 'tijdslimiet' gegaan.

### Totale duur: +- 2u 45min

<br />

# Opmerkingen

Ik heb enkele spelfouten opgemerkt in het design en ook dat er Nederlands en Engels door elkaar wordt gebruikt. Ik heb ervoor gekozen om alles in het Engels te doen om de template consistent te houden, in een echt project zou ik dit even terugkoppelen met een collega die over de content gaat.

Ook vond ik dat de titel <strong>'Wat levert het je op?'</strong> nogal gek geplaatst staat of nog een tekstje eronder mist. Dit zou ik ook nog even overleggen met een ontwerper.
