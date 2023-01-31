$ git cherry-pick [commit]
ermöglicht einzelne commits von einem Branch in einen anderen zu übertragen, anstatt den gesamten branche zu mergen.

$ git rebase
schiebt den derzeitigen Branch in einer ausgewählten Branch Historie.

$ git merge --abort
bricht einen laufenden merge vorgang ab

$ git merge [branch-name]
führt einen merge des angegebenen merge in den aktuellen branch durch.

$ git checkout [branch-name]
Wechselt zwischen Branches. (Verschiebt den Head an den gewünschten Branch)

$ git branch [branch-name]
erschafft einen neuen Branch am derzeitigen Commit (Ein branch ist eine weiteres Zweig um parallel an mehrere Versionen des Projektes zu arbeiten)

$ git checkout [commit-hash]
wechselt zum commit mit dem angegebenen Hash wert (Man befindet sich dann einem abgekoppelten zweig in dem man einen neuen Branch erstellen kann)

$ git revert 
macht einen commit rückgängig in dem es einen neuen commit hinzufügt

$ git init
  erstellt ein lokales repository

$ git add [Datei]
  fügt eine einzelne Datei der "Staging Area" hinzu

$ git add *
  fügt alle Dateien der "staging Area" hinzu
  Wenn eine Datei gelöscht wurde muss man diese einzeln
  commiten

$ git status
  zeigt den Satus der geänderten Dateien an

$ git reset --mixed
  das commiten wird rückgängig gemacht und die Dateien sind
  nicht mehr gestaged (--mixed kann weggelassen werden, weil es als Standart
  befehl für reset festgelegt ist)

$ git reset --soft
  das commiten wird rückgängig gemacht aber die Dateien sind
  noch in der "Staging Area"

$ git reset --hard
  sowohl das commiten als auch die änderungen an den Dateien
  werden rückgängig gemacht

$ git commit -m "[Commit Nachricht]"
  Die Änderungen die sich auf der "Staging Area" befinden werden
  zu einem neuen Commit

$ git log
  Zeigt die Historie des aktuellen Branches

$ git log --all
  zeigt alle Commits von allen Branches

$ git log --all --graph
  zeigt alle Commits von allen Branches als Graph

## GitHub Befehle:

# 1. git clone [url]
Der 'clone' Befehl kopiert das verwiesene Repository in das bestehende Verzeichnis. Das Repository wird durch die URL angegeben, die von GitHub entnommen werden kann.

# 2. git push
Der 'push' Befehl bewegt das eingeführte und gleichzeitig bearbeitete Repository zurück nach GitHub.

# 3. git fetch
Der 'fetch' Befehl fügt dem Repository (in dem man sich gerade befindet) den Commit mit dem remote-Branch hinzu. Diese Referenz markiert den aktuell gesetzten Commit im origin/master Commit-Baum.

# 4. git pull
Der 'pull' Befehl fügt wie der 'fetch' Befehl dem Repository den Commit mit dem remote-Branch hinzu, außer dass der 'merge' Befehl ebenfalls ausgeführt wird. Somit kann man den entstehnden Merge Konflikt direkt lösen ohne vorher den 'merge' Befehl extra ausführen zu müssen.

# 5. git push --set-upstream origin [branch]
Der '--set-upstream' Befehl ist eine Erweiterung für den 'push' Befehl, die bei der Übergabe des Repositorys nach GitHub einen optionalen bzw. zusätzlichen Branch erstellt.

# Die Webseite GitHub:
	## Git Hub User können unter "Issues" verscheidene Fehler im Code kommentieren. Dieses Vorgehen dient der Überschaubarkeit des Verwalters. 
	## Des Weiteren können GitHub User mit "Pull Requests" eine Anfrage auf einen Merge an den Verwalter schicken. Somit endet der Master/Origin nicht durcheinander.
	## Beide Funktionen gehen Hand in Hand. So besteht die Möglichkeit, einem Issue einen Pull Request anzuhängen.
	## Der sogenannte Token ist ein Schlüssel, der in einer bestimmten Zeit abläuft. Er lässt sich generieren und dient der Authentifizierung. 
	## Eine "README"-Datei kann optional jedem Projekt angefügt werden. Es dient als eine Art "Titelblatt" für den Repository. 
	## Ein Repository ist ein Projekt, dass in GitHub erstellt werden können. 
	## Der Repository auf GitHub ist der sogenannte Remote Repository, da hier jeder seinen Code commiten kann.
	## GitHub und Git gehen Hand in Hand. 
	## Git sorgt für die lokale Verwaltung und GitHub die fasst alle Versionen vom Team im "Remote-Repository" zusammen.
	## Zudem bietet GitHub eine Möglichkeit sich mit anderen Entwicklern auszutauschen. Wie Social Media.
	## Github Gist ermöglicht es GitHub-Nutzern, Codestücke oder andere Notizen zu teilen.
	## GitHub Flow ist ein leichtgewichtiger, branchbasierter Workflow für regelmäßig aktualisierte Bereitstellungen.
	## GitHub Pages sind statische Webseiten, die ein Projekt hosten und Informationen direkt aus dem GitHub-Repository einer Person oder Organisation beziehen.
	## Mit GitHub Desktop können Benutzer von Windows- oder Mac-Desktops aus auf GitHub zugreifen, statt die GitHub-Website aufzurufen.