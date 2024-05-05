# Build-Server-Plugin
Dieses Plugin kann auf jedem Buildserver verwendet werden! Hier gibt es alle Informationen die man batraucht und eine Anleitung!

## Commands
**Es gibt verschiedene Commands in diesem Plugin.**

**/world** - öffnet das world Gui (Siehe GUIs) \
**/world join <world>** - lässt dich einer anderen Welt beitreten \
**/gm <gamemode>** - lässt dich den Speilmodus wächseln \
**/items** - gibt dir deine Hotbar items

#### **Admin Commands:** 
**/admin loadDefaultRankConfig** - lädt die standart rang configuration \
**/rank <player> set <rank>** - setzt den Rang eines Spielers \
**/rank <player>** get - ruft den Rang eines Spielers ab

## Hotbar items
Es gibt verschiedene Hotbar Items mit denen man interagieren kann.

#### **World Compass** 
![Compass Hotbar Item](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/compass.png?raw=true)

Mit diesem Item kann man das World Compass man Gui öffnen (siehe Guid).

#### **Gamemode Switcher Item** 
Dieses Item kann verschiedene Aussehen haben.

**Creative:** \
![Gamemode Creative](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gamemode-creative.png?raw=true) \
**Spectaotr:** \
![Gamemode Spectator](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gamemode-spectator.png?raw=true) \
**Adventure:** \
![Gamemode Adventure](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gamemode-adventure.png?raw=true) \
**Survival:** \
![Gamemode Survival](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gamemode-survival.png?raw=true)

## Guis

#### **Compass Main Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/compass-main.png?raw=true)

In diesem Gui gibt es 2 verschiedene Buttons und in der Mitte eine Papier auf dem man allgemeine Statistiken sieht.
- **Grünes Plus:** Leitet dich ins World Create Gui weiter
- **Chest Minecart:** Leitet dich ins world list Gui weiter
- **Papier:** Statistiken

#### **World Create Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/world-create.png?raw=true)

In diesem Gui kann man eine neue Map erstellen.
- **Block (Slot 12):** Einstellung der Welt (flat,normal,nether,end)
- **Nametag:** Wenn geklicke kann man den Namen der Map in den Chat eingeben
- **Rote Glas Panes links:** Bricht das erstellen der Map ab
- **Grüne Glas Panes Rechts:** Erstellen die Map 

#### **World list Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/world-list.png?raw=true)

Dieses Gui ist eine Liste von allen Maps dies es auf dem Server gibt.
- **Map Items (player Heads):** Sind die Spieler köpfe des Map creators. Ist der Name grün, daefgst du bauen und hast Rechte, ist er Orane hat du keine Rechte. In der Item Beschreibung stehen Informationen über die Map.
- **Pfeil nach links:** Vorherige Seite
- **Pfeil nach rechts:** Nächste Seite 

#### **World Settings Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/world-settings.png?raw=true)

Hier kann man verschiedene Sachen an der Map einstellen.
- **Nametag:** Namen ändern. Neuen namen muss man in den Chat eingeben.
- **Allay Spawn egg:** Setzt den Spawn der Map.
- **Chest minecart:** öffnet das World Trusts Gui
- **Barrier:** Admins können hiermit die Map löschen
- **Banner Template:** Infos wie Namen, Owner, Erstelldatum und anderes
- **Papier:** Statistiken wie Anzehl der plazierten Blöcke, zerstörte Blöcke,... 

#### **World Trusts Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/world-trusts.png?raw=true)

Hier sieht man eine Liste an getrusteten Spielern und kann sie auch ändern.
- **Playerhead:** Ist der Spielerkopf des Getursteten spielers. Rechtsclick untrustet den Spieler, Linksclick öffnet die einstellungen in denen man das Machen kann wie im Add Trusted Player Gui.
- **Pfeil nach links:** Vorherige Seite
- **Pfeil nach rechts:** Nächste Seite
- **Pluss:** füge einen Spieler hinzu. Öffnet das add Trusted Player Gui
- **Barrier:** löscht alle Trusts

#### **World Add Trusted Player Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/world-trusts-add.png?raw=true)

Mit diesem Gui kann man einen Spieler zu den Trusts einer Map hinzufügen.
- **Playerhead:** bei klick kann man den Namen im Chat eingeben und der Spieler wird ausgewählt
- **Block (Slot 11):** Permissions des Spielers (Builder recomended!)
- **Grüner glass pane:** Confirm. Fügt den Spieler hinzu
- **Roter glass pane:** Cancel. Bricht den Vorgang ab

#### **Gamemode Gui**
![GUI](https://github.com/Silal123/Documentations/blob/main/images/build-server-plugin/gui/gamemode-gui.png?raw=true)

Mit diesem Gui kann man seinen Gamemode wechseln. Jedes Item ist ein anderer Gamemode.
