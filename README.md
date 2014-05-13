Ordnungen der Studierendenschaft der Otto-von-Guericke-Universität Magdeburg
============================================================================

Dieses Git Repository enthält die Ordnungen der Studierendenschaft der OvGU
Mageburgim [Markdown-Format](http://daringfireball.net/projects/markdown/).
Als Quelle dienen die PDF-Versionen der Ordnungen von
[stura-md.de/downloads](http://stura-md.de/downloads).


Warum Git?
----------

Jeder kann den aktuellen Stand von Ordnungen sehr einfach online finden.
Allerdings ist die Entstehung, die historische Entwicklung und die
Aktualisierung von Ordnungen nicht einfach und frei nachvollziehbar. Das liegt
daran, dass Ordnungen nur in ihrer aktuellsten Version präsentiert werden und
Änderungen an diesen Ordnungen nicht maschinenlesbar vorliegen. Dies soll hier
geändert werden: die aktuellste Version einer Ordnung wird hier mit Git
versioniert gespeichert. Das erlaubt es, die Mächtigkeit von Git auf Ordnungen
und deren änderungen anzuwenden. Das Einpflegen der kompletten
Ordnungen und ihrer Vergangenheit in Git ist das ferne Ziel.

Pull Requests (Änderungsvorschläge)
------------------------------------

Pull Requests (Änderungsvorschläge) können gerne geöffnet werden. Natürlich werden nur solche
gemergt, die tatsächlich vom Studierendenrat verabschiedet wurden und aktuelle
Ordnungen geworden sind.

Dennoch sind Änderungsvorschläge an Ordnungen als Pull Request nützlich.
Die Änderungen lassen sich einfacher im Kontext verstehen, können direkt an der
Ordnung diskutiert und nachvollziehbar verändert werden.



Warum Markdown?
---------------

Ordnungen sind Prosa, sie enthalten keine maschinenlesbare Semantik. Eine
Auszeichnungssprache wie XML verringert die Menschenlesbarkeit, erschwert die
maschinelle Erkennung von Unterschieden und beinhaltet viel überflüssige
Syntax.

Markdown ist eine intuitive Formatierung von Text, die ohne zusätzliche
Programme für Menschen les- und schreibbar ist. Das passt zu Gesetzestexten,
die nur minimale Formatierung benötigen. Weiterhin lässt sich Markdown in
andere Formate wie HTML oder PDF konvertieren und ist damit
maschinen-formatierbar.


Fehler und Bitte um Mithilfe
----------------------------

Es wird kein Anspruch auf Korrektheit erhoben. Bitte verlassen Sie sich nur
auf offizielle Quellen.

Die Konvertierung von PDF nach Markdown erfolgt manuell und ist nicht Fehlerfrei.
Das liegt daran, dass die Ordnungen im PDF-Format
das Markup auch für stilistische Auszeichnungen statt nur für semantische
Auszeichnungen nutzen. Dies erschwert eine Konvertierung und führt zu
fehlerhaftem Markdown. Da fehlerhaftes Markdown immer noch gut lesbar ist,
führt dies erst bei einer Weiterverarbeitung zu Problemen.

Mithilfe ist erwünscht.

Ursprung
--------
Die Idee dieses Repositories und die Vorlage für dies README stammen von [bundesgesetze](https://github.com/bundestag/gesetze)
