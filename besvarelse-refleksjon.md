# Besvarelse på refleksjonspørsmålene

Ditt brukernavn på Oslomet: 

## Refleksjonsspørsmål Oppgave 1 

S1: Hva er fordelene med å bruke JSON i stedet for CSV for API-respons?
- Ditt svar: `JSON har evne til å strukturere data i hierarkier, `
  
S2: Hvordan kan en frontend-applikasjon (nettleser) bruke denne API-en?
- Ditt svar: `En webapp kan bruke api kall til backend ved å benytte f.eks javascript til å gjøre en GET request, dette kan være data som skal fylle ut tomme felter som er forberedt i forveien`

S3: Hvordan ville du testet denne API-en manuelt?
- Ditt svar: `Gå inn på alle endepunkter for å verifisere funksjonalitet via nettleser eller evt. postman`


## Refleksjonsspørsmål Oppgave 2

### Del a):

S1: Hva er Path Traversal (Directory Traversal), og hvorfor er det farlig?
- Ditt svar: `Path traversal benyttes for å finne filer som brukeren ikke skal ha tilgang til, eller eventuelt kartlegge oppbyggningen av tjenesten`

S2: Hvordan kan du beskytte koden din mot Path Traversal?
- Ditt svar: `.normalize() vil fjerne '..' og '/' fra teksten`


### Del b):

S1: Hva er SQL injection, og hvordan kan det oppstå i en webapplikasjon?
- Ditt svar: `SQLi sender manipulerte spørringer til en database.`

S2: Hvordan kan du beskytte deg mot SQL injection?
- Ditt svar: `Saniterte spørringer ved å forhindre ugyldig innhold i feltet`

S3: Hva er forskjellen på validering på frontend vs backend?
- Ditt svar: `Frontend validering kan forbigås ved å sende spørringer direktet via endepunktet`

S4: Hva er likheten mellom Path Traversal og SQL Injection?
- Ditt svar: `Hackeren prøver seg frem uten å vite om innholdet er gyldig eller ikke`

  
## Refleksjonsspørsmål Oppgave 3

S1: Hva er forskjellen mellom POST og PUT?
- Ditt svar: `PUT erstatter og POST lager ny`
  
S2: Hvordan sikrer du at data forblir konsistent når du oppdaterer en fil?
- Ditt svar: `Sørger for at innholdet følger et schema`

S3: Hva skjer hvis to brukere prøver å oppdatere samme student samtidig?
- Ditt svar:  `Den siste som overskriver vinner`

## Refleksjonsspørsmål Oppgave 4 

S1: Hva er implikasjonene av å tillate DELETE-operasjoner?
- Ditt svar: `Kan misbrukes eller føre til permanent datatap`

S2: Hvordan ville du implementert "soft delete"?
- Ditt svar: `Binær verdi i hver rad som markerer om feltet er slettet eller ikke`

S3: Hvordan kan du sikre at statistikk er korrekt når data endres?
- Ditt svar: `Ny spørring hver gang endepunktet sendes`
 


SLUTT.
