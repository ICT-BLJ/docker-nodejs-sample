# **Thema:** Erstellen einer ToDo-Applikation mit Markdown, Git, GitHub und Docker

In dieser Abschlussaufgabe werden alle erlernten Fähigkeiten in den Bereichen **Markdown**, **Git**, **GitHub** und **Docker** kombiniert. Die Aufgabe besteht darin, eine ToDo-Applikation zu erstellen und diese in einem Docker-Container bereitzustellen.

### **Aufgabenstellung:**

1. **GitHub-Fork erstellen:**
   - Schritt 1: Im gewünschten Repo oben rechts Fork erstellen.
   - Schritt 2: In Git Bash folgendes schreiben(füge deinen Benutzernamen hinzu):
   " git clone https://github.com/deinBenutzername/docker-nodejs-sample.git "
   Es klont die Repository.
   - Schritt 3: Mit dem Befehl wechselst du den Ordner: 
   " cd docker-nodejs-sample "
   - Schritt 4: Mit " git status " kannst du den aktuellen Stand deiner Repository überprüfen.

2. **Docker-Konfiguration und -Installation**
1)	Docker Desktop und Docker für VSCode installieren
- Falls du nicht weisst, welche Version (AMD64 vs. ARM64) du benötigst, öffnest du den Administrator (windows + R, cmd) und kopierst ‘’echo %PROCESSOR_ARCHITECTURE%’’ hinein.
 .	Zuerst öffnest du Powershell als Administrator.
2) 	Die folgenden 2 Befehle hinzufügen:
- " dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart "
- " dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart "
3) Nach dem Neustart, tippst du wsl --set-default-version 2 in Powershell ein. Nun kannst du im Microsoft App Store eine Linux-Distribution nach  deiner Wahl installieren.

- Zum testen, ob es geklappt hat, kannst du in powershel den folgenden Befehl eingeben:
" docker run hello-world "


3. **Starten der Applikation in einem Docker-Container**


4.  **Dockerize das Node.js-Projekt:**
   - Verfolge die Anleitung unter [docs.docker.com](https://docs.docker.com/guides/language/nodejs/containerize/) ab dem Schritt **"Initialize Docker assets"**.
   - Dein Ziel ist es, das Projekt in einem Docker-Container lauffähig zu machen, sodass am Ende eine **ToDo-Applikation** in einem Docker-Container bereitsteht.

5. **Git-Workflows:**
   - Arbeite mit **Git**, um Änderungen regelmäßig zu committen und auf GitHub zu pushen.
   - Verwende sinnvolle Commit-Nachrichten, um deinen Fortschritt zu dokumentieren.
   - Stelle sicher, dass dein finaler Stand auf GitHub vorhanden ist.

6. **Abgabe:**
   - **Dokumentation:** Lade die erstellte Word-Dokumentation (inkl. Screenshots und Beschreibung der Schritte) in dein Repository hoch.
   - **GitHub-Link:** Stelle den Link zu deinem GitHub-Repository bereit, das den finalen Stand des Projekts enthält.

### **Ziele der Aufgabe:**
- Anwendung und Vertiefung von Git und GitHub.
- Verfassen einer strukturierten Anleitung mit Markdown.
- Containerisieren einer Node.js-Anwendung mit Docker.
- Dokumentation des gesamten Prozesses in einem Word-Dokument.
  
Viel Erfolg bei der Umsetzung!
