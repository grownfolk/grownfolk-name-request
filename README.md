# Grownfolk Name Request

This repo powers the official .grownfolk name request form.

Built to collect verified wallet addresses, emails, and ZIP codes as part of the Grown Folk identity system. All requests are reviewed manually before any name is registered on-chain.

---

## ✅ What It Does

- Captures wallet address via **MetaMask** or **WalletConnect**
- Submits desired `.grownfolk` name, email, and ZIP
- Sends data to Formspree for manual approval
- Supports **mobile deep linking** and **desktop QR scan**
- Protects identity system by avoiding auto-claim

---

## 🛠 Tech

- HTML, CSS, JavaScript (vanilla)
- WalletConnect v1 + MetaMask deep link
- Polygon network RPC
- ScrollReveal animations
- GitHub Pages hosting

---

## 🌐 Deployed At

- [https://grownfolk.github.io/grownfolk-name-request](https://grownfolk.github.io/grownfolk-name-request)
- Final name registry stored and verified through GrownfolkResolver

---

## Notes

All `.grownfolk` name requests are approved manually.  
No on-chain writes happen directly from this page.  
Smart contract address: `0x68dec9ce94a9a462c092f3f4fb56977698bbf0ab` (Polygon)
