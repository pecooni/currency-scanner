# 🚀 KAKO DEPLOY-OVATI NA VERCEL

## ✅ ŠTA IMATE U OVOM FOLDERU:

```
vercel-deploy/
  ├── index.html       ← Glavna aplikacija (sve u jednom)
  ├── vercel.json      ← Vercel konfiguracija (opciono)
  ├── README.md        ← Opis projekta
  └── DEPLOY.md        ← Ovo uputstvo
```

---

## 🌐 METOD 1: Vercel Web (NAJLAKŠE!) ⭐

### Korak 1: Idite na Vercel
👉 https://vercel.com

### Korak 2: Sign up/Login
- Besplatno!
- Možete sa GitHub/Google/Email

### Korak 3: Deploy
1. Kliknite **"Add New..."** → **"Project"**
2. Kliknite **"Browse"** ili **Drag & Drop ceo folder**
3. **Deploy!**

⏰ 1-2 minuta

### Korak 4: Gotovo! 🎉
Dobijate URL:
```
https://currency-scanner-xyz.vercel.app
```

**Otvorite na telefonu i testirajte!** 📱

---

## 💻 METOD 2: Vercel CLI (za napredne)

### Korak 1: Instalirajte CLI
```bash
npm install -g vercel
```

### Korak 2: Login
```bash
vercel login
```

### Korak 3: Deploy
```bash
cd vercel-deploy
vercel
```

### Korak 4: Production
```bash
vercel --prod
```

---

## 📦 METOD 3: GitHub + Vercel (auto-deploy)

### Korak 1: Push na GitHub
```bash
cd vercel-deploy
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/VAŠ-USERNAME/currency-scanner.git
git push -u origin main
```

### Korak 2: Import u Vercel
1. Vercel → Import Git Repository
2. Izaberite repo
3. Deploy!

**Bonus:** Svaki push = automatski deploy! 🎊

---

## 🎯 PREPORUKA:

**Koristite METOD 1** - najbrži i najlakši način! 

Samo drag & drop folder na Vercel web! ⚡

---

## ⚠️ VAŽNO:

- ✅ Fajl MORA biti `index.html`
- ✅ Vercel automatski detektuje static site
- ✅ HTTPS je automatski (kamera će raditi!)
- ✅ CDN je automatski (brzo širom sveta!)

---

## 🔄 Kako Ažurirati?

### Web metod:
1. Vercel Dashboard → Vaš projekat
2. Settings → Git → Reconnect
3. Ili ponovo drag & drop

### CLI metod:
```bash
vercel --prod
```

---

## 🆘 Pomoć?

Ako nešto ne radi, pišite mi! 😊

---

**Sretno sa deploy-om! 🚀**
