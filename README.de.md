<p align="center"><img src="docs/images/banner_de.png" alt="DunenScope" width="100%"></p>

<p align="center"><a href="README.md">English</a> · <a href="README.fr.md">Français</a> · <a href="README.zh.md">中文</a> · <a href="README.es.md">Español</a> · <b>Deutsch</b> · <a href="README.it.md">Italiano</a> · <a href="README.pt.md">Português (BR)</a> · <a href="README.ru.md">Русский</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a></p>

<p align="center"><a href="https://github.com/simonlabrossedu71-tech/DunenScope/releases/latest"><img src="docs/images/download_de.png" alt="Für Windows herunterladen" height="60"></a></p>
<p align="center"><sub>Windows 10 / 11 · 64 Bit · kostenloser Demomodus</sub></p>

## Diagnose- und Inbetriebnahmesoftware für Dunen / ELYX-Motorcontroller

DunenScope macht aus einem Windows-PC und einem CAN-Adapter einen vollständigen Prüfstand für Dunen / ELYX-Controller: sehen, was die Maschine tut, verstehen, was sie begrenzt, sie einstellen und beweisen, dass sie funktioniert — in Minuten und in Ihrer Sprache.

<p align="center"><img src="docs/images/de/dashboard.png" alt="Übersicht" width="100%"></p>

## Was DunenScope kann

- **Live-Übersicht** — Drehzahl, Drehmoment, Batteriespannung und -strom, Gashebel, Leistung, Temperaturen, Zustand und Fehler auf einem Bildschirm; Pumpenförderstrom oder Fahrzeuggeschwindigkeit aus Ihrem Maschinenprofil.
- **„Warum ist es begrenzt?“** — zeigt, welche Grenze gerade wirkt (Drehmoment, Batteriestrom, Drehzahl, Spannung) und wie lange; Innenwiderstand und Reserven der Batterie; Verdrahtungsprüfung jedes Eingangs; verbleibende Zeit bis zur thermischen Reduzierung; Analyse des letzten Fehlers.
- **Echtzeit-Verläufe** — sechs synchronisierte Diagramme plus ein freies Diagramm mit 4 beliebigen Variablen, CSV-Aufzeichnung.
- **Alle 446 Parameter** — dieselben Zeilennummern wie DunenConfiger, Suche, Vergleich mit einer Datei, xlsx-Export zum Reimport in DunenConfiger, CSV.
- **Sicheres Schreiben** — automatische vollständige Sicherung vor jedem Schreiben, Rücklesen, gefährliche Parameter gesperrt, Motor muss stehen, Speicherung im Festspeicher wie bei DunenConfiger.
- **Drehzahl-PI-Einstellung** — Messung an der Maschine, schrittweise manuelle Einstellung mit Hinweisen und automatische Einstellung.
- **Motortests** — vorgegebene Drehzahl oder vorgegebenes Drehmoment, automatisches Einlernen des Geberwinkels, Stromregelkreis; STOPP / Esc und automatischer Halt.
- **Werkstattwerkzeuge** — Support-Paket mit einem Klick (.zip), Kalibrierassistent für den Gashebel, Bandendetest mit Bericht und Produktionsprotokoll.
- **Für den Einsatz vor Ort** — 10 Sprachen, Adapter PEAK PCAN-USB, Kvaser, IXXAT, Vector und SLCAN, Anwendungsprofile und ein Simulationsmodus, um alles ohne Hardware auszuprobieren.

## Bildschirmfotos

<table>
<tr><td width="50%" align="center"><img src="docs/images/de/diagnostic.png" alt="Diagnose — was die Maschine begrenzt"><br><sub>Diagnose — was die Maschine begrenzt</sub></td><td width="50%" align="center"><img src="docs/images/de/realtime.png" alt="Echtzeit-Verläufe und PI-Einstellassistent"><br><sub>Echtzeit-Verläufe und PI-Einstellassistent</sub></td></tr>
<tr><td width="50%" align="center"><img src="docs/images/de/parameters.png" alt="Parameter — vergleichen, schreiben, exportieren"><br><sub>Parameter — vergleichen, schreiben, exportieren</sub></td><td width="50%" align="center"><img src="docs/images/de/licence.png" alt="Lizenzfenster"><br><sub>Lizenzfenster</sub></td></tr>
</table>

## Kostenloser Demomodus oder Vollversion

| Funktion | Demo (kostenlos) | Vollversion |
| --- | :---: | :---: |
| Verbinden, alle Parameter lesen, Übersicht, Verläufe | ✅ | ✅ |
| Diagnose, Fehlerspeicher, Bandendetest, Exporte, Support-Paket | ✅ | ✅ |
| Simulationsmodus mit allen Funktionen | ✅ | ✅ |
| Einstellungen in einen echten Controller schreiben | — | ✅ |
| Motortests, PI-Einstellung, Gashebel-Kalibrierung | — | ✅ |
| Automatische Updates | — | ✅ |

### Vollversion

**Dauerlizenz 50 €** · **Jahresabonnement 20 €** · **Quartalsabonnement 7 €**. Ein Schlüssel pro PC, in Sekunden über die Schaltfläche **Lizenz** (oben rechts) aktiviert. Funktioniert nach der Aktivierung ohne Internet. Der Onlinekauf startet in Kürze.

<sub>Abos: eine Internetverbindung alle 45 Tage genügt.</sub>

## Erste Schritte

1. Laden Sie **DunenScope_Setup** unter [Releases](https://github.com/simonlabrossedu71-tech/DunenScope/releases/latest) herunter und starten Sie es. Zeigt Windows „Der Computer wurde durch Windows geschützt“, klicken Sie auf *Weitere Informationen* → *Trotzdem ausführen*.
2. Wählen Sie Ihre Sprache. Das Installationsprogramm bietet den PEAK-Treiber an, falls er fehlt.
3. Schließen Sie den CAN-Adapter an den Controller an und schalten Sie die Zündung ein.
4. Adapter, 250 kbit/s, Knoten 1 wählen → **Verbinden**. Noch keine Hardware? Wählen Sie **Simulation**.
5. Vollversion: Schaltfläche **Lizenz** → Schlüssel einfügen → **Aktivieren**.

## Voraussetzungen

- Windows 10 oder 11, 64 Bit.
- Ein CAN-Adapter: PEAK PCAN-USB (empfohlen), Kvaser, IXXAT, Vector oder SLCAN (CANable…).
- Ein Dunen / ELYX-Controller mit dem DunenConfiger-Protokoll (Modbus über CAN, standardmäßig 250 kbit/s).

## Handbücher

Vollständige Handbücher (PDF), auch im Startmenü installiert:

- [English (PDF)](docs/manuals/DunenScope_Manual_EN.pdf) · [Français (PDF)](docs/manuals/DunenScope_Notice_FR.pdf) · [中文 (PDF)](docs/manuals/DunenScope_Manual_ZH.pdf)

## Updates und Sicherheit

- Jedes Installationsprogramm ist signiert; DunenScope prüft die Signatur vor der Installation eines Updates.
- Nutzern der Vollversion werden neue Versionen beim Start angeboten; Einstellungen, Profile und Sicherungen bleiben erhalten.
- DunenScope kontaktiert nur den Lizenzdienst und den Download-Server. Keine anderen Daten verlassen Ihren PC.

## Lizenz und Sicherheitshinweise

Mit der Installation von DunenScope akzeptieren Sie den [Endbenutzer-Lizenzvertrag](docs/licence/EULA_DE.txt). DunenScope kann die Einstellungen eines Controllers ändern und einen Motor drehen lassen: Arbeiten Sie nur an gesicherten Maschinen und mit qualifiziertem Personal. Dunen und ELYX sind Marken ihrer jeweiligen Inhaber.
