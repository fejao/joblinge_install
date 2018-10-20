![Joblinge VSC logo](pics/logo_joblinge_vsc.png?raw=true "Joblinge VSC logo")

[![License GLP3](https://img.shields.io/badge/license-GPL3-red.svg)](LICENSE.md)
[![HitCount](http://hits.dwyl.io/fejao/joblinge_install/vsc.svg)](http://hits.dwyl.io/fejao/joblinge_install/vsc)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/fejao/joblinge_install/issues)

1- Installieren Visual Studio Code
===============
wie Sie Visual Studio Code auf Ihrem Computer installieren sollten
_____________________________________________

- ## 1.1- Herunterladen das Programm
Laden Sie das Programm herunter bei:
https://code.visualstudio.com/

- ## 1.2- Installieren
  Installieren Node JS ins Windows

  - ### 1.2.1- WIP
    WIP 1
    ![VSC Image 01](pics/vsc_01.PNG?raw=true "VSC Image 01")

- ## 1.3- Visual Studio Code  Konfigurieren
  Testen der 'NodeJS' Installation

  - ### 1.3.1- Live Server installieren
    Öffnen Sie das Terminal und testen Sie mit den Befehlen

    - #### 1.3.1.1- Offnen Extensions Marketplace
      Klicken Sie auf die Schaltfläche, um das **Extensions Marketplace** zu öffnen
      ![VSC Image 01](pics/vsc_01.PNG?raw=true "VSC Image 01")

    - #### 1.3.1.2- Suche nach **Live Server**
      Geben Sie den Namen **Live Server** in das Suchfeld ein
      ![VSC Image 02](pics/vsc_02.PNG?raw=true "VSC Image 02")

    - #### 1.3.1.4- **Live Server** Installieren
      Geben Sie den Namen **Live Server** in das Suchfeld ein
      ![VSC Image 03](pics/vsc_03.PNG?raw=true "VSC Image 03")


  - ### 1.3.2- Live Server Testen
    Testen des **Live Server** mit einer Testdatei

    - #### 1.3.2.1- Erstellen Sie eine Testcodedatei
      Fügen Sie den Code zu einer Testdatei namens "index.html" hinzu und geben Sie den Code ein
      ```
      <!DOCTYPE html>
      <html lang="de">
      <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <meta http-equiv="X-UA-Compatible" content="ie=edge">
          <title>JS Example 01</title>
      </head>
      <body>
          <h1>Hallo Welt :)</h1>
      </body>
      </html>
      ```

    - #### 1.3.2.2- Öffnen Sie die Testdatei mit **Live Server**
      Klicken Sie mit der rechten Maustaste auf die Testdatei, um die **Live Server** Erweiterung zu öffnen
      ![VSC Image 04](pics/vsc_04.PNG?raw=true "VSC Image 04")

    - #### 1.3.2.3- Akzeptieren Sie die Sicherheitswarnung
      Klicken                        
      ![VSC Image 05](pics/vsc_05.PNG?raw=true "VSC Image 05")

    - #### 1.3.2.4- Server gestartet Benachrichtigung
      Bitte beachten Sie, an welchem Port der Server läuft
      ![VSC Image 06](pics/vsc_06.PNG?raw=true "VSC Image 06")

    - #### 1.3.2.5- **Live Server** testen
      In Ihrem Webbrowser gehen Sie zur Adresse: "http://localhost:PORT_NUMMER"
      Wenn Ihr Server am Port 5500 gestartet wurde, sollte es sein: http://localhost:5500
      ![VSC Image 07](pics/vsc_07.PNG?raw=true "VSC Image 07")

- ### 1.3.3- Testing JS
  Lassen Sie uns das JavaScript benutzen die **Visual Studio Code** testen

  - #### 1.3.3.1- Erstellen Sie eine Testcodedatei
    Fügen Sie den Code zu einer Testdatei namens "index.html" hinzu und geben Sie den Code ein
    ```
    <!DOCTYPE html>
    <html lang="de">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>JS Example 01</title>
    </head>
    <body>
        <h1>Hallo Welt :)</h1>
        <script>
            console.log('Hallo Welt');
        </script>
    </body>
    </html>
    ```

   - #### 1.3.3.2- Code Beispiel
      ![VSC Image 08](pics/vsc_08.PNG?raw=true "VSC Image 08")

   - #### 1.3.3.3 -Öffnen Sie die Browserkonsole
      Rechtsklick auf die Webseite oder mit der Tastaturkombination **"Stgr+Shift+i"**
      ![VSC Image 09](pics/vsc_09.PNG?raw=true "VSC Image 09")

   - #### 1.3.3.4 -Wählen Sie Konsole
      Ausgabebeispiel                       
      ![VSC Image 10](pics/vsc_10.PNG?raw=true "VSC Image 10")
