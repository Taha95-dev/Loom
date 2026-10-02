## 💰 Commercial Tools

### Loom v2 – The $5 Shortcut Manager

**Stop typing long commands. Start using 3-letter shortcuts.**

#### Before Loom v2:
```powershell
# 27 characters just to check your version
Loom version

# Every. Single. Time.
```

#### After Loom v2:
```powershell
# One-time setup
tap add show-version "Loom version"
✅ Shortcut added: show-version → Loom version

# Now just type:
show-version
Loom v2.6.0
```

That's it. No external tools. No config files. Just shortcuts that work.

#### What else can you do?

| Without Loom v2 | With Loom v2 ($5) |
|---------------------|----------------------|
| `Loom sync -a` | `sync` |
| `docker-compose down -v && docker-compose up -d` | `dbreset` |
| `git add . && git commit -m "quick fix" && git push` | `push "quick fix"` |
| `ssh deploy-server && cd /var/www && npm run build` | `deploy` |

**Create ANY shortcut for ANY command – with arguments.**

#### Why $5?

- You'll save **minutes every day**
- That adds up to **hours every month**
- **One-time payment. Lifetime updates.**
- No subscriptions. No hidden fees.
- **No external dependencies.** No PowerShell modules to install. Just `tap add` and go.

👉 [Buy Loom V2](https://buy.polar.sh/polar_cl_zvnuIMcqUEG0ghrgaFfFV9PivHvnI9esOA40D25wvUK)

---

# 🚀 Loom ━━━━ "v2.7"

**One CLI to rule your dev workflow — git, scripts, env, cleanup, and more.**

[![Go Version](https://img.shields.io/badge/go-1.21%2B-blue)](https://go.dev/)
[![Clones](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=clones&query=clones&url=https%3A%2F%2Fapi.github.com%2Frepos%2FTaha95-dev%2FLoom%2Ftraffic%2FLoomFclones)](https://github.com/Taha95-dev/Loom)
[![Release](https://img.shields.io/github/v/release/Taha95-dev/Loom)](https://github.com/Taha95-dev/Loom/releases)

---

## ✨ Features

| Command | What It Does |
|---------|--------------|
| `Loom doctor` | Concurrent diagnostic suite for environment health |
| `Loom cleanup` | Aggressive recursive purge for build artifacts and logs |
| `Loom run` | Smart script runner (dev/build/test automation) |
| `Loom sync` | Secure Git orchestration with safety validation |
| `Loom info` | Instant project analytics (LOC, TODOs, Git health) |
| `Loom db` | Database migrations and lifecycle management |
| `Loom use` | Create new project from saved template |
| `Loom save` | Save current project as a template |

---

## 🚀 Quick Start

```bash
# Clone and build
git clone https://github.com/Taha95-dev/Loom.git
cd Loom
go build -o Loom

# Run anywhere
./Loom run dev
./Loom info
./Loom cleanup --docker
```

Or [download the latest release](https://github.com/Taha95-dev/Loom/releases).

---

## 📖 Examples

### Templates

```bash
# Save current project as a template
Loom save my-starter

# List saved templates
Loom list-templates

# Create new project from template
Loom use my-starter new-project
```

### Get instant project insights

```bash
$ Loom info
📊 Project Info
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📁 Files:         127
🧮 Lines:         8,452
🐛 TODOs:         3
🌿 Branch:        main
⏰ Last commit:   2 hours ago
```

### Git sync with safety

```bash
Loom sync -a          # auto-commit + push
Loom sync --tag v1.0  # commit + tag + push
```

---

## 🧠 Why Loom?

- **One tool** — no more switching between git, npm, docker, find, du, grep
- **Safety first** — won't let you commit your home folder or drop a production DB without confirmation
- **Fast** — written in Go, runs everywhere
- **Zero config** — works out of the box

---

## 🤝 Support

**Loom is made on a laptop with 4GB RAM, I5 3330U, HDD** — if you find it useful, consider giving it a ⭐ on GitHub.

---

## 📦 Installation

### From source

```bash
go install github.com/Taha95-dev/Loom@latest
```

### From releases

Download the binary for your OS from [Releases](https://github.com/Taha95-dev/Loom/releases).

---

## 📝 License

MIT — use it, learn from it, build something awesome.

---

## 🙌 Credits

Built by [Taha](https://github.com/Taha95-dev) — because building tools is better than waiting for them.

---

## Windows Defender False Positive

Windows Defender may flag `Loom.exe` as a virus. This is a **false positive** — a known issue with Go binaries.

**Your file is safe.** Here's how to fix it:

1. Open Windows Security → Virus & threat protection
2. Click "Manage settings" under Virus & threat protection settings
3. Scroll to "Exclusions" → "Add or remove exclusions"
4. Add the folder where you downloaded `Loom.exe` as an exclusion
5. Run the file again

[Verify the file checksum](https://github.com/Taha95-dev/Loom/releases/download/v2.6.0/checksums.txt) to confirm integrity.

---

**Loom v1 remains free and open source (MIT)**
