# Anleitung für RoboAG-Rechner

Dieses Repository ist eine kleine Hilfe zur Installation und Konfiguration der RoboAG-Rechner. \
Zum Großteil werden die Schritte nur durch Bilder dargestellt. \
Nichtsdestotrotz sind die einzelnen Befehle im [Basis-Repository der RoboAG](https://github.com/RoboAG/bash_roboag) verankert.

# Aktuelle Version

Wir installieren auf allen Rechner des bekannte [Ubuntu](https://releases.ubuntu.com/) in der LTS version. \
Siehe auch [Wiki](https://de.wikipedia.org/wiki/Ubuntu).

[Ubuntu 22.04 LTS](https://releases.ubuntu.com/22.04/) wird aktuell verwendet. \
Zuletzt installiert wurde [Ubuntu 22.04.1 LTS](https://releases.ubuntu.com/22.04/ubuntu-22.04.1-desktop-amd64.iso).

1. [Installationsanleitung](22.04/1_install/) _nur Bilder_ 
2. [globale Einstellungen](22.04/2_setup/) _nur Bilder_ 
3. Konfiguration _keine Anleitung vorhanden_


# Ältere Versionen
Früher haben wir verschiedene Linuxdistributionen für die Client-Rechner und den Server genutzt.

## Client
### Lubuntu 20.04
[Lubuntu 20.04 LTS](https://cdimage.ubuntu.com/lubuntu/releases/20.04/release/) wird aktuell verwendet. \
Zuletzt installiert wurde [Lubuntu 20.04.1 LTS](https://cdimage.ubuntu.com/lubuntu/releases/20.04.1/release/lubuntu-20.04.1-desktop-amd64.iso).

1. [Installationsanleitung](20.04/client/1_install/README.md)
2. [globale Einstellungen](20.04/client/2_setup/README.md)
3. [lokale Konfiguration](20.04/client/3_config/README.md)

### Lubuntu 18.04
1. [Installationsanleitung für 18.04](18.04/client/1_install/README.md)
2. [Konfiguration für 18.04](18.04/client/2_setup/README.md)

## Server
Für den etwas leistungsstärkeren Server fand das weitverbreitete [Ubuntu](https://de.wikipedia.org/wiki/Ubuntu) in der Server-Version Anwendung.

[Downloadlink](https://www.ubuntu.com/download/server)

## Ubuntu Server 20.04
[Ubuntu Server 20.04 LTS](https://cdimage.ubuntu.com/ubuntu/releases/20.04/release/) wird aktuell verwendet. \
Zuletzt installiert wurde [Ubuntu Server 20.04.1 LTS](https://cdimage.ubuntu.com/ubuntu/releases/20.04/release/ubuntu-20.04.1-live-server-arm64.iso).

_keine Anleitungen vorhanden_

## Ubuntu Server 18.04
1. [Installationsanleitung für 18.04](18.04/server/1_install/README.md)
2. [Konfiguration für 18.04](18.04/server/2_setup/README.md)

# Allgemeine Hinweise
* zur Installation braucht man ein Bootmedium
    * entweder einen USB-Stick umformatieren \
      (hilfreich unter Linux ist z.B. das Tool usb-creator-gtk)
    * oder eine DVD brennen
* im BIOS des Zielrechner muss gegebenenfalls die Bootreihenfolge
  angepasst werden
