# ⚡ Get Started: Mastering Visual Studio Code

Welcome to your complete guide to mastering **Visual Studio Code** for web development!

---

### ✅ **VS Code**

A modern, open-source code editor by Microsoft. Lightweight, fast, and extremely flexible for **web development**. Perfect for beginners and pros alike.

🔗 Download: [https://code.visualstudio.com](https://code.visualstudio.com)

🔗 Chrome (for DevTools): [https://www.google.com/chrome](https://www.google.com/chrome)

Supports: **Windows**, **macOS**, **Linux**

---

### 🚀 CLI (Command Line Interface)

Use these commands in terminal to control VS Code:

```bash
code .                 # Open current folder in VS Code
code index.html        # Open specific file
code --status          # Check if any VS Code window is already open
code -v                # Show version of VS Code
```

📌 **Mac Users:** Go to Command Palette → `Shell Command: Install 'code' command in PATH` to enable `code` in terminal.

🔍 Docs: [https://code.visualstudio.com/docs/setup/setup-overview](https://code.visualstudio.com/docs/setup/setup-overview)

---

### 🎨 Tweak Settings

Make your editor look and feel amazing:

* **Theme**: Atom One Dark → [Install](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
* **Icons**: VSCode Icons → [Install](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
* **Font**: Fira Code → [GitHub](https://github.com/tonsky/FiraCode)

🔧 Enable font ligatures for better symbols:

```json
// settings.json
{
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true
}
```

---

### 📘 Command Palette

Access everything with `Ctrl + Shift + P`

* Change theme, font, keybindings
* Run tasks and extensions

💡 Type `@` inside Command Palette to jump to symbols in the current file.

---

### 🗂️ File Explorer

* `Ctrl + B` → Toggle file explorer
* `Ctrl + W` → Close active file tab
* `Ctrl + S` → Save current file
* Collapse folders with collapse icon
* To see hidden files: Search "Exclude" in settings and uncheck filters

---

### ⌨️ Keyboard Shortcuts

Master these for super-speed coding:

* `Ctrl + Shift + P` → Open Command Palette
* `Ctrl + P` → Quick open file
* `Ctrl + /` → Toggle comment line

📜 Download cheat sheets:

* 🔗 [Windows Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
* 🔗 [macOS Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
* 🔗 [Linux Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf)

---

## 👀 Editing Tricks

### 💡 Parameter Hints

* `Ctrl + Space` → Show suggestions
* `Ctrl + Shift + Space` → Show function parameter hints

### 📂 Auto-Directory

When creating files, typing `src/components/Header.js` automatically creates `src`, `components` folders and the file.

### 🔀 Move Quickly

* `Ctrl + P` → Open files fast
* `Ctrl + L` → Select current line
* `:<number>` → Jump to a specific line

### 🧱 Move Lines

* `Alt + ↑/↓` → Move current line up/down
* `Shift + Alt + ↑/↓` → Duplicate current line
* `Ctrl + C/X` without selection → Copies/cuts full line

### 🙈 Code Folding

Collapse/expand blocks:

* Command Palette → `Fold All`
* `Ctrl + Shift + ]` → Expand current section

### 🌈 Bracket Colorizer

Enable via: `Settings → Bracket Pair Colorization`

Helpful to visually match nested brackets.

### 🖱️ Multi Cursor

* `Alt + Click` → Add more cursors
* `Ctrl + D` → Select next occurrence

### 🔗 Linked Editing

Enable in settings: Automatically updates paired HTML/XML tags.

### 📝 Multiline Editing

* `Ctrl + D` multiple times → Select multiple matching words for editing

### 😎 Emmet Snippets

Type shortcuts like:

```html
ul>li*3
```

Then press `Tab` → Expands into 3 list items.

📘 Cheat Sheet: [https://docs.emmet.io/cheat-sheet/](https://docs.emmet.io/cheat-sheet/)

### 🌯 Emmet Wrap Abbreviation

Wrap existing HTML with tags:

* Use `Wrap with Abbreviation` from Command Palette

### ✂️ Snippets

Create custom code templates:

* Open Command Palette → Configure User Snippets

### 🤖 GitHub Copilot

AI assistant that writes code suggestions as you type.

* Install via Extensions
* Works with JavaScript, HTML, React, etc.

### 🔎 Find References

* Right-click symbol → `Peek References`
* See all usages in project

### ✍️ Safe Rename

* Right-click → `Rename Symbol`
* Changes reflected across all files

### 🤯 Code Actions

* `Ctrl + .` or 💡 icon → Quick fixes, refactoring suggestions

---

## 🖥️ Integrated Development Environment

### 💻 Integrated Terminal

* `Ctrl + ~` → Toggle terminal inside VS Code
* Right-click tabs → Rename, split, or colour-code terminals

### ⚙️ Tasks

* Detects npm scripts, docker tasks, and more
* Run via Terminal → Run Task or play icon above scripts

### 🍴 Git

* Built-in source control tab
* `git init` to start
* Commit, stage, and push without leaving editor
* See file changes visually in editor margin

### 🌐 Remote Repos

* Open GitHub repo instantly by pressing `.` key in browser
* Use bottom-left blue icon → Connect to remote repo or container

### 🐛 Debugger

* Click next to line number to add breakpoints
* Use **Logpoints** instead of `console.log()`
* Step through code, view call stack and variables

### 🌐 HTTP Client

* Install **Thunder Client** from Extensions
* Test APIs directly inside VS Code
* Easier than Postman for quick debugging

### 🐳 Docker Integration

* Use Remote Containers: `Reopen in Container`
* VS Code creates Dockerfile, devcontainer.json automatically

Great for consistent dev environments across teams.

---

## 📝 Final Words

VS Code is more than just a text editor—it's a powerful, full-fledged **IDE**.

🎯 Learn the shortcuts
🚀 Automate repetitive tasks
🧠 Use extensions wisely
🛠️ Debug with precision

Keep coding. Keep improving.

Happy Web Development! 💻
