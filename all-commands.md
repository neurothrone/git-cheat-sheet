# Git Cheat Sheet – 60 kommandon

| Git-kommando                           | Beskrivning                                                   | Fel/problem & lösning (om tillämpligt)                                                             |
|----------------------------------------|---------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| git tag                                | Visar alla taggar i repositoriet                              | –                                                                                                  |
| git tag <tag-name>                     | Skapar en enkel tagg med valt namn                            | –                                                                                                  |
| git tag -a <tag-name> -m "Tag message" | Skapar en annoterad tagg med meddelande                       | –                                                                                                  |
| git push origin <tag-name>             | Skickar en tagg till fjärr-repositoriet                       | –                                                                                                  |
| git mv <old> <new>                     | Byter namn på eller flyttar en fil                            | –                                                                                                  |
| git blame <file>                       | Visar vem som ändrat varje rad i en fil                       | –                                                                                                  |
| git shortlog                           | Visar summering av commits per användare                      | –                                                                                                  |
| git archive -o latest.zip HEAD         | Skapar en zip-fil av senaste versionen av projektet           | –                                                                                                  |
| echo "filename.txt" >> .gitignore      | Lägger till en fil i .gitignore                               | –                                                                                                  |
| git rm --cached filename.txt           | Tar bort en fil från Git men inte från datorn                 | Filen hittades inte – lösning: kontrollerade stavning, använde git status för att hitta rätt namn. |
| git log --graph --oneline --all        | Visar grafiskt commit-historik i en rad per commit            | –                                                                                                  |
| git show                               | Visar detaljer om senaste commit                              | –                                                                                                  |
| git reflog                             | Visar historik över branch-rörelser och commits               | –                                                                                                  |
| git diff HEAD~1 HEAD                   | Visar skillnad mellan senaste commit och den innan            | –                                                                                                  |
| git commit --amend                     | Ändrar senaste commit-meddelandet eller lägger till ändringar | Fick fel "nothing to amend" – lösning: använde git add först, sedan git commit --amend.            |
| git checkout main                      | Byter till main-branchen                                      | –                                                                                                  |
