# grownfolk-name-request (Mobile Optimized)

This is the advanced Web3-native name request form for `.grownfolk` digital identity registration.

## Features
- **MetaMask (Recommended):** Desktop-first with one-click wallet connection
- **WalletConnect with Deep Linking:** Automatically detects mobile users and opens wallet app (Trust, Coinbase, MetaMask Mobile, etc.)
- **Secure form submission** for:
  - .grownfolk name
  - email
  - ZIP code
- **Wallet required** — no manual address entry allowed

## Live Demo (example)
Deploy this on GitHub Pages or Fleek:
```
https://grownfolk.github.io/grownfolk-name-request/
```

## How It Works
1. User clicks **Connect with MetaMask** (desktop) or **WalletConnect** (mobile)
2. Wallet address is auto-filled into a hidden form field
3. User completes name + email + ZIP
4. Submission goes to Grown Folk admin via [Formspree](https://formspree.io)

## Smart Design
- **On Desktop:** WalletConnect shows a QR code for scanning
- **On Mobile:** QR is disabled — launches wallet apps directly
- **Fallback Link:** “Create a Wallet” via MetaMask download if needed

---

Built for the future of verified identity in the Grown Folk Network.
