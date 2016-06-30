#Data Engineering Assignment 1

##Assignment 1: Big Data in Ihrem Umfeld

###1.1 Schauen Sie sich in Ihrem Umfeld um. FH Technikum oder Ihr Job. Nennen Sie mindestens ein Beispiel f�r Daten, die schemalos (unstrukturiert) sind und mindestens ein Bespiel f�r Daten, die strukturiert (schematisch) sind.

Beispiele aus dem Berufsumfeld:
Unstrukturiert:
    * Kommunikation �ber diverse Nachrichtendienste (Emails, Skype, Messenger)
    * Schwarzes Brett

Strukturert:
    * Zeitaufzeichnungen
    * Urlaubsantr�ge

###1.2 Nennen Sie ein Beispiel f�r Daten in Ihrem Umfeld, die gestreamt verarbeitet werden, nennen Sie ein Beispiel f�r Daten in Ihrem Umfeld, die �ber Batchverarbeitung verarbeitet werden.

Beispiele aus dem Berufsumfeld:
Gestreamte Daten:
  * �bertragungen von Firmenpr�sentationen

Batchdaten:
  * T�gliche Serverlogs
  
  

##Assignment 2: Big Data in Ihrem Umfeld

###Entscheiden Sie sich f�r eine Data Engineering Plattform. Apache Flink oder Apache Spark. Installieren Sie die auf Ihrem Arbeitsger�t.
###� Erkl�ren Sie ihre Entscheidung

Ich habe bis jetzt keine der beiden Technologien verwendet und mir im Internet (im speziellen: StackOverflow) einen kurzen �berblick verschafft und mich dann kurzerhand f�r Apache Flink entschieden.  Jedoch ist zu beachten dass beide Tools etwa den gleichen Funktionsumfang haben, aber je nach Aufgabenstellung unterschiedlich zu bewerten sind.

###� Schicken Sie einen Screenshot der installierten Umgebung mit

![Flink bat](https://raw.githubusercontent.com/JoBLyM/BLD_2016/master/Screenshots/flink.png?raw=true)

###� Beschreiben Sie Ihre Toolchain, die Sie mit dem Framework nutzen w�rden (z.B: IDE)

Ich verwende gr��tenteils Netbeans oder Eclipse, da Flink jedoch unter Maven lauff�hig ist und Maven Projekte (aus meiner Erfahrung) in Eclipse komplizierter zu verwalten sind, w�rde ich Netbeans verwenden. Hierf�r m�ssten nur die richtigen Maven Dependencies hinzugef�gt werden und man erspart sich gegen�ber von Eclipse einen gr��eren Arbeitsaufwand.

#Data Science 
##Assignment 1: Technologien

###1.1 Sie haben in der LVA zwei Frameworks kennengelernt (R und Python). 
###Nennen Sie zwei weitere Technologien, um Daten zu analysieren (m�ssen nicht open source sein)

Besonders bekannt ist hierbei Scala und Matlab, jedoch kann z.B. auch Mathematika f�r Datenanalyse verwendet werden.


###1.2 Sie bekommen den Auftrag, sich mit einer Data Science Technologie zu arbeiten. Nennen Sie Technologie, die ihnen auf dem ersten Blick am besten f�r Sie ersscheint und begr�nden Sie das!

Ich w�rde zu Python tendieren. Zwar bin ich ge�bt im Umgang mit R, jedoch bietet Python, neben seiner einfachen Syntax, eine Menge von Funktionen und ist mmn. f�r Programmierer ziemlich leicht zu erlernen. Die Community die hinter Python steht bietet auch eine Menge an Hilfestellung und Python selbst ist als Technologie bereits voll ausgereift.

##Assignment 2: Technologien
###Entscheiden Sie sich f�r eine Data Science Plattform. R oder Python Installieren Sie die auf Ihrem Arbeitsger�t.
###� Begr�nden Sie ihre Entscheidung (Warum ziehen Sie pers�nlich aus ihrer Ausgangssituation die eine Technologie der anderen vor).
Wie bereits bei Punkt 1.2 beschrieben: ich w�rde zu Python tendieren da diese Technologie die n�tige Flexibilit�t und Funktionalit�t besitzt. Jedoch h�ngt die Wahl der Technologie immer von der Aufgabenstellung selbst ab. F�r kleinere Aufgaben w�rde ich dann z.B. Matlab verwenden, da dies auch gleichzeitig ein m�chtiges Visualisierungstool ist und meine Vorkentnisse hierf�r ausreichen sollten.

###� Schicken Sie einen Screenshot der installierten Umgebung mit
![Python Hello World](https://raw.githubusercontent.com/JoBLyM/BLD_2016/master/Screenshots/Python.png?raw=true

###� Beschreiben Sie Ihre Toolchain, die Sie mit dem Framework nutzen (z.B. IDE)
F�r kleine und einfache Projekte reicht oft schon Notepad++ mit den richtigen PlugIns aus.
F�r gr��ere Projekte kommt es dann immer an ob man f�r die IDE Geld ausgeben wollen w�rde oder nicht. Da wir Zugriff auf Studentenversionen von Visual Studio haben und hierf�r Python Tools als gratis Extentions angeboten werden, w�rde ich zu Visual Studio tendieren. Hierbei ist jedoch zu beachten, dass VS nicht crossplattformtauglich ist - ob dies jedoch eine Voraussetzung sein sollte h�ngt jedoch wieder von der Aufgabenstellung ab.

##Assignment 3: Big Science
###Der Cheatsheet auf http://scikit-learn.org/stable/tutorial/machine_learning_map/ ist eine einfache Anleitung, wie man den richtigen Algorithmus zum richtigen Data Science Problem findet.
###Schauen Sie in Google nach und lernen Sie classification, regression, clusting und dimensional reduction unterscheiden.
###Nennen Sie ein Beispiel aus ihrem Umfeld, wo Sie mit dem Algorithmus zu tun haben. Das kann ein Beispiel sein, wie: Wenn Sie bei Amazon einkaufen. Wenn Sie von einem Marketinginstitut angerufen werden, etc.

Classification: Daten werden versucht in Kategorien einzuordnen. Die Einordnung erfolgt mithilfe eines sogenannten "classifier" der mithilfe eines Trainingssampels trainiert wird. Ein Beispiel hierf�r w�ren Emailfilter: in meinem Arbeitsumfeld werden so z.B. SVN-Commits, Arbeitsemails, potentielle Spam-Emails und Emails mit interessanten Inhalt (=Fortbildung/Ideenfindung, bei uns im Forschungsbereich werden solche Emails oft an den Teamverteiler weitergeleitet) eingeordnet.

Regression: Der Hauptunterschied zwischen Classification und Regression ist, dass Regression keine Kategorisierung vornimmt, sondern einen konkreten Wert vorraussagen kann. Dies wird vorallem bei Preisprognosen angewendet. 

Clustering: Clustering ist mehr oder weniger eine Erweiterung von Classification. Dabei wird Data nicht in vorher definierte Kategorien eingeteilt, sondern Kategorien werden im Zuge der Analyse erstellt. Ein Beispiel hierf�r w�re die Amazon Produktvorschl�ge, wo mehrere Kategorien verbunden werden um ein perfektes Match zu kreieren.

Dimensonal Reduction: Dimensional Reduction wird bei gro�en Datenmengen verwendet um diese zu reduzieren, da ansonsten Analysen mit langen Bearbeitungszeiten rechnen m�ssen.