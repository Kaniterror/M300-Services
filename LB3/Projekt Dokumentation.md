# M300-Services Hauptdokumentation + LB3 DF 20190325


### GitHub Account erstellt
  - Account erstellt wie verlangt. Keine Probleme dabei aufgetreten.  

### Git Client Installiert
  - Nach Anleitung Problemlos Installiert. Sowie Portable getestet.  

### VirtualBox Installiert
  - div. Linux VMs mit Virtualbox Installiert
  - VirtualBox war neu für mich, VMWare Workstation kenne ich bereits. Funktionen sind sehr ähnlich.

### Vagrant WebServer
  - Vagrant Apache Server Installiert, nach Anleitung keine Probleme festgestellt, vom Client aus Verbindung auf 127.0.0.1 Problemlos funktioniert.

### Vagrant Installiert
  - div. VMs mit Vagrant Installiert
  - Vagrant noch nicht gekannt, Funktionen sehr praktisch und nicht zu schwierig.
[Vagrantfile](https://github.com/Kaniterror/M300-Services/blob/master/Vagrantfile)

### Visual Studio Code Installiert
  - Mit GitHub / Bash eingerichtet
  - Probleme beim Verknüpfen mit Bash, Repository neu geladen -> hat Problem gelöst.

### Eigenes Repository erstellt
   - Repository auf NB erstellt
   - SSH Key generiert und hinterlegt
   - Erster Upload getestet.
Hat alles nach Anleitung geklappt.
Alle Aufgaben für die Toolumgebung 10 wurden hiermit erledigt.

### Markdown Editor
  - Visual Studio funktioniert prima, habe meine Dokumentation nachträglich darüber strukturiert. Ich habe alle benötigten Elemente an einem Ort.

### Wissensstand:
  - Virtualisierungen
Ich arbeite bereits viel mit Virtuellen Maschinen, hauptsächlich aber mit GUI basierten Systemen. Mit der Benutzung von Vagrant kommen für mich viele neue Möglichkeiten hinzu.
  - Linux
Ich arbeite nie mit Linux, mein ganzes Linux-Wissen habe ich aus einem ÜK-Modul. Dieses Wissen muss aber mithilfe von Google wieder aufgefrischt werden.
  - Vagrant
Noch nie von Vagrant gehört, finde es sehr praktisch für Virtualisierungstests.
  - Versionsverwaltung
Mit Versionsverwaltungen habe ich ausser Cloud-Geschichten noch keine Erfahrungen gesammelt, es ist relativ neu für mich.
  - Git
Ich habe schon davon gehört, selbst verwende ich es aber zum ersten mal. Finde es bis jetzt sehr praktisch.
  - Mark Down
Mark Down Struktur ist für mich auch etwas komplett neues, welches aber mit ein bisschen Recherche, recht gut von der Hand geht.
  - Systemsicherheit
Hatte ich diverse Module, aber auch Praxis-Bezug.

### Wissenszuwachs:
- Vagrant kann sehr nützlich sein für das erstellen standartisiertet VMs
- Vagrant funktioniert besser mit Linux
- Mit Windows hat man immer wieder Probleme via Shell eingaben
- AD Profile können Probleme machen mit dieser Testumgebung
- Ich habe eine komplett neue Deployment-Umgebung kennengerlernt
- Meine Linux Kenntnisse wurden aufgefrischt 
- Nützlich um MASSEN an VMs zu erstellen zb. für Testing

### Vagrant AWS Plugin
  - Habe ich über den Befehl "vagrant plugin install vagrant-aws" installiert.

### Vagrant Info - Sammlung: 
  - vagrant init - Initialisiert am aktuellen Pfad eine Vagrant Umgebung und erstellt ein Vagrantfile
  - vagrant up - Erstellt und konfiguriert eine neue VM, anhand der Konfigdatei 
  - vagrant ssh - Stellt Verbindung via SSH zu einer gewählten VM auf
  - vagrant status - Zeigt aktuellen Stand der VM an
  - vagrant port - Zeigt alle Forwarded Ports der VM an
  - vagrant halt - Stoppt laufende VM
  - vagrant destroy - Stoppt die VM und löscht sie.

### Vagrant Config Detail Infos: 
  - config.vm.box = "ubuntu/bionic64" Hier wird bestimmt welche BOX von der Vagrant Cloud bezogen wird.
  - config.ssh.config Hier wird der Pfad des SSH Schlüssels angegeben.

## Reflexion
- Ich habe sehr viele neue Dinge gelernt über Service Deployment, was am anfang eine Weile gedauert hat, um es zu verstehen und um damit arbeiten zu können.
- Viel ärger hatte ich wegen eines Notebook wechsels inklusive AD-Profile anpassungen von unserem Geschäft aus.
- Bis jetzt finde ich dieses Modul eines der besseren Module, weil sehr viel ausprobiert werden kann.
- Es hat mich zwar viel mehr Aufwand gekostet wie andere Module, aber ich habe dabei auch sehr viel gelernt.