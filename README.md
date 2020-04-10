# Arbeiten mit git

## Neues Repository erstellen
git init

## Konfiguration (Global) 
git config --global user.email "E-Mail" <br>
git config --global user.name "Name" <br>


## Add und Commit
git add */dateiname <br>
git commit -m "Commit-Nachricht" <br>


## Remote (z.B. Github) hinzufügen
git remote add origin <server> <br>


## Auf Remote hochladen
git push origin master <br>

## Branching

### Branch erstellen und wechseln
git checkout -b feature_x <br>
oder <br>
git branch feature_x <br>
git checkout feature_x <br>


### Branch wieder löschen
git branch -d feature_x <br>

### Branches anzeigen
git branch <br>

### Branch in das enfernte Repo hochladen
git push origin <branch> <br>
oder <br>
git push --set-upstream origin new <br>


## Merge
git checkout master <br>
git merge <branch> <br>
git push <br>



## letzten Stand vom entfernten Repository holen:
git fetch origin <br>
git reset --hard origin/master <br>