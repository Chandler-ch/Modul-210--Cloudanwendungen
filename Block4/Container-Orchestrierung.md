# Recherche Auftrag über Container-Orchestrierung
## Warum braucht man Container-Orchestrierung?
Ohne Container-Orchestrierung würde die Skalierung des Einsatzes von Containern den Arbeitsaufwand für deren Verwaltung exponentiell erhöhen. Wenn die Zahl der Container in einem Unternehmen in die Tausende geht, kann deren Verwaltung sehr zeitaufwendig sein.

## Wie funktioniert Container-Orchestrierung?
Anwendungen setzen sich üblicherweise aus einzeln in Containern enthaltenen Komponenten (sogenannten Microservices) zusammen, die auf Netzwerkebene organisiert werden müssen, damit die Anwendung in der gewünschten Weise ausgeführt werden kann.

Mit Container-Orchestrierung lassen sich komplexe Anwendungen managen, die aus vielen Containern bestehen und auf unterschiedlichen Clustern oder Hosts laufen. Lösungen für die Orchestrierung von Containern ermöglichen so die automatisierte Bereitstellung, Verwaltung und Skalierung von containerbasierten Anwendungen


## Welche Container-Orchestrierung Technologien kennen Sie?
Es gibt zum Beispiel Apache Mesos, Docker Swarm und Kubernetes.
Kubernetes ist dabei Open Source und von Google.

## Was versteht man unter "Scaling Containers"?
Natürlich dass man noch zusätzlich RAM oder GB zb dem Container mitgibt. In Docker Container werden mehr Replikas erstellt. Das dauert jedoch ein wenig, auch wenn der Command direkt wieder zurückkommt.


## Was gibt es für Deployment Strategien?
Es gibt verschiedene Deployment Strategien.
+ recreate
Version A wird terminated und dann wird Version B gestartet.
+ ramped
Version B ist langsam am übernehmen und ersetzt Version A.
+ blue/green
Version B wird gleichzeitig mit Version A hochgeladen. Wenn viel Traffic los ist, wird alles gleichmässig auf die beiden verteilt.
+ canary
Version B wird wie in einer Alpha mehreren Usern vorgeschlagen und wenn alles klappt ersetzt Version B als nächstes Version A.
+ a/b testing
Version B wird mehreren Usern vorgeschlagen unter bestimmten Konditionen.
+ Shadow
Version B wird neben Version A released und handelt den WorldTraffic aber hat keinen Einfluss auf eine Antwort.