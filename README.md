Mein Git Lernjournal
Grundlagen
1. Frage: 3 Dinge, die die Commit speichert Antwort: Der Commit speichert grundlegend 3 Dinge. Wer
hat was verändert, was wurde verändert und warum wurde etwas verändert. Durch diese 3
Informationen entsteht für mich, wie für alle an dem Projekt Mitarbeitenden eine nachvollziehbare
Historik des gesamten Projektes.
2. Frage: Was ist der Stamm / Trunk bei der Versionskontrolle Antwort: Der Stamm ist das bereits
bestehende Gesamtprojekt, also die Hauptversion. An welchem entweder eine oder gleichzeitig
mehrere Personen arbeiten. Um dieses bereits bestehende Gesamtprojekt durch Änderungen nicht zu
gefährden, gibt es Möglichkeiten, während der fortlaufenden Bearbeitung an diesem Stamm mit
abzweigenden Ästen (sogenannten Branches) zu arbeiten. Gleichzeitig ist es möglich, dass sich
mehrere Personen an eigenen verschiedenen Ästen/Branches an dem Stamm/ der Hauptversion
betätigen. Wo jede Änderung in der Commit aus Frage 1 festgehalten wird.

Architektur
3. Frage: Was ist ein zentralisiertes Versionssystem Antwort: Das CVCS - das zentralisierte
Versionssystem wird von den beiden Varianten weniger benutzt. Es birgt hohe Gefahren des
Verlustes, da sich die Hauptversion, also der Stamm mit allen Änderungen an einem einzigen Ort
be nden. Ist dieser Ort nicht mehr zu erreichen, kann an dem Projekt nicht mehr weiter gearbeitet
werden. Kommt es zu dem Verlust der Hauptversion, ist es unwiederbringbar verloren. Ebenso ist das
lokale Arbeiten sehr eingeschränkt.
Beispiele für das zentralisierte Versionssystem sind: subversion (SVN), CVS, Perforce
4. Frage: Was ist ein verteiltes Versionssystem Antwort: Das DVCS - das verteilte Versionssystem bringt
viele Vorteile und Sicherheiten mit sich. Jeder Projektarbeiter erhält das gesamte Projekt als Kopie für
seine eigenen Tätigkeiten. Ein vollständiges Exemplar mit allen bisherigen Schritten. Es erleichtert
ganz wesentlich das lokale Arbeiten. Änderungen an dem Projekt werden im eigenen Ermessen zu
dem Hauptprojekt gepusht.
Beispiele für das vereilte Versionssystem sind: ekannte Beispiele: Git, Mercurial


