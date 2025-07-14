# 🛸 nebuline-host

> 🐾 Local client to securely connect your VRChat bots to nebuline

![Node.js](https://img.shields.io/badge/Node.js-20.x-green?logo=node.js)
![Socket.io](https://img.shields.io/badge/socket.io-4.8.1-010101?logo=socket.io)
![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Issues](https://img.shields.io/github/issues/lunatine-dev/nebuline-host)
![Stars](https://img.shields.io/github/stars/lunatine-dev/nebuline-host?style=social)

## 🚀 Purpose

`nebuline-host` runs alongside your VRChat bots to register and forward authenticated commands securely through nebuline.

---

## ⚙️ Technical stack

-   **Client**: Node.js + Socket.io
-   **Authentication**: Token-based
-   **Integration**: Forwards commands to your VRChat bots

---

## 📦 Installation

```bash
git clone https://github.com/lunatine-dev/nebuline-host.git
cd nebuline-host
pnpm install
# Configure .env (bot tokens, nebuline URL, etc.)
pnpm run start
```

## 📦 Related projects

-   **[nebuline](https://github.com/lunatine-dev/nebuline)** – Backend socket relay & API gateway
-   **[nebuline-frontend](https://github.com/lunatine-dev/nebuline-frontend)** – Dashboard to control your bots

## ⚠️ Disclaimer

> 🐾 `nebuline-host` is a client built for **entertainment, educational, and personal use only**.  
> ❌ It must _not_ be used with malicious intent or to harm others.  
> 🛡️ Use responsibly and in compliance with VRChat’s Terms of Service.
