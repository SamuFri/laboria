# Anforderungen
## IndexDB Initial
Im Tab Upgrades wird eine Liste von UpgradeItem anzeigt.
Die Daten kommen aus dem UpgradeDbService.
Im UpgradeDbService wird die IndexDB erstellt mit idb.
Außerdem werden dort drei Upgrades frei definiert und in der IndexDB gespeichert.

Es soll auch eine Methode geben die dann alle Upgrades abfragt.
In UpgradeListComponent soll dann die Liste geladet werden.

*Achtung viele Dinge laufen hier asynchron bei der DB.*

## Upgrade Item
Die Upgrades sollen dann den Klicker Count beeinflussen.
isActive gibt an ob das Item schon gekauft worden ist oder nicht.
multiplier gibt den Einfluss zum Klicker Count an. (pro Klick bekommt man dann 10 mehr Clicks)
name und description soll angezeigt werden
cost gibt an wie viel Clicks abgezogen werden sollen wenn man das Upgrade active schalten möchte.
