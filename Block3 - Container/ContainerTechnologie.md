# Fragen zur Container Technologie
## Was ist Container-Technologie oder Container-Virtualisierung?
Container sind eine Technologie, die dazu verwendet wird, eine Anwendung mit allen ihren erforderlichen Dateien in einer einzigen Runtime-Umgebung zu bündeln. Als eine solche Einheit kann ein Container problemlos verlegt und auf jedem beliebigen Betriebssystem in jedem Kontext ausgeführt werden.

Unter Containervirtualisierung versteht man ein Konzept, bei dem interne Funktionen des Betriebssystems dazu genutzt werden, Anwendungen voneinander isoliert auf demselben Hostsystem zu betreiben. 
Wie bei virtuellen Maschinen werden Container dazu verwendet, Anwendungen voneinander isoliert auf einem System zu betreiben.

## Was sind die Vor- und Nachteile der Container-Technologie zu virtuellen Servern (VM)?
Nachteile wären zum Beispiel dass sich einzelne Dateien nicht abspeichern oder verschieben lassen oder vollständige Betriebssysteme nicht ausführbar sind, während auf der anderen Seite (Vorteile) eine höhere Effizienz steht, eine bessere Portabilität und weniger Zeitaufwand, welcher unnötig gewesen wäre. Ausserdem brauchen Container weniger Systemressourcen als VMs, da sie keine Betriebssystem Images enthalten.

## Welche Produkte kennen Sie im Zusammenhang mit virtuellen Servern und Container?
**Container:**
+ Docker Desktop
+ Open Shift
+ Microsoft Azure
+ Amazon Elastic Compute Cloud

**Virtual Servers:**
+ VMWare
+ VirtualBox
+ Hyper-V
+ Citrix


## Wie unterscheiden sich die Technologien VM und Container in Bezug auf Bereitstellung, Speicherplatz, Portabilität, Effizienz und Betriebssystem (Kernel)?
**Portabilität**
*As they are more lightweight and portable than VMs, containers support decomposition of a monolith into microservices. Containers are faster to manage and deploy than VMs, which can save time and money with application deployment.*

**Bereitstellung**
in konstruktion

**Speicherplatz**
Beide brauchen ein persistentes Speichersystem, ansonsten würden die ganzen Daten verloren gehen.