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
