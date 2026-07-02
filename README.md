Hallo und Willkommen auf meiner Seite.

Meine Projekte sind eigentlich sehr viele,
wobei sie nur Zuhause sichtbar sind.

Das nützt aber der Gemeinschafft nichts.
Darum versuche ich es hier der Welt zu zeigen
und ihnen bei einigen Ideen zu helfen.


Dieses Projekt ist die D-Link Kamera von der Telekom.


model=SmartHome Kamera Innen Basic

product=Wireless Internet Camera

brand=D-Link

<img width="1664" height="936" alt="DCS-T8000" src="https://github.com/user-attachments/assets/e9d93391-4570-4424-975d-24c5c1f3505e" />

Meine Antwort: Ja und Nein.

Ich habe es geschafft, einige Funktionen herauszufinden

Doch das wäre ohne „github.com“ nicht möglich gewesen.
Was habe ich geschafft:
Ich kann im Heimnetz das Video und Ton Streamen und auch das Datum konnte ich ändern. Leider geht die Uhrzeit aber noch falsch aber das ist eines der Baustellen. Bilder gehen auch im Edge wie auch das Video in Edge und Videolan.
Bilder ruft man auf mit:

http://admin:@ DIE IP DER KAMERA /image/jpeg.cgi

Video mit der Adresse: - Die auch für VLC gilt.

rtsp://admin:@ IP DER KAMERA /live1.sdp

Wichtige Seiten:

http://admin:@ DIE IP DER KAMERA /common/info.cgi

model=SmartHome Kamera Innen Basic

product=Wireless Internet Camera

brand=D-Link

version=1.00

build=07

hw_version=A

nipca=1.9.7

name=DCS-T8000

location=

macaddr=xx:xx:xx:xx:xx:xx

ipaddr= IP ADRESSE DER KAMERA

netmask=255.255.255.0

gateway= IP ADRESSE DES ROUTERS

wireless=yes

inputs=0

outputs=0

speaker=no

videoout=no

pir=no

icr=yes

ir=yes

mic=yes

led=no

td=no

playing_music=no

whitelightled=no

http://admin:@ DIE IP DER KAMERA /config/datetime.cgi

timeserver=0.de.pool.ntp.org

timezone=2

utcdate=2026-07-02

utctime=09:45:16

date=2026-07-02

time=22:45:16

dstenable=yes

dstauto=yes

offset=01:00

starttime=3.2.0/02:00:00

stoptime=11.1.0/02:00:00

Den Timserver habe ich geändert, da der von D-Link wohl nicht mehr funktioniert.
Das geht ganz einfach mit: http://admin:@ DIE IP DER KAMERA /config/datetime.cgi?timeserver=0.de.pool.ntp.org
