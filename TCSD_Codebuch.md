# Scientology Netzwerk #
Codebuch: finaler Stand 

# Ungerichtetes Scientology Netzwerk
## von der Gruppe: TCSD

# EDGE-Attribute
 
**relation**
Art der Beziehung zwischen Akteuren
ceo = CEO oder Head of oder Verantwortliche Person der Organisation (von Personen zu Organisationen gelesen),
pb = persönliche Beziehung (Freundschaft, verwandt, verheiratet),
bs = bestätigter Kontakt,
teach = Lehrende Funktion,
immo = Immobilienmakler-Beziehung
work = Arbeitsverhältnis

**member**
Ob Akteure Mitglieder bei zu Scientology gehörenden Organisationen (die bei dem Node-Attribut "so" die Ausprägung "= is" haben) sind.
bemi = bestätigte Mitglieder (zu irgendeinem Zeitpunkt), 
ubemi = nicht (sicher) bestätigte Mitglieder


**time**
Zeit der Beziehung zwischen AKteuren.
unterfuenf = unter 5 Jahre, 
fuenfbiszehn = 5-10 Jahre, 
zehnbiszwanzig= 10-20 Jahre, 
ueberzwanzig = über 20 Jahre

**money**
Ob ein Akteur dem anderen Akteur Geld gespendet hat. Da das Netzwerk ungerichtet ist, drückt die Ausprägung aus, wer wem (in welche Richtung) gespendet hat.

Öffentlich einsehbare Spenden:
gespezuorg = Geld gespendet (Person zu Organisation), 
gespezuperso = Geld gespendet (Organisation zu Person)

# NODE-ATTRIBUTE

**id**
Eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
Name oder Bezeichnung des Knotens.

**name_short**
Gleich wie ID, für die Visualisierung.

**type**
Ob der Akteur ein Mensch oder eine Institution/Organisation ist.
keinmensch = nicht menschlich: z.B. Projekte, Unternehmen, Verlage, Vereine, Organisationen
mensch = Menschen

**sector**
Differenziert Sektoren bei bei nicht-menschlichen Akteuren.
learn = Bildung, 
verl = Verlage und Redaktionen, 
nonprofit = Non-Profit (z.B. Vereine von sozialen Projekten), 
econ = Wirtschaft, 
party = Partei, 
health = Gesundheit (mit Einnahmen, wie Arztpraxen), 
immos = Immobilien, 
church = Kirche/religöse Einrichtung

**sex**
Geschlecht der menschlichen Akteure.
male = männlich,
female = weiblich,
divers = unklar/divers.

**county**
bei nicht-menschlichen Akteuren: Der Sitz nach Bundesland.
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
Nur bei nicht-menschlichen AKteuren: Definiert, ob sie offiziell zu Scientology gehören.
is = Gehört offiziell zu Scientology,
isn = gehört nicht offiziell zu Scientology

**NA**
Definiert fehlende Werte.