# Interpretive Orchestration - Starter Project

A ready-to-use research environment for qualitative analysis with AI partnership.

---

## 🎯 You're In VS Code? Let's Get You Set Up!

**Copy this prompt into your AI assistant** (Copilot, Cursor, Claude, etc.):

```
Help me set up the Interpretive Orchestration plugin for qualitative research.

Prerequisites:
- Node.js 18+: https://nodejs.org/
- Claude Code: https://claude.ai/code (or `brew install anthropic/tap/claude-code` on Mac)

Please:
1. Check if Node.js 18+ is installed (`node --version`), help me install it if not
2. Check if Claude Code is installed (`claude --version`), help me install it if not
3. Once both are ready, help me run: claude
4. Then help me run: /plugin install linxule/interpretive-orchestration
5. Finally, help me run: /qual-init to initialize my research project

Plugin repo: https://github.com/linxule/interpretive-orchestration

Guide me step by step and wait for my confirmation at each step.
```

That's it! Your AI assistant will walk you through everything.

---

## 🛠️ Prefer Manual Setup?

<details>
<summary>Click to expand step-by-step instructions</summary>

### Step 1: Check Prerequisites

Open terminal (`Cmd+J` on Mac, `Ctrl+J` on Windows):

```bash
node --version    # Need v18+
claude --version  # Need Claude Code
```

**If missing:**
| Tool | Mac | Windows |
|------|-----|---------|
| Node.js | `brew install node@20` | [nodejs.org](https://nodejs.org/) |
| Claude Code | `brew install anthropic/tap/claude-code` | [claude.ai/code](https://claude.ai/code) |

### Step 2: Install Plugin

```bash
claude
/plugin install linxule/interpretive-orchestration
/qual-check-setup
```

### Step 3: Initialize Project

```
/qual-init
```

</details>

---

## 📥 Don't Have This Project Yet?

If you're viewing this on GitHub:

1. **Download:** Click "Code" → "Download ZIP" (or `git clone`)
2. **Open:** Double-click `starter.code-workspace`
3. **Install extensions:** Click "Install All" when prompted
4. **Follow the setup above**

---

## What's Pre-Configured

- Clean interface (no minimap, minimal distractions)
- Auto-save every 5 seconds
- Large fonts for readability
- Light theme for long sessions
- Recommended extensions

Customize in [SETUP.md](SETUP.md).

---

## Resources

| Resource | Description |
|----------|-------------|
| [Main Plugin](https://github.com/linxule/interpretive-orchestration) | Full documentation |
| [SETUP.md](SETUP.md) | Customize theme, fonts |
| [Troubleshooting](https://github.com/linxule/interpretive-orchestration/blob/main/TROUBLESHOOTING.md) | Common issues |

---

*Built for qualitative researchers by Xule Lin and Kevin Corley*
