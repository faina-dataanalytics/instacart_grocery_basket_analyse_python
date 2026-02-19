# Instacart Grocery Basket Analyse (Python)

## Überblick
Dieses Projekt umfasst eine explorative Datenanalyse des Instacart Online Grocery Shopping Datasets. Ziel ist es, das Kunden‑ und Bestellverhalten zu untersuchen und datenbasierte Empfehlungen für Marketing‑ und Vertriebsstrategien abzuleiten.
Die Analyse wurde vollständig in Python durchgeführt (pandas, NumPy, seaborn, matplotlib) und folgt den strukturellen und methodischen Vorgaben des CareerFoundry Data Analytics Programms.

## Zielsetzung
Instacart möchte besser verstehen:
- wann Kunden bestellen
- wie viel sie zu verschiedenen Tageszeiten ausgeben
- welche Produktkategorien besonders beliebt sind
- wie sich Kundentypen (Loyalität, Region, Demografie) unterscheiden
- welche Segmente sich für gezielte Marketingkampagnen eignen
Die Analyse liefert Antworten auf diese Fragen und unterstützt datenbasierte Entscheidungen.

## Key Questions
- Was sind die geschäftigsten Tage und Tageszeiten?
→ Optimierung von Werbezeiten.
- Zu welchen Zeiten geben Kunden am meisten Geld aus?
→ Hinweise auf geeignete Produktplatzierungen.
- Wie lassen sich Preisspannen sinnvoll gruppieren?
→ Unterstützung für Marketing‑ und Preisstrategien.
- Welche Produktabteilungen sind am beliebtesten?
→ Fokus für Promotions und Sortimentsgestaltung.
- Wie unterscheiden sich Kundentypen im Bestellverhalten?
→ Loyalität, Region, Alter, Einkommen, Familienstand.
- Welche Kundenprofile lassen sich ableiten?
→ Grundlage für Segmentierung und zielgerichtete Kampagnen.

## Methodik & Vorgehen (Python)
Die Analyse wurde in mehreren Schritten durchgeführt:
1. Datenimport & erste Prüfung
- Import der Instacart‑Datensätze (Orders, Products, Departments, Customers)
- Prüfung von Struktur, Datentypen und Vollständigkeit
2. Datenbereinigung
- Entfernen von Duplikaten
- Behandlung fehlender Werte
- Korrektur gemischter Datentypen
- Vereinheitlichung von Spaltennamen
3. Zusammenführung der Datensätze
- Merge über gemeinsame Schlüssel (z. B. product_id, order_id, customer_id)
- Prüfung des Merge‑Flags (100 % Übereinstimmung)
4. Ableitung neuer Variablen
- Loyalitätsflag
- Preisspannen (Low / Mid / High Range)
- Kundenprofile
- Tageszeitkategorien
5. Gruppierung & Aggregation
- Häufigkeiten
- Durchschnittswerte
- Segmentvergleiche
6. Visualisierung
Erstellt wurden u. a.:
- Histogramme
- Balkendiagramme
- Liniendiagramme
- Streudiagramme
Alle Visualisierungen wurden exportiert und im Ordner Plots gespeichert.

## Zentrale Ergebnisse
Bestellzeiten
- Höchste Bestellvolumina am Vormittag und frühen Abend
- Sehr geringe Aktivität nachts
Ausgaben nach Tageszeit
- Höhere Ausgaben am späten Nachmittag und Abend
- Niedrigere Ausgaben am frühen Morgen
Preisspannen
- Klare Unterschiede zwischen Low‑, Mid‑ und High‑Range Produkten
- High‑Range Produkte werden seltener, aber zu bestimmten Zeiten bevorzugt gekauft
Beliebteste Abteilungen
- Produce, Dairy & Eggs, Snacks und Beverages gehören zu den Top‑Kategorien
Kundensegmente
- Loyal customers bestellen häufiger und regelmäßiger
- Regionale Unterschiede im Ausgabeverhalten
- Jüngere Kunden bestellen häufiger, ältere geben mehr pro Bestellung aus
- Familien haben höhere Warenkörbe

## Empfehlungen für Stakeholder
- Werbezeiten optimieren
Anzeigen in Zeiten geringer Aktivität (Nacht, früher Morgen) schalten.
- Produktplatzierungen an Tageszeiten anpassen
Premium‑Produkte am Abend bewerben, Essentials am Vormittag.
- Preisspannen gezielt nutzen
- Low Range → Massenkampagnen
- High Range → zielgruppenspezifische Werbung
- Beliebte Abteilungen hervorheben
Häufig bestellte Kategorien regelmäßig promoten.
- Kundenprofile differenziert ansprechen
- Loyal customers → exklusive Angebote
- Regular customers → Anreize zur Steigerung der Frequenz
- New customers → einfache Empfehlungen & Rabatte
- Regionale Unterschiede berücksichtigen
Marketingkampagnen regional anpassen.

## Technologien
- Python
- pandas, NumPy
- seaborn, matplotlib
- Jupyter Notebook
- Anaconda

## Hinweis
Nicht alle Projektdateien sind in diesem Repository enthalten. Insbesondere die ursprünglichen Rohdatensätze und die meisten verarbeiteten Datendateien sind aus Platzgründen ausgeschlossen. Zu Demonstrationszwecken wird nur eine kleine Auswahl bereinigter Datensätze bereitgestellt.

Datenquelle
„The Instacart Online Grocery Shopping Dataset 2017“,
abgerufen von www.instacart.com/datasets/grocery-shopping-2017 (instacart.com in Bing).
