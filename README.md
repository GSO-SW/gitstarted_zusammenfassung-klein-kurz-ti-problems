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
	## Das GitHub Student Developer Pack ist ein kostenloses Angebot von Entwicklertools, das auf Studenten beschränkt ist und Cloud-Ressourcen, Programmiertools und Support sowie GitHub-Zugang umfasst.