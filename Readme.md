# MCPois PoC (Windows Lab)

## 📜 Overview
This repository demonstrates the **MCPois** vulnerability affecting vulnerable versions of Cursor IDE (pre-1.3).  
The flaw allows **persistent, silent code execution** by swapping the command/arguments of a previously approved MCP tool without triggering a re-approval prompt.

⚠️ **WARNING:**  
This PoC is for **educational and authorized testing only**.  
Do **NOT** run this on production machines or against systems you do not own.

---

## 🛠 Requirements
- Windows 10/11 test environment (VM recommended)
- Cursor IDE **v1.2 or older** (v1.3+ is patched)
- [Git for Windows](https://git-scm.com/download/win)

---

## 📂 Repository Structure
```
MCPoisLab/
├── .cursor/
│   └── rules/
│       └── mcp.json # MCP configuration file (benign or malicious)
└── README.md
