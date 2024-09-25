# Installations-Schritte des Projekts

### Klonen des Repositories
Um das Repositorie zu klonen, muss man zuerst einen Fork vom Repositorie in GitHub erstellen. Danach die Repositorie URL für den SSH Key auf GitHub kopieren und dann im gewünschten Ordner lokal klonen.

### Docker-Konfiguration und -Installation
Um Doker Desktop herunterzuladen, muss man auf die Website [Docs.Doker](https://docs.docker.com/manuals/) öffnen. Dann muss man auf der linken Seite Doker Desktop auswählen, Install, das Betriebssystem das man benutzt und zum Schluss welche Version man herunterladen möchte.

### Installation der notwendigen Pakete
Um die notwendigen Pakete installieren kann man der Anleitung auf [Docs.Doker](https://docs.docker.com/guideslanguage/nodejs/containerize/). Um die Anleitung zu starten, muss man in der Kommandozeile ```docker init``` eingeben. Danach muss man die Fragen wie folgt beantworten.

```text
? What application platform does your projectuse? Node
? What version of Node do you want to use? 18.0.0
? Which package manager do you want to use? npm
? What command do you want to use to start the app: node src/index.js
? What port does your server listen on? 3000
```

### Starten der Applikation in einem Docker-Container!
Um dann die Applikation zu starten, muss man in der Kommandozeile ```docker compose up --build``` eingeben. Falls man dann kein Error hat, hat man alles richtig gemacht. Jetzt kann man den Doker Desktop öffnen und die Applikation starten. Um die Applikation wieder zu stoppen, muss man in der Kommandozeile ```docker compose down``` eingeben.