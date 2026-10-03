# 🤖 TwinTik / TechnoCIT Interactive AI Avatar

A landing page that embeds a **HeyGen interactive streaming avatar** — an AI assistant that visitors can talk to for questions and support. Built for TwinTik at TechnoCIT.

---

## ✨ Features

- Welcome screen introducing the AI avatar
- **"Start Chat with AI Avatar"** button that opens the HeyGen streaming avatar in an overlay
- Close button to dismiss the avatar
- Avatar is connected to a HeyGen knowledge base, so answers are specific to the business

## 🛠️ Tech stack

HTML · CSS · JavaScript · [HeyGen Interactive Avatar](https://www.heygen.com/) (streaming embed)

## 🚀 How to use

```bash
git clone https://github.com/nawfil03/twintik_bot.git
cd twintik_bot
```

Open `avatar.html` in a browser, or serve it locally:

```bash
npx serve .
```

Click **Start Chat with AI Avatar** and allow microphone access when asked.

### Use your own avatar

1. In HeyGen, create an Interactive Avatar and copy its **embed / share code**.
2. In `avatar.html`, replace the `share=...` value in the `url` of the HeyGen script with your own.
3. Embed the page (or the script) into your website.

---

👤 Built by **Nawfil Faraaz** · [GitHub](https://github.com/nawfil03)
