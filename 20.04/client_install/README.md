# Installationsanweisung für die Clients
Anleitung für Lubuntu 20.04

Gegebenenfalls auch die Hilfe in den [RoboAG-Skripten](https://github.com/RoboAG/bash_roboag) nutzen:

    $ robo_help_install

**Hinterher** müssen die Clients noch [eingerichtet](../client_setup/README.md) werden.



# Bilder
## Sprache wählen und LiveCD starten
<img src="001_sprache.png"          width="300" align="left">
<img src="002_live_cd_starten.png"  width="300">

_... lange warten ..._


## Installationsprogramm ausführen
<img src="003_installationsprogramm_ausfuehren.png" width="300" align="left">
<img src="004_start.png"            width="300">


## Zeitzone und Keyboard
<img src="005_zeitzone.png"         width="300" align="left">
<img src="006_tastatur.png"         width="300">


## Partitionierung
<img src="007_manuelle_partitionierung.png" width="300">

### 0. Festplatte löschen
<img src="008_partionen_loeschen.png" width="300" align="left">
<img src="009_bestaetigen.png"      width="300">

### 1. Root-Partition
<img src="010_freien_speicher_waehlen.png" width="300" align="left">
<img src="011_partition_1_erstellen.png" width="300">

<img src="012_partition_1_einstellungen.png" width="300">

Für die Root-Partition sollten zwischen 30GB und **50GB** genutzt werden. \
_Hinweis: im Beispiel waren insgesamt für alle Partitionen nur 40GB verfügbar_

### 2. Swap-Partition
<img src="013_partition_2_erstellen.png" width="300" align="left">
<img src="014_partition_2_einstellungen.png" width="300">

Die Swap-Partition kann 5 bis **10GB** groß sein. \
_Hinweis: falls zu wenig Speicher verfügbar ist, kann auf diese Partition_
_verzichtet werden_

### 3. home-Partition
<img src="015_partition_3_erstellen.png" width="300" align="left">
<img src="016_partition_3_einstellungen.png" width="300">

Die home-Partition kann 10 bis **20GB** groß sein.

### 4. Backup-Partition
<img src="017_partition_4_erstellen.png" width="300" align="left">
<img src="018_partition_4_einstellungen.png" width="300">

Die Backup-Partition nimmt den kompletten verbleibenden Platz ein.

### Überblick
<img src="019_alle_partitionen.png" width="300">


## Benutzer anlegen
<img src="020_benutzer_anlegen.png" width="300">


## Installation starten
<img src="021_ueberblick_einstellungen.png" width="300" align="left">
<img src="022_bestaetigen.png"      width="300" align="left">

<img src="023_laufende_installation.png" width="300" align="left">
<img src="024_ende_installation.png" width="300">

<img src="025_bootmedium_entfernen.png" width="300">
