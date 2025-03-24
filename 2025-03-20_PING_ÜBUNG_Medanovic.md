## IPCONFIG von meinem Laptop

C:\Users\adome>ipconfig

Windows-IP-Konfiguration


Ethernet-Adapter Ethernet 2:

   Verbindungsspezifisches DNS-Suffix:
   Verbindungslokale IPv6-Adresse  . : fe80::62ad:a3a6:ea0d:1969%9
   IPv4-Adresse (Auto. Konfiguration): 169.254.243.202
   Subnetzmaske  . . . . . . . . . . : 255.255.0.0
   Standardgateway . . . . . . . . . :

Drahtlos-LAN-Adapter LAN-Verbindung* 1:

   Medienstatus. . . . . . . . . . . : Medium getrennt
   Verbindungsspezifisches DNS-Suffix:

Drahtlos-LAN-Adapter LAN-Verbindung* 2:

   Medienstatus. . . . . . . . . . . : Medium getrennt
   Verbindungsspezifisches DNS-Suffix:

Drahtlos-LAN-Adapter WLAN:

   Verbindungsspezifisches DNS-Suffix: grg
   Verbindungslokale IPv6-Adresse  . : fe80::38a0:c589:ae79:7321%16
   IPv4-Adresse  . . . . . . . . . . : 192.168.33.150
   Subnetzmaske  . . . . . . . . . . : 255.255.255.0
   Standardgateway . . . . . . . . . : 192.168.33.1

Ethernet-Adapter Ethernet:

   Medienstatus. . . . . . . . . . . : Medium getrennt
   Verbindungsspezifisches DNS-Suffix: htl-wien5.schule

## PING an den Laptop von Cesur Kul (192.168.33.149)

C:\Users\adome>ping 192.168.33.149

Ping wird ausgeführt für 192.168.33.149 mit 32 Bytes Daten:
Antwort von 192.168.33.149: Bytes=32 Zeit=3ms TTL=128
Antwort von 192.168.33.149: Bytes=32 Zeit=2ms TTL=128
Antwort von 192.168.33.149: Bytes=32 Zeit=2ms TTL=128
Antwort von 192.168.33.149: Bytes=32 Zeit=3ms TTL=128

Ping-Statistik für 192.168.33.149:
    Pakete: Gesendet = 4, Empfangen = 4, Verloren = 0
    (0% Verlust),
Ca. Zeitangaben in Millisek.:
    Minimum = 2ms, Maximum = 3ms, Mittelwert = 2ms

## ARP REQUEST an den Laptop von Cesur Kul (192.168.33.149) um seine MAC Adresse zu kriegen
C:\Users\adome>arp -a 192.168.33.149

Schnittstelle: 192.168.33.150 --- 0x10
  Internetadresse       Physische Adresse     Typ
  192.168.33.149        74-4c-a1-be-87-6f     dynamisch
