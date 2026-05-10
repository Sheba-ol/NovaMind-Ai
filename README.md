# ✦ NovaMind AI — Your Personal Claude-Powered Chatbot

A fully functional AI chat app powered by **Anthropic's Claude API** (claude-sonnet-4-20250514).  
Deploy it free in under 5 minutes — no subscription, no backend needed.

---

## ✨ Features

- 🤖 Real Claude AI responses (claude-sonnet-4-20250514)
- 💬 Conversation history (stored in browser localStorage)
- 📝 Markdown rendering (code blocks, bold, lists, headings)
- 🎨 Dark-themed, polished UI
- 📱 Mobile-responsive
- 🔑 Uses YOUR Anthropic API key (free tier available)
- 🚀 One-click deploy to Vercel

---

## 🚀 Deploy in 3 Steps

### Step 1 — Get a FREE Anthropic API Key
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up (free, no credit card required for free tier)
3. Navigate to **API Keys** → **Create Key**
4. Copy your key (starts with `sk-ant-...`)

### Step 2 — Upload to GitHub
1. Create a new repository on [github.com](https://github.com)
2. Upload `index.html` and `vercel.json` to the repo
3. Commit the files

### Step 3 — Deploy to Vercel (FREE)
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New Project** → select your repo
3. Click **Deploy** — done!

Your app is now live at `https://your-project.vercel.app` 🎉

---

## 🔑 How to Use

1. Open your deployed app
2. Paste your Anthropic API key in the top-right field
3. Click **Save**
4. Start chatting!

> Your API key is stored **only in your browser** (localStorage) — never sent to any server other than Anthropic directly.

---

## 💡 Anthropic Free Tier

The free tier gives you enough credits to test and use the app extensively.  
Pricing details: [anthropic.com/pricing](https://www.anthropic.com/pricing)

---

## 🛠 Customization

Edit `index.html` to:
- Change the AI name/personality (search for "NovaMind" and "system" prompt)
- Adjust the model (change `claude-sonnet-4-20250514`)
- Modify colors via CSS variables at the top of the `<style>` block
- Add new suggestion buttons in the empty state section

---

## 📁 Files

```
├── index.html      ← The entire app (HTML + CSS + JS)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```

---

## ⚠️ Notes

- This is a **client-side only** app — your API key stays in your browser
- For production use with many users, consider building a backend proxy to protect your key
- The app uses `anthropic-dangerous-direct-browser-access: true` header which Anthropic supports for personal projects

---

Made with ❤️ using the Anthropic Claude API
