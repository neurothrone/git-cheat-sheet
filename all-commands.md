# Git Cheat Sheet – 60 kommandon

| Git-kommando                                   | Beskrivning                                     | Fel/problem & lösning (om tillämpligt) |
| ---------------------------------------------- | ----------------------------------------------- | -------------------------------------- |
| git init                                       | Skapar nytt Git-repostitory                     |                                        |
| git clone <repository-url>                     | Klonar ett repo från en URL till din dator.     |                                        |
| git status                                     | Visar ändringar, staged och unstaged filer.     |                                        |
| git help <command>                             | Visar hjälp för ett specifikt kommando.         |                                        |
| git config --list                              | Visar alla aktuella Git-inställningar.          |                                        |
| git config user.name "Your Name"               | Sätter användarnamn för Git.                    |                                        |
| git config user.email "your.email@example.com" | Sätter e-postadress för Git.                    |                                        |
| git add <file>                                 | Lägger till en fil till staging (Commit).       |                                        |
| git add .                                      | Lägger till alla ändrade filer i aktuell mapp.  |                                        |
| git add -A                                     | Lägger till alla ändringar (ändrade, borttagna) |                                        |
| git commit -m "Commit message"                 | Sparar ändringar med ett meddelande.            |                                        |
| git diff                                       | Visar skillnader mella arbkatalog & staging.    |                                        |
| git diff --staged                              |Visar skillnader mellan staging och senaste commit. |                                     |
| git log                                        | Visar commit-historiken.                        |                                        |
|git show <commit-hash>                          |Visar detaljerad info om en commit.              |                                        |
|git branch                                      |Visar alla grenar och markeraraktuell.           |                                        |
|git branch <branch-name>                        |Skapar en ny gren med angivet namn.              |                                        |
|git commit -am "Add and commit tracked files"  | Lägger till OCH committar ändrade, redan spårade filer. |                                 |
| git help                                      | Visar hjälpsystemet för Git. Används för att få översikt av tillgängliga kommandon. |