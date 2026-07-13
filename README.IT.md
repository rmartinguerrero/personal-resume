<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/🇪🇸-ES-ff4b4b?style=for-the-badge&labelColor=1a1a2e" alt="Español"></a>
  <a href="README.EN.md"><img src="https://img.shields.io/badge/🇬🇧-EN-4b8bff?style=for-the-badge&labelColor=1a1a2e" alt="English"></a>
  <a href="README.IT.md"><img src="https://img.shields.io/badge/🇮🇹-IT-2ecc71?style=for-the-badge&labelColor=1a1a2e" alt="Italiano"></a>
</p>

# 📄 Personal Resume — Demo

Curriculum web statico multilingua generato come **pagina demo** del progetto principale [CV para Todos](https://github.com/rmartinguerrero/CV-para-todos).

Questo repository contiene la versione esportata e statica di un CV costruito con il template **techy** del generatore. È progettato per essere mostrato come esempio vivo di ciò che qualsiasi utente può creare con il progetto principale.

---

🌐 **[Visualizza Demo Live](https://rmartinguerrero.github.io/personal-resume/)**

---

## ✨ Caratteristiche

* 🌍 **Multilingua Nativo:** Supporta Spagnolo, Inglese e Italiano con rilevamento automatico della lingua del browser.
* 🎨 **Template Techy:** Design tecnico scuro con tipografia JetBrains Mono e Inter.
* ⚡ **Prestazioni Ottimali:** Pagina statica HTML/CSS/JS senza dipendenze backend o framework pesanti.
* 📱 **Totalmente Responsivo:** Si adatta a qualsiasi dimensione dello schermo.
* 🔒 **Privacy:** Zero cookie, zero tracciatori, zero telemetria.

---

## 📁 Struttura del Progetto

```
├── index.html            # Pagina di ingresso (redirect automatico della lingua)
├── style.css             # Stili unificati con 3 temi (minimalist, techy, artistic)
├── profile.webp          # Foto del profilo
├── resume.es.json        # Dati del CV in spagnolo (standard JSON Resume)
├── resume.en.json        # Dati del CV in inglese
├── resume.it.json        # Dati del CV in italiano
├── es/index.html         # CV renderizzato in spagnolo
├── en/index.html         # CV renderizzato in inglese
├── it/index.html         # CV renderizzato in italiano
└── .nojekyll             # Previene l'elaborazione di Jekyll su GitHub Pages
```

---

## 🚀 Deployment

Il sito è distribuito su **GitHub Pages** e si aggiorna automaticamente ad ogni push al repository.

### Sviluppo Locale

Per visualizzare la demo in locale, basta aprire `index.html` in un browser o usare un server locale:

```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx serve .
```

---

## 🔗 Progetto Principale

Questo repository è una demo statica del progetto completo:

> 👉 **[CV para Todos](https://github.com/rmartinguerrero/CV-para-todos)** — Curriculum web multilingua open-source con editor visivo No-Code e deployment automatico.

---

## 🤖 Sviluppo Assistito da IA

Questo progetto è stato sviluppato con l'aiuto di strumenti di Intelligenza Artificiale come supporto durante la progettazione, la programmazione e la documentazione.

Tutte le decisioni finali appartengono a **Raúl Martín Guerrero**.

---

## 📜 Licenza

Questo progetto è distribuito sotto la **GNU General Public License v3.0 (GPL-3.0)**.

Copyright © 2026 Raúl Martín Guerrero

## 🧠 Autore

Progetto sviluppato da **Raúl Martín Guerrero**.
