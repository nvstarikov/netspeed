<div align="center">

**🌐 Language:** English · [Русский](SECURITY_RU.md)

</div>

---

# Security Policy

## Supported versions

Security updates are issued only for the latest major branch.

| Version | Supported |
|---------|-----------|
| 1.0.x   | ✅        |

If you're on an older version — update via the launcher (auto-update on startup) or grab the latest build from [GitHub Releases](https://github.com/nvstarikov/netspeed/releases/latest).

---

## 🛡️ Reporting a vulnerability

**DO NOT open a public Issue for security vulnerabilities.** A public report can put users at risk before a patch is available.

### How to report correctly

**Option 1 — email (preferred):**

Send a message to **security@stargrd.ru** with the subject:

Include:
- Type of vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

**Option 2 — private channel via forum:**

Registered users can send a private message to the **СТАРГРАДД security team** on the [forum](https://stargrd.ru/forum/).

### What we promise

- Acknowledge receipt within **48 hours**
- Keep you informed about the fix status
- Credit you in the acknowledgements (unless you prefer to stay anonymous)

---

## 🚫 What is NOT a vulnerability

The following are expected behaviors, not security issues:

- **Missing digital signature on `.exe`** — planned for future releases
- **Antivirus warnings on unsigned builds** — normal for independent projects
- **Foreign nodes (Hetzner, Tele2) unreachable from Russian networks** — DPI/blocking, not a bug
- **User-level rights required** (no admin needed to run) — architectural decision
- **No support for Windows 7/8/Vista** — outdated platforms

---

## 🔐 What we do for security

NetSpeed is designed with a minimal attack surface:

- **No telemetry** — no data leaves your computer
- **No cloud sync** — all measurements are stored locally in `netspeed_history.md`
- **No auto-upload** — nothing is sent to STARGRAD servers automatically
- **No dependencies on external APIs for core functions** — measurements use public mirrors
- **Distribution only via the official launcher** and GitHub Releases — no third-party mirrors

---

## 📋 If you find something suspicious

If you notice suspicious behavior (unexpected network activity, file writes outside the executable directory, unusual outbound connections):

1. **Disconnect from the network** — isolate the machine
2. **Note what you observed** — screenshots, commands, timestamps
3. **Contact us immediately** — security@stargrd.ru
4. **Don't post publicly** until we confirm

We take every report seriously.

---

<div align="center">
  <sub>© 2026 STARGRAD · security@stargrd.ru · <a href="https://stargrd.ru/forum/">Форум</a></sub>
</div>
