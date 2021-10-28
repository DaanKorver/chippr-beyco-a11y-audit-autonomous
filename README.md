# Rapportage webtoegankelijkheid-test voor Beyco
![Beyco website mockup](assets/mockup.jpg)
Dit document is een template voor een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschilelnde tests kunnen worden vergeleken.

Datum webtoegankelijkheid-test: 28-10-2021

Webtoegankelijkheid-test uitgevoerd door: Daan Korver

## Inhoudsopgave
  * [Samenvatting](#samenvatting)
  * [Achtergrond bij de evaluatie](#achtergrond-bij-de-evaluatie)
  * [Afbakening](#afbakening)
  * [Beoordelaars](#beoordelaars)
  * [Beoordelingsproces](#beoordelingsproces)
  * [Testresultaten en aanbevelingen](#testresultaten-en-aanbevelingen)
  * [Bijlagen](#bijlagen)

## Samenvatting
Dit rapport beschrijft in hoeverre de website [beyco.nl](https://www/beyco.nl) overeenstemt met de Web Content Accessibility Guidelines (WCAG) van het W3C. Na de achtergrondinformatie en afbakening van de test worden beoordelaars, beoordelingsproces en testresulltaten beschreven.

Conslusie van deze test luidt dat de {Frontend Design & Development} website {niet voldoet/ voldoet/ dichtbij voldoen is aan} de WCAG 2.1, op niveau {A/ AA/ AAA}. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.

## Achtergrond bij de evaluatie
De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 28-10-2021. De website kan ondertussen aangepast zijn.

## Afbakening
[beyco.nl](https://www.beyco.nl)

Beyco is een platform waarbij je je koffie kan kopen en verkopen.

URLs die mee zijn genomen in de beoordeling:
* [www.beyco.nl](https://www.beyco.nl)


Test data:
* 28-10-2021
* 29-10-2021

Taal: Nederlands

## Beoordelaars
Daan Korver  
Student  
daan.korver@hva.nl  
Nederlands


## Beoordelingsproces
Deze beoordelings is uitgevoerd op WCAG 2.1 Niveau AA

De tools die zijn gebruikt voor deze beoordeling zijn de volgende:
* [A11Y Checklist](https://www.a11yproject.com/checklist/)
* [WCAG Guidelines Overview](https://www.w3.org/WAI/standards-guidelines/wcag/)
* [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)

## Testresultaten en aanbevelingen
{Samenvatting van testresultaten, bv. deze website {voldoet/ voldoet niet/ is dichtbij aan voldoen} aan de WCAG 2.1, op niveau A, AA of AAA.}

### Sterke punten
{Samenvatting van de de sterke punten ...}

### Ontoegankelijke punten
{Samenvatting van ontoegankelijke punten ...}

### Checklist 

##### Content

##### Global code

##### Keyboard

##### Images

##### Headings

##### Lists

##### Controls
* All inputs in a form are associated with a corresponding  ```
<label>``` element.   
Label elementen missen het ```for``` attribuut en bevatten geen tekst
* 
##### Tables

##### Forms



##### Media

##### Video

##### Audio

##### Appearance

##### Animation

##### Color contrast

##### Mobile and touch

{Schrijf per check wat er uit de test is gekomen}

{Neem links op naar de WCAG 2.1 succescriteria en technieken voor de ontoegankelijke punten}

{Voeg per check specifieke rapportage(s), of links naar rapportage(s) toe in de Wiki, bv. screenshots van tests}

{Schrijf per check aanbevelingen voor het verbeteren van ontoegankelijke punten}

{Beschrijf of verwijs per check naar een programma voor het monitoren van webstite toegankelijkheid, her-beoordeling aan de hand van beoordelingsinstrumenten etc.}

## Bijlagen

### Lighthouse Desktop Before
Dit is de huidige score van beyco zonder enige optimalisatie.
![Lighthouse Desktop Before](assets/lighthouse_desktop_before.png)

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
