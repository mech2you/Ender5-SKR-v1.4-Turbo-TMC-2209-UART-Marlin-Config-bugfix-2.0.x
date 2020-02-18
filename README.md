# Ender5-SKR-v1.4-Turbo-TMC-2209-UART-Marlin-Config-bugfix-2.0.x
marlinfw bugfix-2.0.x für einen Ender 5 mit SKR 1.4 Turbo Board, TMC 2209 UART, Z-Achse Endschalter, X-Y StallGuard

Wichtig!! Wird die Z Achse mit einen Endschalter verwendet muss am TMC 2209 der Diagnosepin abgetrennt werden sonnst geht der Schalter nicht. 

MarlinFW bugfix-2.0.x Runterladen https://marlinfw.org/meta/download/ und entpacken. Dann die Dateien überschreiben. Firmware mit Visual Studio Code kompalieren (https://code.visualstudio.com/). Dann die Extension PlatformIO IDE installieren. Ordner in VS laden und unten auf Build klicken. Wenn alles klappt dann läuft das Programm durch und ihr könnt die Firmware auf die SD Karte des Druckers packen. Danach den Druck starten und die neue Firmware ist drauf ;)
