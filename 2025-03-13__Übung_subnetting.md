# Übung Subnetting
# Hilfsmittel: https://www.aelius.com/njh/subnet_sheet.html^
# Hinweis: Sie sollten sich die Antworten in einem Editor ansehen für die Formatierung

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

**Antwort**
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
Wir brauchen mind. 10 Subnets, die mind. 12 Hosts pro Subnet haben.
/28 bietet sich perfekt an weil wir mit /28 insgesamt 14 Hosts pro Subnet haben.
Subnetzmaske: 255.255.255.240

Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.
193.170.20.0                   193.170.20.1 - 193.170.20.14       193.170.20.15                  /28
193.170.20.16                  193.170.20.17 - 193.170.20.30      193.170.20.31                  /28
193.170.20.32                  193.170.20.33 - 193.170.20.46      193.170.20.47                  /28
193.170.20.48                  193.170.20.49 - 193.170.20.62      193.170.20.63                  /28
193.170.20.64                  193.170.20.65 - 193.170.20.78      193.170.20.79                  /28
193.170.20.80                  193.170.20.81 - 193.170.20.94      193.170.20.95                  /28
193.170.20.96                  193.170.20.97 - 193.170.20.110     193.170.20.111                 /28
193.170.20.112                 193.170.20.113 - 193.170.20.126    193.170.20.127                 /28
193.170.20.128                 193.170.20.129 - 193.170.20.142    193.170.20.143                 /28
193.170.20.144                 193.170.20.145 - 193.170.20.158    193.170.20.159                 /28
193.170.20.160                 193.170.20.161 - 193.170.20.174    193.170.20.175                 /28
193.170.20.176                 193.170.20.177 - 193.170.20.190    193.170.20.191                 /28
193.170.20.192                 193.170.20.193 - 193.170.20.206    193.170.20.207                 /28
193.170.20.208                 193.170.20.209 - 193.170.20.222    193.170.20.223                 /28
193.170.20.224                 193.170.20.225 - 193.170.20.238    193.170.20.239                 /28
193.170.20.240                 193.170.20.241 - 193.170.20.254    193.170.20.255                 /28

## Übung 5

Bestimmen Sie die Subnetmaske mit folgenden Angaben:

Netzadresse: 210.52.190.0
Subnetze: Anzahl 5
Mindestanzahl von Hosts je Subnetz: 10

**Antwort**
Es ist ungefähr wie bei Übung 4.
Weil wir im Subnet mind. 10 Hosts brauchen, müssen wir /28 oder niedriger (z.B.: /27, /26, /25,...) wählen.
Ein /28 Subnet hat 16 Adressen, heißt 14 Host-Adressen.
Wir benötigen nur 5 Subnets, die restlichen 11 Subnets dienen als Reserve.

Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.
210.52.190.0                   210.52.190.1 - 210.52.190.14       210.52.190.15                  /28
210.52.190.16                  210.52.190.17 - 210.52.190.30      210.52.190.31                  /28
210.52.190.32                  210.52.190.33 - 210.52.190.46      210.52.190.47                  /28
210.52.190.48                  210.52.190.49 - 210.52.190.62      210.52.190.63                  /28
210.52.190.64                  210.52.190.65 - 210.52.190.78      210.52.190.79                  /28
210.52.190.80                  210.52.190.81 - 210.52.190.94      210.52.190.95                  /28
210.52.190.96                  210.52.190.97 - 210.52.190.110     210.52.190.111                 /28
210.52.190.112                 210.52.190.113 - 210.52.190.126    210.52.190.127                 /28
210.52.190.128                 210.52.190.129 - 210.52.190.142    210.52.190.143                 /28
210.52.190.144                 210.52.190.145 - 210.52.190.158    210.52.190.159                 /28
210.52.190.160                 210.52.190.161 - 210.52.190.174    210.52.190.175                 /28
210.52.190.176                 210.52.190.177 - 210.52.190.190    210.52.190.191                 /28
210.52.190.192                 210.52.190.193 - 210.52.190.206    210.52.190.207                 /28
210.52.190.208                 210.52.190.209 - 210.52.190.222    210.52.190.223                 /28
210.52.190.224                 210.52.190.225 - 210.52.190.238    210.52.190.239                 /28
210.52.190.240                 210.52.190.241 - 210.52.190.254    210.52.190.255                 /28


## Übung 6

Teile  ein /30 Netz auf!    Wozu werden diese /30 Netze am häufigsten verwendet?
Antwort:

**Antwort**
/30 Subnets werden am häu     ungen zwischen Routern verwendet.

## Übung 7

Nennen Sie den jeweiligen Netz- und Hostanteil der Klassen A, B und C

**Antwort**
