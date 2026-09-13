# Laboration 2 - Versionhantering och publicering

## Om webbplatsen

Detta är en webbplats som jag skapade i Laboration 1. Webbplatsen innehåller en startsida, en sida om mitt intresse för katter och en kontaktsida.

## Tekniker som använts

- **HTML** - används för webbplatsens struktur och innehålle.

## Publicerade versioner

Webbplatsen finns publicerad på dessa plattformar:
- [Github Pages](https://s-web26.github.io/dt224g-laboration2/)
- [Netlify](https://prismatic-bonbon-a2bf1a.netlify.app/)

## Git och versionhantering

### Vad är skillnaden mellan git add och git commit?
`git add` används för att välja vilka ändeingar som ska tas med i nästa commit. `git commit` sparar sedan de valda ändringarna i Git historiken.

### Varför använder man branches istället för att jobba direkt i main?
En branch är en separat gren av projektet där man kan göra ändringar utan att direkt ändra huvudversionen. När ändringarna är klara kan de slås ihop med huvudgrenen.

### Vad händer rent praktiskt när man gör en merge?
Merge används för att slå ihop ändringar från en branch med en annan. I laborasionen används merge för att slå ihop ändringarna från `dev` med `main`.

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex Netlify?
GitHub andvänds för att lagra projektet och dess versionhistorik när man pushar sin kod. Netlify används för att publicera webbplatsen så att den går att besöka på webben.

### Om du vill exkludera någon fil i projektet från versionhanteringen, hur gör du då?
Man kan lägga till filen i en `.gitignore`-fil. Då kommer Git att ignorera filen.