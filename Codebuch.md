# Codebuch #

Two-mode Netzwerk mit den Mitglieder und den dazugehörigen Organisationen der Kohlekomission

# NODE-Attribute  

**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**type:** 0= Partei 1= Organisation

**sex:** 1= weiblich, 2= männlich 3= divers

**age:** 1= 0-29, 2= 30-39, 3= 40-49, 4= 50-59, 5= <60

**party:** 0= Parteilos  1= SPD, 2= CDU, 3= CSU, 4= FDP, 5= Grünen

**representation:** 1= Politik, 2= Wirtschaft, 3= Gewerkschaft 4= Umwelt, 5= Regionen 6= Wissenschaft

**position:** 0= Kein Stimmrecht, 1= Vorsitz, 2= Mitglied 

**state:** 1= Bayern, 2= BW, 3= NRW, 4= Berlin, 5= Brandenburg 6=Sachsen, 7=  Sachsen-Anhalt 8= Mecklenburg- Vorpommern, 9= Saarland, 10= Rheinland-Pfalz, 11=Hessen 2= Thüringen 13= Niedersachen, 14= Bremen 15= Hamburg, 16= Schleswig-Holstein


# EDGE-Attribute

**from:** (ID Mitglied der Kommision),

**to:** alle Mitgliedschaften der Person, soweit recherchierbar, dazu gehört z.B. politische Partei
	
