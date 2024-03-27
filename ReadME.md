# Docker
## Warum werden Docker verwendet ? (Vorteile / Nachteile)
| Vorteile                                            | Nachteile                                                               |
|-----------------------------------------------------|-------------------------------------------------------------------------|
| - schnelles Verpacken und Ausführen von Anwendungen | - unübersichtlich Verwaltung/Einrichtung                                |
| - schnelle Software bereitstellung                  | - Falsche Konfigurationen sorgen für Sicherheitsprobleme                |
| - Unabhängigkeit von der Umgebung                   | - unnötiger Ressourcenverbrauch des Systems                             |
| - Schnelle Rollbacks und Updates                    | - mögliche Leistungsprobleme, besonders bei älteren Computer            |
| - Effizente Ressourcennutzung durch Container      | - Lernkurve für Anfänger                                                |

## Was sind Dockerfiles und für was werden sie verwendet?
### Was sind Docker Files?
<p1>
<p1/>

Ein Dockerfile ist ein **TextDokument**

### Wofür werden werden DockerFiles verwendet 
<p1>
<p1/>

DockerFiles werden dafür verwendet **anweisungen zu erstellen von Docker Images** zu erhalten

## Wie werden Docker-Images erstellt, und Welche Rolle spielt dabei die Dockerfile?
### Wie werden Docker Images erstellt?
<p1>
<p1/>

Docker-Images werden durch das **Ausführen eines Docker-Befehls erstellt**, der die Anweisungen in einem Dockerfile befolgt.
<p1>
<p1/>

### Welche Rolle spielt dabei die Dockerfile
Dieser Befehl nimmt das Dockerfile und verwandelt es in ein ausführbares Image.
![Dockerfiles](https://miro.medium.com/v2/resize:fit:1400/0*CP98BIIBgMG2K3u5.png)

##	Was versteht man unter einem Basis-Image in Bezug auf Docker? 
<p1>
<p1/>

Ein Basis-Image ist das Ausgangsimage, auf dem ein Docker-Image aufbaut. Es enthält das Betriebssystem und grundlegende Softwarepakete, die für die Ausführung von Anwendungen benötigt werden.

## Welche Vorteile bietet die Verwendung von Docker-Registries wie Azure-Registry?
<p1>
<p1/>

Docker-Registries dienen dazu, **Docker-Images zu speichern und zu verteilen**. Sie ermöglichen es, Images zentral zu verwalten und mit anderen zu teilen. Beispiele sind Azure-Registry oder Docker Hub.
![Docker-Registry](https://i.ibb.co/r5QV7Hg/1-in6-B62-Uq-KHCFP0t6-Tu-Vt-KA.jpg)

## Wie können Docker-Images mit Tags versehen werden, und wozu dienen diese Tags? 
### Wie könen Docker-Images mit Tags versehen werden?
<p1>
<p1/>
Docker-Images können mit Tags versehen werden, um verschiedene Versionen oder Varianten zu kennzeichnen.

### Wozu dienen die Tags in Docker-Images
<p1>
<p1/>
Die Tags dienen zur Identifizierung und zum einfachen Zugriff auf bestimmte Versionen eines Images.


## Eläuterung des Prozess Pullens und Pushens von Docker-Images zwischen einem lokalen System und einer Docker-Registry.
### Wie funktioniert das Pullen eines Docker Image ?
<p1>
<p1/>

Beim Pullen wird ein Docker-Image von einem Registry server auf das lokale System heruntergeladen.

### Wie funktioniert das Pushen eines Docker Images?
<p1>
<p1/>

Beim Pushen wird ein lokal erstelltes Imagine in den Registry-Server hochgeladen.

## Warum sind Docker-Images schichtbasiert aufgebaut, und welche Vorteile bringt es mit sich?
Docker-Images sind schichtbasiert aufgebaut, wobei jede Schicht Änderungen am Dateisystem darstellt. Dies ermöglicht eine effiziente Speicherung und Übertragung von Images sowie eine Wiederverwendung von gemeinsamen Schichten zwischen verschiedenen Images.

## Wie können Docker-Images effizient genutzt werden, um die Bereitstellung von Anwendungen zu verbessern?
Mit Docker können Anwendungen schnell und einfach bereitgestellt und skaliert werden, weil sie in Containern verpackt sind. Diese Container enthalten alles, was die Anwendung benötigt, um zu funktionieren, wodurch sie unabhängig und leicht zu handhaben sind.

## Welche Best Practices sollten beim Erstellen und Verwalten von Docker-Images beachtet werden?
Best Practices für Docker-Images beinhalten die Nutzung von kleinen Basis-Images, das Minimieren der Schichtanzahl, das Optimieren der Dockerfiles und die Verwendung von Multi-Stage-Builds, um die Bildgröße zu reduzieren.
![Docker-Best-Practice](https://sysdig.es/wp-content/uploads/Dockerfile-best-practices-02-local-development.png)

## Wie kann die Sicherheit von Docker-Images sichergestellt werden, insbesondere beim Einsatz in Produktionsumgebungen?
Die Sicherheit von Docker-Images kann durch Überprüfen von Quellcode, Verwendung bekannter und vertrauenswürdiger Basis-Images, regelmäßige Updates und Patches sowie die Implementierung von Sicherheitsrichtlinien und -maßnahmen verbessert werden.


