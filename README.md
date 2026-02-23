# 🖥️ Dedicated-Servers

A collection of practical guides for setting up dedicated game servers on low-cost or repurposed hardware, using free and open-source tools.

These guides focus on real-world scenarios: old laptops, limited budgets, remote access, and getting friends connected without spending money on hosting services.

---

## 📚 Guides

| Game | OS | Stack | File |
|------|----|-------|------|
| Hytale | Debian 12 | ZeroTier · Adoptium Temurin 21 · RustDesk · SSH · Screen | [Ver guía](https://FredoCubap.github.io/Dedicated-Servers/hytale_server-debian.html) |

> 📝 Guides are written in Spanish. 
> Browser auto-translate works great for non-Spanish speakers.
> More guides coming soon.

---

## 🧰 Common Stack

Most guides in this repo are built around the same free tools:

- **[Debian 12 Bookworm](https://www.debian.org/)** — lightweight, stable Linux base
- **[ZeroTier](https://www.zerotier.com/)** — virtual LAN network, replaces Hamachi/Radmin VPN, works on Linux/Windows/Mac/Android
- **[Adoptium Temurin](https://adoptium.net/)** — open-source Java runtime for game servers
- **[RustDesk](https://rustdesk.com/)** — open-source remote desktop (TeamViewer alternative)
- **[Screen](https://www.gnu.org/software/screen/)** — keeps the server running after closing SSH sessions
- **[SSH](https://www.openssh.com/)** — secure remote terminal access

---

## 🎯 Who is this for?

Anyone who wants to:
- Host a game server on spare or old hardware
- Let friends connect remotely without a paid hosting service
- Administer a server remotely without being physically present
- Keep setup costs at zero

---

## 📄 Guide Format

Each guide is a standalone `.html` file — no dependencies, no build step. Just open it in any browser. Guides include:

- Full architecture diagram
- Step-by-step installation commands with copy buttons
- Explanations aimed at people unfamiliar with Linux server administration
- `.bat` → `.sh` script migration when applicable

---

## 🤝 Contributing

Have a guide for another game or setup? PRs are welcome. Try to follow the existing format so the collection stays consistent.

---

## 📝 License

MIT — free to use, share, and adapt.
