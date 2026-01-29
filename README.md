# 🛡️ Check Compliance Sicurezza Lavoro

## Questionario D.Lgs 81/08 con Lead Generation BREVO

### 📋 Contenuto Repository

- `index.html` - Landing page
- `questionario.html` - Questionario completo (7 step)
- `logo.png` - Logo Delivery Care Srl - SB
- `README.md` - Questo file

---

## 🚀 Deploy su GitHub Pages

### 1. Crea Repository

```bash
# Su GitHub.com
1. Vai su github.com
2. Click "New Repository"
3. Nome: "compliance-check" (o altro nome)
4. Public
5. Create repository
```

### 2. Upload Files

**Carica questi 3 file:**
- ✅ index.html
- ✅ questionario.html
- ✅ logo.png

**Via Web:**
1. Click "Add file" → "Upload files"
2. Drag & drop i 3 file
3. Commit changes

**Via Git:**
```bash
git clone https://github.com/TUO-USERNAME/compliance-check.git
cd compliance-check
# Copia i 3 file nella cartella
git add .
git commit -m "Add compliance check files"
git push
```

### 3. Attiva GitHub Pages

1. Vai su **Settings** del repository
2. Nella sidebar sinistra: **Pages**
3. Source: **Deploy from branch**
4. Branch: **main** (o master)
5. Folder: **/ (root)**
6. Click **Save**

### 4. Aspetta 2-3 minuti

GitHub compilerà il sito e ti darà un URL:
```
https://TUO-USERNAME.github.io/compliance-check/
```

---

## 🧪 Test BREVO

Una volta online, testa:

1. ✅ Apri la landing page
2. ✅ Click "Avvia Check"
3. ✅ Compila questionario (7 step)
4. ✅ Compila form BREVO
5. ✅ Click "Visualizza Report"
6. ✅ **Verifica che:**
   - Report appare
   - Email arriva su BREVO
   - Dati salvati correttamente

---

## 📊 Google Analytics

Il tracking è già configurato:
- **Property ID:** G-YKRX5MWW0Z
- **Eventi tracciati:**
  - `click_avvia_questionario` (landing page)
  - `questionario_iniziato` (step 1)
  - `lead_submitted` (form BREVO)

**Verifica su:**
https://analytics.google.com → Realtime

---

## 🔧 Configurazione BREVO

**Form Endpoint già configurato:**
```
https://d62e0a7b.sibforms.com/serve/MUIFALKwDBJk4OcnNWEtufWXX8uR64iideRXZJ_Ff80MkC1kEUV3Bhps_ZJK_6TyYamlE1pW1dLeccmnJC2DgZd2SyKOQ-f0QThBAcipcKnaEHHWvhFVQTRe-l9KikMlq0BTVZfX0_x_aWIUq3XjyfUxCtfvBbxrhKm5aEiAD-mNcUeSiKKeXIM32c7kvn0xWb-3A1Nq-GLPuGHa
```

**Campi inviati:**
- NOME_AZIENDA (required)
- NOME (optional)
- EMAIL (required)
- TELEFONO (required)
- DIPENDENTI (hidden)
- PUNTEGGIO (hidden)
- SETTORE (hidden)
- CRITICITA (hidden)

---

## 📞 Contatti

**Delivery Care Srl - SB**
- P.IVA: 11263630961
- Indirizzo: P.zza centro commerciale 44, 20090 Segrate (MI)
- Tel: +39 02 50047124
- Email: info@deliverycare.it

---

## ✅ Checklist Pre-Launch

- [ ] Logo caricato
- [ ] Index.html caricato
- [ ] Questionario.html caricato
- [ ] GitHub Pages attivato
- [ ] URL funzionante
- [ ] Test questionario completo
- [ ] Test form BREVO
- [ ] Verifica email BREVO
- [ ] Verifica Google Analytics
- [ ] Test mobile responsive

---

## 🎯 Flusso Utente

```
Landing Page (index.html)
    ↓
Click "Avvia Check"
    ↓
Questionario (7 step)
    ↓
Cerchio % adeguamento
    ↓
Form BREVO (lead capture)
    ↓
Report completo
    - Aree critiche 🟢🟡🔴
    - Sanzioni dettagliate
    - CTA Delivery Care
    - Pulsante Stampa
```

---

© 2025 Delivery Care Srl - SB
