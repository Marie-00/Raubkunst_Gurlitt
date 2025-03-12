# Codebuch Raubkunst Gurlitt	
Edgelist 

From: Definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort.
To: Definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 
Time: Zeitpunkt der Transaktion, nur ein Jahr angeben, (DAS LETZE BEI UNKLAREM ZEITRAUM) Bsp. von 1950-1960 verschollen --> 1960
Transition: 1=gekauft, 2=gestohlen, 3=verschenkt, 4=vererbt, 5=verschollen, 6=beschlagnahmt, 7=restituiert, 8=getauscht, 9=sichergestellt, 10=treuhändische Übernahme, 11= Übernahme aus ehem. Reichsvermögen
Direkte Übergabe: 1= ja, 2= nein (-> verschollen)
	
	
Nodelist

Id: Eindeutige Identifikation jedes einzelnen Knotens (vertex).
Name: Name oder Bezeichnung des Knotens. 
Type: Was ist es: Person=1, Organisation/Museum/Institution =2, Kunstwerk=3, Auktion=4
Object_type: Gemälde=1, Skulptur=2, Gegenstand=3
Role: Nur Menschen! 1=Kunsthändler, 2=Privatperson, 3= Politiker, 4 = Erbe, 5=Künstler, 6=Sammler
Status: Keine Rückgabe an ursp. Besitzer=1, Rückgabe an ursprüngl. Besitzer=2 Rückgabe an DE = 3
Provenience status: 1=Raubkunst, 2=Ungeklärt mit Verdacht
Person mit NS-Bezug: 1= ja, 2= nein
