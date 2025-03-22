# Git Cheat Sheet – Grupparbete

## Syfte

Denna lathund innehåller 60 Git-kommandon (15 per person) med korta beskrivningar och eventuella fel/problem som
uppstod. Målet är att lära sig grunderna i Git och arbeta tillsammans med branches, commits och merge.

## Steg-för-steg – Så här gör du

### 1. Skapa din personliga branch

Utgå från `dev` branchen och skapa en ny branch med namnet på formen: `namn-dev`. Exempel: `niklas-dev`.

### 2. Lägg till dina kommandon

Öppna filen `all-commands.md`. Scrolla längst ner i tabellen och fyll i dina 15 kommandon. Varje rad ska innehålla:

- Kommandot
- En kort beskrivning
- Eventuellt fel/problem och hur det löstes, eller – (tomt) om inget fel uppstod

### 3. En commit per kommando

Varje kommando ska läggas till i en separat commit. Commit-meddelandet ska tydligt beskriva vilket kommando det gäller.

### 4. Skicka upp din branch

När du är klar, skicka upp din branch till vår remote repository.

### 5. Skapa en pull request

Skapa en pull request till `dev` branchen. Vi granskar tillsammans innan det mergas in.

## Exempel på tabellrader (Markdown)

| Git-kommando | Beskrivning                                    | Fel/problem & lösning (om tillämpligt) |
|--------------|------------------------------------------------|----------------------------------------|
| git status   | Visar aktuellt status för filer i repositoriet | –                                      |
| git add .    | Lägger till alla ändrade filer i staging       | –                                      |

## När allt är klart

När alla har lagt in sina kommandon och vi är nöjda med innehållet i `dev` branchen, gör vi en gemensam merge till
`main`.
