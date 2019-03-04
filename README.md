# M300-Services Hauptdokumentation + LB2 DF 04.03.2019


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

## LB2 Projekt 
  - Active Directory VM via Vagrant erzeugt mit Windows Server 2012 R2
  - Client VM via Vagrant erzeugt XXXXXX
  - 

    +---------------------------------------------------------------+
    ! DinoPC Schulnetz 10.71.13.159 und Privates Netz 192.168.55.1  !                 
    ! Port: 8080 (192.168.220.101:80)                               !	
    !                                                               !	
    !    +--------------------+          +---------------------+    !
    !    ! Active Directory   !          ! Test Client         !    !       
    !    ! Host: web01        !          ! Host: db01          !    !
    !    ! IP: 192.168.55.101 ! <------> ! IP: 192.168.220.100 !    !
    !    ! Port: 80           !          ! Port 3306           !    !
    !    ! Nat: XXXX          !          ! Nat: XXX            !    !
    !    +--------------------+          +---------------------+    !
    !                                                               !	
    +---------------------------------------------------------------+