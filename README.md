# recipes

Ziel: autopkg mit Version: NameProgram-VersionNummer.pkg

Überblick Fälle Programmen beim Herunterladen:
 
- .dmg ---> .app  -----> .pkg mit Version : Google Chrome
- .dmg ---> .pkg ------> .pkg mit Version : Cisco Webex Meetings
- .pkg ----------------> .pkg mit Version : Zoom
- .zip ---> .app ------> .pkg mit Version : Visual Studio Code

je nachdem datei die man herunterlädt, kann man das Script anpassen

Rechte des Programm in pkg.recipe anpassen, user: root und group: admin


Die Rechte in recipes mit CFBundleVersion kann man nicht direkt die Rechte anpassen, es wird automatisch user: root und group: wheel. 
