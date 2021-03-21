#Notes
git init
git clone
git status
git add
git rm --cached <file>... //cofnąć do unstage
git reset //usuwa wszystkie pliki dodane do stage do unstage
git commit -m "Message"
git restore README //cofa zmiany
git log // wyswietla commity
git revert <hash> // cofniecie commita
git show <hash> //wyświetla informacje o commitcie
git commit --amend // zmiana informacji (Message) w commicie
git push //publikuje lokalne zmiany w repozytorium zdalnym
git pull //pobiera zmiany ze zdalnego repozytorium
git checkout -b NazwaBrancha //utworzenie nowej gałęzi