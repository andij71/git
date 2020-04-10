# Arbeiten mit git

## Neues Repository erstellen
git init

## Konfiguration (Global) 
git config --global user.email "E-Mail"
git config --global user.name "Name"


## Add und Commit
git add */dateiname
git commit -m "Commit-Nachricht"


## Remote (z.B. Github) hinzufügen
git remote add origin <server>


## Auf Remote hochladen
git push origin master

## Branching

### Branch erstellen und wechseln
git checkout -b feature_x
oder
git branch feature_x
git checkout feature_x


### Branch wieder löschen
git branch -d feature_x

### Branches anzeigen
git branch

### Branch in das enfernte Repo hochladen
git push origin <branch>
oder
git push --set-upstream origin new


## Merge
git checkout master
git merge <branch>
git push



## letzten Stand vom entfernten Repository holen:
git fetch origin
git reset --hard origin/master