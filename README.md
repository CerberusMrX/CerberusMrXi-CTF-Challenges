# 👾 CerberusMrXi-CTF-Challenges: The Ultimate Security Playground! 🚀

![CTF Banner](https://img.shields.io/badge/Capture--The--Flag-Challenges-blueviolet)
![Difficulty](https://img.shields.io/badge/Difficulty-Beginner%20to%20Advanced-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 🔥 Welcome, Hacker! 🔥

This repository is a vibrant collection of original Capture The Flag (CTF) challenges created by **CerberusMrX**. Get ready to dive into diverse cyber realms, testing your skills from beginner basics to advanced techniques!

**🎯 Categories Included:** Web Exploitation, Cryptography, and more thrilling domains!

---

## 🌈 Challenge Categories at a Glance

| Category | 🌟 Focus Area | 🔗 Challenge Location | Status |
|----------|---------------|----------------------|---------|
| 🔑 **CRYPTOGRAPHY** | Cracking ciphers, decryption, hashing, and deep cryptanalysis | [`/Crypto/`](./Crypto/) | ✅ **Active** |
| 🌐 **WEB** | SQLi, XSS, SSRF, broken authentication, and exploiting modern web apps | [`/Web/`](./Web/) | ✅ **Active** |
| 🔎 **FORENSICS** | Analyzing data, images, and network traffic | `/Forensics/` | 🚧 **Coming Soon!** |
| ⚙️ **REVERSE ENGINEERING** | Decompiling and analyzing binaries | `/Reverse/` | 🚧 **Coming Soon!** |

---

## 💻 Quick Start: Launch Your Challenge!

Most challenges are designed to be run locally using **Docker** for a clean, isolated experience.

### ⬇️ Step 1: Get the Code

Use git to clone the entire challenge collection:

```bash
git clone https://github.com/CerberusMrX/CerberusMrXi-CTF-Challenges.git
cd CerberusMrXi-CTF-Challenges
```

### ⚙️ Step 2: Deploy (Docker Required)

Navigate into the specific challenge folder you want to solve:

```bash
# Example: Web Challenge
cd Web/SecureLogin

# Deploy the challenge
docker compose up -d
```

> **💡 Tip:** Always check the challenge's internal `README.md` for specific port numbers and setup instructions!

### 🛑 Step 3: Cleanup

When you are finished with a challenge, shut down the container to free up resources:

```bash
# Inside the challenge folder
docker compose down
```

---

## 🎯 Challenge Structure

Each challenge follows this organized structure:

```
ChallengeName/
├── README.md          # Challenge description, hints, and objectives
├── docker-compose.yml # Container configuration
├── src/               # Source code and application files
├── solution/          # Solution write-up (available after solving)
└── flag.txt           # The target flag (hidden in actual challenges)
```

---

## ✅ Rules of Engagement

- **The Flag Format:** All correct solutions will yield a flag in the format:  
  **`FLAG{Your_Secret_Here}`**

- **Difficulty Levels:** Challenges are clearly marked with emoji indicators:
  - 🟢 **Easy** - Perfect for beginners
  - 🟡 **Medium** - Intermediate skills required  
  - 🔴 **Hard** - Advanced techniques needed
  - ⚫ **Expert** - For the elite hackers

- **Feedback is Gold!** 💎 If you find a bug or have a suggestion, please open a shiny new [Issue](https://github.com/CerberusMrX/CerberusMrXi-CTF-Challenges/issues)!

- **Share Your Victory!** 🏆 We love write-ups! Feel free to open a [Pull Request](https://github.com/CerberusMrX/CerberusMrXi-CTF-Challenges/pulls) with a link to your solution or simply share it in an Issue.

---

## 🚀 Getting Help

- Check the individual challenge README for specific hints
- Review the `solution/` directory after solving (or if really stuck!)
- Open an Issue for technical problems with challenge setup

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Happy Hacking!

**Remember:** The journey of a thousand hacks begins with a single `FLAG{}`!  

*"In the world of cybersecurity, every challenge solved makes the digital world a little safer."* - CerberusMrX

---

<div align="center">

**⭐ Don't forget to star this repo if you enjoy the challenges!**

[![GitHub stars](https://img.shields.io/github/stars/CerberusMrX/CerberusMrXi-CTF-Challenges?style=social)](https://github.com/CerberusMrX/CerberusMrXi-CTF-Challenges/stargazers)

</div>
