#Data Engineering Assignment 1

##Assignment 1: Big Data in Ihrem Umfeld

###1.1 Schauen Sie sich in Ihrem Umfeld um. FH Technikum oder Ihr Job. Nennen Sie mindestens ein Beispiel für Daten, die schemalos (unstrukturiert) sind und mindestens ein Bespiel für Daten, die strukturiert (schematisch) sind.

Beispiele aus dem Berufsumfeld:
Unstrukturiert:
    * Kommunikation über diverse Nachrichtendienste (Emails, Skype, Messenger)
    * Schwarzes Brett

Strukturert:
    * Zeitaufzeichnungen
    * Urlaubsanträge

###1.2 Nennen Sie ein Beispiel für Daten in Ihrem Umfeld, die gestreamt verarbeitet werden, nennen Sie ein Beispiel für Daten in Ihrem Umfeld, die über Batchverarbeitung verarbeitet werden.

Beispiele aus dem Berufsumfeld:
Gestreamte Daten:
  * Übertragungen von Firmenpräsentationen

Batchdaten:
  * Tägliche Serverlogs
  
  

##Assignment 2: Big Data in Ihrem Umfeld

###Entscheiden Sie sich für eine Data Engineering Plattform. Apache Flink oder Apache Spark. Installieren Sie die auf Ihrem Arbeitsgerät.
###• Erklären Sie ihre Entscheidung

Ich habe bis jetzt keine der beiden Technologien verwendet und mir im Internet (im speziellen: StackOverflow) einen kurzen Überblick verschafft und mich dann kurzerhand für Apache Flink entschieden.  Jedoch ist zu beachten dass beide Tools etwa den gleichen Funktionsumfang haben, aber je nach Aufgabenstellung unterschiedlich zu bewerten sind.

###• Schicken Sie einen Screenshot der installierten Umgebung mit

![Flink bat](https://raw.githubusercontent.com/JoBLyM/BLD_2016/master/Screenshots/flink.png?raw=true)

###• Beschreiben Sie Ihre Toolchain, die Sie mit dem Framework nutzen würden (z.B: IDE)

Ich verwende größtenteils Netbeans oder Eclipse, da Flink jedoch unter Maven lauffähig ist und Maven Projekte (aus meiner Erfahrung) in Eclipse komplizierter zu verwalten sind, würde ich Netbeans verwenden. Hierfür müssten nur die richtigen Maven Dependencies hinzugefügt werden und man erspart sich gegenüber von Eclipse einen größeren Arbeitsaufwand.

#Data Science 
##Assignment 1: Technologien

###1.1 Sie haben in der LVA zwei Frameworks kennengelernt (R und Python). 
###Nennen Sie zwei weitere Technologien, um Daten zu analysieren (müssen nicht open source sein)

Besonders bekannt ist hierbei Scala und Matlab, jedoch kann z.B. auch Mathematika für Datenanalyse verwendet werden.


###1.2 Sie bekommen den Auftrag, sich mit einer Data Science Technologie zu arbeiten. Nennen Sie Technologie, die ihnen auf dem ersten Blick am besten für Sie ersscheint und begründen Sie das!

Ich würde zu Python tendieren. Zwar bin ich geübt im Umgang mit R, jedoch bietet Python, neben seiner einfachen Syntax, eine Menge von Funktionen und ist mmn. für Programmierer ziemlich leicht zu erlernen. Die Community die hinter Python steht bietet auch eine Menge an Hilfestellung und Python selbst ist als Technologie bereits voll ausgereift.

##Assignment 2: Technologien
###Entscheiden Sie sich für eine Data Science Plattform. R oder Python Installieren Sie die auf Ihrem Arbeitsgerät.
###• Begründen Sie ihre Entscheidung (Warum ziehen Sie persönlich aus ihrer Ausgangssituation die eine Technologie der anderen vor).
Wie bereits bei Punkt 1.2 beschrieben: ich würde zu Python tendieren da diese Technologie die nötige Flexibilität und Funktionalität besitzt. Jedoch hängt die Wahl der Technologie immer von der Aufgabenstellung selbst ab. Für kleinere Aufgaben würde ich dann z.B. Matlab verwenden, da dies auch gleichzeitig ein mächtiges Visualisierungstool ist und meine Vorkentnisse hierfür ausreichen sollten.

###• Schicken Sie einen Screenshot der installierten Umgebung mit
![Python Hello World](https://raw.githubusercontent.com/JoBLyM/BLD_2016/master/Screenshots/Python.png?raw=true

###• Beschreiben Sie Ihre Toolchain, die Sie mit dem Framework nutzen (z.B. IDE)
Für kleine und einfache Projekte reicht oft schon Notepad++ mit den richtigen PlugIns aus.
Für größere Projekte kommt es dann immer an ob man für die IDE Geld ausgeben wollen würde oder nicht. Da wir Zugriff auf Studentenversionen von Visual Studio haben und hierfür Python Tools als gratis Extentions angeboten werden, würde ich zu Visual Studio tendieren. Hierbei ist jedoch zu beachten, dass VS nicht crossplattformtauglich ist - ob dies jedoch eine Voraussetzung sein sollte hängt jedoch wieder von der Aufgabenstellung ab.

##Assignment 3: Big Science
###Der Cheatsheet auf http://scikit-learn.org/stable/tutorial/machine_learning_map/ ist eine einfache Anleitung, wie man den richtigen Algorithmus zum richtigen Data Science Problem findet.
###Schauen Sie in Google nach und lernen Sie classification, regression, clusting und dimensional reduction unterscheiden.
###Nennen Sie ein Beispiel aus ihrem Umfeld, wo Sie mit dem Algorithmus zu tun haben. Das kann ein Beispiel sein, wie: Wenn Sie bei Amazon einkaufen. Wenn Sie von einem Marketinginstitut angerufen werden, etc.

Classification: Daten werden versucht in Kategorien einzuordnen. Die Einordnung erfolgt mithilfe eines sogenannten "classifier" der mithilfe eines Trainingssampels trainiert wird. Ein Beispiel hierfür wären Emailfilter: in meinem Arbeitsumfeld werden so z.B. SVN-Commits, Arbeitsemails, potentielle Spam-Emails und Emails mit interessanten Inhalt (=Fortbildung/Ideenfindung, bei uns im Forschungsbereich werden solche Emails oft an den Teamverteiler weitergeleitet) eingeordnet.

Regression: Der Hauptunterschied zwischen Classification und Regression ist, dass Regression keine Kategorisierung vornimmt, sondern einen konkreten Wert vorraussagen kann. Dies wird vorallem bei Preisprognosen angewendet. 

Clustering: Clustering ist mehr oder weniger eine Erweiterung von Classification. Dabei wird Data nicht in vorher definierte Kategorien eingeteilt, sondern Kategorien werden im Zuge der Analyse erstellt. Ein Beispiel hierfür wäre die Amazon Produktvorschläge, wo mehrere Kategorien verbunden werden um ein perfektes Match zu kreieren.

Dimensonal Reduction: Dimensional Reduction wird bei großen Datenmengen verwendet um diese zu reduzieren, da ansonsten Analysen mit langen Bearbeitungszeiten rechnen müssen.