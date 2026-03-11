# 🔐 Cryptography Visualizer

An interactive web-based tool for visualizing **RSA**, **Elliptic Curve Cryptography (ECC)**, and **Diffie-Hellman Key Exchange (DHKE)**.

## 🌐 Live Demo

👉 **[Launch Visualizer](https://Varun-SV.github.io/crypto-visualizer/)**

> Replace `YOUR_USERNAME` with your GitHub username after deployment.

## 📸 Screenshots

### RSA Encryption & Decryption
- Key generation with prime validation
- Step-by-step encryption/decryption
- Visual communication flow between Alice and Bob

### Elliptic Curve Cryptography
- Curve visualization over finite fields
- Scalar multiplication with double-and-add
- ECDH key exchange simulation

### Diffie-Hellman Key Exchange
- Cyclic group visualization
- Step-by-step or instant exchange mode
- Eve's eavesdropper perspective

## ✨ Features

- 🎨 **Interactive visualizations** with HTML5 Canvas
- 📊 **Step-by-step computation logs** showing all math
- 🧮 **Real modular arithmetic** (modular exponentiation, extended GCD, Tonelli-Shanks)
- 👩‍💻 **Alice & Bob** communication simulation
- 🕵️ **Eve's perspective** showing why attacks are hard
- 📱 **Responsive design** works on desktop and mobile
- 🌌 **Beautiful UI** with starfield background
- 🔢 **Tooltips** explaining cryptographic concepts

## 🛠️ Technologies

- Pure HTML, CSS, and JavaScript
- No frameworks or dependencies
- BigInt for large number arithmetic
- HTML5 Canvas for visualizations

## 📚 Concepts Covered

| Algorithm | Key Concepts |
|-----------|-------------|
| **RSA** | Prime factorization, Euler's totient, modular inverse, public/private keys |
| **ECC** | Elliptic curves over finite fields, point addition, scalar multiplication, ECDLP |
| **DHKE** | Discrete logarithm problem, cyclic groups, modular exponentiation |

## 🚀 Local Development

Simply open `index.html` in any modern web browser:

```bash
git clone https://github.com/YOUR_USERNAME/crypto-visualizer.git
cd crypto-visualizer
open index.html
