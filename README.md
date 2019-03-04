# M300-Services LB2 DF 25.02.2019


### GitHub Account erstellt
  - Account erstellt wie verlangt. Keine Probleme dabei aufgetreten.  
### Git Client Installiert
  - Nach Anleitung Problemlos Installiert. Sowie Portable getestet.  
### VirtualBox Installiert
  - div. Linux VMs mit Virtualbox Installiert
  - VirtualBox war neu für mich, VMWare Workstation kenne ich bereits. Funktionen sind sehr ähnlich.
  

### Vagrant Installiert
  - div. VMs mit Vagrant Installiert
  - Vagrant noch nicht gekannt, Funktionen sehr praktisch und nicht zu schwierig.
[Vagrantfile](https://github.com/Kaniterror/M300-Services/blob/master/Vagrantfile)

### Visual Studio Code Installiert.
  - Mit GitHub / Bash eingerichtet
  - Probleme beim Verknüpfen mit Bash, Repository neu geladen -> hat Problem gelöst.

### Eigenes Repository erstellt.
   - Repository auf NB erstellt
   - SSH Key generiert und hinterlegt
    - Erster Upload getestet.
Hat alles nach Anleitung geklappt.
Alle Aufgaben für die Toolumgebung 10 wurden hiermit erledigt.


### Vagrant Info - Sammlung: 
  - vagrant init - Initialisiert am aktuellen Pfad eine Vagrant Umgebung und erstellt ein Vagrantfile
  - vagrant up - Erstellt und konfiguriert eine neue VM, anhand der Konfigdatei 
  - vagrant ssh - Stellt Verbindung via SSH zu einer gewählten VM auf
  - vagrant status - Zeigt aktuellen Stand der VM an
  - vagrant port - Zeigt alle Forwarded Ports der VM an
  - vagrant halt - Stoppt laufende VM
  - vagrant destroy - Stoppt die VM und löscht sie.
### Vagrant Config Detail Infos: 
  - config.vm.box = "ubuntu/bionic64" Hier wird bestimmt welches OS verwendet wird.