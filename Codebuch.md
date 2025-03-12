# Raubkunst_Gurlitt	
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from	Definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort.
to 	Definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 
time	Zeitpunkt der Transaktion, nur ein Jahr angeben, (DAS LETZE BEI UNKLAREM ZEITRAUM) Bsp. von 1950-1960 verschollen --> 1960
transition	1=gekauft, 2=gestohlen, 3=verschenkt, 4=vererbt, 5=verschollen, 6=beschlagnahmt, 7=restituiert, 8=getauscht, 9=sichergestellt, 10=treuhändische Übernahme, 11= Übernahme aus ehem. Reichsvermögen
direkte Übergabe	1= ja, 2= nein (-> verschollen)
	
	
nodelist	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id	Eindeutige Identifikation jedes einzelnen Knotens (vertex).
name	Name oder Bezeichnung des Knotens. 
type	Was ist es: Person=1, Organisation/Museum/Institution =2, Kunstwerk=3, Auktion=4
object_type	Gemälde=1, Skulptur=2, Gegenstand=3
role	Nur Menschen! 1=Kunsthändler, 2=Privatperson, 3= Politiker, 4 = Erbe, 5=Künstler, 6=Sammler
status	Keine Rückgabe an ursp. Besitzer=1, Rückgabe an ursprüngl. Besitzer=2 Rückgabe an DE = 3
provenience status	1=Raubkunst, 2=Ungeklärt mit Verdacht
Person mit NS-Bezug	1= ja, 2= nein
