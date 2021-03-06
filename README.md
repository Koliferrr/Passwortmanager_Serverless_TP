# Passwortmanager_Serverless_TP
Dieser Passwortmanager ist ein einfaches Programm wo man sich einen Benutzer erstellen und mit diesem seine Passwörter verwalten kann.
Bei dieser Version kann man sich nur einen lokalen Benutzer erstellen. Geplant war ein Multiuser Programm mit mehreren Usern und deren Passwörter.
Wegen mehreren Fehlern konnte dies aber nicht realisiert werden.
So kann man wie gesagt nur einen Benutzer erstellen und dort nur Passwörter hinzufügen die dann in einer Datenbank gespeichert werden.
Um das Programm zu starten muss man einfach die index.html mit Google Chrome (oder einen anderen Browser) öffnen.
Zuerst muss man sich registireren und dann einloggen. Nach dem Einloggen kommt man auch schon zu den Passwörtern. Hat man schon Passwörter gespeichert,
so werden diese gleich angezeigt ansonsten kann man Neue hinzufügen.
Lädt man die Seite neu so muss man sich erneut registrieren.

Die Grafische oberfläche wurde mit HTML geschrieben und bei Serverless wurde IBM.com benutzt.
Dort wurde eine API mit 2 Funktionen verwendet. Die Erste liest alle Daten aus der Datenbank heraus und die Zweite schreibt die Daten in die Datenbank hinein.
API:

![image](https://user-images.githubusercontent.com/60352250/110208622-9c6d6880-7e88-11eb-910b-34bdfc74a4f6.png)

