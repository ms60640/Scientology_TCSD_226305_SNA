# Scientology Netzwerk #
Codebuch Stand 2023-09-13

# Ungerichtetes Scientology Netzwerk
## von der Gruppe: TCSD

# EDGE-Attribute
 
**relation**
Art der Beziehung zwischen Akteuren
ceo = CEO oder Head of oder Verantwortliche*r der Organisation (von Personen zu Organisationen gelesen),
pb = persönliche Beziehung (Freundschaft, verwandt, verheiratet),
bs = bestätigter Kontakt,
teach = Lehrende Funktion,
immo = Immobilienmakler*in
work = Arbeitsverhältnis

**member**
Ob Akteure Mitglieder bei Scientology sind.
bei Scientology Organisationen so = is , wenn nicht: so =isn
bemi = bestätigte Mitglieder (zu irgendeinem Zeitpunkt), 
ubemi = nicht (sicher) bestätigte Mitglieder


**time**
Zeit der Beziehung zwischen AKteuren.
unterfuenf = unter 5 Jahre, 
fuenfbiszehn = 5-10 Jahre, 
zehnbiszwanzig= 10-20 Jahre, 
ueberzwanzig = über 20 Jahre

**money**
Ob ein Akteur dem anderen Akteur Geld gespendet hat. Da das Netzwerk ungerichtet ist, drückt die character Ausprägung aus, wer wem (in welche Richtung) gespendet hat.

öffentlich einsehbare Spenden:
gespezuorg = Geld gespendet (Person zu Organisation), 
gespezuperso = Geld gespendet (Organisation zu Person)

# NODE-ATTRIBUTE

**id**
Eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
Name oder Bezeichnung des Knotens.

**name_short**
Gleich wie ID, zur besseren Visualisierung.

**type**
Ob der Akteur ein Mensch oder eine Institution ist.
keinmensch = nicht menschlich: z.B. Projekte, Unternehmen, Verlage, Vereine
mensch = Menschen

**sector**
Differenziert Sektoren bei Institutionen.

Bei Organisationen/Unternehmen/Parteien: 
learn = Bildung, 
verl = Verlage und Redaktionen, 
nonprofit = Non-Profit (z.B. Vereine von sozialen Projekten), 
econ = Wirtschaft, 
party = Partei, 
health = Gesundheit (mit Einnahmen, wie Arztpraxen), 
immos = Immobilien, 
church = Kirche/religöse Einrichtung

**sex**
Geschlecht, der menschlichen Akteure.
male = männlich,
female = weiblich,
divers = unklar/divers.

**county**
bei type: Sitz der Organisation/Person nach Bundesland;

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
journalism = Journalistische Quelle, 
socials = Social Media, 
website = Impressum/Website selbst, 
blog = Blogpost, 
wiki = Wikipedia, 
book = Buch, 
self = Scientology selbst, 
other = Andere

**so** 

Nur bei type = keinmensch, is = Gehört offiziell zu Scientology, isn = gehört nicht offiziell zu Scientology

**NA**
Definiert fehlende Werte, bei der Datenerhebung das Feld.