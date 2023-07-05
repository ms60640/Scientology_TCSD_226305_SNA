 	
Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.	
Achtung: das Codebuch wird immer als eigene Datei in Github gesetzt. Beispiel siehe hier.	
Wert	Kommentar
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from	definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort
to 	definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 
relation	1 = CEO oder Head of oder Verantwortliche*r der Organisation, 2 = Geld gespendet, 3 = persönliche Beziehung (Freundschaft, verwandt, verheiratet), 4 = bestätigter Kontakt
	
	
nodelist	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  
name	Name oder Bezeichnung des Knotens. 
name_short	Gleich wie ID, zur besseren Visualisierung
member	(bei Menschen und Unternehmen/Projekten); 1 = confirmed member, 2 = no member: bestätigt keine Mtiglied, 3 = nicht gesichertes Mitglied; 
type	1 = Projekte, Unternehmen, Verläge, Vereine (kein Mensch), 2 = Mensch
position	Bei Menschen: 1 = CEO, 2 = Politiker, 3 = Leitende oder lehrende Funktion, 4 =  normaler Arbeitnehmer, 5 = Immobilienmakler*in
sector	Bei Organisationen/Unternehmen: 1 = Bildung 2 = Verläge und Redaktionen, 3 = Vereine (z.B. von sozialen Projekten), 4 = Wirtschaft (Immobilien, etc.)
sex	1 = männlich, 2 = weiblich, 3 = unklar/divers
county	Nur bei type Unternehmen: Sitz der Organisation nach Bundesland; BW = Baden-Württemberg, BY =Bayern, SL = Saarland, SH = Schleswig-Holstein, NW = Nordrhein-Westfalen, BE = Berlin, BB = Brandenburg, HB = Bremen, HH = Hamburg, HE = Hessen, MV = Mecklenburg-Vorpommern,  NI = Niedersachsen,  RP = Rheinland-Pfalz, SN = Sachsen, ST = Sachsen-Anhalt, TH = Thüringen
source	1 = Journalistische Quelle, 2 = Social Media, 3 = Impressum/Website selbst, 4 = Blogpost, 5 = Andere
NA	definiert fehlende Werte, bei der Datenerhebung das Feld einfach leer lassen, R rechnet NAs (missing values) automatisch raus..
	
Bearbeitungshinweise	
Achten Sie bitte auf die Kommentare in den Spalten. Diese erklären genauer, welche Daten erfasst werden. 	
Sie sehen die Kommentare, wenn Sie auf die entsprechende Spalte gehen. 	
Skizzieren Sie zunächst Ihr Netzwerk bzw. die Daten, die für Sie relevant sind. 	
Welche Informationen wollen Sie erheben? Wie müssen diese erfasst sein?	
Legen Sie bitte im Codebuch möglichst genau fest, wie die Daten erhoben werden (Codebuch)	
Bitte verwenden Sie keine Sonderzeichen in der Erfassung, dazu gehören Satzzeichen, Umlaute, etc.	
Verpflichten Sie alle Teammitglieder darauf, das Codebuch zwingend einzuhalten. 	
Wer seine Daten nicht sauber erstellt muss diese nachbereinigen.	
Dokumentieren Sie jeden Schritt Ihrer Datenerfassung mit, um dies zu rekonstruieren.	
Nutzen Sie das Skript zur Datenbereinigung auf dem letzten Reiter!	
Beispiel für die Dokumentation von Codebuch, Edge- und Nodelist	
https://github.com/hdm-crpr/226305/tree/master/data/crpr2	
Vergeben Sie stets eindeutige Spaltenbeschriftungen. Am besten immer nur ein Begriff ohne Sonderzeichen etc.	