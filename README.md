# M300-Services Hauptdokumentation + LB2 DF 04.03.2019


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

## LB2 Projekt zuerst mit Windows dann doch mit Linux
  - Active Directory VM via Vagrant erzeugt mit Windows Server 2012 R2, hat eine weile gedauert in der TBZ.
  - Client VM via Vagrant erzeugt
  - Server AD aufgesetzt test.local
  - Ich habe jetzt erneut einen Windows Server und einen Windows Client installiert, dabei hatte ich diverse Probleme mit dem Code
  - Es scheint mir nicht möglich das ganze via Vagrant zu installieren.
  - Nachdem ich einen neuen Notebook im Geschäft erhalten habe welcher ein verändertes Benutzerprofil aufwies habe ich und unser Applikationsentwickler 5 Stunden lang probiert diese Toolumgebung zu mirgieren oder neu zu installieren beides hat nicht funktioniert.
  - Erneut habe ich mit mit dem Alten Notebook probiert die aufgetragene LB2 zu absolvieren.
  - Jetzt habe ich aber hier ein neues Problem mit Vagrant, es scheint Probleme zu geben erneut.
  - Ich habe jetzt mein komplettes Vagrant file gelöscht weil es plötzlich nicht mehr geht. Selbst die Backupfiles welche 100% funktionierten gehen nicht mehr.
  
## Netzwerkplan Idee mit Windows Umgebung
                +---------------------------------------------------------------+
                ! DinoPC Schulnetz 10.71.13.159 und Privates Netz 10.0.2.1      !                 
                ! Port: 8080                                                    !	
                !                                                               !	
                !    +--------------------+          +---------------------+    !
                !    ! Active Directory   !          ! Test Client         !    !       
                !    ! Host: web01        !          ! Host: db01          !    !
                !    ! IP: 10.0.2.10      ! <------> ! IP: 10.0.2.101      !    !
                !    ! Port: 80           !          ! Port 80             !    !
                !    ! Nat: XXXX          !          ! Nat: XXX            !    !
                !    +--------------------+          +---------------------+    !
                !                                                               !	
                +---------------------------------------------------------------+
  


## LB2 Projekt Linux
- Ich möchte einen Linux Client via DHCP welchen ich auf einem Linux Server installiere verbinden.
- Ich habe jetzt einen Linux Server installiert.
- Zudem habe ich einen Linux Client installiert welcher die IP-Adresse vom Linux Server - DHCP-Dienst beziehen soll.
- Damit der DHCP konfiguriert werden kann, passe ich die DHCP.conf an und lade diese dann via Vagrant in die VM.

## Netzwerkplan Linux
                +---------------------------------------------------------------+
                ! DinoPC Private   10.71.13.159 und Privates Netz 10.0.2.1      !                 
                !                                                               !	
                !                                                               !	
                !    +--------------------+          +---------------------+    !
                !    !DHCP Server         !          ! Test Client         !    !       
                !    ! Host: SRV01        !          ! Host: WS01          !    !
                !    ! IP: 192.168.1.10   ! <------> ! IP: 192.168.1.101   !    !
                !    ! Port: 80           !          ! Port 80             !    !
                !    ! Nat: XXXX          !          ! Nat: XXXX           !    !
                !    +--------------------+          +---------------------+    !
                !                                                               !	
                +---------------------------------------------------------------+

## Reflexion
- 
- 

  
