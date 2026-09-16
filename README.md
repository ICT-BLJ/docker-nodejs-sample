# Installationshilfe

In diesem README wird erklärt, wie man dieses Repository installiert.

## Schritt 1: Klonen des Repostitories

Um das Repository zu Klonen wird Git Bash benötigt. Drücke in GitHub auf "Code" und kopiere den Link. In Git Bash, schreibe "git clone" und setze den kopierten Link danach ein. Drücke Enter. Das Repository wurde nun auf deinem Computer im lokalen Benutzer gespeichert.

## Schritt 2: Installation der Notwendigen Pakete

Als nächstes sind die Packages benötigt. In diesem Repository hat es eine Datei namens "package.json". Dort stehen alle benötigten Packages drin. Gehe auf die Webseite [NPM](https://www.npmjs.com/) und suche nach "docker-nodejs". Dieses Package wird alle benötigten Packages enthalten. Kopiere den Command links und öffne nun Git Bash. Setze den Command nun bei Git Bash ein und drücke Enter.

## Schritt 3: Docker-Konfiguration und -Installation

Gehe auf die Webseite [DockerDesktop](https://www.docker.com/products/docker-desktop/) und lade die neuste Version von Docker Desktop herunter. Danach öffne PowerShell als Administrator und schreibe: "dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart". Wenn die Neuste Version von WSL installiert ist, schreibe direkt danach: "dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart" Nun ist das Neustarten des Computers Notwendig, um alles einzurichten. Wenn der Computer wieder aufgestartet ist, öffne Powershell nochmals als Administrator und schreibe: "wsl --set-default-version 2". Gratulation! Die Installation ist fertig.

## Schritt 4: Starten der Applikation in einem Docker-Container

Gehe in den Ordner docker-nodejs-sample und mache ein Rechtsklick wo nichts ist und wähle "Terminal". Schreibe zulezt noch "docker compose up". Die App ist nun in [http://localhost:3000](http://localhost:3000) erreichbar.
