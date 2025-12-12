# Setup & Customization Guide

---

## What is "Terminal"?

The **terminal** (also called "command line" or "console") is a text-based way to give instructions to your computer. Instead of clicking buttons, you type commands.

**Don't worry** - you only need to type a few simple commands, and your AI assistant can help you with each one.

### How to Open Terminal in Your Editor

| Editor | How to Open Terminal |
|--------|---------------------|
| **VS Code** | Press `Cmd+J` (Mac) or `Ctrl+J` (Windows/Linux) |
| **Cursor** | Press `Cmd+J` (Mac) or `Ctrl+J` (Windows/Linux) |
| **Windsurf** | Press `Cmd+J` (Mac) or `Ctrl+J` (Windows/Linux) |
| **Any editor** | Look for "Terminal" in the top menu → "New Terminal" |

**What you'll see:** A panel appears at the bottom of your screen with a blinking cursor. This is where you type commands.

**Can't find it?** Ask your AI assistant: *"Help me open the integrated terminal in this editor"*

### How to Open Terminal Outside Your Editor

If you need to use terminal before opening your editor:

| System | How to Open |
|--------|-------------|
| **Mac** | Press `Cmd+Space`, type "Terminal", press Enter |
| **Windows** | Press `Win` key, type "PowerShell" or "Terminal", press Enter |
| **Linux** | Press `Ctrl+Alt+T` or find "Terminal" in applications |

---

## Prerequisites Checklist

Before starting:
- [ ] VS Code, Cursor, or similar editor installed
- [ ] Node.js 18+ installed
- [ ] Claude Code installed

### How to Check If You Have Node.js

1. Open terminal (see above)
2. Type: `node --version`
3. Press Enter

**If you see** `v18.x.x` or `v20.x.x` or higher → You're good!

**If you see** "command not found" or a lower version → You need to install Node.js

### How to Install Node.js

| System | Command |
|--------|---------|
| **Mac** (with Homebrew) | `brew install node@20` |
| **Mac** (without Homebrew) | Download from [nodejs.org](https://nodejs.org/) |
| **Windows** | `winget install OpenJS.NodeJS.LTS` or download from [nodejs.org](https://nodejs.org/) |
| **Linux** | Use your package manager or [nodejs.org](https://nodejs.org/) |

### How to Check If You Have Claude Code

1. Open terminal
2. Type: `claude --version`
3. Press Enter

**If you see** a version number → You're good!

**If you see** "command not found" → You need to install Claude Code

### How to Install Claude Code

| System | Command |
|--------|---------|
| **Mac** | `brew install anthropic/tap/claude-code` |
| **Windows** | `npm install -g @anthropic-ai/claude-code` |
| **Linux** | `npm install -g @anthropic-ai/claude-code` |

---

## Installing the Plugin

Once you have Node.js and Claude Code:

1. Open terminal in your editor (`Cmd+J` / `Ctrl+J`)
2. Type `claude` and press Enter
3. A browser may open for login - complete the authentication
4. Once Claude Code is running, type:
   ```
   /plugin install linxule/interpretive-orchestration
   ```
5. Verify with: `/qual-check-setup`
6. Start your project: `/qual-init`

**Plugin repo:** [github.com/linxule/interpretive-orchestration](https://github.com/linxule/interpretive-orchestration)

---

## Customizing Your Environment

### Change Theme

1. Press `Cmd+K Cmd+T` (Mac) or `Ctrl+K Ctrl+T` (Windows)
2. Use arrow keys to preview themes
3. Press Enter to select

**Popular choices:**
- Light: "Default Light Modern", "Quiet Light"
- Dark: "Default Dark Modern", "One Dark Pro"

### Change Font Size

1. Press `Cmd+,` (Mac) or `Ctrl+,` (Windows) to open Settings
2. Search "font size"
3. Adjust "Editor: Font Size" to your preference (default is 15)

### Reset to Defaults

If you want to start over:
1. Delete the `.vscode` folder in this project
2. Close and reopen the workspace file (`starter.code-workspace`)

---

## Keyboard Shortcuts

| Action | Mac | Windows/Linux |
|--------|-----|---------------|
| Open/close terminal | `Cmd+J` | `Ctrl+J` |
| Preview markdown | `Cmd+Shift+V` | `Ctrl+Shift+V` |
| Side-by-side preview | `Cmd+K V` | `Ctrl+K V` |
| Toggle sidebar | `Cmd+B` | `Ctrl+B` |
| Command palette | `Cmd+Shift+P` | `Ctrl+Shift+P` |
| Find in all files | `Cmd+Shift+F` | `Ctrl+Shift+F` |
| Quick file open | `Cmd+P` | `Ctrl+P` |

**Tip:** Ask your AI assistant *"What are the most useful keyboard shortcuts for writing?"*

---

## Screen Sharing Tips (for Workshops)

When sharing your screen:
- **Increase font size:** `Cmd+=` (Mac) / `Ctrl+=` (Windows) - press multiple times
- **Hide sidebar:** `Cmd+B` (Mac) / `Ctrl+B` (Windows)
- **Full screen:** `Ctrl+Cmd+F` (Mac) / `F11` (Windows)
- **Zoom in browser:** `Cmd+=` / `Ctrl+=` if showing documentation

---

## Getting Help

| Problem | Solution |
|---------|----------|
| Can't open terminal | Ask your AI: *"Help me open the terminal"* |
| Node.js not found | Ask your AI: *"Help me install Node.js on my system"* |
| Claude Code not found | Ask your AI: *"Help me install Claude Code"* |
| Plugin won't install | Check [Troubleshooting](https://github.com/linxule/interpretive-orchestration/blob/main/TROUBLESHOOTING.md) |
| Anything else | Ask your AI assistant - that's what it's for! |
