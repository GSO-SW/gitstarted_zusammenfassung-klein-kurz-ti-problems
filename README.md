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