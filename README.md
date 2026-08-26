# 📁 Smart Vault v3.6 — GT Documents

> Ψηφιακό θησαυροφυλάκιο για αποθήκευση εγγράφων και αριθμών  
> **ΑΔΤ • ΑΦΜ • ΑΜΚΑ • IBAN • Τηλέφωνα και άλλα**

🔗 **Live:** https://[your-username].github.io/smartvault

---

## ✨ Χαρακτηριστικά

| | |
|---|---|
| 🔐 | PIN κλείδωμα 6 ψηφίων (SHA-256) + Auto-lock 2 λεπτών |
| 📂 | Οργάνωση ανά πρόσωπο με κατηγορίες (Προσωπικά, Υγεία, Τράπεζα, Άλλο) |
| 🔍 | Αναζήτηση σε όλα τα πεδία |
| 💾 | Εξαγωγή & Εισαγωγή JSON / CSV |
| 📤 | Επιλογή πεδίων με checkbox και κοινοποίηση/αντιγραφή |
| 🎨 | 13 θέματα χρωμάτων (Light, Dark, OLED, Glass κ.ά.) |
| 📱 | PWA — Εγκατάσταση σαν εφαρμογή σε Android & iOS |
| ✈️ | Λειτουργεί **χωρίς internet** (offline-first) |
| 🔃 | Drag & drop αναδιάταξη πεδίων |

---

## 📱 Εγκατάσταση στο κινητό

### Android (Chrome)
1. Άνοιξε το link στο Chrome
2. Μενού **⋮** → **"Προσθήκη στην αρχική οθόνη"**
3. Πάτα **Προσθήκη** — εμφανίζεται σαν εφαρμογή!

### iOS (iPhone / iPad)
1. Άνοιξε το link στο **Safari** (όχι Chrome)
2. Κουμπί **□↑** (Share) → **"Προσθήκη στην οθόνη Αφετηρίας"**
3. Πάτα **Προσθήκη** — εμφανίζεται με το εικονίδιο!

---

## 🚀 GitHub Pages — Πώς να ανεβάσεις

1. Δημιούργησε νέο repository στο GitHub (π.χ. `smartvault`)
2. Ανέβασε **όλα** τα αρχεία αυτού του φακέλου
3. Settings → Pages → Source: **main branch / root**
4. Σε λίγα λεπτά: `https://[username].github.io/smartvault`

---

## 📁 Δομή αρχείων

```
smartvault/
├── index.html          ← Η εφαρμογή (self-contained)
├── manifest.json       ← PWA manifest
├── sw.js               ← Service Worker (offline)
├── favicon.ico         ← Browser tab icon
├── icons/
│   ├── icon-192x192.png
│   ├── icon-512x512.png
│   ├── apple-touch-icon.png
│   └── ... (όλα τα μεγέθη)
└── README.md
```

---

## 🔒 Ασφάλεια & Δεδομένα

- Τα δεδομένα αποθηκεύονται **αποκλειστικά τοπικά** στη συσκευή (`localStorage`)
- **Κανένα δεδομένο δεν αποστέλλεται** σε εξωτερικό server
- Το PIN κρυπτογραφείται με **SHA-256** πριν αποθηκευτεί
- Τα IBAN εμφανίζονται masked — αποκαλύπτονται μόνο με tap

---

© ΤΑΧΜΑΖΙΔΗΣ ΓΙΩΡΓΟΣ • 2026 • Smart Vault v3.6
