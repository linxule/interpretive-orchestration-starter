# Interpretive Orchestration - Starter Project

A ready-to-use research environment for qualitative analysis with AI partnership.

> This is a **companion starter project** for the [Interpretive Orchestration](https://github.com/linxule/interpretive-orchestration) Claude Code plugin.

---

## Step 1: Open This Project

Double-click `starter.code-workspace` to open in VS Code or Cursor.

You should see:
- A clean interface (no minimap, minimal distractions)
- A prompt to install recommended extensions - **click "Install All"**

---

## Step 2: Install Prerequisites

You need three things installed. **Don't worry if this seems technical - Claude can help you!**

### Check What You Have

Open the terminal in VS Code (`Cmd+J` on Mac, `Ctrl+J` on Windows) and run:

```bash
node --version    # Should show v18 or higher
claude --version  # Should show Claude Code version
```

### If Something Is Missing

**Option A: Ask Claude for help** (Recommended!)

Once you have Claude Code installed, just ask:
> "Help me install Node.js 18 on my Mac/Windows"

Claude will guide you step by step.

**Option B: Manual installation**

| Tool | Mac | Windows |
|------|-----|---------|
| **Node.js 18+** | `brew install node@20` | [Download installer](https://nodejs.org/) |
| **Claude Code** | `brew install anthropic/tap/claude-code` | [Download installer](https://claude.ai/code) |

---

## Step 3: Install the Plugin

Open the terminal (`Cmd+J` / `Ctrl+J`) and start Claude Code:

```bash
claude
```

Then install the Interpretive Orchestration plugin:

```
/plugin install linxule/interpretive-orchestration
```

**Verify it worked:**
```
/qual-check-setup
```

You should see green checkmarks for bundled MCPs and commands.

---

## Step 4: Initialize Your Research Project

Still in Claude Code, run:

```
/qual-init
```

This starts a Socratic dialogue that helps you:
- Articulate your research question
- Clarify your philosophical stance
- Choose your methodological tradition

**Take your time with this.** It's not paperwork - it's the foundation of your research.

---

## Step 5: Begin Your Research Journey

You're ready! Next steps:

1. **Add your data** - Put interview transcripts, field notes, etc. in this folder
2. **Start Stage 1** - Manually code 10-15 documents (this builds theoretical sensitivity AI can't replace)
3. **Write memos** - Use `/qual-memo` to capture insights
4. **Use @stage1-listener** - A thinking partner who asks good questions without suggesting codes

---

## Need Help?

### Ask Claude!

Claude Code can help you with almost anything:
- "Help me install Node.js"
- "How do I use the /qual-memo command?"
- "What should I do after coding my first 5 documents?"

### Resources

| Resource | Link |
|----------|------|
| **Main Plugin** | [interpretive-orchestration](https://github.com/linxule/interpretive-orchestration) |
| **Full Install Guide** | [INSTALL.md](https://github.com/linxule/interpretive-orchestration/blob/main/INSTALL.md) |
| **Troubleshooting** | [TROUBLESHOOTING.md](https://github.com/linxule/interpretive-orchestration/blob/main/TROUBLESHOOTING.md) |
| **Customization** | [SETUP.md](SETUP.md) (local) |

---

## What's Pre-Configured

This starter project gives you:

- **Clean interface** - No minimap, hidden developer files
- **Auto-save** - Your work saves every 5 seconds
- **Large fonts** - Readable for long sessions and screen sharing
- **Light theme** - Comfortable for extended reading
- **Recommended extensions** - Markdown tools, spell checker, etc.

See [SETUP.md](SETUP.md) to customize theme, font size, and more.

---

*Built for qualitative researchers by Xule Lin and Kevin Corley*
*Companion to [Interpretive Orchestration](https://github.com/linxule/interpretive-orchestration) v0.2.0+*
