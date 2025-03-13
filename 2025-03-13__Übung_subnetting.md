# Übung Subnetting
# Hilfsmittel: https://www.aelius.com/njh/subnet_sheet.html

## Übung 1

Bilde aus dem Netz 192.168.0.0 /24 4 Subnetze. Netze mit Mindestzahl an nutzbaren Host aber nicht darunter wählen: Netz a mit 20, Netz b mit 15, Netz c mit 30, und das Netz d mit den Rest Anteil der Netzwerkadressen.

**Antwort**
Netz A (mind. 20 Hosts):
Netzwerkadresse: 192.168.0.0/27
Hostadressen: 192.168.0.1 - 192.168.0.30
Broadcastadresse: 192.168.0.31

Netz B (mind. 15 Hosts):
Netzwerkadresse: 192.168.0.32/27
Hostadressen: 192.168.0.33 - 192.168.0.62
Broadcastadresse: 192.168.0.63

Netz C (mind. 30 Hosts):
Netzwerkadresse: 192.168.0.64/26
Hostadressen: 192.168.0.65 – 192.168.0.126
Broadcastadresse: 192.168.0.127

Netz D (Rest):
Netzwerkadresse: 192.168.0.128/25
Hostadressen: 192.168.0.129 – 192.168.0.254
Broadcastadresse: 192.168.0.255


## Übung 2

Teile das Netz 193.170.20.0 /24 in 8 gleich große Netze! Erstelle eine Tabelle mit folgenden Angaben:

## Antwort
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.
193.170.20.0                   193.170.20.1 - 193.170.20.30       193.170.20.31                  /27
193.170.20.32                  193.170.20.33 - 193.170.20.62      193.170.20.63                  /27
193.170.20.64                  193.170.20.65 - 193.170.20.94      193.170.20.95                  /27
193.170.20.96                  193.170.20.97 - 193.170.20.126     193.170.20.127                 /27
193.170.20.128                 193.170.20.129 - 193.170.20.158    193.170.20.159                 /27
193.170.20.160                 193.170.20.161 - 193.170.20.190    193.170.20.191                 /27
193.170.20.192                 193.170.20.193 - 193.170.20.222    193.170.20.223                 /27
193.170.20.224                 193.170.20.225 - 193.170.20.254    193.170.20.255                 /27

## Übung 3

172.28.40.0 /26 Teile wie folgt auf: 2 Netze!
Erstelle eine Tabelle mit folgenden Angaben:

**Antwort**
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.
172.28.40.0                    172.28.40.1 - 172.28.40.30         172.28.40.31                   /27
172.28.40.32                   172.28.40.33 - 172.28.40.62        172.28.40.63                   /27

## Übung 4

Wie lautet die Subnetzmaske bei der Netzadresse: 17.0.0.0 mit 10 verwendbaren Subnetzen, sowie mit mindestens 12 Hosts je Subnetz?
Antwort in Sätzen, wie sie zu dieser Lösung kommen; und erstelle eine Tabelle:

**Antwort**

## Übung 5

Bestimmen Sie die Subnetmaske mit folgenden Angaben:

Netzadresse: 210.52.190.0
Subnetze: Anzahl 5
Mindestanzahl von Hosts je Subnetz: 10

**Antwort**

## Übung 6

Teile  ein /30 Netz auf!    Wozu werden diese /30 Netze am häufigsten verwendet?
Antwort:

**Antwort**

## Übung 7

Nennen Sie den jeweiligen Netz- und Hostanteil der Klassen A, B und C

**Antwort**
