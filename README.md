Noten
=====

Script for fetching grades from the internet and sending a notification, if there are new grades onlin

===============================================

EIn Skript um aus dem Datenlotsen Webportal Noten abzurufen. Derzeit ausgerichtet auf die DHBW Stuttgart

How-To
==============================================

Um das Skript auch an deinen Kurs anzupassen, müssen alle Variablen die mit Rauten gefuellt wurden ersetzt werden.

Am besten kann man dann das Skript auf einem Server laufen lassen

-> 1&1 Campuscode: Linuxserver mit Rootzugriff für 1€ pro Jahr ( https://student.campus-code.de/click.aspx?prog=1001&wid=68844&mid=3)

-> crontab zum ausführen ( https://help.ubuntu.com/community/CronHowto )

Changelog
===============================================
12.11.2014

  Nur neue Fächer werden auch an die zweite Mailadresse geschickt
  
  Erstellung der Datei gefixt
  
  Ersetzen der Umlaute in den Faechernamen
