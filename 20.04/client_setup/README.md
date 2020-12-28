# Setup für die Clients
Anleitung für Lubuntu 20.04

Bitte **vorher** die [Installation](../client_install/README.md) ausführen!

Gegebenenfalls auch die Hilfe in den [RoboAG-Skripten](https://github.com/RoboAG/bash_roboag) nutzen:

    $ robo_help_install

**Hinterher** sollten die Clients noch für jeden Benutzer
[konfiguriert](../client_config/README.md) werden.

_Hinweis: Konsole mit [strg]+[alt]+[t] öffnen und hinterher z.B. mit [strg]+[d] schließen_



# Bilder
## Erste Anmelden und Updates
<img src="101_anmeldung.png"        width="300" align="left">
<img src="102_start_updates.png"    width="300">


## RoboAG-Skripte auschecken

    # Konsole öffnen (<strg>+<alt>+<t>)
    $ sudo mkdir -p /opt/roboag/repos
    $ sudo chown guru:guru /opt/roboag/repos
    $ cd /opt/roboag/repos
    $ wget raw.githubusercontent.com/RoboAG/bash_roboag/master/checkout.sh

<img src="103_roboag_scripts_vorbereitung.png" width="300" align="left">
<img src="104_roboag_scripts_auschecken.png" width="300">

    $ source checkout.sh
        # Fragen mit "yes" beantworten

<img src="105_bestaetigung.png" width="300">

    # hinterher Konsole schließen (<strg>+<d>)

## Repositorys herunterladen

    # Konsole öffnen (<strg>+<alt>+<t>)
    $ repo_clone_all
        # Frage mit "yes" beantworten

<img src="106_alle_repos_herunterladen.png" width="300" align="left">
<img src="107_fertig.png"           width="300">

    # hinterher Konsole schließen (<strg>+<d>)

## Globale Einstellungen setzen

    # Konsole öffnen (<strg>+<alt>+<t>)
    $ config_bash_search
        # Frage mit "yes" beantworten
    $ config_clear_home
        # Frage mit "yes" beantworten

<img src="108_einstellung_bash_suche.png" width="300" align="left">
<img src="109_einstellung_clear_home.png" width="300">

    # hinterher Konsole schließen (<strg>+<d>)

## Benutzer RoboAG anlegen

    # Konsole öffnen (<strg>+<alt>+<t>)
    $ sudo adduser roboag
        # neues Passwort eingeben (2x)
        # Name eingeben: RoboAG
        # die nächsten 4 Felder frei lassen (Zimmer, Telefon, Sonstiges)
        # Frage mit "J" beantworten (oder ebenfalls leer lassen)

<img src="110_benutzer_roboag.png"  width="300">

    $ sudo addgroup guru roboag

<img src="111_guru_zu_roboag.png"   width="300">

    $ sudo addgroup roboag dialout
    $ sudo addgroup roboag plugdev

<img src="112_roboag_zu_dialout.png" width="300" align="left">
<img src="113_roboag_zu_plugdev.png" width="300">


## Samba-Freigabe

    $ sudo mkdir -p /mnt/roboag
    $ sudo mkdir -p /mnt/robosax

<img src="114_samba_ordner.png"     width="300">

_... todo ..._





## Herunterfahren
<img src="198_herunterfahren.png"   width="300" align="left">
<img src="199_bestaetigen.png"      width="300">
