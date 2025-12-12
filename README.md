# Interpretive Orchestration - Starter Project

A ready-to-use research environment for qualitative analysis with AI partnership.

---

## 🎯 Let Your AI Assistant Set Everything Up

**Copy this prompt into your AI assistant** (Copilot Chat, Cursor AI, Windsurf, etc.):

```
I need help setting up a qualitative research environment in this workspace.
Please act as a technical guide and walk me through each step one by one.

CONTEXT:
- I'm setting up "Interpretive Orchestration," a Claude Code plugin for qualitative research
- This plugin helps with grounded theory, thematic analysis, and interpretive inquiry
- It's NOT automation - it's a thinking partner that helps me reflect deeper
- Plugin repo: https://github.com/linxule/interpretive-orchestration

STEP 1 - CHECK NODE.JS:
- Run `node --version` in the integrated terminal (Cmd+J on Mac, Ctrl+J on Windows)
- I need Node.js v18 or higher
- If missing or outdated, give me the exact install command for my OS:
  - Mac: `brew install node@20` (or guide me to install Homebrew first if needed)
  - Windows: `winget install OpenJS.NodeJS.LTS` (or guide me to nodejs.org)
  - Linux: Use nvm or package manager

STEP 2 - CHECK CLAUDE CODE:
- Run `claude --version` in the terminal
- If missing, give me the install command:
  - Mac: `brew install anthropic/tap/claude-code`
  - Windows/Linux: `npm install -g @anthropic-ai/claude-code`

STEP 3 - LAUNCH CLAUDE CODE:
- First, make sure I have a file open/selected in the editor (like this README)
- Look for the Claude logo icon in the editor tab bar (top right area)
- Click it to launch Claude Code in the sidebar
- ALTERNATIVE: If no icon, run `claude` in the integrated terminal
- IMPORTANT: A browser window may open for authentication - I need to complete that login
- Wait for me to confirm Claude Code is running before proceeding

STEP 4 - INSTALL THE PLUGIN:
- Once Claude Code is running, I need to type THIS COMMAND INTO CLAUDE CODE (not the regular terminal):
  /plugin install linxule/interpretive-orchestration
- Then run: /qual-check-setup (to verify installation)

STEP 5 - START MY RESEARCH JOURNEY:
- Run: /qual-init
- This starts a "Socratic onboarding" dialogue that establishes my research philosophy

Please guide me step by step. Wait for my confirmation at each step.
If any step fails, stop and help me debug - don't assume it worked.
```

That's it! Your AI assistant will walk you through everything without leaving VS Code.

---

## 🛠️ Prefer Manual Setup?

<details>
<summary>Click to expand step-by-step instructions</summary>

### Step 1: Check Prerequisites

Open terminal (`Cmd+J` on Mac, `Ctrl+J` on Windows):

```bash
node --version    # Need v18+
claude --version  # Need Claude Code CLI
```

**If missing:**
| Tool | Mac | Windows |
|------|-----|---------|
| Node.js | `brew install node@20` | `winget install OpenJS.NodeJS.LTS` |
| Claude Code | `brew install anthropic/tap/claude-code` | `npm install -g @anthropic-ai/claude-code` |

### Step 2: Launch Claude Code

**Option A (GUI):** Open any file → Click Claude logo in tab bar (top right)

**Option B (Terminal):**
```bash
claude
```

A browser may open for authentication. Complete the login.

### Step 3: Install Plugin (inside Claude Code)

```
/plugin install linxule/interpretive-orchestration
/qual-check-setup
```

### Step 4: Initialize Project

```
/qual-init
```

</details>

---

## 📥 Viewing This on GitHub?

1. **Download:** Click green "Code" button → "Download ZIP" (or `git clone`)
2. **Open:** Double-click `starter.code-workspace` to open in VS Code/Cursor
3. **Extensions:** Click "Install All" when prompted for recommended extensions
4. **Setup:** Follow the AI-assisted setup above

---

## What's Pre-Configured

- Clean interface (no minimap, minimal distractions)
- Auto-save every 5 seconds
- Large fonts for readability
- Light theme for long sessions
- Recommended extensions (including Claude Code)

Customize in [SETUP.md](SETUP.md).

---

## What This Plugin Does

**Interpretive Orchestration** is NOT a coding automation tool. It's an **epistemic partnership system** for qualitative researchers.

| What It's NOT | What It IS |
|---------------|------------|
| Auto-coder that replaces your thinking | Thinking partner that deepens reflection |
| Speed tool for faster analysis | Depth tool for richer interpretation |
| Black-box AI that gives answers | Transparent dialogue that asks questions |

**The methodology:**
1. **Stage 1** - You code 10-15 documents manually (builds theoretical sensitivity)
2. **Stage 2** - Human-AI collaboration with visible reasoning
3. **Stage 3** - You synthesize theory (AI asks tradition's questions)

---

## Resources

| Resource | Description |
|----------|-------------|
| [Main Plugin](https://github.com/linxule/interpretive-orchestration) | Full documentation & philosophy |
| [SETUP.md](SETUP.md) | Customize theme, fonts, shortcuts |
| [Troubleshooting](https://github.com/linxule/interpretive-orchestration/blob/main/TROUBLESHOOTING.md) | Common issues |

---

*Built for qualitative researchers by Xule Lin and Kevin Corley*
