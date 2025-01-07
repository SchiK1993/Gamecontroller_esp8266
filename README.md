/*
 * -----------------------------------------------------------------------------
 * Titel        : Schnuppertage Controller 2024
 * Entwickler   : Kevin Schiechtl
 * Jahr         : 2024
 * Beschreibung : 
 * Dieses Programm ist ein vielseitiger Controller, der während der Schnuppertage 
 * an der HTL Anichstraße genutzt wird, um Schüler:innen verschiedene Spiele und 
 * Sensoranwendungen auf einem ESP8266 zu demonstrieren. Die Steuerung erfolgt 
 * über Joysticks und Tasten, während ein OLED-Display die grafische Ausgabe 
 * übernimmt.
 * 
 * Hauptfunktionen:
 *  - Verschiedene Spiele wie Snake, Pong, Flappy Bird und Space Shooter.
 *  - Anzeige von Sensorwerten wie Temperatur und Lichtintensität.
 *  - Würfel-Simulation für Demonstrationszwecke.
 *  - OTA-Update-Modus für einfache Programmaktualisierung via WLAN.
 *
 * Hardware:
 *  - ESP8266 Microcontroller
 *  - SH1106 OLED Display
 *  - Temperatursensor (DallasTemperature) DS18B20
 *  - LDR für Lichtintensitätsmessung
 *  - Ein Joystick für Steuerung (X- und Y-Achse)
 *  - Eine ButtonTaste für Moduswechsel und Auswahl
 *
 * Steuerung:
 *  - Bewegung in der X-Richtung des Joysticks ändert den Modus (z. B. Spiele).
 *  - Joystick Y-Bewegungen und Tasten interagieren mit den einzelnen Modi.
 *
 * WLAN-Features:
 *  - Eigenes WLAN-Netzwerk ("ESP8266_wifi", PW: "elektronik").
 *  - HTTP-Update-Server für einfache Firmware-Updates.
 *  - Anzeigen von WLAN-Details auf dem Display.
 *  - OTA Update Adresse: http://192.168.4.1/update
 * Hinweis:
 * Dieses Programm wurde speziell für die Schnuppertage entwickelt und dient 
 * als praktische Demonstration der Möglichkeiten von Mikrocontrollern in 
 * Verbindung mit moderner Elektronik und Programmierung.
 *
