# Interpretive Orchestration - Starter Project

A ready-to-use research environment for qualitative analysis with AI partnership.

---

## 🤖 Let Your Editor's AI Set Everything Up

Most modern editors have AI assistants built-in:
- **VS Code** → Copilot Chat (click the chat icon in the sidebar, or `Cmd+Shift+I` / `Ctrl+Shift+I`)
- **Cursor** → AI Chat (already open in sidebar)
- **Windsurf** → Cascade (already open in sidebar)

**Copy this prompt into your AI chat panel:**

```
Help me set up "Interpretive Orchestration" - a Claude Code plugin for qualitative research.

CONTEXT:
- Plugin repo: https://github.com/linxule/interpretive-orchestration
- This helps with grounded theory, thematic analysis - it's a thinking partner, not automation

SETUP STEPS:
1. Open the terminal panel in this editor (help me find it if needed)
2. Check Claude Code: run "claude --version"
   - If missing, install it:
     - Mac/Linux: curl -fsSL https://claude.ai/install.sh | bash
     - Windows PowerShell: irm https://claude.ai/install.ps1 | iex
   - After install, restart the terminal panel
3. Start Claude Code: run "claude"
   - A browser may open for login - complete the authentication
4. INSIDE Claude Code (not regular terminal), run:
   /plugin install linxule/interpretive-orchestration
   /qual-check-setup
5. Start research: /qual-init

Walk me through step by step. If anything fails, help me troubleshoot.
Once setup is complete, give me a quick tour of this editor's features.
```

---

## 🛠️ Manual Setup

<details>
<summary>Click here if you don't have an AI assistant, or prefer step-by-step instructions</summary>

### What You Need

1. **Node.js** (v18 or higher) - Download from [nodejs.org](https://nodejs.org) (click the green LTS button)
2. **Claude Code** - Install after Node.js is working

### Step-by-Step

**1. Open the terminal in your editor**
- Menu: View → Terminal
- Or keyboard: `Cmd+J` (Mac) / `Ctrl+J` (Windows)

**2. Check Node.js**
```
node --version
```
- Need v18+. If missing, download from [nodejs.org](https://nodejs.org), install, restart your editor.

**3. Install Claude Code**
```
npm install -g @anthropic-ai/claude-code
```

**4. Start Claude Code**
```
claude
```
- A browser may open for login. Complete it.
- Your terminal prompt will change - you're now inside Claude Code.

**5. Install the plugin** (type these INTO Claude Code)
```
/plugin install linxule/interpretive-orchestration
/qual-check-setup
```

**6. Start your research**
```
/qual-init
```

</details>

---

## 📥 Viewing This on GitHub?

1. **Download:** Click green "Code" button → "Download ZIP"
2. **Unzip** the downloaded file
3. **Install an editor** if you don't have one: [Cursor](https://cursor.sh) (recommended - has AI built-in) or [VS Code](https://code.visualstudio.com)
4. **Open the folder** in your editor (File → Open Folder)
5. **Follow the setup above**

---

## What This Plugin Does

**Interpretive Orchestration** helps qualitative researchers think deeper - it's NOT automation.

| What It's NOT | What It IS |
|---------------|------------|
| Auto-coder that replaces your thinking | Thinking partner that asks good questions |
| Speed tool for faster analysis | Depth tool for richer interpretation |
| Black box that gives answers | Transparent dialogue that shows reasoning |

**The methodology:**
1. **Stage 1** - You code 10-15 documents manually (builds your intuition)
2. **Stage 2** - You + AI collaborate with visible reasoning
3. **Stage 3** - You synthesize theory (AI asks tradition's questions)

---

## Resources

| Resource | Description |
|----------|-------------|
| [Main Plugin](https://github.com/linxule/interpretive-orchestration) | Full documentation |
| [SETUP.md](SETUP.md) | Customize theme, fonts |
| [Troubleshooting](https://github.com/linxule/interpretive-orchestration/blob/main/TROUBLESHOOTING.md) | Common issues |

---

*Built for qualitative researchers by Xule Lin and Kevin Corley*
