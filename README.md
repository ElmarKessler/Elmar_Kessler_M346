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

## C
### Screenshot von Index Seite
![](/Apache2.PNG "")
### Screenshot von Info Seite
![](/PhpPage.PNG "")
### Screenshot von DB Seite
![](/DBPage.PNG "")
## KN3
## A 
Siehe commented-cloud-config.yaml file im Repository an.

## B
Bilder hochladen

## KN07
## 1 Rehosting
![](/Uebersicht.PNG "")
![](/UebersichtAz.PNG "")
## Warum diese Auswahl:
Ich habe bei der Konfiguration des EC2 Webservers darauf geachtet, dass alle Anforderungen erfüllt oder sogar übertroffen wurden. Ich entschied mich jedoch immer für die günstigste Variante der Konfiguration. Wenn die Anforderung z.B. 20 GB Speicher war und entweder 16 oder 32 GB zur Auswahl stünden, entschiede ich mich für 32 GB um die Anforderung abzudecken. 
Dies habe ich bei AWS sowie auch Azure getan, wobei die vorgegeben Ressourcenpakete näher an den Anforderungen waren.

## 2 Replatforming
![](/HekoruUebersicht.PNG "")
![](/PerformanceM.PNG "")
![](/Premium.PNG "")
## Warum diese Auswahl:
Beim Dynos entschied ich ich für die Performance M Variante, da sie mit 2.5 GB RAM die Anforderung von 2 GB RAM erfüllt. Das Performance M Paket verfügt über die meisten Funktionen, die ein Nutzer braucht. Bei der Datenbank entschied ich mich für die Heroku Postgres Premium Variante. Gründe dafür waren die hohe Zuverlässigkeit und maximale Auszeit von nur 15 Minuten pro Monat.

## 3 Repurchasing

Dies Beginnen
