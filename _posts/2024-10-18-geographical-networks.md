---
layout: post
title: Geographische Netzwerke von Korrespondenz August Wilhelm Schlegels (Gwanghun Park, Prof. Dr. Jochen Strobel)
---
<p style="text-align:justify">
Mit Hilfe von Netzwerkgraphen können wir heute Metadaten in Korpora visualisieren und im Rahmen der qualitativen Analysen solcher Netzwerkstrukturen Informationen aufdecken, die nicht immer auf den ersten Blick zugänglich sind (vgl. u.a. Rodrigues 2019). Ein Beispiel dafür sind soziale oder geographische Relationen, die hier nachfolgend für die Untersuchung von Korrespondenzen aus dem Kreis der sogenannten Frühromatiker und Frühromantikerinnen rund um Schlegel dargestellt und im nächsten Schritt netzwerktheoretisch analysiert wurden. Diese Arbeit basiert auf Arbeiten in den Projekte "Digitalisierung und elektronische Edition der Korrespondenz August Wilhelm Schlegels" (abgeschlossen, weitere Informationen unter https://www.uni-marburg.de/de/fb09/neuere-deutsche-literatur/institut/personen/strobel/dfg-projekt-schlegel) und "Korrespondenzen der Frühromantik. Edition – Annotation – Netzwerkforschung" (aktuell, https://www.uni-marburg.de/de/fb09/neuere-deutsche-literatur/institut/personen/strobel/dfg-projekt-korrespondenzen-der-fruehromantik).<br><br>
Ziel der netzwerktheoretischen Modellierung der Daten war es, die Beziehungen zwischen Absendenden und Empfangenden, Absende- und Empfangsorten innerhalb einer bestimmten Zeitperiode im Verlauf des Lebens des Literaten zu vergleichen. Im Fokus stand dabei auch zu untersuchen, ob sich hinsichtlich der Regionalität der Korrespondenzen im Verlauf der Zeit Unterschiede ergeben, d.h. die Internationalität der Korrespondenzen von Schlegel und dadurch die Reichweite seines Einflusses und seiner Arbeit aus anderer Perspektive zu bestätigen.<br><br>
Die Datengrundlage sind digitalisierte Briefe aus der "Digitalen Edition der Korrespondenz August Wilhelm Schlegels", die im Rahmen des DFG-Projekts "Schlegel" zu einer digitalen Edition zusammengeführt wurden. Die Analyse der Briefdaten deckt drei relevante Dimensionen ab: Absendende und Empfangende liefern Informationen zur sozialen Dimension, Absende- und Empfangsorte zur räumlichen Dimension und weitere Metadaten wie das Datum des Versands zur zeitlichen Dimension.
6426 Datensätzen dabei wurden aus 5684 Briefen extrahiert, weil mehr als zwei Absendende, Empfangende, Absendungsorte oder Empfangsorte in einem einzelnen Brief auftauchen können. Jede Person und jeder Ort wurden daher miteinander als 1:1-Beziehung verbunden. Auf der Grundlage der 6426 Datensätze wurden die Orte der Absender und die der Adressaten von August Wilhelm Schlegels Korrespondenz jeweils in ein geographisches Netzwerk übertragen. Die Netzwerke (vgl. Abb. 1 bis 5) wurden mit den Paketen pandas, numpy, networkx (https://networkx.org/) und folium (https://python-visualization.github.io/folium/latest/) erstellt.<br><br>
Zugunsten der anschließenden qualitativen Analyse sind die geographischen Netzwerke als interaktive Graphen erstellt worden. Das erlaubt den Forschenden, die Netzwerke ohne Rückgriff auf Metadaten in zusätzlicher Form (z.B. als Liste) oder die eigentlichen Briefe auszuwerten. Da es sich bei der Datengrundlage um Briefe von und an August Wilhelm von Schlegel handelt, können im Rahmen dieser Untersuchung nur egozentrierte Netzwerke (vgl. Wolf 2010) generiert werden. Die Korrespondenz wird dabei mittels der Darstellung der räumlichen Informationen über verschiedene Personen hinweg abgebildet (d.h. dass theoretisch mehrere Personen in einem Ort in Verbindung zu einem anderen stehen können). Wenn man auf der jeweiligen Karte einen Ort oder eine Linie anklickt, erhält man dann zusätzliche Informationen zum Ortnamen und zu den Namen der Absendenden und der Empfangenden. Darüber hinaus kann innerhalb des Kartenbereichs die Ansicht gezoomt werden, wodurch auch kleinere Orte für die Analyse aufgefunden und berücksichtigt werden. Die roten Grenzen sind die deutschen Grenzen um 1820 und wurden aus der "HGIS Germany" (https://hgl.harvard.edu/catalog/harvard-ghgis1820germanconfed) übernommen. Indem man das Icon rechts oben in der Ecke anklickt und ein Häkchen bei "Germany Confederation Boundary Lines, 1820" setzt, kann man die roten Grenzen aber auch ausblenden. Für die Netzwerkanalyse ist daneben der sogenannte Grad (vgl. Jannidis 2017) relevant. In den geographischen Netzwerken ist die Größe eines Knotens (Ortspunkt) nach seinem Grad definiert, d.h. dadurch, "wie viele Verbindungen ein Knoten in einem Graphen hat" (ebd., S. 149), und die Dicke einer Kante steht für die Häufigkeit des Briefverkehrs zwischen zwei Knoten. Rote Dreiecke auf der Karte dienen als Pfeile, die am Ende jeder Kante, d.h. jeder Verbindung, hinzugefügt werden und auf den jeweiligen Empfangsort hinweisen.<br><br>
Die Abbildungen 1 bis 5 illustrieren nachfolgend Korrespondenzen zwischen Schlegel und "der Welt" in fünf verschiedenen Zeitabschnitten.
</p>

<iframe src='files/html/posts/geographic_network_of_correspondence_by_letter_between_1781_and_1796.html' height='600px' width='100%' style='border:none;'></iframe>
<p style='font-size:15px'> Abb. 1: Graph für Korrespondenz von AWS zwischen 1781 und 1796 </p>

<iframe src="files/html/posts/geographic_network_of_correspondence_by_letter_between_1797_and_1802.html" height="600px" width="100%" style="border:none;"></iframe>
<p style='font-size:15px'> Abb. 2: Graph für Korrespondenz von AWS zwischen 1797 und 1802 </p>

<iframe src="files/html/posts/geographic_network_of_correspondence_by_letter_between_1803_and_1817.html" height="600px" width="100%" style="border:none;"></iframe>
<p style='font-size:15px'> Abb. 3: Graph für Korrespondenz von AWS zwischen 1803 und 1817 </p>

<iframe src="files/html/posts/geographic_network_of_correspondence_by_letter_between_1818_and_1830.html" height="600px" width="100%" style="border:none;"></iframe>
<p style='font-size:15px'> Abb. 4: Graph für Korrespondenz von AWS zwischen 1818 und 1830 </p>

<iframe src="files/html/posts/geographic_network_of_correspondence_by_letter_between_1831_and_1845.html" height="600px" width="100%" style="border:none;"></iframe>
<p style='font-size:15px'> Abb. 5: Graph für Korrespondenz von AWS zwischen 1831 und 1845 </p>

### Erste Ergebnisse de graph- und netzwerktheoretischen Analyse
<p style="text-align:justify">
 Schlegel war die am weitesten gereiste, die 'europäischste' der Personen aus dem Kreis der Jenaer Frühromantik um 1800. Zu ermitteln war, wie international Schlegels Korrespondenz war. Er selbst hielt sich zweimal mehrere Jahre im Ausland auf: jeweils als Hauslehrer in Amsterdam und in Coppet am Genfer See. Die Graphen (Abb. 1) und (Abb. 3) zeugen von diesen Tätigkeiten, Graph (Abb. 3) auch davon, wie dicht Schlegels Korrespondentennetz über Europa hinweg in den Kriegsjahren ab etwa 1804 war. Das geographische Korrespondenzwerk (Abb. 2) aus der für die Wirkung der Romantik wichtigen Jenaer und Berliner Zeit, etwa zwischen 1796 und 1803, erweist sich als fast ausschließlich deutschlandintern, also richtiggehend als provinziell. (Abb. 4) und (Abb. 5) repräsentieren Schlegels letztes Lebensdrittel ab 1818 als Professor in Bonn: Er baut das international agierende Fach Indologie auf und korrespondiert deswegen mit London und Paris. Die geographischen Knoten konzentrieren sich: neben Bonn, London und Paris ist es nun vor allem Berlin, Hauptstadt und Sitz seines Ministers. Die Graphen lassen Rückschlüsse zu auf den 'europäischen' Charakter von Schlegels Korrespondenz und deren Dynamik über die Jahrzehnte seines Lebens.
</p>

### Literatur
- Jannidis, F. (2017): „10 Netzwerke“. In: Digital Humanities: eine Einführung, herausgegeben von Fotis Jannidis u. a., J.B. Metzler Verlag, S. 147–161.
- Rodrigues, Francisco Aparecido (2019): Network Centrality: an Introduction. (zuletzt abgerufen am 18.10.2024, http://arxiv.org/abs/1901.07901).
- Wolf, C. (2010). Egozentrierte Netzwerke: Datenerhebung und Datenanalyse. In: Stegbauer, C., Häußling, R. (eds) Handbuch Netzwerkforschung. VS Verlag für Sozialwissenschaften, S. 471–483.

### Internetquellen
- https://august-wilhelm-schlegel.de/briefedigital/ (zuletzt abgerufen am 18.10.2024).
- https://hgl.harvard.edu/catalog/harvard-ghgis1820germanconfed (zuletzt abgerufen am 18.10.2024).
- https://networkx.org/ (zuletzt abgerufen am 18.10.2024).
- https://python-visualization.github.io/folium/latest/ (zuletzt abgerufen am 18.10.2024).
- https://www.uni-marburg.de/de/fb09/neuere-deutsche-literatur/institut/personen/strobel/ (zuletzt abgerufen am 18.10.2024).dfg-projekt-korrespondenzen-der-fruehromantik
- https://www.uni-marburg.de/de/fb09/neuere-deutsche-literatur/institut/personen/strobel/dfg-projekt-schlegel (zuletzt abgerufen am 18.10.2024).