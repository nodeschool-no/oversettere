# Velkommen til repo'et for de som oversetter NodeSchool materiale

Diskusjoner rundt oversettelser ligger som [issues](https://github.com/nodeschool-no/oversettere/issues).

Formålet er å hjelpe hverandre oversette NodeSchool materiale. Allerede er [NodeSchool.io oversatt til norsk](http://nodeschool.io/nb-no/). [Workshopper](https://github.com/workshopper/workshopper) er i ferd med å oversettes. Største jobben ligger i å oversette workshops, ikke alle er mulig å oversette pga tekniske ting.

## Komme igang med å bidra

Første mål er å få oversatt alle oppgaver i [learnyounode workshoppen](https://github.com/nodeschool-no/learnyounode). Den er forket til nodeschool-no:
- Finn en oppgave ved å se under [exercises](https://github.com/nodeschool-no/learnyounode/tree/norwegian/exercises) ved å se om det _ikke_ ligger en _problem-nb-no.md_ i katalogen.
- Deretter lag en issue for oppgaven i [oversetter repoet](https://github.com/nodeschool-no/oversettere/issues) og assign den til deg selv
- Lag en ny branch under [leanyounode forken](https://github.com/nodeschool-no/learnyounode) basert på [Norwegian branchen](https://github.com/nodeschool-no/learnyounode/tree/norwegian). For å se
- Oversett
- Lag en Pull Request til [Norwegian branchen](https://github.com/nodeschool-no/learnyounode/tree/norwegian) på vår fork hvor vi kan diskutere. (Det er litt kronglete å lage pull requesten. Pass på at du har riktig fork, så du ikke prøver å merge med master branchen)
- Når alt er i orden merger vi den inn i Norwegian branchen og legger den til i lista nedenfor

Når alt er gjort så sender vi en PR inn til Learnyounode.

## Status på oversettelser
Dette er prosjektene vi har tenkt å oversette i første omgang. Vi har alt oversatt [NodeSchool](http://nodeschool.io/nb-no) og Workshoper](https://github.com/workshopper/workshopper/).
- [Learnyounode](https://github.com/nodeschool-no/oversettere/milestones/Learnyounode%20oversettelse)
- [Javascripting](https://github.com/nodeschool-no/oversettere/milestones/Oversette%20javascripting%20workshop)

### Hvordan kjøre lokalt for å teste?

````
  $ cd <sti til der du klonet leanryounode>
  $ rm -rf node_modules/workshopper
  $ npm link ../<fil sti til der workshopper ligger clonet> 
  $ node learnyounode.js
````

### Begreper i NodeSchool verden brukt mange steder ifbm oversetting av NodeSchool materiale

- Workshopper (altså ordet, ikke workshops i flertall) oversettes ikke ettersom det er en modul [workshopper](https://github.com/workshopper/workshopper)
- En Workshop består av oppgaver. På engelsk er det Workshops og exercises
- Events oversettes med arrangement (eller noen ganger kan man også skrive "en NodeSchool")
