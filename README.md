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