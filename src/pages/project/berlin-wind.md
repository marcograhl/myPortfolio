---
layout: ../../layouts/project.astro
title: Berlin Wind
client: Cimdata
project: Javascript Aufbaukurs
published_at: 2020-03-06 00:00:00
img: /assets/projects/P-Berlinwind.jpg
description: |
 Die Webapp “Berlinwind” ist eine Möglichkeit schnell auf einem Blick die Windstärke und das Wetter rund um die Seen in Berlin zu erfassen. 
tags:
  - design
  - dev
---

# Berlin Wind App

| Weiterbildung:  | |
| ------------- | ------------- |
| **Client:**  | [Cimdata, Berlin](https://www.cimdata.de/)  |
| **Kurs:** | Webentwicklung JavaScript Aufbaukurs  |
| **Zeitraum:** | 15.06-10.07.2020 |
| **Projekt:** | **97**/100 Punkte|
| **Github:** | [BerlinWind](https://github.com/marcograhl/BWind) |
| **Link zur App:** | [App testen](https://marcograhl.github.io/BWind/) |

Worte vom Dozenten, **Klaus Domass**:

> „ Deine App hat mir besonders gut gefallen. Du hast dich nicht gescheut Pionierarbeit mit Leaflet zu leisten.“

## Idee
Ich möchte Windsport-Enthusiasten in Berlin unter die Arme greifen. Die App soll mit einem Blick eine schnelle Einschätzung geben, über Wind-stärke, -richtung und diese visuell unterstützen. Mit Windbarbs und einem Ampelsystem zeigt die App an, ob man gerade auf den Badeseen Berlins Windsport betreiben kann, oder nicht. Hier ein Einblick was sind Windbarbs, um warum sind Sie so nützlich zum darstellen von Windeigenschaften [How to read Wind Barbs](https://www.wikihow.com/Read-Wind-Barbs). 

## Vorrausetzungen
Der MVP definiert die Mindestanforderung der App und wird in der Entwicklungsphase als erstes umgesetzt. Folgende Punkte wurden hier berücksichtigt:
  - Anbindung an eine Wetter Api, für aktuelle Daten: [openweathermap.org](https://openweathermap.org/)
  - Interactive Map, um die Windbards zum leben zu erwecken: [Leaflet.js](https://leafletjs.com/)
  - Tiles, zur Darstellung von Berlin: [openmaptiles](https://openmaptiles.org/)
  - Windbarbs, um die Windverhältnisse darzustellen: [Leaflet Windbarb](https://github.com/spatialsparks/Leaflet.windbarb)

## Die App
![WindBarb](/assets/projects/P-Berlinwindraw.jpg)

Die Windbarbs sind an allen Badegewässern Berlins eingezeichnet und die Neigung zeigt die Windrichtung an. Durch anklicken eines Pins kann man direkt ablesen von wo der Wind herkommt und wieviel Km/h dieser aktuell beträgt. Die Legende gibt dem Windsportler Hinweise und die Möglichkeit sein Erfahrungswert auszuwählen. In der ersten Version kann man zwischen Beginner und Fortgeschritten auswählen. Das Ampelsystem passt sich dem Schwierigkeitsgrad an.

## Abschluss Worte
Die Arbeit an der App hat mir besonders viel Spass gemacht. Man kann schnell erahnen wie powervoll eine interactive Map seien kann. Probiert Wind Berlin einfach selber mal aus [link](https://marcograhl.github.io/BWind/)