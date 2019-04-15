# M300-Services Hauptdokumentation + LB3 DF 20190325


### GitHub Account erstellt
  - Account erstellt wie verlangt. Keine Probleme dabei aufgetreten

### Git Client Installiert
  - Nach Anleitung Problemlos Installiert. Sowie Portable getestet

### VirtualBox Installiert
  - div. Linux VMs mit Virtualbox Installiert
  - VirtualBox war neu für mich, VMWare Workstation kenne ich bereits. Funktionen sind sehr ähnlich

### Vagrant WebServer
  - Vagrant Apache Server Installiert, nach Anleitung keine Probleme festgestellt, vom Client aus Verbindung auf 127.0.0.1 Problemlos funktioniert

### Vagrant Installiert
  - div. VMs mit Vagrant Installiert
  - Vagrant noch nicht gekannt, Funktionen sehr praktisch und nicht zu schwierig.
[Vagrantfile](https://github.com/Kaniterror/M300-Services/blob/master/Vagrantfile)

### Visual Studio Code Installiert
  - Mit GitHub / Bash eingerichtet
  - Probleme beim Verknüpfen mit Bash, Repository neu geladen -> hat Problem gelöst

### Eigenes Repository erstellt
   - Repository auf NB erstellt
   - SSH Key generiert und hinterlegt
   - Erster Upload getestet
Hat alles nach Anleitung geklappt
Alle Aufgaben für die Toolumgebung 10 wurden hiermit erledigt.

### Markdown Editor
  - Visual Studio funktioniert prima, habe meine Dokumentation nachträglich darüber strukturiert. Ich habe alle benötigten Elemente an einem Ort

### Wissensstand:
  - Vor diesem Modul hatte ich noch keinen Bezug zu Containern
  - Docker kannte ich auch noch nicht
  - Ich kannte Microservices noch nicht als solches
### Wissenszuwachs:
  - Ich weiss jetzt +/- was ein Container ist
  - Ich verstehe jetzt wie ein Container aufgebaut ist
  - Ich weiss jetzt wofür Container eingesetzt werden
  - Ich kann jetzt meine eigenen Container erstellen
  - Ich kenne jetzt Docker und dessen Möglichkeit Container zu Verwalten/erstellen/Löschen
  - Ich weiss jetzt wie ich Docker verwende
  - Ich verstehe den Ausdruck Microservices jetzt und was damit gemeint ist und wofür diese verwendet werden können
### Vagrant AWS Plugin
  - Habe ich über den Befehl "vagrant plugin install vagrant-aws" installiert

### Vagrant Info - Sammlung: 
  - vagrant init - Initialisiert am aktuellen Pfad eine Vagrant Umgebung und erstellt ein Vagrantfile
  - vagrant up - Erstellt und konfiguriert eine neue VM, anhand der Konfigdatei 
  - vagrant ssh - Stellt Verbindung via SSH zu einer gewählten VM auf
  - vagrant status - Zeigt aktuellen Stand der VM an
  - vagrant port - Zeigt alle Forwarded Ports der VM an
  - vagrant halt - Stoppt laufende VM
  - vagrant destroy - Stoppt die VM und löscht sie

### Vagrant Config Detail Infos: 
  - config.vm.box = "ubuntu/bionic64" Hier wird bestimmt welche BOX von der Vagrant Cloud bezogen wird
  - config.ssh.config Hier wird der Pfad des SSH Schlüssels angegeben

### Docker Befehle
  - docker run -it ubuntu /bin/bash   Startet einen Container mit einer interaktiven Shell
  - docker run -d ubuntu sleep 20
  Startet einen Container, der im Hintergrund läuft und nach 20 Sekunden sich beendet
  - docker run -d --rm ubuntu sleep 20
  Hier löscht sich der Container nach 20 Sekunden.
  - docker run -d ubuntu touch /tmp/lock
  Startet einen Container und legt eine Datei an.
  - docker ps -a
  Zeigt Aktive und Beendete Container an
  - docker images
  Gibt Lokale Images aus
  - docker rm `docker ps -a -q`
  Alle beendeten COntainer werden gelöscht
  - docker start [id]
  Docker Container neu starten, Daten bleiben erhalten
  - docker build -t mysql .
  Erstellt Container als MYSQL
## Reflexion
  - Ich habe sehr viele neue Dinge gelernt über Service Deployment, was am anfang eine Weile gedauert hat, um es zu verstehen und um damit arbeiten zu können
  - Viel ärger hatte ich wegen eines Notebook wechsels inklusive AD-Profile anpassungen von unserem Geschäft aus
  - Bis jetzt finde ich dieses Modul eines der besseren Module, weil sehr viel ausprobiert werden kann
  - Es hat mich zwar viel mehr Aufwand gekostet wie andere Module, aber ich habe dabei auch sehr viel gelernt
  - Ich weiss jetzt +/- was ein Container ist
  - Ich verstehe jetzt wie ein Container aufgebaut ist
  - Ich weiss jetzt wofür Container eingesetzt werden
  - Ich kann jetzt meine eigenen Container erstellen
  - Ich kenne jetzt Docker und dessen Möglichkeit Container zu Verwalten/erstellen/Löschen
  - Ich weiss jetzt wie ich Docker verwende
  - Ich verstehe den Ausdruck Microservices jetzt und was damit gemeint ist und wofür diese verwendet werden können