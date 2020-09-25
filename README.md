# GitTut
## GIT Short Tutorial for University students

Branching + Remote Repository

We can choose 3 areas:
```
working directory - katalog roboczy
stage area - przechowalnia
.git folder - repozytorium
```

**Main actions:**

                       
working directory     -----git add.---->    stage area
             
  stage area          -----git commit---->    .git folder
                
  .git folder         -----git checkout---->    working directory
  

**File Status:**

modified ---git add---> staged ---git commit---> comitted

**Basic Git commands:**
```
git status - status zmian
git add - dodanie pliku na stage, kolejki oczekiwania
git commit - dodanie pliku do .git
git branch //nazwa// -  nowego rozgałęzienia
git branch -D //nazwa// - usuwanie rozgałęzienia
git clean - usunięcie plików
git clean -n - wyświetlenie plików przed ich usunięciem
git clean -nd - wyświetlenie katalogów i plików przed ich usunięciem
git clean -idf - usuwanie plikow i katalogow w trybie interaktywnym
git reset - przenoszenie plików ze stage do working directory, odwrotność git add
git checkout //nazwapliku//- przywrocenie poprzedniej wersji pliku
git rm/mv //nazwapliku// - usuwanie/przenoszenie pliku z repozytorium o podanej nazwie
git log --oneline - wyświetlenie logów w skondensowanej wersji
git log --author="..."
git log --oneline --author="..."
git log --grep="view"
git log --oneline -3
git log --oneline -- //nazwapliku//
git log --oneline --summary -- //nazwapliku// - skrócona informacja
git log --oneline --stat
git log --format="%h %an %s (%cr)"
git shortlog - historia zmian z podziałem na użytkowników
git stash - odłożenie zmian na stos
git stash pop - przełożenie zmian ze stosu na wybrane miejsce
git stash push -m "..." - odłożenie zmian na stos z komentarzem
git stash list - lista zmian obecnych na stosie
git stash apply - przywracanie zmian do katalogu roboczego i pozostawienie ich na stosie
git revert - odwrócenie zmian z wybranego commit'u
git log --graph --decorate --all --oneline
git merge - łączenie 2 różnych plików
subl //nazwa// - modyfikowanie pliku
git tag //nazwa// - nadanie tagu
git tag - wyświetlenie tagów
git show //nazwa// - informację o commicie wskazywanym przez tag
git tag //nazwa// -a -m "..." - przypisanie informacji o autorze oraz komentarza do wybranego tagu
```
