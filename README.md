# Netzwerke-Kohlekommission
#id Codebuch:

#id Edgelist:

-id (eindeutige Codierung der Knoten)
codiert mit Namen der Person, Organisation, Partei o. Verband
-from 
ID Mitglied der Kommission
-to
alle Mitgliedschaften der Person


#id Nodelist: 

-id
Identische ID wie aus der Edgelist zur Identifikation der Knoten 
-type
0=Person
1=Organisation
-sex 
Geschlecht des Knotens 
male=1 
female=2 
NA (->Organisationen)=3
-age 
0 = Organisationen/Unternehmen/Verbände
1 = bis 40 Jahre
2 = 41 bis 50 Jahre
3 = 51 bis 60 Jahre
4 = 61 und älter
-representation 
bezieht sich auf die Funktion innerhalb der Kommission
1=Politik
2=Gewerkschaft
3=Wirtschaft
4=Umwelt 
5=Wissenschaft
6=Regionen
7=keine Funktion

-party 
Mitgliedschaft in politischer Partei
1=CDU
2=SPD
3=FDP
4=Die Grünen
5=parteilos
6=Organisation/Unternehmen/Verband

-position
1=Vorsitz
2=Mitglied
3=kein Stimmrecht

-state
1=Nordrhein-Westfalen 
2=Brandenburg
3=Bayern
4=Sachsen 
5=Baden-Württemberg
6=Schleswig-Holstein 
7=Niedersachsen
8=Hessen 
9=Berlin
10=Hamburg
