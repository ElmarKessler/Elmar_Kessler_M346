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

![](/zoho.PNG "")
![](/salesforce.PNG "")

## Warum diese Auswahl:
Bei ZOHO CRM kostet das Standat Angebot für 16 Mitarbeiter zusammen 224$ im Monat.
Bei Salesforce kostet das Starter Angebot für 16 Mitarbeiter zusammen 400$ im Monat.
Ich habe mich bei beiden Anbieter für die günstigst mögliche Option entschieden. Die Angebote sind nicht allzu teuer, jedoch ist Salesforce teurer als Zoho CRM.
Ich entscheide mich wegen des Preises für Zoho CRM als SaaS.

## Vergleiche der Systeme:
Bei der Auswahl zwischen den verschiedenen Cloud-Service-Modellen, nämlich SaaS (Software as a Service), PaaS (Platform as a Service) und IaaS (Infrastructure as a Service), sollten Sie einige wichtige Faktoren berücksichtigen.

SaaS: Unternehmen wie Zoho und Salesforce bieten SaaS-Lösungen an. Bei SaaS erhalten Sie fertige Produkte, ohne sich um die Hintergrundkonfiguration kümmern zu müssen. Dies ermöglicht eine schnelle Bereitstellung und ist besonders attraktiv für Unternehmen, die eine benutzerfreundliche Lösung suchen. Allerdings gehen mit dieser Bequemlichkeit oft höhere Kosten einher, da Wartung und Aktualisierung in den Gebühren enthalten sind. Ihre Wahl für SaaS hängt von der Dringlichkeit Ihrer Anforderungen und Ihrem Budget ab.

PaaS: Heroku und Google App Engine sind Beispiele für PaaS-Anbieter. Mit PaaS müssen Sie sich nicht um die Serverkonfiguration kümmern, haben jedoch die Verantwortung, eigene Anwendungen zu entwickeln und zu programmieren. Dies ist ideal für Unternehmen, die die Flexibilität benötigen, eigene Anwendungen zu erstellen und zu verwalten, aber die Serverseite auslagern möchten. PaaS-Modelle sind oft kostengünstiger als SaaS, insbesondere wenn Sie Ihre eigene Software entwickeln können. Ihre Wahl für PaaS sollte davon abhängen, ob Sie die Entwicklungsfähigkeiten und Ressourcen haben, um Ihre Anwendungen zu erstellen.

IaaS: Amazon Web Services (AWS) und Microsoft Azure sind führende IaaS-Anbieter. Bei IaaS sind Sie für die vollständige Konfiguration und Verwaltung der Infrastruktur verantwortlich. Dies bietet maximale Kontrolle und Flexibilität, kann jedoch komplex und anspruchsvoll sein, insbesondere ohne entsprechendes technisches Wissen. IaaS ist in der Regel kostengünstiger als SaaS und PaaS, erfordert jedoch mehr technisches Know-how und Ressourcen für die Verwaltung. Ihre Wahl für IaaS sollte davon abhängen, wie wichtig Ihnen die Kontrolle über Ihre Infrastruktur ist und ob Ihr Team die erforderlichen Fähigkeiten besitzt.

Ihre endgültige Wahl zwischen diesen Modellen sollte sorgfältig abgewogen werden. Berücksichtigen Sie Faktoren wie Skalierbarkeit, Sicherheit, langfristige Kosten, Verfügbarkeit von Personalressourcen und die Fähigkeit, zukünftigen Anforderungen gerecht zu werden. Es ist ratsam, eine gründliche Analyse Ihrer Geschäftsanforderungen durchzuführen und möglicherweise eine Kombination dieser Modelle in Betracht zu ziehen, um die besten Ergebnisse für Ihr Unternehmen zu erzielen.
