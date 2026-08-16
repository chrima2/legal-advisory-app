# ⚖️ LegalFlow AI – Pitch Deck & Concept Mockup

> **Human-in-the-Loop Legal Triage**: KI-gestützte Sachverhaltsaufnahme und Musterschreibengenerierung mit anwaltlicher Endprüfung und Haftungsabsicherung.

---

## 📌 Über das Projekt

**LegalFlow AI** schließt die Lücke zwischen unverbindlichen KI-Antworten und teuren, langwierigen Kanzleiprozessen. Mandanten schildern Alltagsprobleme (z. B. Mietrecht, Verkehrsunfälle) per Sprachnachricht, ein LLM strukturiert die Fakten und entwirft das passende Schreiben, und der zugelassene Anwalt prüft und signiert den Fall in **2–3 Minuten** über ein optimiertes Kanzlei-Dashboard.

* **Effektiver Kanzlei-Stundensatz:** 600 €+
* **Zeitersparnis:** Bis zu 90 % weniger administrativer Aufwand bei Erstberatungen
* **Rechtssicherheit:** 100 % konform mit BRAO, RDG (§ 3), RVG (§ 34) und DSGVO (§ 203 StGB)

---

## 🖥️ Live-Präsentation ansehen

Die interaktive HTML-Präsentation kann direkt im Browser geöffnet werden:

1. **Lokal:** Datei `index.html` (oder `LegalFlow_AI_Pitch_Deck.html`) herunterladen und per Doppelklick in Chrome/Safari/Edge öffnen.
2. **Online via GitHub Pages:** 
   * Gehe in diesem Repo auf **Settings** -> **Pages**.
   * Wähle als Source `Deploy from a branch` (Branch: `main` / `root`).
   * Die Präsentation ist anschließend unter `https://<dein-username>.github.io/<repo-name>/` live abrufbar.

**Steuerung:** 
* ⬅️ / ➡️ Pfeiltasten oder Klick auf **Weiter / Zurück**
* Responsive Ansicht für Desktop und Mobile (inkl. Foldables wie Galaxy Z Flip).

---

## 📊 Kerninhalte des Pitch Decks

* **Problem & Marktineffizienz:** Hürden für Mandanten vs. unrentable Bagatellfälle für Kanzleien.
* **Human-in-the-Loop Workflow:** Voice-Intake (Whisper) -> RAG-Triage (BGB/BGH) -> Anwalts-Cockpit -> PDF-Zustellung.
* **UI Mockups:**
  * *Mandanten-Interface:* Simpler Voice-Recorder mit Dokumenten-Upload.
  * *Kanzlei-Dashboard:* Split-Screen-Ansicht mit KI-Sachverhalt und editierbarem Schreibentwurf.
* **Tarifstruktur & Unit Economics:**
  * **Light (39 €):** Schnelle Ersteinschätzung (2–3 Min. Anwaltszeit)
  * **Medium (79 €):** Einschätzung + geprüftes Musterschreiben (5–7 Min. Anwaltszeit)
  * **Pro (179 €):** Offizielles Kanzleimandat mit Briefkopf (15 Min. Anwaltszeit)
* **Compliance & Haftung:** Auftragsverarbeitung mit Zero-Data-Retention, Pauschalhonorar nach RVG, Ausschluss gerichtlicher Folgevertretung in den AGB.
* **Rollenverteilung & Roadmap:** IT-Entwicklung & Growth vs. juristische Endfreigabe & Haftungsübernahme.

---

## 🛠️ Geplanter Tech-Stack

* **Frontend:** Next.js / Tailwind CSS / Web Audio API
* **Voice-to-Text:** OpenAI Whisper API / Deepgram
* **KI-Engine & RAG:** LLM mit Vektoranbindung an BGB/StVO und aktuelle BGH-Rechtsprechung
* **Backend & Auth:** Node.js / PostgreSQL / Supabase
* **Payments:** Stripe Checkout (Sofortabwicklung vor Mandatsprüfung)
