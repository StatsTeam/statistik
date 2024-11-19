# Erste Schritte

**Windows**

- Python 3 oder höhere Version installieren
- Repository klonen:
  ```
  git clone  <git lab template url> <project_name>
  ```
- Gehe dann in das Projektverzeichnis:
  ```
  cd <project_name>
  ```
- Virtuele Entwicklungsumgebung erstellen:
  ```
  python -m venv .venv
  ```
- Virtuele Entwicklungsumgebung aktivieren:
  ```
  .venv\Scripts\activate  
  ```
- Abhängigkeiten installieren:
  ```
  pip install -r requirements.txt
  ```

**MacOS**

- Python 3 oder höhere Version installieren
- Repository klonen:
  ```
  git clone  <git lab template url> <project_name>
  ```
- Gehe dann in das Projektverzeichnis:
  ```
  cd <project_name>
  ```
- Virtuele Entwicklungsumgebung erstellen:
  ```
  python3 -m venv .venv
  ```
- Virtuele Entwicklungsumgebung aktivieren:
  ```
  source .venv/bin/activate 
  ```
- Abhängigkeiten installieren:
  ```
  pip install -r requirements.txt
  ```

# Statistik

 Dieses Repository enthält verschiedene Materialien und Ressourcen rund um die Themen Statistik,
 Datenanalyse und Wahrscheinlichkeitsrechnung. Hier findest du Code-Beispiele,
 Erklärungen und Dokumentationen zu gängigen statistischen Methoden und Konzepten.

## Inhaltsverzeichnis

### I. Mathematische Grundlagen

<ul>
    <li>
      <a href="lecture_notes/Was_ist_Mathematik.ipynb">1. Was ist Mathematik</a>
    </li>
    <li>
      <a href="lecture_notes/Die_Grundlagen_der_Mengenlehre.ipynb">2. Die Grundlagen der Mengenlehre</a>
    </li>
      <li>
        <a href="lecture_notes/Aufgaben_Die_Grundlagen_der_Mengenlehre.ipynb">3 Aufgaben zu: Die Grundlagen der Mengenlehre</a>
      </li>
    <li>
      <a href="lecture_notes/Die_Grundlagen_der_Arithmetik.ipynb">4. Die Grundlagen der Arithmetik</a>
    </li>
    <li>
      <a href="lecture_notes/Aufgaben_Die_Grundlagen_der_Arithmetik.ipynb">5. Aufgaben zu: Die Grundlagen der Arithmetik</a>
    </li>
    <li>
      <a href="lecture_notes/Die_Grundlagen_der_Algebra.ipynb">6. Die Grundlagen der Algebra</a>
    </li>
    <li>
      <a href="lecture_notes/Einführung_in_Funktionen.ipynb">8. Einführung in Funktionen</a>
    </li>
    <ul>
      <li>
        <a href="lecture_notes/Projekt_Funktionsploter_lineare_Funktionen.ipynb">8.1 Projekt: Funktionsploter für lineare Funktionen</a>
      </li>
    </ul>
</ul>


### II. Grundlagen der Statistik

<ul>
    <li>
        <a href="lecture_notes/Was_ist_Statistik.ipynb">1. Was ist Statistik</a>
    </li>
    <li>
        <a href="lecture_notes/Grundlegende_Begriffe_der_Statistik.ipynb">2. Grundlegende Begriffe der Statistik</a>
        <ul>
            <li>
                <a href="lecture_notes/Aufgaben_Grundlegende_Begriffe_der_Statistik.ipynb">2.1 Aufgaben zu: Grundlegende Begriffe der Statistik</a>
            </li>
        </ul>
    </li>
    <li>
        <a href="lecture_notes/Klassifikation_von_Merkmalen.ipynb">3. Klassifikation von Merkmalen</a>
        <ul>
            <li>
                <a href="lecture_notes/Aufgaben_Klassifikation_von_Merkmalen.ipynb">3.1 Aufgaben zu: Klassifikation von Merkmalen</a>
            </li>
        </ul>
    </li>
    <li>
        <a href="lecture_notes/Deskriptive_(beschreibende)_Statistik.ipynb">4. Deskriptive (beschreibende) Statistik</a>
        <ul>
            <li>
                <a href="lecture_notes/Darstellung_qualitativer_Daten.ipynb">4.1 Darstellung qualitativer Daten </a>
            </li>
            <li>
                <a href="lecture_notes/Aufgaben_Darstellung_qualitativer_Daten.ipynb">4.2 Aufgaben zu: Darstellung qualitativer Daten </a>
            </li>
            <li>
                <a href="lecture_notes/Darstelung_quantitativ_diskreter_Daten.ipynb">4.3 Darstelung quantitativ diskreter Daten</a>
            </li>
            <li>
                <a href="lecture_notes/Aufgaben_Darstelung_quantitativ_diskreter_Daten.ipynb">4.4 Aufgaben zu: Darstelung quantitativ diskreter Daten</a>
            </li>
              <li>
                <a href="lecture_notes/Darstellung_quantitativ_stetiger_Daten.ipynb">4.5 Darstelung quantitativ stetiger Daten</a>
            </li>
                <li>
                <a href="lecture_notes/Aufgaben_Darstellung_quantitativ_stetiger_Daten.ipynb">4.6 Aufgaben zu: Darstellung quantitativ stetiger Daten</a>
            </li>
            <li>
                <a href="lecture_notes/Empirische_Verteilungsfunktion.ipynb">4.7 Empirische Verteilungsfunktion</a>
            </li>
            <ul>
                <li>
                    <a href="lecture_notes/Empirische_Verteilungsfunktion_bei_quantitativ_diskreten_Merkmalen.ipynb">4.7.1 Empirische Verteilungsfunktion bei quantitativ diskreten Merkmalen</a>
                </li>
                <li>
                    <a href="lecture_notes/Aufgaben_Empirische_Verteilungsfunktion_diskret.ipynb">4.7.2 Aufgaben zu: Empirische Verteilungsfunktion bei quantitativ diskreten Merkmalen</a>
                </li>
                <li>
                    <a href="lecture_notes/Empirische_Verteilungsfunktion_bei_quantitativ_stetigen_Merkmalen.ipynb">4.7.3 Empirische Verteilungsfunktion bei quantitativ stetigen Merkmalen</a>
                </li>
                  <li>
                    <a href="lecture_notes/Aufgaben_zu_Empirische Verteilungsfunktion bei quantitativ stetigen Merkmalen.ipynb">4.7.4 Aufgaben zu: Empirische Verteilungsfunktion bei quantitativ stetigen Merkmalen</a>
                </li>
            </ul>
             <li>
                <a href="lecture_notes/Lagemaßzahlen.ipynb">4.8 Die Lagemaßzahlen</a>
              </li>
              <ul>
              <li>
                <a href="lecture_notes/Das_arithmetische_Mittel.ipynb">4.8.1 Das arithmetische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Das_arithmetische_Mittel.ipynb">4.8.2 Aufgaben zu: Das arithmetische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Das_gewichtete_arithmetische_Mittel.ipynb">4.8.3 Das gewichtete arithmetische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Das_gewichtete_arithmetische_Mittel.ipynb">4.8.4 Aufgaben zu: Das gewichtete arithmetische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Das_arithmetische_Mittel_klassierter_Daten.ipynb">4.8.5 Das arithmetische Mittel klassierter Daten</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Das_arithmetische_Mittel_klassierter_Daten.ipynb">4.8.6 Aufgaben zu: Das arithmetische Mittel klassierter Daten</a>
              </li>
              <li>
                <a href="lecture_notes/Der_Median.ipynb">4.8.7 Der Median</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Der_Median.ipynb">4.8.8 Aufgaben zu: Der Median</a>
              </li>
              <li>
                <a href="lecture_notes/Quantile_und_Boxplots.ipynb">4.8.9 Quantile und Boxplots</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Quantile_und_Boxplots.ipynb">4.8.10 Aufgaben zu: Quantile und Boxplots</a>
              </li>
              <li>
                <a href="lecture_notes/Der_Modalwert.ipynb">4.8.11 Der Modalwert (Modus)</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Der_Modalwert.ipynb">4.8.12 Aufgaben zu: Der Modalwert</a>
              </li>
              <li>
                <a href="lecture_notes/Zusammenfassung_Modalwert_Mittelwert_Median.ipynb">4.8.13 Zusammenfassung zum arithmetischen Mittel, Median und Modus</a>
              </li>
              <li>
                <a href="lecture_notes/Das_geometrische_Mittel.ipynb">4.8.14 Das geometrische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Das_geometrische_Mittel.ipynb">4.8.15 Aufgaben zu: Das geometrische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Das_harmonische_Mittel.ipynb">4.8.16 Das harmonische Mittel</a>
              </li>
              <li>
                <a href="lecture_notes/Aufgaben_zu_Das_harmonische_Mittel.ipynb">4.8.17 Aufgaben zu: Das harmonische Mittel</a>
              </li>
              </ul>
        </ul>
    </li>
</ul>

### III. Anhang

<ul>
  <li>
    <a href="lecture_notes/Glossar.ipynb">Glossar</a>
  </li>
</ul>

