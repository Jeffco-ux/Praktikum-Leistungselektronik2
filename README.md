# Praktikum-Leistungselektronik
akademisches Praktikum- Einphasenbrückenschaltung als Gleich- und Wechselrichter/ Elektrotechnik / Labor
Hochschule : Technische Hochschule Georg Agricola
Wissenschaftsbereich : Elektrotechnik (BET-Energietechnik)
Team : 2 Studenten

    Ziele:

Verstehen von Gleichrichter- und Wechselrichterbetrieb in einer Schaltung
Kennenlernen der ungesteuerten Einphasenbrückenschaltung
Untersuchung der gesteuerten Einphasenbrückenschaltung im Gleichrichterbetrieb
Realisierung des Wechselrichterbetriebs
Verständnis des 4-Quadranten-Betriebs

    Verwendete Werkzeuge und Geräte:

Transformator (Sekundärspannung UNetz = 45 V~)
Einphasen-Brückenschaltung B2 mit Dioden (ungesteuert)
Einphasen-Brückenschaltung B2 mit Thyristoren (gesteuert)
Ohmsche Last (RLast = 100 Ω)
Glättungsinduktivitäten (100 mH, 200 mH)
Regelbare Gleichspannungsquelle (für Wechselrichterbetrieb, max. 200V)
Oszilloskop mit Trennverstärker
Multimeter für Spannungs- und Strommessungen

    Theoretische Grundlagen:
    Dioden:

Stromfluss nur in Vorwärtsrichtung (Anode → Kathode)
Idealisiert: kein Spannungsabfall im leitenden Zustand
Sperren in Rückwärtsrichtung
Verhalten wie "elektronisches Rückschlagventil"

    Thyristoren:

Sperren in Rückwärtsrichtung wie Dioden
Sperren auch in Vorwärtsrichtung zunächst
Zünden durch Gate-Impuls bei positiver Anodenspannung
Nach Zündung: Verhalten wie Diode
Erlöschen nur bei Stromnulldurchgang
Kann nicht aktiv ausgeschaltet werden

    Ungesteuerte Einphasenbrückenschaltung:

    4 Dioden in Brückenanordnung
Automatischer Stromübergang bei Spannungsnulldurchgang
Gleichspannungsmittelwert: Udi = (2·Û)/π
Pulsierende Gleichspannung (zwischen 0 und Û)
Glättung durch Induktivität möglich

Gesteuerte Einphasenbrückenschaltung:
Gleichrichterbetrieb (0° ≤ α ≤ 90°):

    4 Thyristoren statt Dioden
Zündwinkel α verzögert gegenüber Nulldurchgang
Gleichspannungsmittelwert: Udα = Udi · cos(α)
Mit Glättungsinduktivität: negative Spannungsaugenblicke möglich
Steuerbarkeit der Ausgangsspannung

Wechselrichterbetrieb (90° < α ≤ ~150°):

Umkehr der Energierichtung
Negative Gleichspannungsmittelwerte
Erfordert aktive Energiequelle auf DC-Seite (Batterie, Gleichstrommaschine)
Wechselrichtertrittgrenze αW ≈ 150-160° (Sicherheitsabstand zu 180°)

    Aufgaben des Studenten:
    Vorbereitung (Kapitel 2):

Funktion und Aufbau der ungesteuerten und gesteuerten Einphasenbrückenschaltung
Verhalten bei ohmscher, induktiver und ohmsch/induktiver Last
Gleich- und Wechselrichterbetrieb verstehen
4-Quadranten-Betrieb mit Anwendungsbeispiel erläutern
Berechnung der Zeitdifferenz Δt [ms] für gegebene Zündwinkel α bei fNetz = 50 Hz

    Versuchsteil I: Ungesteuerter Einphasenbrückengleichrichter
    Versuchsaufbau:

B2-Schaltung mit 4 Dioden (R1-R4)
RLast = 100 Ω
Trafospannung sekundär = 45 V~

    Durchführung:
    Ohne Glättung:

Darstellung von Trafospannung (sek.), Gleichspannung und -strom mit Oszilloskop
Beachtung unterschiedlicher Potentiale
Protokollierung von Ablenkfaktoren und Übersetzungsverhältnissen
Messung des arithmetischen Mittelwerts Ud

    Mit Glättung:

Ergänzung durch Induktivität:

a) LD = 100 mH
b) LD = 200 mH


Darstellung der gleichen Größen
Messung der Mittelwerte

    Auswertung:

Beschriftung der Oszillogramme mit Maßstäben
Einzeichnung der Gleichspannungsmittelwerte
Bewertung der drei Fälle hinsichtlich Glättungsqualität

    Versuchsteil II: Gesteuerte Einphasenbrückenschaltung im Gleichrichterbetrieb
    Versuchsaufbau:

B2-Schaltung mit 4 Thyristoren (Q1-Q4)
RLast = 100 Ω
Optional: LD = 200 mH

    Durchführung:
    Ohne Glättung:

Variation von α
Beobachtung des Verhaltens
Messung von Ud für verschiedene α (Tabelle 1)
Oszillogramme für mindestens 3 verschiedene α
Zündwinkel: 0°, 20°, 40°, 60°, 80°, 100°, 120°, 140°, 160°, 180°

    Mit Glättung (LD = 200 mH):

Wiederholung von 4.2.1
Vergleich mit ungeglättetem Betrieb

    Auswertung:

Kennlinie Ud = f(α) (ohne Glättung)
Vergleichsdiagramm: Ud vs. α (mit und ohne Glättung)
Beschriftung der Oszillogramme
Einzeichnung der Gleichspannungsmittelwerte
Bewertung des Verhaltens mit/ohne Glättung
Grenze zwischen lückendem und nichtlückendem Betrieb markieren

    Versuchsteil III: Gesteuerte Einphasenbrückenschaltung im Wechselrichterbetrieb
    Versuchsaufbau:

Gesteuerte B2-Schaltung
RLast = 300 Ω
LD = 200 mH
Gleichspannungsquelle (max. 200V)

    Durchführung:
    Einsetzen des Stromflusses:

α = 150°, Gleichspannungsquelle = 200V
Vorsichtiges Verkleinern von α bis Stromfluss einsetzt
Beobachtung des Einsetzens

    Variation des Zündwinkels:

α variieren gemäß Tabelle 2
Messung von Ud und Id
Oszillogramme für mindestens 3 Einstellungen
Zündwinkel: 0°, 20°, 40°, 60°, 80°, 100°, 120°, 140°, 160°

    Auswertung:

Beschriftung der Oszillogramme
Einzeichnung der Gleichspannungsmittelwerte
Berechnung und grafische Darstellung der Leistung P(α)
Kennzeichnung der Bereiche: Gleichrichten vs. Wechselrichten
Erklärung des abrupten Stromnulldurchgangs (Punkt 5.2.1)

Erwartete Ergebnisse und Kompetenzen:
Messungen ungesteuerter Gleichrichter:

Theoretischer Mittelwert: Udi = (2·45V·√2)/π ≈ 40,5 V
Ohne Glättung: stark pulsierende Gleichspannung
Mit 100 mH: deutliche Glättung, aber noch sichtbare Welligkeit
Mit 200 mH: sehr gute Glättung, nahezu konstanter Strom

    Messungen gesteuerter Gleichrichter:
    Ohne Glättung:

Bei α = 0°: Ud,max ≈ 40,5 V
Bei α = 60°: Ud ≈ 20,3 V (cos(60°) = 0,5)
Bei α = 90°: Ud ≈ 0 V
Bei α > 90°: Spannungswerte nehmen stark ab, lückender Strom

    Mit Glättung:

Cosinus-Kennlinie: Udα = Udi · cos(α)
Negative Spannungsaugenblicke bei α > 0°
Kein Lücken bis höhere α
Bei α = 90°: Ud = 0 V (Grenze Gleich-/Wechselrichten)

    Wechselrichterbetrieb:

Bei α = 150°: Ud ≈ -35 V
Abruptes Einsetzen des Stromflusses beim Unterschreiten der Quellspannung
Energiefluss von DC-Quelle ins Wechselspannungsnetz
Leistung P = Ud · Id (negativ im Wechselrichterbetrieb)

    Praktische Erkenntnisse:
4-Quadranten-Betrieb:

Quadrant I: Gleichrichterbetrieb, positive Spannung, positiver Strom
Quadrant II: Wechselrichterbetrieb, negative Spannung, positiver Strom
Durch Thyristorbrücke: nur 2 Quadranten möglich
Für 4 Quadranten: zwei antiparallele Thyristorbrücken nötig

    Glättungswirkung:

Je größer L, desto besser die Glättung
Negative Spannungsaugenblicke bei ausreichender Glättung
Energiespeicherung in der Induktivität
Überbrückung bis zur nächsten Zündung

    Lückbetrieb:

Tritt bei zu kleiner Induktivität auf
Stromunterbrechung führt zu Spannungserhöhung
Beeinträchtigt die Regelbarkeit

    Anwendungen:

Windkraftanlagen (Generator → Gleichrichter → Wechselrichter → Netz)
Antriebstechnik (Drehzahlregelung von Gleichstrommotoren)
Batteriespeichersysteme (Laden/Entladen)
HVDC-Übertragung

    Diagramme und Kennlinien:

Charakteristische cos(α)-Kennlinie bei Glättung
Sprunghafte Kennlinie ohne Glättung (Lückbetrieb)
Leistungskennlinie über α: positiv (Gleichrichten), negativ (Wechselrichten)

    Sicherheitsaspekte:

Wechselrichtertrittgrenze bei ~150° (nicht bis 180°!)
Gefahr des "Kippens" bei zu großem α
Notwendigkeit einer Gleichspannungsquelle mit korrekter Polung
