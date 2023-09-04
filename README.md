# Elmar_Kessler_M346
## KN1
### Der VM wird weniger CPUS zugeteilt als der PC zu Verfügung hat.
![Der VM wird weniger CPUS zugeteilt als der PC zu Verfügung hat.](/wenigerCPU.png "")
### Der VM wird weniger RAM zugeteilt als der PC zu Verfügung hat.
![Der VM wird weniger RAM zugeteilt als der PC zu Verfügung hat.](/wenigerRAM.png "")
### Der VM wird mehr CPUS zugeteilt als der PC zu Verfügung hat.
![Der VM wird mehr CPUS zugeteilt als der PC zu Verfügung hat.](/zuvielCPU.png "")
### Der VM wird mehr RAM zugeteilt als der PC zu Verfügung hat.
![Der VM wird mehr RAM zugeteilt als der PC zu Verfügung hat.](/zuvielRAM.png "")
(KN1 in Zusammenarbeit mit Ruben gemacht.)

## KN2
## A Lab 4.1 - EC2
### HTML-Seite, inkl. URL
![](/WebseiteMitUrlEC2.PNG "")
### Liste der EC2-Instanzen
![](/ListeInstanzenEC2.PNG "")
### Details der Web Server-Instanz (öffentliche IP sichtbar)
![](/DetailsEC2.PNG "")
### Security-Group: Liste der Inbound-Regeln
![](/ListeInboundRegelnEC2.PNG "")

## A Lab 4.2 - S3
### Liste der Buckets
![](/ListeBucketsS3.png "")
### HTML-Seite, inkl. URL
![](/webseiteMitUrlS3.PNG "")
### Liste der Dateien im Bucket
![](/ListeDateienInucketS3.PNG "")
### Eigenschaften von "Static website hosting"
![](/EigenschaftenS3.png "")

## B 
### Screenshot mit dem ssh-Befehl und des Resultats unter Verwendung des ersten Schlüssels
![](/Authenticated.PNG "")
### Screenshot mit dem ssh-Befehl und des Resultats unter Verwendung des zweiten Schlüssels
![](/Unauthenticated.PNG "")
### Screenshot der Instanz-Detail (oder Liste), so dass der verwendete Schlüssel sichtbar ist
![](/SeeKeyPair.PNG "")

## KN3
## A 

#cloud-config
# Cloud-Konfigurationsdatei
users:
  - name: ubuntu  # Benutzer mit dem Namen "ubuntu" definiert.
    sudo: ALL=(ALL) NOPASSWD:ALL # Benutzer erhält sudo-Rechte ohne Passworteingabe.
    groups: users, admin  # Benutzer ist Mitglied der Gruppen "users" und "admin".
    home: /home/ubuntu     # Heimatverzeichnis für den Benutzer ist "/home/ubuntu".
    shell: /bin/bash  # Der Benutzer verwendet die Bash-Shell als Standard-Shell.
    ssh_authorized_keys:
      - ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC0WGP1EZykEtv5YGC9nMiPFW3U3DmZNzKFO5nEu6uozEHh4jLZzPNHSrfFTuQ2GnRDSt+XbOtTLdcj26+iPNiFoFha42aCIzYjt6V8Z+SQ9pzF4jPPzxwXfDdkEWylgoNnZ+4MG1lNFqa8aO7F62tX0Yj5khjC0Bs7Mb2cHLx1XZaxJV6qSaulDuBbLYe8QUZXkMc7wmob3PM0kflfolR3LE7LResIHWa4j4FL6r5cQmFlDU2BDPpKMFMGUfRSFiUtaWBNXFOWHQBC2+uKmuMPYP4vJC9sBgqMvPN/X2KyemqdMvdKXnCfrzadHuSSJYEzD64Cve5Zl9yVvY4AqyBD aws-key       
    # Öffentlicher SSH-Schlüssel wird für den Benutzer hinzugefügt, um sich ohne Passwort anzumelden.
ssh_pwauth: false # Die Passwort-Authentifizierung über SSH ist deaktiviert.
disable_root: false # Die Möglichkeit, sich als Root-Benutzer anzumelden, ist aktiviert.
package_update: true # Das System wird aktualisiert, um sicherzustellen, dass alle Pakete auf dem neuesten Stand sind.
packages:
  - curl 
  - wget 
# Pakete "curl" und "wget" werden installiert.

