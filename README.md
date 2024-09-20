# Erstellen einer ToDo-Applikation mit Markdown, Git, GitHub und Docker 📋✏️📝

- **Klonen des Repositories**
1. Von der Git-Hub-Seite klickst du auf "Code"
2. Kopiere den HTTPS- oder den SSH-Link.
3. Öffne CMD oder Git-Bash und schreibe:
4. `$ git clone "Link"`

---
  
- **Installation der notwendigen Pakete**
- Da Sie nun eine Anwendung haben, können Sie die erforderlichen Docker-Assets erstellen, um Ihre Anwendung zu containerisieren. 
- Sie können die in Docker Desktop integrierte Funktion Docker Init verwenden, um den Prozess zu optimieren, oder Sie können die Assets manuell erstellen.

---

- **Docker-Konfiguration und -Installation**
1. Im geöffnetem CMD oder Git-Bash gibt man folgenden Code ein:
2. `$ docker init`
3. Dann erscheinen verschiedene Fragen welche man wie folgt beantworten soll: 
- ? What application platform does your project use?   *Node*
- ? What version of Node do you want to use?           *18.0.0*
- ? Which package manager do you want to use?          *npm*
- ? What command do you want to use to start the app:  *node src/index.js*
- ? What port does your server listen on?              *3000*

---

- **Starten der Applikation in einem Docker-Container 🐋**
Nach der Konfiguration, muss man es nur noch ausführen.
1. Man geht wieder in den CMD oder Git-Bash
2. Dort tippt man:
3. `$ docker compose up --build`
4. Die Applikation sollte ausgeführt werden.
5. Wenn alles geklappt han kann man auf [localhost:3000](http://localhost:3000)
6. Zum schliessen gilt `$ docker compose down`
7. Und dann wieder zu öffnen `$ docker compose up`  

Es Sollte so aussehen:

![localhost](https://github.com/user-attachments/assets/cf71a306-2f4d-4941-b75d-3d1da0ea6250)


