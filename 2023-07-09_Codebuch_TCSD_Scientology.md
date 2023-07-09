 ,
"Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.",
Achtung: das Codebuch wird immer als eigene Datei in Github gesetzt. Beispiel siehe hier.,
Wert,Kommentar
edgelist,Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from,"definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort"
to ,"definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. "
relation,"1 = CEO oder Head of oder Verantwortliche*r der Organisation (von Personen zu Organisationen gelesen), 2 = persönliche Beziehung (Freundschaft, verwandt, verheiratet), 3 = bestätigter Kontakt, 4 = Politiker, 5 = Lehrende Funktion,  6 = Immobilienmakler*in"
member,"1 = bestätigte Mitglieder (zu irgendeinem Zeitpunkt), 2 = nicht bestätigte Mitglieder"
time,"1 = unter 5 Jahre, 2 = 5-10 Jahre, 3 = 10-20 Jahre, 4 = über 20 Jahre"
money,"1 = Geld gespendet (Person zu Organisation), 2 = Geld gespendet (Organisation zu Person), 3 = Geld gespendet (Organisation zu Organisation)"
,
nodelist,Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id,"eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  "
name,Name oder Bezeichnung des Knotens. 
name_short,"Gleich wie ID, zur besseren Visualisierung"
type,"1 = Projekte, Unternehmen, Verlage, Vereine (kein Mensch), 2 = Mensch"
sector,"Bei Organisationen/Unternehmen/Parteien: 1 = Bildung, 2 = Verlage und Redaktionen, 3 = Non-Profit (z.B. Vereine von sozialen Projekten), 4 = Wirtschaft, 5 = Partei, 6 = Gesundheit (mit Einnahmen, wie Arztpraxen), 7 = Immobilien"
sex,"1 = männlich, 2 = weiblich, 3 = unklar/divers"
county,"Nur bei type Unternehmen: Sitz der Organisation nach Bundesland; BW = Baden-Württemberg, BY =Bayern, SL = Saarland, SH = Schleswig-Holstein, NW = Nordrhein-Westfalen, BE = Berlin, BB = Brandenburg, HB = Bremen, HH = Hamburg, HE = Hessen, MV = Mecklenburg-Vorpommern,  NI = Niedersachsen,  RP = Rheinland-Pfalz, SN = Sachsen, ST = Sachsen-Anhalt, TH = Thüringen"
source,"1 = Journalistische Quelle, 2 = Social Media, 3 = Impressum/Website selbst, 4 = Blogpost, 5 = Wikipedia, 6 = Buch, 7 = Andere"
NA,"definiert fehlende Werte, bei der Datenerhebung das Feld"
,
Bearbeitungshinweise,
"Achten Sie bitte auf die Kommentare in den Spalten. Diese erklären genauer, welche Daten erfasst werden. ",
"Sie sehen die Kommentare, wenn Sie auf die entsprechende Spalte gehen. ",
"Skizzieren Sie zunächst Ihr Netzwerk bzw. die Daten, die für Sie relevant sind. ",
Welche Informationen wollen Sie erheben? Wie müssen diese erfasst sein?,
"Legen Sie bitte im Codebuch möglichst genau fest, wie die Daten erhoben werden (Codebuch)",
"Bitte verwenden Sie keine Sonderzeichen in der Erfassung, dazu gehören Satzzeichen, Umlaute, etc.",
"Verpflichten Sie alle Teammitglieder darauf, das Codebuch zwingend einzuhalten. ",
Wer seine Daten nicht sauber erstellt muss diese nachbereinigen.,
"Dokumentieren Sie jeden Schritt Ihrer Datenerfassung mit, um dies zu rekonstruieren.",
Nutzen Sie das Skript zur Datenbereinigung auf dem letzten Reiter!,
"Beispiel für die Dokumentation von Codebuch, Edge- und Nodelist",
https://github.com/hdm-crpr/226305/tree/master/data/crpr2,
Vergeben Sie stets eindeutige Spaltenbeschriftungen. Am besten immer nur ein Begriff ohne Sonderzeichen etc.,