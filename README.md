# 👋 Hi, ich bin David

IT-Umschüler im zweiten Jahr der Ausbildung zum **Fachinformatiker Anwendungsentwicklung (FIAE)**  
📍 Hamburg · 🎓 IHK-Abschluss 2027 · 🐧 Linux Daily Driver

🧪 **Portfolio:** [Creative Tech Lab](https://itdavid04.github.io/Creative_Tech_Lab/), meine Projekte als Versuchsprotokolle, mit Lebenslauf und Kontakt

Ich bringe einen handwerklichen Hintergrund mit und habe den Sprung in die IT bewusst gewählt.  
Mein Fokus liegt auf Anwendungsentwicklung, Linux und Automatisierung. Zuletzt baue ich vor allem Web-Apps, die beim Lernen in der Umschulung helfen und auf dem Handy auch offline laufen.

Hier meine aktuellen Projekte, das neueste zuerst.

---

## 🗂️ Projekte

### 📚 [Wiki-APP](https://github.com/ITDavid04/Wiki-APP)
**JavaScript · PWA · three.js · GitHub Actions**

Das Lern-Wiki unseres Umschulungsteams als installierbare Web-App für Handy und Desktop. Auf der Startseite wächst beim Scrollen eine 3D-Ranke mit, jedes Blatt ist ein Artikel. Artikel lassen sich direkt in der App lesen, mit Formeln (KaTeX) und farbig markierter Prüfungsrelevanz nach Ampel. Pro Artikel merkt sich die App den Lernstand, ein Prüfungsmodus zeigt, was noch offen ist, und ein Leseausweis sammelt Stempel für Meilensteine. Nach dem ersten Besuch läuft alles offline. Fehler in einem Artikel lassen sich aus der App heraus als GitHub-Issue melden.

Ein GitHub-Actions-Workflow holt jede Nacht die neuen Artikel, baut die App, testet sie automatisch im Browser (Puppeteer) und veröffentlicht sie auf GitHub Pages. Die Versionsnummer zählt sich dabei selbst hoch.

▶️ **Live:** [itdavid04.github.io/Wiki-APP](https://itdavid04.github.io/Wiki-APP/)

---

### ⚔️ [Prüfungsprügler](https://github.com/ITDavid04/Souls_Pruefungspruegler)
**JavaScript · PWA · Python · Lernkasten**

Lernkarten für die AP1 und AP2 als Souls-like fürs Handy, mit 1134 Karten. Richtig bringt Seelen, falsch kostet Leben. Wer stirbt, lässt seine Seelen bei der Karte liegen, die ihn erledigt hat, und holt sie sich im nächsten Gang zurück. Die Reise folgt Dante: sechs Höllenkreise für die AP1, der Läuterungsberg für die AP2, je Lernfeld ein Boss und ganz oben der Prüfungsausschuss. Abseits des Weges warten die Katakomben der Kürzel mit 304 Abkürzungen, das Pixelparadies mit sieben Inseln, Rätsel zwischen den Karten und eine Werkstatt zum Ausprobieren. Das ganze Spiel gibt es in zwei Stilen: **Souls** (düster, gemalt) oder **Pixel** (alles in 8 Bit), umschaltbar auf dem Titel. Dahinter steckt ein Lernkasten mit fünf Fächern (Wiederholung nach 0, 1, 3, 7 und 14 Tagen). Ohne Framework gebaut, läuft offline, der Spielstand bleibt auf dem Gerät.

▶️ **Live:** [itdavid04.github.io/Souls_Pruefungspruegler](https://itdavid04.github.io/Souls_Pruefungspruegler/)

🎬 **Werbespot:** [im Creative Tech Lab](https://itdavid04.github.io/Creative_Tech_Lab/#pruefungspruegler)

> Stand: Prototyp mit der ganzen Reise von der AP1 bis zum Prüfungsausschuss.

---

### 🧠 [LLM-Claude-Skills-etc](https://github.com/ITDavid04/LLM-Claude-Skills-etc)
**Markdown · Python · Claude Skills · Gemini Gems**

Meine Sammlung eigener Claude Skills und Gemini Gems rund um Umschulung, Prüfung und Bewerbung, mit Kurzanleitungen zur Einrichtung. Darunter:

- **wiki-fiae**: erstellt und prüft Wiki-Artikel im IHK-Prüfungsformat mit ROT/GELB/GRÜN-Markierung
- **lockeres-lernmaterial** und **natuerliche-konversation**: Lerntexte und Chat-Antworten, die sich natürlich lesen, ohne an fachlicher Genauigkeit zu verlieren
- **token-sparmodus**: Arbeitsweise für Claude Code gegen hohe Tokenkosten, mit Python-Werkzeug und Installationsskript
- **it-bewerbungscoach-2026**, **praktikanten-search** und **firmen-briefing-fiae**: Bewerbung, Praktikumssuche und Vorbereitung aufs Vorstellungsgespräch
- **workshop-planer-2026**: Workshop-Pläne mit Zeitraster für Dozent:innen
- sechs Gemini Gems, zum Beispiel ein Python-Tutor und ein EduScrum-Transformer

---

### 🖥️ [Ubuntu 26.04 Autoinstall](https://github.com/ITDavid04/Autoinstall_Ubuntu26.04-Final)
**Shell · cloud-init · LUKS · TPM 2.0**

Vollautomatische Installation von Ubuntu 26.04 für Schulungsrechner. Die Autoinstall-Konfiguration wird mit Cubic in ein Standard-ISO eingebettet, danach läuft die Installation ohne einen einzigen Klick durch. Eine ThinkPad-Variante verschlüsselt die Platte mit LUKS und entsperrt sie über TPM 2.0. Nach dem ersten Login richtet ein Postinstall-Skript mit einem Befehl den Rest ein (Firewall, SSH, Firefox als .deb, VS Code, KVM, Flatpak) und erkennt selbst, ob Internet da ist. Ohne Netz läuft eine Offline-Variante.

> Weiterentwicklung meines ersten Autoinstall-Projekts für Ubuntu 24.04, mit klarer Aufteilung in Phasen und echtem Offline-Betrieb.

---

## 🛠️ Skills

| Bereich | Technologien |
|---|---|
| Entwicklung | Python, JavaScript, Node.js, SQLite, DDD, OOP, Unit-Tests |
| Web-Apps | PWA, Service Worker, three.js, HTML/CSS ohne Framework, Puppeteer |
| Linux / Sysadmin | Ubuntu, CachyOS, Shell-Scripting, systemd (Dienste, Timer), cloud-init, LUKS, KVM |
| Automatisierung | Autoinstall-YAML, Postinstall-Scripting, Bash, GitHub Actions |
| Dokumentation | Markdown, strukturierte Wissensvermittlung, IHK-Curriculum |
| KI / LLM | Claude Code, KI-Agenten, Claude Skills, Gemini Gems, Piper-TTS (lokale Sprachausgabe) |
| Tools | Git, GitHub Pages, Docker, VS Code, QEMU/Virt-Manager |
| Im Aufbau | Lokale KI mit Ollama und Whisper, Reverse Engineering |

---

## 📫 Kontakt

Ich freue mich über Praktikumsanfragen und Einstiegsmöglichkeiten im Bereich  
Applikationsentwicklung, Softwarearchitektur oder Linux-nahe Entwicklung.
