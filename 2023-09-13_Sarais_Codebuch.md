# Scientology Netzwerk #
Codebuch Stand 2023-09-13

# Ungerichtetes Scientology Netzwerk
## von der Gruppe: TCSD

# EDGE-Attribute
 
**relation**
Art der Beziehung zwischen Akteuren
1 = CEO oder Head of oder Verantwortliche*r der Organisation (von Personen zu Organisationen gelesen),
2 = persönliche Beziehung (Freundschaft, verwandt, verheiratet),
3 = bestätigter Kontakt,
4 = Politiker*in,
5 = Lehrende Funktion,
6 = Immobilienmakler*in
7 = Arbeitsverhältnis

**member**
Ob Akteure Mitglieder bei Scientology sind.
bei Scientology Organisationen (so =1):
1 = bestätigte Mitglieder (zu irgendeinem Zeitpunkt), 
2 = nicht (sicher) bestätigte Mitglieder


**time**
Zeit der Beziehung zwischen AKteuren.
1 = unter 5 Jahre, 
2 = 5-10 Jahre, 
3 = 10-20 Jahre, 
4 = über 20 Jahre

**money**
Ob ein Akteur dem anderen Akteur Geld gespendet hat. Da das Netzwerk ungerichtet ist, drückt die numerische Ausprägung aus, wer wem (in welche Richtung) gespendet hat.

öffentlich einsehbare Spenden:
1 = Geld gespendet (Person zu Organisation), 
2 = Geld gespendet (Organisation zu Person)

# NODE-ATTRIBUTE

**id**
Eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
Name oder Bezeichnung des Knotens.

**name_short**
Gleich wie ID, zur besseren Visualisierung.

**type**
Ob der Akteur ein Mensch oder eine Institution ist.
1 = nicht menschlich: z.B. Projekte, Unternehmen, Verlage, Vereine
2 = Menschen

**sector**
Differenziert Sektoren bei Institutionen.

Bei Organisationen/Unternehmen/Parteien: 
1 = Bildung, 
2 = Verlage und Redaktionen, 
3 = Non-Profit (z.B. Vereine von sozialen Projekten), 
4 = Wirtschaft, 
5 = Partei, 
6 = Gesundheit (mit Einnahmen, wie Arztpraxen), 
7 = Immobilien, 
8 = Kirche/religöse Einrichtung

**sex**
Geschlecht, der menschlichen Akteure.
1 = männlich,
2 = weiblich,
3 = unklar/divers.

**county**
bei type 1 und 2: Sitz der Organisation nach Bundesland;

BW = Baden-Württemberg, 
BY =Bayern, 
SL = Saarland, 
SH = Schleswig-Holstein, 
NW = Nordrhein-Westfalen, 
BE = Berlin, BB = Brandenburg, 
HB = Bremen, 
HH = Hamburg, 
HE = Hessen, 
MV = Mecklenburg-Vorpommern,  
NI = Niedersachsen,  
RP = Rheinland-Pfalz, 
SN = Sachsen, 
ST = Sachsen-Anhalt, 
TH = Thüringen

**source**
Quelle, aus der die Informationen über den Akteur stammen.
1 = Journalistische Quelle, 
2 = Social Media, 
3 = Impressum/Website selbst, 
4 = Blogpost, 
5 = Wikipedia, 
6 = Buch, 
7 = Scientology selbst, 
8 = Andere

**so** 

Nur bei type = 1, 1 = Gehört offiziell zu Scientology, 2 = gehört nicht offiziell zu Scientology

**NA**
Definiert fehlende Werte, bei der Datenerhebung das Feld.