
# Multi Guide Frontend

Projekt MVP aplikacji "Multi Guide AI" z logowaniem przez Clerk i prostym odtwarzaczem audio dla słuchaczy.

## 🔧 Instalacja lokalna

```bash
git clone https://github.com/erdmanski/multi-guide-frontend.git
cd multi-guide-frontend
npm install
```

Utwórz plik `.env.local` w katalogu głównym z zawartością:

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_aGFwcHktaGVuLTYzLmNsZXJrLmFjY291bnRzLmRldiQ
```

## 🚀 Uruchomienie lokalne

```bash
npm run dev
```

Aplikacja będzie dostępna pod: [http://localhost:3000](http://localhost:3000)

## 📁 Struktura katalogów

```
multi-guide-frontend/
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   └── page.tsx
├── .env.local
├── package.json
├── next.config.js
├── tsconfig.json
└── README.md
```

## ✅ Funkcje
- Logowanie przez Clerk
- Przycisk "Słuchaj przewodnika"
- Odtwarzacz strumienia audio (Icecast)

## 🧠 Co dalej
- Podstrony z listą wydarzeń
- Panel administratora
- Integracja z backendem i RTMP/Narratorem

---

Repozytorium: [https://github.com/erdmanski/multi-guide-frontend](https://github.com/erdmanski/multi-guide-frontend)

---

Masz pytania? Skontaktuj się: [contact@erdmanski.pl](mailto:contact@erdmanski.pl)
