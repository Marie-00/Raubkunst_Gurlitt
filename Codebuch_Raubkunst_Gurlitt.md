# Codebuch Raubkunst Gurlitt #	
Codebuch Stand 2025-04, aktualisiert 2025-04

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)
## Datenerhebung
Die Daten haben wir überwiegend aus Datenbanken aus dem Internet erhoben.

## Edgelist 

**from**
Definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist.

**to**
Definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. 

**time**
Zeitpunkt der Transaktion, das letztze Jahr angeben

**time period**
Zeitraum der Transaktion, 
1=frühestes Kunstwerk-1918, 2=1919-1932, 3=1933-1938, 4= 1939-1945 5=1946-1955, 6=1956-2000, 7=2000-2013, 8=2014-jetzt	

**edge**
1=gekauft, 2=gestohlen, 3=verschenkt, 4=vererbt, 5= eingelagert, 6=beschlagnahmt, 7=restituiert, 8=getauscht, 9=sichergestellt, 10=treuhändische Übernahme, 11= Übernahme aus ehem. Reichsvermögen, 12=Besitz, 13=Handel, 14=Bekanntschaft, 15=Erschaffung

**direkte Übergabe**
1= ja, 2= nein (-> verschollen)

## Nodelist

**id**
Eindeutige Identifikation jedes einzelnen Knotens (vertex).

**name**
Name oder Bezeichnung des Knotens. 

**type**
Person=1, Organisation/Museum/Institution/Auktion =2, Kunstwerk=3Object_type: Gemälde=1, Skulptur=2, Gegenstand=3

**role**
1=Kunsthändler, 2=Privatperson, 3= Politiker, 4 = Erbe, 5=Künstler, 6=Sammler

**status**
Keine Rückgabe an ursp. Besitzer=1, Rückgabe an ursprüngl. Besitzer=2 Rückgabe an DE = 3

**provenience status**
1=Raubkunst, 2=Ungeklärt mit Verdacht

**ns_contact**
1= ja, 2= nein

**jewish**
1 = ja 2=nein

**subnetwork**
1= Paris 2= Linz, 3= beide

##
