# Vecka 44 - Krocken och kortet

## Question 1 - Agile

**English:** Agile, briefly, and the benefit: the line you moved, the sentence that remained.

**Svenska:** Agil, kort, och fördelen: raden ni flyttade, meningen som låg kvar.

**Answer:** Agil utveckling är att arbeta i korta rundor och leverera en liten, testbar del i taget, sedan justera efter feedback. Jag flyttade raden för `return` i `hamtaNamn` från backloggen till en färdig funktion, men sprintmålet låg kvar som en oförändrad mening: namnet skulle synas i webbläsaren. Fördelen var att jag kunde visa en fungerande del tidigt och bara ändra detaljerna som faktiskt behövde ändras.

## Question 2 - Scrum

**English:** Scrum with at least two concepts or roles you wrote, and how you used them.

**Svenska:** Scrum med minst två begrepp eller roller ni skrivit, och hur ni använde dem.

**Answer:** Jag använde sprintmål, produktbacklog och sprinttavla. Jag tog rollen som Product Owner när jag skrev kraven och acceptanskriterierna för US-1 till US-4, och rollen som utvecklare när jag byggde funktionerna. Varje User Story bröts ner till en rad i backloggen och flyttades från In Progress till In Review och Done.

## Question 3 - Git and GitHub

**English:** Git and GitHub with an example: a feature branch, an approval, the conflict.

**Svenska:** Git och GitHub med ett exempel: ett sidofack, en Approve, krocken.

**Answer:** Jag arbetade i repot `team-repo` på GitHub (`github.com/ihabau/team-repo`). Jag skapade sidofacket `feature/ihab` från `main`, ändrade bara `return`-raden i `hamtaNamn` och pushade branchen. Jag öppnade en Pull Request och läste `Files changed` innan jag mergade. När två sidofack hade ändrat samma rad uppstod en krock; jag behöll namnet från sprintmålet, tog bort markörerna och mergade igen.

## Reflection

**English:** Reflection, 3-5 sentences. One sentence you changed, if you used AI.

**Svenska:** Reflektion, 3–5 meningar. En mening ni ändrade, om ni använde AI.

**Answer:** Det svåraste var krocken i `hamtaNamn`, eftersom båda sidofacken hade ändrat exakt samma rad. Jag förstod först inte varför den andra Pull Requesten stannade, men teoriguiden hjälpte mig att se att HEAD var raden som redan låg i `main`. Jag valde namnet som sprintmålet angav i stället för att bara ta den övre raden. En mening jag ändrade innan den stämde var att krocken inte ”löstes automatiskt” – jag valde raden själv.

## Notis - planen ändrades

- **Rad:** `return` i `hamtaNamn`
- **Sidofack:** `feature/ihab` och `feature/ihab-krock`
- **Namn som behölls:** `Ihab Al Ubaidi` (sprintmålets namn)
- **Varför:** båda sidofacken utgick från samma `main` och ändrade samma rad. Den första PR:en gick in, den andra krockade. HEAD var redan `main`s rad, så jag behöll sprintmålets namn och tog bort markörerna.
