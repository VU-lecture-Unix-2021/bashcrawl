1. Darbas vyks linux terminale, kuriame veikia `bash` aplinka. Ar terminale yra `bash` aplinka, galime pasitikrinti įvykdydami tinkamą komandą `echo`, kurios atsakymą matysite terminale:
```bash
$ echo $SHELL
/bin/bash
```

2. Jei nesate įsirašę, įsirašykite linux programėlę `git`.

3. Pereikite į pagrindinį savo katalogą ir įsirašykite mokomąjį paketą
```bash
$ cd
$ git clone https://gitlab.com/slackermedia/bashcrawl.git bashcrawl
```
Atkreipkite dėmesį, kad šis `learn.md` failas priklauso kitai, senai talpyklai, sukurtai pasiskolinant originalo failus iš gitlab'o.

4. Pereikite į naujai atsiradusį katalogą:
```bash
$ cd bashcrawl
```

5. Pasitikrinkite, padarėte gerai: įvedę komandas `pwd` bei `git status` turėtumėte matyti panašią informaciją:
```bash
$ pwd
/home/uspecas/bashcrawl
$ git status
# On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```
Jei paskutinis `pwd` programos atsakymas nėra `bashcrawl` arba matote tokią informaciją:
```bash
$ git status
fatal: Not a git repository (or any of the parent directories): .git
```
pasitikrinkite, ar gerai įvedėte komandas.

6. Dabar pradėsime naudoti mokomąją programą `bashcrawl`, kurią sukūrė gitlab.com vartotojas `slackermedia`. Programa padės įprasti prie `bash` terminalo komandų.

Programa parašyta laikantis "Dungeons & Dragons" kompiuterinių žaidimų principu. Šių žaidimų tikslas būdavo tiesiog tyrinėti požeminį labirintą, skaitant užrašus, tyrinėjant randamus daiktus, renkant turtus ir susigrumiant su baidyklėmis.


Kaip galėtumėte perskaityti `README.md` faile (ir turėtumėte jį perskaityti), pirmasis žingsnis - žengti į požemį ir perskaityti pirmąjį raštelį:
```bash
$ cd entrance    # žengiame į požemį
$ ls             # patikriname, kas jame yra
$ cat scroll
```
O tada - vaikščiokite po požemio kambarius, įsidėmėdami savo naudojamas ir patarimuose pateikiamas komandas. Ankstesnėje šio žaidimo versijoje buvo ir "paslėptų" katalogų.
