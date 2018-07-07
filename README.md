# [Konzept] WIFIonICE
Raspberry PI Zero W als unendlichen ICE Wlan Hotspot konfigurieren

## Benötigte Hardware
- Raspberry PI Zero W
- SD-Karte
- Mikro-USB-Kabel

## Konfigurationsschritte

Dies muss Headless passieren
1. Wlan
2. SSH
3. Ethernet über USB-OTG

Dies kann über SSH passieren
4. ICE Wlan einrichten
5. (OpenVPN einrichten)

Dies passiert im Hintergrund
6. MAC-Adressen bei Bedarf ändern

## Umsetzung
Am besten wär ein Konfigurationsscript, dass alle Schritte automatisch durchführt

## Probleme
Die Installation sollte Headless (ohne Monitor) funktionieren, da viele den HDMI Adapter für den Raspberry PI nicht besitzen
