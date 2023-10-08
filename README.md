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
## A
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

## Zoho CRM
![](/zoho.PNG "")

##Salesforce
![](/salesforce.PNG "")

## Warum diese Auswahl:
Bei ZOHO CRM kostet das Standardangebot für 16 Mitarbeiter insgesamt 224$ pro Monat, während das Starterangebot bei Salesforce für 16 Mitarbeiter 400$ pro Monat kostet. Ich habe mich für die kostengünstigste Option bei beiden Anbietern entschieden. Obwohl die Angebote nicht übermäßig teuer sind, ist Salesforce teurer als Zoho CRM. Aufgrund des Preisunterschieds habe ich mich für Zoho CRM als SaaS-Option entschieden.

Beim Vergleich der verschiedenen Cloud-Service-Modelle, nämlich SaaS (Software as a Service), PaaS (Platform as a Service) und IaaS (Infrastructure as a Service), sind einige wichtige Überlegungen zu beachten.

SaaS: Unternehmen wie Zoho und Salesforce bieten SaaS-Lösungen an. Mit SaaS erhalten Sie fertige Produkte, ohne sich um die technischen Details kümmern zu müssen. Dies ermöglicht eine schnelle Bereitstellung und ist besonders attraktiv für Unternehmen, die eine benutzerfreundliche Lösung suchen. Allerdings können SaaS-Optionen aufgrund der enthaltenen Wartung und Aktualisierungskosten etwas teurer sein. Ihre Entscheidung für SaaS hängt von der Dringlichkeit Ihrer Anforderungen und Ihrem Budget ab.

PaaS: Heroku und Google App Engine sind Beispiele für PaaS-Anbieter. Mit PaaS müssen Sie sich nicht um die Serverkonfiguration kümmern, müssen jedoch Ihre eigenen Anwendungen entwickeln und programmieren. Dies ist ideal für Unternehmen, die die Flexibilität wünschen, eigene Anwendungen zu erstellen und zu verwalten, aber die Serverseite auslagern möchten. PaaS-Modelle sind oft kostengünstiger als SaaS, insbesondere wenn Sie über die erforderlichen Entwicklerfähigkeiten und Ressourcen verfügen.

IaaS: Amazon Web Services (AWS) und Microsoft Azure sind führende IaaS-Anbieter. Bei IaaS sind Sie für die vollständige Konfiguration und Verwaltung der Infrastruktur verantwortlich. Dies bietet maximale Kontrolle und Flexibilität, kann jedoch komplex sein und erfordert technisches Know-how. IaaS ist in der Regel kostengünstiger als SaaS und PaaS, erfordert jedoch mehr technisches Wissen und Ressourcen für die Verwaltung. Ihre Wahl für IaaS sollte von Ihrem Bedarf an Kontrolle über die Infrastruktur und den vorhandenen Fähigkeiten in Ihrem Team abhängen.

Die endgültige Entscheidung zwischen diesen Modellen sollte sorgfältig abgewogen werden. Berücksichtigen Sie Faktoren wie Skalierbarkeit, Sicherheit, langfristige Kosten, die Verfügbarkeit von Personalressourcen und die Fähigkeit, zukünftige Anforderungen zu erfüllen. Eine gründliche Analyse Ihrer Geschäftsanforderungen ist ratsam, und es kann auch sinnvoll sein, eine Kombination dieser Modelle in Betracht zu ziehen, um die besten Ergebnisse für Ihr Unternehmen zu erzielen.

## B

Die Unterschiede zwischen den verschiedenen Optionen sind ziemlich groß. Wenn wir über den Preis sprechen, ist AWS mit seinem Rehosting-Service normalerweise am günstigsten. Herokus Replatforming-Service ist im Vergleich dazu teurer. Das liegt daran, dass Heroku eine umfassendere Konfiguration bietet, was die Kosten erhöht.

Die Frage nach dem "billigsten" hängt von Ihren speziellen Bedürfnissen ab. In der Regel ist AWS jedoch preislich wettbewerbsfähig und bietet oft die kostengünstigste Lösung.

Warum ist eines teurer als das andere? Das liegt vor allem an den zusätzlichen Funktionen und den individuellen Anforderungen. Heroku bietet mehr Möglichkeiten zur Anpassung, was die Kosten erhöht, aber auch mehr Funktionen bietet.

Es ist wichtig zu beachten, dass "teurer" nicht gleichbedeutend mit "übermäßig teuer" ist, da die höheren Kosten durch zusätzliche Leistungen und Funktionen gerechtfertigt sein können. Daher sollten Sie Ihre Entscheidung nicht allein aufgrund des Preises treffen, sondern auch die speziellen Anforderungen und den Mehrwert berücksichtigen, den jede Option bietet.
