# Linea 2 - Catalogo Presentazione

## 📁 Struttura File

### Pagina Principale
- **index.html** - Pagina principale con 6 card che linkano alle sezioni

### Pagine Sezioni (vuote, pronte da riempire)
- **sezione-casa.html** - Collezione Casa 🏠
- **sezione-novita.html** - Novità 2024 ✨
- **sezione-design.html** - Design Esclusivo 🎨
- **sezione-ecofriendly.html** - Eco-Friendly 🌿
- **sezione-premium.html** - Premium Selection 💎
- **sezione-contatti.html** - Contattaci 📞

### Risorse
- **logo-linea2.png** - Logo aziendale originale
- **catalogo-linea2.html** - Versione precedente (backup)

---

## 🌍 Funzionalità Multilingua

Il sito rileva automaticamente la lingua del browser e traduce i contenuti in:
- **Italiano (IT)** - Lingua predefinita
- **Inglese (EN)**
- **Francese (FR)**
- **Spagnolo (ES)**
- **Tedesco (DE)**

### Come funziona
Il rilevamento avviene tramite JavaScript che legge `navigator.language` del browser.
Se imposti il tuo PC in inglese, vedrai automaticamente i testi in inglese!

---

## 🎨 Caratteristiche Design

### Sfondo
- Gradiente beige dinamico che si adatta allo scroll
- Nessun limite di lunghezza pagina

### Decorazioni
- 10 elementi floreali SVG distribuiti sulla pagina
- Animazioni leggere di "galleggiamento"
- Su mobile: solo la decorazione principale rimane visibile

### Logo
- Logo originale Linea 2 embedded in base64
- Nessun problema di percorsi o caricamento

### Responsive
- **Desktop**: Layout a 2 colonne
- **Tablet**: Layout adattivo
- **Mobile**: Layout a 1 colonna ottimizzato

---

## ✏️ Come Personalizzare le Sezioni

Ogni pagina sezione (es. `sezione-casa.html`) ha:

1. **Stesso sfondo e decorazioni** della home
2. **Pulsante "Torna al Catalogo"** per navigare indietro
3. **Area contenuto vuota** pronta per i tuoi prodotti

### Per aggiungere contenuti:
Apri la sezione che vuoi modificare e sostituisci il contenuto dentro `<div class="content-area">`:

```html
<div class="content-area">
    <!-- Qui inserisci il TUO contenuto -->
    <h2>Titolo Prodotto</h2>
    <p>Descrizione...</p>
    <img src="tua-immagine.jpg" alt="Prodotto">
    <!-- Tabelle, gallerie, ecc. -->
</div>
```

---

## 📱 Test Lingue

Per testare le diverse lingue:

1. **Chrome/Edge:**
   - Impostazioni → Lingue → Aggiungi lingua e spostala in cima
   - Ricarica la pagina

2. **Firefox:**
   - Impostazioni → Lingue → Scegli lingua preferita
   - Ricarica la pagina

3. **Safari:**
   - Preferenze di Sistema → Lingua e Zona → Lingua preferita
   - Ricarica la pagina

---

## 🚀 Pubblicazione

Per pubblicare il sito:
1. Carica tutti i file HTML sulla tua piattaforma di hosting
2. Il file `index.html` deve essere nella root
3. Tutte le sezioni devono essere nella stessa cartella
4. Non serve caricare `logo-linea2.png` (già embedded)

---

## 💡 Suggerimenti

- Mantieni lo stile coerente tra le sezioni
- Usa le stesse palette di colori (#8B7355, #A0826D)
- Per aggiungere immagini prodotti, usa lo stesso bordo-radius (15-20px)
- Ogni sezione può scrollare infinitamente senza problemi di sfondo

---

## 📞 Supporto

Per qualsiasi modifica o aggiunta di funzionalità, contatta lo sviluppatore.

Versione: 1.0
Data: Novembre 2024
