# 🚀 GUIA — Publicar "Bebé Saudável" na Google Play Store

## 📦 O QUE TENS NESTA PASTA

```
bebe-saudavel-pwa/
├── index.html       ← O aplicativo completo
├── manifest.json    ← Informações do app (nome, cores, ícones)
├── sw.js            ← Service Worker (funciona offline)
└── icons/           ← Ícones em todos os tamanhos necessários
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

---

## PASSO 1 — Hospedar o app online (GRÁTIS)

Precisas de colocar estes ficheiros num servidor. A forma mais fácil é o **Netlify**:

1. Vai a **https://netlify.com** e cria uma conta grátis
2. Clica em **"Add new site" → "Deploy manually"**
3. Arrasta a pasta `bebe-saudavel-pwa` inteira para o ecrã
4. O Netlify dá-te um link como: `https://bebe-saudavel.netlify.app`
5. ✅ O teu app já funciona online e pode ser instalado no telemóvel!

---

## PASSO 2 — Converter para APK com PWABuilder (GRÁTIS)

1. Vai a **https://pwabuilder.com**
2. Cola o link do teu site Netlify (ex: `https://bebe-saudavel.netlify.app`)
3. Clica **"Start"** — o PWABuilder vai analisar o teu app
4. Clica em **"Package for stores"**
5. Escolhe **"Android"** → clica **"Generate Package"**
6. Faz download do ficheiro **.aab** (Android App Bundle)

---

## PASSO 3 — Criar conta Google Play Developer

1. Vai a **https://play.google.com/console**
2. Cria uma conta Google (se não tiveres)
3. Paga a taxa única de registo: **$25 USD** (~1.600 MZN)
4. Preenche os dados do developer (nome, endereço, etc.)

---

## PASSO 4 — Publicar na Play Store

1. No Google Play Console, clica **"Criar aplicação"**
2. Preenche:
   - **Nome:** Bebé Saudável Moçambique
   - **Descrição curta:** Acompanha o crescimento do teu bebé
   - **Descrição longa:** (descreve as funcionalidades)
   - **Categoria:** Saúde e bem-estar
   - **Classificação:** Para todas as idades
3. Faz upload do ficheiro **.aab** que criaste no Passo 2
4. Adiciona capturas de ecrã do app (pelo menos 2)
5. Clica **"Publicar"**
6. ⏳ A Google revê em **1-3 dias** e notifica-te por email

---

## 📱 OPÇÃO MAIS RÁPIDA — Instalar sem Play Store

As tuas utilizadoras podem instalar o app AGORA, sem precisar da Play Store:

1. Abre o link Netlify no **Chrome** do telemóvel
2. Aparece uma mensagem: **"Adicionar ao ecrã inicial"**
3. Clica e o app instala como se fosse da Play Store!

---

## ❓ PRECISAS DE AJUDA?

Se tiveres dificuldades em algum passo, pede ajuda ao Claude e ele guia-te!

---

*Criado com ❤️ para as mães de Moçambique*
