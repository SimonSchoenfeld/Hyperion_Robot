# Hyperion Roboter
<img src="images/Hyperion_v2_01.png" width = 600>
<br>
<br>
Dieses Repository enthält die Dokumentation des Hyperion Roboters, <br>
welcher von Simon Schönfeld für den Robocup Rescue Line Wettbewerb 2024 gebaut wurde. 

## Über mich
Mein Name ist Simon Schönfeld, ich besuchte seid der 5ten Klasse die Informatik AG meiner Schule. Ziel dieser AG war es, Lego Roboter zu bauen, welche einer Linie folgen, um mit diesen dann einmal im Jahr beim Robocup Wettbewerb teil zu nehmen. 
Obwohl ich es nie geschafft habe, mich mit einem Lego Roboter für die deutschen Meisterschaften des Robocup zu qualifizieren, beschloss ich mich während der Coronapause gemeinsam mit meinem damaligen Teamkameraden, dazu, einen eigenen Roboter zu bauen. 

## Regeln des Robocups
Die Roboter beim Robocup müssen einen Parkour absolvieren , welcher aus einer Schwarzen Linie und einer "Rescue Area" besteht. Der Roboter muss der Schwarzen Linie folgen und dabei verschiedene Hindernisse überwinden. Diese Hindernisse bestehen aus Bumpern, Blockaden und Lücken. An Kreuzungen befinden sich zudem grüne Makierungen, welche die Roboter erkennen und abhängig von der Position des Punktes drehen müssen. Die Rescue Area wird mit einem Silbernen Streifen eingeleitet. In ihr kann der Roboter Kugeln in verschiedene Ecken befördern um Zusatzpunkte zu bekommen. Schwarze Kugeln müssen in die rote Ecke, die Silbernen Kugeln müssen in die grüne Ecke.

Die genauen Regeln befinden sich [hier](https://junior.robocup.org/wp-content/uploads/2024/04/RCJRescueLine2024-final-1.pdf).
<br>
<br>
<img src="images/Rules_Map.png" width = 500>



## Vorheriger Roboter
Obwohl ich es nie geschafft habe, mich mit einem Lego Roboter für die deutschen Meisterschaften des Robocup zu qualifizieren, beschloss ich mich während der Coronapause gemeinsam mit meinem damaligen Teamkameraden, dazu, einen eigenen Roboter zu bauen. Zu diesem Zeitpunkt war ich  zwischen 14 und 15 Jahre alt und wusste so gut wie gar nichts über Elektronik und dem Erstellen von 3D Modellen, lediglich mit dem Programmieren hatte ich mich bereits länger beschäftigt. 
Da sich zu der Zeit auch Niemand in der AG damit auskannte, waren wir mehr oder weniger auf uns alleine gestellt und brauchten bereits mehrere Monate um zum ersten Mal zwei Schrittmotoren zu verwenden. Ich nahm den Roboter mehrfach mit nach Hause und baute und testete ihn dort ausgiebig. 
Als wir schließlich mit dem Roboter angetreten sind, versagte er vollkommen auf grund von vielen unterschiedlichen Problemen. Dennoch habe ich in diesem Jahr so viel gelernt wie nie zuvor und beherrschte nun Grundkenntnisse in Schaltkreisen, 3D modellieren mit Fusion 360 und der Gesamtmechatronik eines Roboters. Da der Roboter meinem Teammitglied über die Zeit deutlich zu komplex und zeitintensiv wurde baute und programmierte ich ihn fast vollständig alleine und nach dem Wettbewerb verließ er die AG.

>[!NOTE]
> Wenn es darum geht im Robocup zu gewinnen, ist das bauen eines eigenen Roboters absolut kontraproduktiv. Die Lego Roboter sind inzwischen so ausgereift, dass sie um Welten genauer und simpler sind. Die Gewinner des Robocups sind fast ausschließlich Lego Roboter und auch in den Qualifikationsrunden an denen ich teilgenommen habe bin ich bis jetzt immer der Einzige Teilnehmer mit einem 100% selbstgebauten Roboter gewesen. Ich baue dennoch einen eigenen Roboter, da es mir nicht um das Gewinnen, sondern um die Herausforderung geht und darum, neue Dinge zu lernen. 

## Probleme des ersten Roboters

- Der Roboter basierte auf einem Fahrwerk eines Schülers, welcher schon vor mehreren Jahren die Schule verlassen hatte. Er hat sich damals mit seinem selbstgebauten Roboter für die deutsche Meisterschaft qualifizieren können. Der Roboter befand sich zu großen Teilen noch im Besitz der AG, weshalb wir das Fahrwerk als Grundbaustein nutzen und über die Zeit immer weiter veränderten. Am Ende war zwar nur noch die verwendete Kette ein Originalteil, dennoch haben wir die Ursprungsmaße nie verändert. Der Roboter war zu klein und Schmal um noch mehr Bauteile unter zu bringen. Somit bestand der Roboter lediglich aus den Motoren und Treibern, sowie den Farbsensoren, Arduino und Akku. Später fügten wir zudem ein Greifarm hinzu.
<br>
<br>
<img src="images/Hyperion_v1_gif1.gif" width = 200>

- Aufgrund der Bauweise war es sehr schwierig an das Innere des Roboters zu kommen, weshalb man ihn ständig auseinander bauen musste. Die Kabel waren zudem alle weiß und rot, was schnell zu Verwirrung führte. Der Später hinzugefügte Greifarm war sehr schlecht Konsturiert und passte nicht wirklich zum Fahrwerk. All dies führte dazu, dass das Finden und Beheben von Fehlern sehr zeitaufwändig war. Zudem gab es gar keine Möglichkeiten die Kugeln überhaubt zu finden oder die Rescue Are überhaubt zu localisieren. 
<br>
<br>
<img src="images/Hyperion_v1_02.png" height = 300>
<img src="images/Hyperion_v1_05.png" height = 300>

- Die Kette war nicht rutschfest genug, wodurch der Roboter auf Steigungen wiederholt abrutschte. Die Räder unter den Ketten haben sich zu dem bei zu großer Belastung selber festgezogen und sind regelmäßig blockier, da sie auf Schrauben Montiert waren. Die hohe Anzahl an kleinen Bauteilen hat zudem dafür gesorgt, dass an dem kleinen Roboter über 100 Schrauben verbaut waren. Dies machte ihn schließlich sehr schwer. Durch dieses Problem und dadurch, dass die Schrittmotoren sehr ineffizient angesteuert wurden, sorgte dafür, dass der Roboter sich kaum bewegen konnte. 
<br>
<br>
<img src="images/Hyperion_v1_03.png" height = 300>
<img src="images/Hyperion_v1_04.png" height = 300>

- Wenn es darum ging einer einfachen Linie zu Folgen hat der Roboter sehr präzise funktioniert. Dennoch gab es immer wieder Probleme welche schnell dazu führten, dass der Roboter gar nicht mehr funktionierte. Zusätzlich konnte er die Fortgeschrittenen Hindernisse des Pakours zu bestehen, da die Farbsensoren zu ungenau waren und sehr genau kalibriert werden musten. (Dies liegt auch an dem speziellen Grünton der Punkte)
<br>
<br>
<img src="images/Hyperion_v1_gif2.gif" height = 300>
<img src="images/Hyperion_v1_06.png" height = 300>

<br>
<br>
<br>

# Planung Hyperion v2
<br>

## Platinen
Statt einem Arduino Mega soll nun ein Raspberry Pi verwendet werden. Dieser ermöglicht es eine Kamera zu verwenden um die Kugeln zu finden. Zudem ermöglicht er durch mehrere Cores das Nutzen von Multiprocessen. Zudem kann der Roboter nun kabellos Programmiert werden und ist insgesamt Leistungfähiger. Damit der Roboter einfach auseinandergebaut werden kann bedarf es mehrer Platinen, welche verschiedene Aufgaben erfüllen. Diese Platinen sind wiederum mit angesteckten Kabeln verbunden. Somit sind keine Bauteile permanent mit einander verbunden und lassen sich leicht zerlegen. 

### Analog-Digital-Wandler
Da die Grünen Punkte an den Kreuzungen durch die Kamera erkannt werden können, benötigt der Roboter lediglich die Grayscalesensoren zum erkennen der Linie und ein Ultraschallsensor, welcher Hindernisse auf der Fahrbahn erkennen soll. Leider kann der Raspberry Pi die analogen Werte der Farbsensoren nicht selber auslesen, wie es der Arduino getan hat. Aus diesem Grund wird ein Analog zu Digital Wandler benötigt. Genutzt werden zwei MCP3008 Chips mit je 8 Inputs. Diese können über den SPI Bus mit dem Raspberry Pi verbunden werden und befinden sich auf der ersten Platine. Da die Anzahl an Analogen Inputs nicht mehr von den Anschlüssen des Raspberry Pis abhängig ist, sondern rein von der Anzahl an Wandlern, können gleich zwölf Grayscale Sensoren verwendet werden, wobei trotzdem noch vier Anschlüsse offen bleiben. Eine hohe Anzahl an Sensoren ermöglicht es die Linie in einer großen Fläche lokalisieren zu können. Zudem wird der Einfluss eines einzelnen, eventuell fehlerhaften Sensors reduziert. 
<br>
<br>
<img src = "images/AnalogToDigital_02.png" height = 150>
<img src = "images/AnalogToDigital_01.png" height = 150>

### Stromversorgung
Für die Schaltung werden zwei verschiedene Spannungen benötigt. 12V für die Motoren und 5.1V für den Raspberry Pi. Der Raspberry Pi hat zudem einen 3.3V Pin Ausgang. Als Stromquelle wird ein 3S 12V Lip Akku verwendet. Ein Aufwärtswandler bringt diese 12V auf 5.1V, welche über eine Verteilerplatine auf ein USB Slot geleitet werden. Über ein kurzes USB Kabel kann so der Raspberry Pi versorgt werden. Wenn man ein externes USB Kabel verwendet kann der PI auch angeschaltet und programiert werden ohne dass die Motoren verbunden sind. An dem Akku befindet sich zudem ein Schalter um den gesamten Strom abzuschalten. 
<br>
<br>
<img src = "images/PowerSupply_01.png" height = 150>

### Motortreiber
Um die Schrittmotoren ordnungsgemäß bedienen zu können bedarf es an einem Motortreiber für jeden Motor. Um diese Treiber richtig verwenden zu können müssen sie richtig verkabelt werden. Diesen vergleichsweise komplexen Schaltkreis hatte ich zu beginn des Projektes noch wie alle anderen Platinen von Hand gelötet. Als ich jedoch schließlich von "a4988" Treibern auf "drv8825" Treiber gewelchselt bin, musste ich eine Änderung an dem Schaltkreis vornehmen. Da die Platine nicht besonders gut verlötet war, ich nicht mit der Steckerpostition zufrieden war und die Rückseite der Platine bereits sehr unordentlich geworden ist, entschied ich mich für eine neue Platine. Um den Service zu testen und mir gleichzeitg das Löten zu sparen designte ich die Platine digital und ließ sie von einem Online Service herstellen. Das Ergebniss ist deutlich professioneller und weniger anfällig für Schäden als eine von Hand gelötete Platine.
<br>
<br>
<img src = "images/circuitboard_01.png" height = 300>
<img src = "images/circuitboard_02.png" height = 300>

### Knöpfe
Der Roboter muss während des Robocup Wettbewerbes mehrfach von der Fahrbahn genommen werden und an einer anderen Stelle neu gestartet werden. Um den Roboter zu starten und zu stoppen bedarf es eine Möglichkeit für Manuelle Inputs, da der Roboter während des Wettbewerbes nicht über WLAN verbunden sein darf. Aus diesem Grund befinden sich an der Rückseite des Roboters zwei Knöpfe für mögliche Eingaben und zwei LEDs zur Statusanzeige. 
<br>
<br>
<img src = "images/circuitboard_03.png" width = 600>
<img src = "images/circuitboard_04.png" width = 600>

### Verteiler
Damit die Einzelnen Teile des Roboters einfach und schnell zu verkabeln, empfielt es sich breite Stecker zu verwenden, sodass jeweils nur ein Kabelstrang eingesteckt werden muss. Um die Signale auf die richtigen Kabel zu leiten gibt es eine Verteilerplatine, welche sich unter dem Raspberry Pi befindet. Mit ihr ist sowohl die obere Hälfte des Roboters als auch die abnehmbahre Heckplatte verbunden. 
<br>
<br>
<img src = "images/circuitboard_06.png" height = 150>
<img src = "images/circuitboard_05.png" height = 150>
 
 ### Servo Motoren
An der operen Hälfte des Roboters befinden sich fünf Servo Motoren sowie einen Lüfter. Um diese Bauteile korrekt zu verbinden und dabei nur einen Stecker zu verwenden wird ebenfalls eine Platine verwendet. Zudem befindet sich an dieser Platine ein weiterer Stecker um zwei helle LEDs an der Vorderseite des Roboters mit Strom zu versorgen.
<br>
<br>
<img src = "images/circuitboard_08.png" height = 150>
<img src = "images/circuitboard_07.png" height = 150>


## Das Fahrwerk
Die meisten Probleme des ersten Roboters entstanden durch das Fahrwerk. Jeder versuch, eine neue Kette auszudrucken scheiteterte, weshalb wir keine Möglichkeit hatten den Roboter zu vergrößern. Die genutze Kette war sehr glatt und haftete nur schlecht an dem Boden. Um diese Probleme zu vermeiden nutzt der neue Roboter vier Räder. Die Räder haben einen durchmeser von 90cm, welches das überqueren von Bumpern deutlich erleichtert. Um genügend haftung zu erreichen, werden um die Räder Herum Aktengummibänder geklebt. Diese haben die perfekte Größe und Breite und haften super an glatten Oberflächen.
Damit der Roboter trotz der großen Räder nicht zu schnell fährt und beim Fahren mehr Kraft hat, werden die Räder mit einer Zahnradübersetzung von 15 zu 20 angetrieben. Das kleinere Zahnrad sitzt dabei in der mitte zwischen den beiden Rädern und ist direkt mit der Motorachse verbunden. Dadurch befinden sich die schweren Motoren genau in der Mitte des Roboters. Die Räder sitzen dabei in Kugellagern, weshalb nur wenig Reibung entsteht. 
<br>
<br>
<img src = "images/Hyperion_v2_03.png" height = 200>


## Das Gehäuse
Eine große Änderung des Roboters ist das Gehäuse. Es bietet den Grundstein für den gesamten Roboter. Ein großer Unterschied zum Vorgänger ist, dass das Gehäuse dieses Mal aus einem großen, einzelnen Stück besteht. In ihm soll die gesamte Elektronik untergebracht werden können und gleichzeitig schnell zu erreichen sein. Damit später alles passt, wurde die Elektronik bereits vorher ausgewählt und getestet, um jedem Bauteil einen festen Platz zu geben. Die Motoren bilden zusammen mit ihren Treibern ein eimzelnes Modul, welches sich entfernen lässt um einfacher an den Motoren arbeiten zu können. Der Mittlere Teil des Roboters Besteht also aus den Motoren. Im Vorderen Teil befinden sich die Sensoren und im Hinteren Teil der Spannungswandler, der Akku und die Platine mit den Analog zu Digital Wandlern. Der Raspberry Pi selber befindet sich auf einer seperat entfehrnbaren Platte über dem LiPo Akku.
<br>
<br>
<img src = "images/Hyperion_v2_02.png" height = 300>
<img src = "images/Hyperion_v2_06.png" height = 300>
<img src = "images/Hyperion_v2_04.png" width = 800>
<img src = "images/Hyperion_v2_05.png" width = 800>


## Die Kamera 
 Die Kamera soll beim befahren des Kurses senkrecht nach unten gerichtet sein um mögliche Kreuzungen zu erkennen. Wenn der Roboter jedoch die entsprechende Makierung überfährt muss die Kamera nach vorne gerichtet werden, damit die Kugeln von dem Roboter gefunden und aufgesammelt werden können. Um den Komplikationen eines doppelten Kamerasystems aus dem Weg zu gehen, wird eine enzelne kamera mit Hilfe eines Servo Motors in die Richtige Position gedreht. Damit die Ausrichtung stimmt werden zudem mehrere Zahnräder genutzt. 
<br>
<br>
<img src = "images/cameramount_01.png" width = 740>
<br>
<img src = "images/cameramount.gif" height = 300>
<img src = "images/cameramount_02.png" height = 300>

## Schleifkontate
Damit der Roboter überhaubt Kugeln finden und später einsammeln kann, muss er zuerst die "Rescue Area" finden. Diese beginnt mit einem silbernen Streifen auf der Fahrbahn. Da das Erkennen von Reflektieren von refelktierenden Oberflächen sowohl für die Sensoren als auch für die Kamera zu Komplikationen führen kann, macht der Roboter von einer weiteren (vermutlich unbeabsichtlichen) Eigenschaft des Streifens gebrauch. Der silberne Streifen leitet Strom und kann daher mit zwei Schleifkontakten erfasst werden. Danach kann sich der Roboter mit Hilfe der Kamera und des Ultraschall-Sensors in der "Rescue Area" zurechtfinden. 
<br>
<br>
<img src = "images/schleifkontakt.gif" height = 200>
<img src = "images/schleifkontakt.png" height = 200>