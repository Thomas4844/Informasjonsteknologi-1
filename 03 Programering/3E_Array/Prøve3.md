# Prøve 3

## Oppgave 1

```javascript
let byer = [
    "Venezia",
    "Liverpool",
    "New York",
    "Lisboa",
    "Berlin",
    "San Francisco",
    "Amsterdam",
];
```

-   **a)** Legg Budapest til `byer` med en komando.
-   **b)** Skriv ut alle byene i `byer` med en løkke.
-   **c)** Lag en funksjon som plukker ut en tilfeldig by fra `byer` og skriver ut: Din 1. destinasjon er \_\_\_. Byen skal også fjernes fra `byer`.
-   **d)** Utvid c) med en løkke og skriv ut en tilfeldig nummerert liste med alle destinasjonene. 1. by, 2. by osv.

## Oppgave 2

```javascript
let partall = [];
```

-   **a)** Lag en løkke som fyller en array med partallene fra 2 til 30.
-   **b)** Skriv ut tallene som er større enn 8 og mindre enn 32.

## Oppgave 3

```javascript
let tall = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55];
```

-   **a)** Summer alle tallene i `tall`.
-   **b)** Skriv ut alle tallene i `tall` med indeksen: **i**:**talllet**
-   **c)** Bruk en løkke og legg til de 10 neste tallene i tallfølgen. og skriv ut resultatet.

## Oppgave 4

Kodelås med 4 siffer fra 0-9

-   **a)** Lag en funksjon som returnerer et tilfeldig tall fra 0-9.
-   **b)** Lag så en funksjon som returnerer en array med en 4-sifred tilfeldig kodekombinasjon. f.eks. `[3, 4, 3, 8]`.
-   **c)** Koden min er `[6, 4, 1, 5]`. Bruk en løkke og tell opp hvor mange forsøk du bruker på å generere en tilfeldig kode som er helt lik min. Skriv ut svaret.

## Oppgave 5

Et **skuddår**, eller **skotår**, er et år som har ett døgn mer enn et normalår: 29. februar. 2020 er skuddår, det neste blir 2024. Det er skuddår i hovedsak hvert fjerde år.

I den gregorianske kalenderen er det normalt skuddår hvert fjerde år – alle årstall som er delelige med 4 er skuddår, unntatt hundreårene (1700, 1800, 1900 osv.) som ikke er skuddår med mindre de er delelige med 400 (1600, 2000, 2400 osv.). Dermed ble 2000 et skuddår, mens 1900 ikke var skuddår og 2100 blir heller ikke skuddår.

Bruk denne informasjonen til å generere en array med de neste 50 skuddårene. Skriv ut resultatet.

## Oppgave 6

Lag en funksjon som tar en array med temperaturer og skriver ut temperaturen som er nærmest 0.

```javascript
console.log(nærmestNull([1, -2, -8, 4, 5]));
console.log(nærmestNull([10, -2, 7, 4, 1, -1, -1, 2, 9]));
console.log(nærmestNull([23, 18, 17, 22, 15, 20, 20]));
```

Utskrift:

```
1
1
15
```
