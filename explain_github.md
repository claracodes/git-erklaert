# Kollaborativ Arbeiten auf GitHub

## Git und GitHub

GitHub ist die größte Plattform, die es Developern, Engineers und Designern erlaubt ihre Arbeit zu teilen und im Team an einem Projekt zu arbeiten. Sie basiert auf git, dem version control system, welches jede Änderung in einer Datei nachverfolgen kann und es so möglich macht, nicht nur die komplette Historie einer Bearbeitung nachzuvollziehen, sondern darin auch zu erkennen, welcher Autor welchen Teil einer Datei verfasst hat.
Festzuhalten ist, dass git und GitHub nicht konkruent sind. Git ist das Werkzeug, welches Versionskontrolle ermöglicht. [GitHub](https://github.com/) ist eine Plattform auf der man Dateien (häufig Code) speichern und verwalten kann. Andere Anbieter sind [Gitlab](https://gitlab.com) oder [BitBucket](https://bitbucket.org/).

## Wie funktioniert die Versionskontrolle?

Wir alle kennen es: wir arbeiten an einem längeren Dokument und speichern immer wieder verschiedene Versionen ab.

Bachelorarbeit.docx
Bachelorarbeit_final.docx
Bachelorarbeit_final_final.docx
Bachelorarbeit_final_jetzt_aber_wirklich.docx

Keine besonders sichere Methode, um tatsächlich den letzten Stand eines Dokuments zu speichern. Noch komplizierter wird es, wenn nicht nur einzelne Bearbeiter, sondern ein ganzes Team an einem Dokument arbeitet. Wird dann nur einmal nicht die richtige Datei geteilt, geht wertvolle Arbeit verloren.

Git kann hier aushelfen. Jeder Arbeitsschritt, sei es ein fertiggestelltes Feature beim Coden oder ein Absatz beim Schreiben, sollte mit einem sogenannten _commit_ abgeschlossen werden. So wird der aktuelle Stand der Arbeit abgespeichert. Man kann sich eine Liste aller commits ansehen und seine Arbeit in den Stand vorheriger Commits zurückversetzten. Dies macht insbesondere beim Programmieren Sinn, da nie sukkzesiv in einer einzelnen Datei gearbeitet wird, sondern jeweils in mehreren Dateien.
In einem commit wird nicht nur die aktuelle Version gespeichert, sondern auch die Zeit und der Bearbeiter.

GitHub kommt dann als neues Level zum Arbeitsprozess hinzu. Ein Ordner, mit Dateien auf dem eigenen Computer kann auf GitHub hochgeladen und dort verwaltet werden. Dieser Arbeitsschritt sollte ein- oder mehrmals am Tag durchgeführt werden. GitHub dient dabei auch als Backup, im Falle eines Problems mit der lokalen Datei. Im Fachjargon spricht man beim Hochladen von _pushen_, da der Befehl, der im Terminal ausgeführt wird, `git push` lautet.



