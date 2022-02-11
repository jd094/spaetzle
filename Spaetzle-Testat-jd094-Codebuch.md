# Datensatz Spaetzle Connection
Codebuch für das Testat vom 3. Semester von jd094, HdM Stuttgart

# Worum geht es?
Uns interessiert die ""Spätzle""-Connection im aktuellen Kabinett Scholz
("Ampel-Koalition"). Damit sind Politiker:innen gemeint, die aus
Baden-Württemberg kommen und Teil der Regierung sind, dazu gehören auch
Staatsminister:innen. Die Zuordnung Baden-Württemberg ist über den
letzten Wahlkreis oder eine entsprechende Landesliste definiert. 

# Edge-Attribute

id
identisch mit nodelist, aber hier nur einmalige Nennung

from
initiierender Knoten

to
erhaltender Knoten

relationship
Beziehungsart zwischen den Politiker:innen und zu den Organisationen/Ort/Verband etc.

1 = Achtung: Regierung umfasst auch Staatsekretäre und das
Bundeskanzleramt, etc. hier sollte als Knoten das entsprechende
Ministerium angegeben werden.

2 = aktuelle und ehemalige politische Funktionen in politischen
Ausschüssen, Gremien und der Partei. etc. Das kÃ¶nnen auch frÃ¼here
Stationen gewesen sein, z.B. GeschÃ¤ftsfÃ¼hrer:in einer Partei, etc.

3 = umfasst alle Mitgliedschaften in NGOs, Stiftungen, GedenkstÃ¤tten,
etc: werden im Bundestagsprofil als KÃ¶rperschaften Ã¶ffentlichen Rechts
bezeichnet.

4 = Beteiligung an Unternehmen durch Mandate, etwa Aufsichtsratsmandate,
Gremien, etc.

5 = erhalten Stipendien (egal wann), etwa Deutsche Studienstiftung,
Parteinahe Stiftungen, Internationale Organisationen im In- und Ausland
etc.

6 = ausgeÃ¼bte BerufstÃ¤tigkeiten, falls vorhanden

7 = Studien- bzw. (lÃ¤ngere) Aufenthaltsort(e) in In- und Ausland

year (Bezieht sich auf das Jahr, in dem die Variable relationship erhoben wurde)

# Node-Attribute

id (identisch mit edgelist, aber hier nur einmalige Nennung)

name_short (Nachname)

name (voller Name)
z.B. FranziskaBrantner

type
(0 = Person, 1 = Organisation/Ort/Verband etc.)

sex (Geschlecht)
1 = weiblich
2 = männlich
3 = divers

birth (Geburtsjahr)
Als ganze Zahl angeben

position (jetzige Position, z.B. StaatssekretÃ¤r:in, Minister)

education (hÃ¶chster Bildungsabschluss)

subject (Fachrichtung bei Studium/Promotion)

party (ParteizugehÃ¶rigkeit)
1 = gruene
2 = fdp
3 = spd

religion (Religion)

kids (Anzahl der Kinder)

twitter (Anzahl follower)

instagram  (Anzahl follower)

facebook (Anzahl follower)

youtube  (Anzahl Abonnenten)
