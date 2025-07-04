# Energiemanagement Case Study - Investitionsanalyse für Kraftwerke

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DEIN-USERNAME/DEIN-REPOSITORY/HEAD)

> 🚀 **Direkt loslegen**: Klicken Sie auf den Binder-Button oben, um das Notebook sofort im Browser zu starten - ohne Installation!

## 📋 Überblick

Diese interaktive Case Study analysiert Investitionsentscheidungen für drei Kraftwerkstechnologien:
- **Windkraft (Onshore)** 🌪️
- **Biomassekraftwerk** 🌱  
- **Batteriespeicher** 🔋

## 🎯 Was Sie lernen werden

✅ **NPV-Berechnung unter Unsicherheit** - Bewertung von Investitionen mit Monte-Carlo-Simulation  
✅ **Portfolio-Optimierung** - Diversifikation zur Risikominimierung  
✅ **Szenarioanalyse** - Robuste Entscheidungen unter verschiedenen Marktbedingungen  
✅ **Interaktive Visualisierung** - Professionelle Plots und Dashboards

## 🚀 Schnellstart

### Option 1: Binder (Empfohlen - kein Setup nötig!)
1. Klicken Sie auf den Binder Button
2. Warten Sie 1-2 Minuten bis die Umgebung geladen ist
3. Öffnen Sie `CaseStudy_PP_Profitability_Solution.ipynb`
4. Führen Sie die Zellen nacheinander aus (Shift + Enter)

### Option 2: Lokale Installation
```bash
git clone https://github.com/DEIN-USERNAME/DEIN-REPOSITORY.git
cd DEIN-REPOSITORY
pip install -r requirements.txt
jupyter notebook CaseStudy_PP_Profitability_Solution.ipynb
```

## 📊 Notebook-Struktur

Das Notebook ist in logische Abschnitte unterteilt:

### 1. **Grundlagen** 🔧
- Modellsetup und Parameter
- NPV-Berechnungen für einzelne Technologien

### 2. **Interaktive Analyse** 🎮
- Parameter-Explorer mit Slidern
- Sensitivitätsanalyse (Tornado-Diagramm)
- Live-Visualisierungen

### 3. **Monte-Carlo Simulation** 🎲
- Berücksichtigung von Preisschwankungen
- Risikoanalyse mit statistischen Kennzahlen
- Value-at-Risk (VaR) Berechnung

### 4. **Portfolio-Optimierung** ⚖️
- Diversifikationseffekte
- Efficient Frontier
- Risiko-Rendite-Optimierung

### 5. **Szenarioanalyse** 🌍
- Vordefinierte Marktszenarien
- Robustheitstests
- Strategische Empfehlungen

## 🛠️ Technische Features

- **Interaktive Widgets**: Slider, Buttons, Dropdown-Menüs für Parameter
- **Professionelle Plots**: Plotly-basierte Visualisierungen
- **Automatische Reports**: Exportierbare Zusammenfassungen
- **Portfolio-Tools**: Optimierung mit scipy
- **Responsive Design**: Funktioniert auf verschiedenen Bildschirmgrößen

## 📈 Beispiel-Outputs

Das Notebook generiert verschiedene Visualisierungen:
- NPV-Vergleiche zwischen Technologien
- Risiko-Rendite-Diagramme
- Monte-Carlo Verteilungen
- Efficient Frontier Charts
- Szenario-Heatmaps

## 🎓 Für Studierende

Diese Case Study eignet sich für:
- **Energieökonomik** Kurse
- **Investitionsrechnung** Vorlesungen  
- **Risikomanagement** Seminare
- **Portfoliotheorie** Anwendungen

## 🔧 Technische Anforderungen

Das Notebook nutzt folgende Python-Bibliotheken:
- `numpy`, `pandas` für Datenanalyse
- `plotly` für interaktive Visualisierungen
- `ipywidgets` für interaktive Controls
- `scipy` für Optimierung
- `matplotlib` für zusätzliche Plots

## 📞 Support & Fragen

Bei Problemen oder Fragen:
1. Prüfen Sie zuerst die **häufigen Probleme** unten
2. Erstellen Sie ein Issue in diesem Repository
3. Kontaktieren Sie den Kursleiter

### Häufige Probleme

**❓ Widgets werden nicht angezeigt**
- Führen Sie alle Zellen der Reihe nach aus
- Starten Sie das Notebook neu (Kernel → Restart & Run All)

**❓ Binder lädt nicht**
- Aktualisieren Sie die Seite
- Versuchen Sie es zu einer anderen Tageszeit

**❓ Plots erscheinen nicht**
- Stellen Sie sicher, dass alle Pakete geladen sind
- Führen Sie die Setup-Zellen erneut aus

## 📄 Lizenz

Dieses Material steht unter [MIT Lizenz](LICENSE) und kann frei für Bildungszwecke verwendet werden.

---

*Entwickelt für praktisches Lernen im Energiemanagement* 🌟
